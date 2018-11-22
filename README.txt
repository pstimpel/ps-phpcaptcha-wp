=== PS PHPCaptcha WP ===
Contributors: (pstimpel)
Donate link: https://www.paypal.me/redzoneaction
Tags: comments, spam, captcha, recaptcha-replacement
Requires at least: 4.0.0
Tested up to: 4.9.8
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Simple PHP-GD based captcha to replace tracking prone systems like Google recaptcha

== Description ==

If you are keen to provide your users kind of a tracking free environment, you would have to remove
Google Recpatcha and other cloud based Captcha solutions from your Wordpress installation.

PS PHPCaptcha WP does not use any remote resources. This make it fully GDPR compliant without any need to mention it
in your privacy policy.

To generate the image this plugin does not need use the Wordpress database and therefore IO of the database is very low.
This very important if you run a site with high traffic.

System requirements:
* Wordpress up and running
* PHP5 or PHP7 installed
* PHP-GD installed and activated
* uses PHP sessions

== Installation ==

1. Upload `psphpcaptchawp`-directory to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Configure the plugin using the provided settings page

== Frequently Asked Questions ==

* none

== Screenshots ==

1. This plugin will create a captcha displaying a text, with the try to confuse OCR by drawing some random lines.
2. It integrates in the comment form below each Wordpress post
3. If the commenting user fails to solve it, an error message appears
4. The behavior of the image can be set in the settings area of Wordpress

== Changelog ==

= 1.0 =
* initial version
* Languages: en, de


