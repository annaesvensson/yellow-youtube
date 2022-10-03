<p align="right"><a href="README-de.md">Deutsch</a> &nbsp; <a href="README.md">English</a> &nbsp; <a href="README-sv.md">Svenska</a></p>

# Youtube 0.8.6

Bädda in Youtube-videor.

<p align="center"><img src="youtube-screenshot.png?raw=true" alt="Skärmdump"></p>

## Hur man bäddar in en video

Skapa en `[youtube]` förkortning.

Följande argument är tillgängliga, alla utom det första argumentet är valfria:

`Id` = sista delen av en [Youtube](https://www.youtube.com) länk, t.ex. `https://www.youtube.com/watch?v=fhs55HEl-Gc`  
`Style` = videostil, t.ex. `left`, `center`, `right`  
`Width` = videobredd, pixel eller procent  
`Height` = videohöjd, pixel eller procent  
 
## Exempel

Bädda in en video, olika videor:

    [youtube fhs55HEl-Gc]
    [youtube wNiyp89pTi0]
    [youtube OV5J6BfToSw]

Bädda in en video, olika storlekar:

    [youtube fhs55HEl-Gc right 50%]
    [youtube fhs55HEl-Gc right 200 112]
    [youtube fhs55HEl-Gc right 400 224]

## Inställningar

Följande inställningar kan konfigureras i filen `system/extensions/yellow-system.ini`:

`YoutubeStyle` = video style, e.g. `flexible`  

## Installation

[Ladda ner tillägg](https://github.com/annaesvensson/yellow-youtube/archive/main.zip) och kopiera zip-fil till din `system/extensions` mapp. Högerklicka om du använder Safari.

Detta tilläg använder [Youtube](https://www.youtube.com) av Google. Tjänsteleverantören samlar in personuppgifter och använder cookies.

## Utvecklare

Anna Svensson. [Få hjälp](https://datenstrom.se/sv/yellow/help/).
