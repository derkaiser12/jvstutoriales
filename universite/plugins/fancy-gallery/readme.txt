=== Fancy Gallery ===
Contributors: dhoppe
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=1220480
Tags: image, images, picture, pictures, photo, photos, gallery, galleries, photo-albums, Post, admin, media, fancy, fancybox, thickbox, lightbox, jquery, 
Requires at least: 2.8
Tested up to: 3.0
Stable tag: trunk

Fancy Gallery associate linked images and galleries with the jQuery Fancybox.

== Description ==

Fancy Gallery integrates the [Fancy Image Box](http://fancybox.net) in your WordPress. All links pointing to an image will automaticly opened in the FancyBox. If you use the [Gallery] ShortCode the images will get a navigation and the gallery itself will converted into a valid XHTML block.

Of course you can use 'exclude' and 'include' parameters in your [GALLERY] shortcode.

= Requirements =
* **Fancy Gallery requires PHP5!**
* WordPress 2.8 or higher

= Settings =
You can find the settings page in WP Admin Panel -> Settings -> Fancy Gallery.

= Questions =
If you have any questions you can leave a comment in my blog. But please think about this: I will not add features, write customizations or write tutorials for free. Please think about a donation. I'm a human and to write code is hard work.

= Language =
* This Plugin is available in English.
* Dieses Plugin ist in Deutsch verfügbar. ([Dennis Hoppe](http://dennishoppe.de/))
* Este plugin está disponível em Português do Brasil. ([Rafael Sirotheau](http://rsirotheau.wordpress.com/))
* Cette extension est traduite en français. ([Charles Alain](http://www.domarin-tt.com/))

If you translated this plugin in your language feel free to send me the language file (.po file) via E-Mail with your name and this translated sentence: "This plugin is available in %YOUR_LANGUAGE_NAME%." So i can add it to the plugin.

You can find the *FancyGallery.pot* file in the *language/* folder in the plugin directory.

* Copy it
* Rename it
* Change it
* Send it via E-Mail to mail@DennisHoppe.de
* Thats it. Thank you =)

The translation file contains 36 strings.


== Installation ==

Installation as usual.

1. Unzip and Upload all files to a sub directory in "/wp-content/plugins/".
1. Activate the plugin through the 'Plugins' menu in WordPress.
1. View a post or page which contains a gallery.
1. You like what you see?

== Changelog ==

= 1.3.8 =
* Added French translation by [Charles Alain](http://www.domarin-tt.com/).


= 1.3.7 = 
* Added Portuguese (Brasil) translation by [Rafael Sirotheau](http://rsirotheau.wordpress.com/).


= 1.3.6 =
* Fixed German translation.
* Added .pot file to language folder


= 1.3.5 =
* fixed a problem in the fancy-js.php does not need parameters anymore.
* added a workaround for themes that show images as block elements.


= 1.3.4 =
* fancy-js.php does not define Functions or Classes anymore
* Fixed the exclude bug


= 1.3.3 =
* optimized settings handling in fancy-js.php


= 1.3.2 =
* New version of the donation plugin


= 1.3.1 =
* Some small translation, CSS, JS, XHTML fixes


= 1.3 =
* Upon now FancyGallery runs only with PHP5 and higher!
* There is a new admin panel in Settings > Fancy Gallery
* Added my new "Please donate" Plugin ;) 


= 1.2.4 =
* You can use the "id" parameter to sepcify the gallery that should be shown.


= 1.2.3 =
* Modified FancyBoy CSS. Should now also work in IE6 and IE7.


= 1.2.2 =
* Chage BaseUrl function. Now the plugin should even work if the wp folder is diffrent from your blog url. 


= 1.2.1 =
* Added necessary javascript files (Sorry)


= 1.2 =
* updated the fancy gallery to 1.3.1


= 1.1.2 =
* added the url to the plugin page
* Bug Fix: FancyGallery didn't work if you have the blog installed in a different directory.


= 1.1.1 =
* Bug Fix: In some cases (No attributes) you got an error "array_merge(): Argument #2 is not an array [...]"


= 1.1 =
* Now you can use exclude="x,y,z" and include="a,b,c" attributes in your tag.


= 1.0 =
* Everything works fine.