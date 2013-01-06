Featured Video Plus - WordPress Plugin
=============

Add Featured Videos to your posts and pages, just like you add Featured Images. Works with every theme which supports Featured Images.

Description
-------

*A picture is worth a thousand words. How many words is a video worth?*

This plugin enables you to define Featured Videos for your posts and pages. When Featured Images are supported by your theme the Featured Videos will automatically be displayed inplace if available. The Featured Image will be used as fallback.
The Featured Videos can either be displayed inplace of Featured Images, can be added to the theme by editing the theme's source files or inserted in your posts manually using the shortcode.

The plugin will add an box to the admin interface's post and pages edit page where you can paste your videos URL. At the moment the plugin supports __YouTube__ (including [time-links](http://support.google.com/youtube/bin/answer.py?hl=en&answer=116618 "Link to a specific time in a video")), __Vimeo__ and __Dailymotion__. As experimental feature the plugin now also supports your __local videos__.
If you are missing a certain video platform: Leave a message in the supports forum.

After activating the plugin you will get some additions to your media settings. There you can choose how the videos will be sized and get some other individualisation properties - have a look at the [screenshots](http://wordpress.org/extend/plugins/featured-video-plus/screenshots/). If the theme you are using does not work with any combination of the width and height settings please contact me and I will look into it.

__Shortcode:__

	[featured-video-plus]
	[featured-video-plus width=300]


__Theme functions:__

    the_post_video(array(width, height), fullscreen = true)
    has_post_video(post_id)
    get_the_post_video(post_id, size(width, height), fullscreen = true)

All parameters are optional. If no post_id is given the current post's id will be used.

Changelog
-------

= 1.2 =
* __Added experimental support for local videos__. Activate under settings.
* Allow webM mime type for media upload
* Added Media Settings link in plugin info
* fixed some small bugs

= 1.1 =
* __Added Dailymotion__
* fixed youtube 'start at specific time' embeds
* overhaul of the interaction between Featured Videos and Featured Images
* existing featured images will no longer be replaced by newly added featured videos in the administration interface

= 1.0 =
* Release