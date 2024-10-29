=== Wordpress Admin10X ===
Contributors: brandonliles, toddlevy
Tags: admin, performance
Requires at least: 4.7
Tested up to: 5.0.3
Stable tag: 5.0.3
License: MIT

This plugin improves the performance of Wordpress Admin when a wordpress instance has many users.

== Description ==

When a Wordpress instance has hundreds of thousands of users, the query to get the list of WP
authors can become very slow (see https://core.trac.wordpress.org/ticket/28160). This plugin
works around this limitation by adding a cache table of authors and optimizing the query.

Copyright (c) 2019 Brandon Liles

== Installation ==

Just install the plugin to your plugins directory and activate it.

== Changelog ==

= 1.0.3 =
Removed additional debugging lines.

= 1.0.2 =
Removed debugging lines and add toddlevy as a contributor

= 1.0.1 =
Fixed plugin installation/uninstallation bugs.
Support author removal, thanks toddlevy! (https://github.com/toddlevy)

= 1.0 =
Initial release.

