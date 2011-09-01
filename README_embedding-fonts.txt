TO EMBED A FONT:

1 - COPY THE DESIRED FONT TO YOUR DESKTOP
2 - CHANGE THE FILE NAME TO "EmbedFont-1" (or -2 or -3, depending on which embedded font this will be)
3 - NAVIGATE TO http://www.fontsquirrel.com/fontface/generator
4 - ADD YOUR FONT FROM THE DESKTOP, USE 'OPTIMAL' SETTINGS, CLICK DOWNLOAD
5 - OPEN THE DOWNLOADED .zip FILE
6 - COPY THE FOUR FONT FILES (.eot, .svg, .ttf, .woff) TO THE FONT FOLDER IN YOUR SITE FOLDER


TO USE YOUR EMBEDDED FONT IN ANY .sass OR .css FILE, SIMPLY USE THIS PROPERTY (be sure to use the correct -# indicator):

yourElement {
	font-family: "EmbedFont-1"
}





NOTE: Helvetica Neue is also embedded by default. Use font-family: "Embed-Helvetica"