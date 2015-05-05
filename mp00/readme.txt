/**
* $Id: readme.txt v 1.0 / 7 November 2004 hsalazar Exp $
* Package: MP00 Theme
* Version: v 1.0
* Release Date: 7 November 2004
* Author: hsalazar
* Licence: GNU
*/
This is the first theme released under the flag of Mesa de pruebas, my personal Xoops site.
It's a fixed-width theme, mostly grayish-bluish, with little graphic sophistication, yet I like its simplicity and have used it a long time in my site.
It has several things worth mentioning:
1) Includes a repeated background image whose URL is set in the BODY selector, within the style.css file. Please change this URL so your Xoops system finds the file.
2) Includes the script Live Clock, by Mark Plachetta. It's configured for Monterrey, the city I live in. Please adapt it to your own place. You change the text in line 63 in theme.html. You can find at the beginning of liveclock.js the parameters used to configure this script. Mainly, you'll need to adapt the last one to suit your time zone. If you use a more explicit setting, you'll have to enlarge the parameter width in 63 in theme.html. Also, if you go above a certain width, you might need to change the width in the SPAN containing the clock, line 60 in theme.html.
3) Includes a script to hide/show the side columns, to compensate partially the effect of having a fixed width for those sites that have a lot of content or those contents that require full width, such as the forums or the users list. This script was taken from xoops-themes site, which at the moment is changing hosts so is not reachable. They in turn had taken it from PetitOOps, so this little script has travelled some.
I've included a sample logo.png file. You need to put your own logo. To do it, create a file 265 pixels wide by 60 pixels high, give it a background color #99AABB (that is, if you keep the current colors in your theme) and put there whatever image and text you want. You can change the ALT text to whatever you want editing line 77 in theme.html.
What if you want the theme centered on the page? To do this in an approximate way, just change the div#todo selector in the style.css file so that it reads:
div#todo
{
width: 760px;
margin: 0 auto;
border: 0;
}
The result will be slightly moved to the right, due to the fact that the original one has the content div 10 pixels from the left. If you want it EXACTLY centered, now is the time to learn to play with the CSS and the widths <lol>. I promise you it's quite easy to do.
In what browsers does this theme work? Thanks to ackbarr, I can say it does display more or less correctly in the following browsers: 
PC versions: Mozilla 1.4, Firebird 0.7, Opera 6, Opera 7, MSIE 5.5, MSIE 6.0
Mac versions: MSIE 5.2, Safari 1.0
For this to work, I had to twiddle a bit the style.css file, specifically in the td#leftcolumn div.blockContent selector. There I applied the well-known Tantek Celik hack.
----
I hope to release some more themes in the future. If you like this one, or if you have any comment about it, please mail me at hsalazar@xoops.codigolivre.org.br.
Horacio Salazar
hsalazar@xoops.codigolivre.org.br
