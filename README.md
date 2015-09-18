Yellow CSS Gallery plugin (ycssg)
=================
CSS only Gallery with Lightbox. The plugin is based on [Fotorama Plugin](https://github.com/datenstrom/yellow-extensions/tree/master/plugins/fotorama).

![Slideshow](slideshow.jpg?raw=true)
![Lightbox](lightbox.jpg?raw=true)

How do I install this?
----------------------
1. Download and install [Yellow](https://github.com/datenstrom/yellow/).  
2. Download [ycssg.php](ycssg.php?raw=true), copy it into your `system/plugins` folder.  
3. Download [ycssg.css](ycssg.css?raw=true), copy them into your `system/themes/` folder.  

To uninstall delete the plugin files.

How to use the gallery?
------------------
Create a `[ycssg]` shortcut with the `PATTERN` as argument.

`PATTERN` = file name as [regular expression](https://en.wikipedia.org/wiki/Regular_expression)  

Example
-------
I have structured my images into the media/images folder of yellow. Each collection
of images is in one subfolder.

Adding an image gallery:

    [ycssg path_to_gallery.*jpg]

How to configure the gallery?
------------------------
Nothing to do. It should work out of the box. If you don't like the color,
etc. Just check the [ycssg.css](ycssg.css?raw=true) and adapt.

Issues
------------------------
- If the lightbox is open and you change the image, the images on the original site do not slide.

Feature requests
------------------------
- Keyboard/Swipe support

Contributing
------------------------
If you notice something wrong or broken, let me know by opening an issue. Pull requests are very welcome.

