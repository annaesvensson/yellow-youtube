<p align="right"><a href="README-de.md">Deutsch</a> &nbsp; <a href="README.md">English</a> &nbsp; <a href="README-sv.md">Svenska</a></p>

# Youtube 0.8.6

Embed Youtube videos.

<p align="center"><img src="youtube-screenshot.png?raw=true" alt="Screenshot"></p>

## How to embed a video

Create a `[youtube]` shortcut. 

The following arguments are available, all but the first argument are optional:
 
`Id` = last part of a [Youtube](https://www.youtube.com) link, e.g. `https://www.youtube.com/watch?v=fhs55HEl-Gc`  
`Style` = video style, e.g. `left`, `center`, `right`  
`Width` = video width, pixel or percent  
`Height` = video height, pixel or percent  
 
## Examples

Embedding a video, different videos:

    [youtube fhs55HEl-Gc]
    [youtube wNiyp89pTi0]
    [youtube OV5J6BfToSw]

Embedding a video, different sizes:

    [youtube fhs55HEl-Gc right 50%]
    [youtube fhs55HEl-Gc right 200 112]
    [youtube fhs55HEl-Gc right 400 224]

## Settings

The following settings can be configured in file `system/extensions/yellow-system.ini`:

`YoutubeStyle` = video style, e.g. `flexible`  

## Installation

[Download extension](https://github.com/annaesvensson/yellow-youtube/archive/main.zip) and copy ZIP file into your `system/extensions` folder. [Learn more about extensions](https://github.com/annaesvensson/yellow-update).

This extension uses [Youtube](https://www.youtube.com) by Google. The service provider collects personal data and uses cookies.

## Developer

Anna Svensson. [Get help](https://datenstrom.se/yellow/help/).
