# net.art-generator ver.5b
https://nag.iap.de/

![Image of n.a.g](https://github.com/siusoon/n.a.g/blob/master/nag.png)

The net.art generator automatically produces net.art on demand.

nag_05-this version of the net.art generator creates images. The resulting image emerges as a collage of a number of images which have been collected on the WWW in relation to the 'title' you have chosen. The original material is processed in 12-14 randomly chosen and combined steps. For finding the images, nag_05 draws on Google search; that is the delicate part as Google limits access to their search results for all non-paying clients including net.art projects like this one.

The technical base of the net.art generator is a PERL script, running on apache and debian servers. For the library of imagemagick:
v6.9.10.23+dfsg-2.1+deb10u1 (as of Oct 2020) and libimage-magick-q16-perl for the perl interface. 

See the net.art generator main page: http://net.art-generator.com/

note: Currently, the encoding format is utf-8 for index.cgi. There is also nag_extensions, which is developed and maintained by Gerrit Boelz, displaying a collection of the generated images as thumbnails in a grid and allowing to click on them to open a more detailed view of the image. See here for more info: https://lab.madbox.synology.me/nag_extensions/gallery

CC BY 4.0 - https://creativecommons.org/licenses/by/4.0/

