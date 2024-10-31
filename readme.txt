=== Remove Admin Meta Boxes ===
Contributors: Justin Adie (http://rathercurious.net)
Tags: admin, meta-box, meta, post, page, write panel
Requires at least: 2.7.1
Donate Link: rathercurious.net
Tested up to: 2.8.0
Stable tag: 0.1.2

This plugin allows you to remove selectively the various panels (or meta-boxes) within the post/page screens.

== Description ==

Sometimes you want to declutter your life.  This plugin might help you a litle bit.  It allows you to remove some of the less often used boxes from the write panels.

This might be useful in an environment where you want to create a fully customised write panel but don't want to create a new menu item or muck around with the admin menus.

Equally, for certain users you might want to keep things simple.  To make things user-granular just insert an if test just about anywhere in the index.php file.  i.e. either around the instantiation of the class, in the constructor or the actual action.  If there is enough demand i will consider parametrising this in an settings page.

== Installation ==

Just upload the folder to your wp-content/plugins directory and activate the plugin as normal from the admin->plugins menu.

comment out the lines in the index.php file to select which meta-boxes you do and don't want to show.  I know this is far from graceful but it seems silly to create a whole UI to do a one-off job that will take a max of 5 seconds!

== Frequently Asked Questions ==

There are no Frequently Asked Questions (yet)...

== Screenshots ==
There are no screenshots
