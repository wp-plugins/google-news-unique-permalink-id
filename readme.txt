=== Plugin Name ===
Contributors: brainsap-dev
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=ebay%40gfxandmore%2ecom&lc=US&item_name=Brainsap%20Development%20Wordpress%20Plugins&no_note=0&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHostedGuest
Tags: permalink, google news, unique id
Requires at least: 3.0
Tested up to: 3.2
Stable tag: 1.0

This Plugin automatically is adding 5 Digit Unique IDs to Permalinks ready for use with Google News.

== Description ==

This Plugin will generate Permalinks formatted for Google News, i.e. `myblog.org/this-is-a-very-interesting-post-12345` or `myblog.org/this-is-a-very-interesting-post-for-real-45678`

*Requirements:*

* Settings > Permalinks has to be set to "Custom Structure" /%postname% (dont forget the leading slash)


*Features:*

* Adds a unique 5-digit ID to all Permalinks on your Blog to make it work properly with Google News
* On Editing a Post which has already a Permanent ID, the URL may change if you are changing the Title, but the Unique ID always remains the same
* Older Posts which have been created before installing this Plugin will not be affected at all, neither on install nor on edit
* You are still free to add your own unique ID to the permalink, the Plugin won't override it

*Examples:*

* You add a Post with the name "This is a very Interesting Post"
	-> The Permalink will look like this: `myblog.org/this-is-a-very-interesting-post-12345` where 12345 is a randomly generated unique ID
* You edit a Post with the name "This is a very Interesting Post" to "This is a very Interesting Post for sure" (The post was created after installing this Plugin)
    	-> The new Permalink will look like this: `myblog.org/this-is-a-very-interesting-post-for-sure-12345` where the unique ID 12345 remains the same
    
* You edit a Post with the name "This is a very Interesting Post" to "This is a very Interesting Post for sure" (The post was created before installing this Plugin)
        -> The Permalink will not change.

== Installation ==

1. Upload `google-news-unique-permalink-id.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Settings > Permalinks has to be set to "Custom Structure" /%postname% (dont forget the leading slash)

== Frequently Asked Questions ==

Checkout [Brainsap Development](http://www.brainsap-development.com/wp-plugins/google-news-permalink.php "Brainsap Development Website") for further Information

== Changelog ==

= 1.0 =
* Plugin Created

== Upgrade Notice ==

= 1.0 =
* Plugin Created

