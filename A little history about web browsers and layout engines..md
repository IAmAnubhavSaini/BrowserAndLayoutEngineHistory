---
tags: web, layout-engines, KHTML, Konqueror, Gecko, FireFox, Chrome, Blink, WebKit, EdgeHTML, IE, Internet-Explorer
---

[TOC]

# Browsers' story

## Usage share on web

![Usage share of web browsers](https://lh3.googleusercontent.com/-ceGacpridxk/VyS4nbFgsnI/AAAAAAAAPZ0/CEaJYKlpMzoaJVuRctyCuPnzCiX8MQrDACKgB/s0/Usage_share_of_web_browsers_%2528Source_StatCounter%2529.svg.png "Usage_share_of_web_browsers_&#40;Source_StatCounter&#41;.svg.png")

### Share of non-mobile browser traffic on WikiMedia (Feb '14)

![enter image description here](https://lh3.googleusercontent.com/-nlcxFpzsXHk/VyS6VfJiIdI/AAAAAAAAPak/nCmnyaBC_8kgFT7oNWt-lOFkGNi6kVt4QCKgB/s0/Screen+Shot+2016-04-30+at+7.28.15+PM.png "Screen Shot 2016-04-30 at 7.28.15 PM.png")

## Timeline

![enter image description here](https://lh3.googleusercontent.com/-Pr05vtGNSlg/VyS5NIOmY5I/AAAAAAAAPaI/V2_eHgdJGYkyi2Z3e_QKAW20OGP3ni6FwCKgB/s0/e990b9e01adcd29b4b3965c3f32f697c.png "e990b9e01adcd29b4b3965c3f32f697c.png")

# KHTML and forks

## KHTML

## WebKit

## Blink

Blink is the [rendering engine](http://en.wikipedia.org/wiki/Web_browser_engine) used by Chromium.

> Blink's Mission:
> 
> To improve the open web through 
>  technical innovation and good citizenship


## General Idea Diagram

```sequence
Note right of KHTML: . Konqueror .
KHTML->WebKit: Fork.
Note right of WebKit: . Safari .
Note right of WebKit: . Chrome .
WebKit->Blink: Fork.
Note right of Blink: . Chrome .
Note right of Blink: . Opera .
```

# Trident and forks

## Trident

### Version History

> Trident | MSHTML.dll | IE | IE Mobile
> :--------:|:------------:|:----:|:----------:
> NA | 4.x | IE 4 | NA
> NA | 5.x | IE 5 | NA
> NA | 5.5.x | IE 5.5 | NA
> NA | 6.x | IE 6 | NA
> NA | 7.x | IE 7 | NA
> NA | NA | NA | 6
> 3.1 | 7 | NA | 7
> 4 | 8 | 8 | NA
> 5 | 9 | 9 | 9
> 6 | 10 | 10 | 10
> 7 | 11 | 11 | 11
> 




## Tasman

> WikiPedia:
>
> "Tasman is a discontinued layout engine developed by Microsoft for inclusion in the Macintosh version of Internet Explorer 5. Tasman was an attempt to improve support for web standards, as defined by the World Wide Web Consortium. At the time of its release, Tasman was seen as the layout engine with the best support for web standards such as HTML and CSS."
>
> Tantek Çelik led the team that developed the Tasman engine as the Software Development Lead.


## EdgeHTML

### General Idea Diagram

```sequence
Trident->Tasman: Fork
Note right of Trident: . IE4 ... IE 10 .
Note right of Tasman: . IE 5 for MAC .
Trident->EdgeHTML: Fork
Note right of EdgeHTML: . IE 11 .
```

### MicroSoft Edge

> Replaced `IE 11` and `IE Mobile`.

### IE8

> IE 8 Architecture.
> 
![The architecture of IE8. Previous versions had a similar architecture, except that both tabs and the UI were within the same process. Consequently, each browser window could have only one "tab process".](https://lh3.googleusercontent.com/-3x6pFDTbWfs/VyS3Zb2O2kI/AAAAAAAAPZk/NBUKdW1-BoMQSOK7w2RW-1H3N4qiVqbvwCKgB/s0/IExplore.svg.png "IExplore.svg.png")

&nbsp;

----

# References

## Concepts

1. http://en.wikipedia.org/wiki/Web_browser_engine

## Engines

### KHTML

### Gecko

### WebKit

### Blink

1. http://www.chromium.org/blink
2. 

### EdgeHTML

1. https://en.wikipedia.org/wiki/EdgeHTML

### Trident

1. https://en.wikipedia.org/wiki/Trident_(layout_engine)

### Tasman

1. https://en.wikipedia.org/wiki/Tasman_(layout_engine)

## Browsers

### Konqueror

### FireFox

### Safari

### Chrome

### IE

1. https://en.wikipedia.org/wiki/Microsoft_Edge
2. https://en.wikipedia.org/wiki/Internet_Explorer_11
3. https://en.wikipedia.org/wiki/Internet_Explorer

## Resources

1. https://commons.wikimedia.org/wiki/File:IExplore.svg
2. https://en.wikipedia.org/wiki/File:Usage_share_of_web_browsers_(Source_StatCounter).svg