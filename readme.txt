=== WP Featherlight Disabled - A Simple jQuery Lightbox ===

Contributors: wpjohnny, yin
Tags: lightbox, jquery lightbox, jquery, gallery, image, lightbox images, image lightbox, lightbox gallery, lightbox image, lightbox popup, featherlight, photo gallery, popup image, popup images, popup lightbox, responsive lightbox, swipe, wordpress image lightbox, wordpress lightbox, wordpress slideshow lightbox, photography, images, minimal, responsive, photo, photos  
Requires at least: 4.0  
Tested up to: 5.4.1  
Stable tag: 1.3.3  
License: GPL-2.0+  

Forked version of the original lightweight jQuery lightbox for WordPress images and galleries.

== Description ==

WP Featherlight is a WordPress lightbox plugin for adding a minimal, high-performance, responsive jQuery lightbox to your WordPress website. At its core, WP Featherlight is a WordPress plugin wrapper for the Featherlight jQuery lightbox plugin. When installed, the plugin will automatically display all standard WordPress images and galleries in a simple, minimalistic lightbox popup.

In order for WordPress images and galleries to be lightboxed, you need to select the "Media File" option when choosing where the thumbnails should link. You can also select the "Custom Link" option if you make sure to link directly to an image file. This should work for any image file, even if it's hosted on another website.

It's also possible to lightbox videos, iframes, and ajax content with WP Featherlight by adding data attributes to your content. For more details on custom content loading, check out the [featherlight documentation](https://github.com/noelboss/featherlight/#usage).

There are no settings for WP Featherlight, so you should be able to install it without needing to configure anything. In the event you don't want a lightbox on certain pages or posts, there is an option to disable it from within the post editor screen.

If you find a display problem, it may be related to your theme but please [open an support request](https://wordpress.org/support/plugin/wp-featherlight) about it so we can look into it. For more information about the Featherlight script itself, check out their [GitHub plugin page](http://noelboss.github.io/featherlight/).

= Developer Notes =

Plugin has no options. Some handy filters are available to modify defaul behavior. All images using default WordPress captions will also include a caption when the image is lightboxed. To disable this behavior, filter `wp_featherlight_captions` to false.

You can also disable inclusion of the CSS and JavaScript conditionally using filters which can be found in the `/includes/class-scripts.php` file. If you have questions about how any part of the plugin works, please don't hesitate to [open an issue on the official GitHub](https://github.com/cipherdevgroup/wp-featherlight/issues).

= Contributing =

Can contribute to this fork or make your own from the original [fork the plugin on GitHub](https://github.com/cipherdevgroup/wp-featherlight).

== Screenshots ==

1. A view of the jQuery lightbox in action.

== Changelog ==

= 1.0 =

Starting fork off of the official WP Featherlight version 1.3.3. For older changes, see [their official full changelog on GitHub](https://github.com/cipherdevgroup/wp-featherlight/blob/release/CHANGELOG.md)