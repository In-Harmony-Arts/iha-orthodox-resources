=== IHA Orthodox Resources ===
Contributors:      inharmonyarts, Vitzkrieg
Tags:              daily,orthodox,calendar,saints,scripture
Requires at least: 6.8
Tested up to:      7.1
Stable tag:        1.1.0
License:           GPL-2.0-or-later
License URI:       https://www.gnu.org/licenses/gpl-2.0.html

Adds features to support Orthodox Christian websites.

== Description ==

=== Orthodox Calendar ===

Adds a Gutenberg Block for loading the daily Orthodox Calendar information from https://www.holytrinityorthodox.com/calendar.
* Settings to customize what and how the daily content information is displayed.
* 3 prebuilt styles to choose from
* Option for no applied styles so it applies your theme styles

There are plans to expand the blocks and/or functionality related to running an Orthodox Christian website in the future.

== External Services ==

The content displayed from this plugin is being provided by The Holy Trinity Orthodox Church server at: https://www.holytrinityorthodox.com/calendar
All content copyright and/or ownership is of Holy Trinity Orthodox Church or as displayed in the content and not of the author(s) or contributor(s) of this plugin
There is no account needed for these services.

Terms of Service: https://www.holytrinityorthodox.com/htc/orthodox-calendar/about-calendar/

== Installation ==

1. Upload the plugin files to the `/wp-content/plugins/iha-orthodox-resources` directory, or install the plugin through the WordPress plugins screen directly.
1. Activate the plugin through the 'Plugins' screen in WordPress

== Source Code ==

Original source code can be found at: https://github.com/In-Harmony-Arts/daily-orthodox-calendar-block

== Screenshots ==

1. Orthodox Calendar
2. Block setttings

== Changelog ==

= 0.1.0 =
* Release

= 0.2.0 =
* Removed seperate functions PHP file and combined into main PHP file

= 0.3.0 =
* Updated contributors to include original plugin author

= 0.4.0 =
* Added date picker option
* Copy static text files to build folder so they are included in package zip script

= 0.5.0 =
* Name space PHP functions

= 0.5.1 =
* Fix error getting static text

= 0.6.0 =
* Move date picker to end of buttons & wrap

= 0.7.0 =
* Update PHP code to use wp_remote_get
* Update JS code to move all functions outside of init

= 0.8.0 =
* Enqueue JS only if block in on page
* Use block name as contianer class name
* Small cleanup

= 0.9.0 =
* Externalize text into settings

= 0.10.0 =
* Added support and options for Russian language
* Implemented server side sanitizing from original plugin update
* Removed client side sanitizing
* Handle link popups
* Add cachebuster query param

= 0.10.1 =
* Recompile JS

= 0.11.0 =
* Add content overlay for links

= 0.11.1 =
* Uninstall react-resizable

= 1.0.0 =
* Overhaul to use render.php and WP Interactivity API
* Updates for wordpress.org repo submission

= 1.1.0 =
* Add height setting to daily calendar
* Made date header sticky when scrolling
* Fix garbled Russian popup content by detecting UTF-8 encoding