Project from SVG training

pro znovuvyziti kresby to muzu dat do <symbol> a pak to muzu pouzit pomoci xlinku
symbol ma vlastni viewBox a preserveAspectRatio

SVG nema z-index, co je pozdeji v kodu, je vys na strance
optimalizovat tvary - snazit se, aby to byl jeden symbol

https://css-tricks.com/svg-line-animation-works/

transformace - transform=(translate x y) pak moje tranfosrmace (scale, rotate...) a pak transalte (-x -y) - aby se mi to napozicovalo tak, jak potrebuju napric browserama

Greensock - knihovna na svg animace

http://calendar.perfplanet.com/2014/tips-for-optimising-svg-delivery-for-the-web/ - optimizing
gzip, no base64, min vrstev, couplovat to do objektu/containeru
