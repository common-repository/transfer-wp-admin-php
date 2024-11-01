=== Transfer WP-ADMIN.php ===
Contributors: Neil Patel, WPTechnical.in
Donate link: https://www.wptechnical.in/donations/wordpress-donation/
Tags: change wp-login.php, rename wp-login, rename wp-admin, transfer wp-admin, change login uri, login, rename, change, wp-login.php, wp-login
Requires at least: 5.0 or higher 
Tested up to: 5.2
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

you can change or rename wp-login.php to anything you want.

== Description ==

Transfer wp-admin.php is very light plugin that let's you easily and safely change your wp-admin.php to anything you want. It doesn’t literally rename or change files in core, not does it add rewrite rules. It simply intercepts page requests and works on any WordPress website. The wp-admin directory and wp-login.php page become inaccessible, so you should bookmark or remember the url. Deactivating this plugin brings your site back exactly to the state it was before.

** We offer tranmsfer wp-admin.php support throught [website](https://www.wptechnical.in/plugin/transfer-wp-admin/)

==Compatibility ==

All login related things such as the registration form, lost password form, login widget and expired sessions just keep working.

It’s also compatible with any plugin that hooks in the login form, including

    BuddyPress,
    bbPress,
    TML,
    UserPro,
    Limit Login Attempts,
    and User Switching.

Obviously it doesn’t work with plugins that hardcoded wp-login.php.

Works with multisite, but not tested with subdomains. Activating it for a network allows you to set a networkwide default. Individual sites can still rename their login page to something else.

If you’re using a page caching plugin you should add the slug of the new login url to the list of pages not to cache.

If you wish, you can block wp-login.php with .htaccess from now on.

== Frequently Asked Questions (FAQ) ==

= I forgot my login url! =

1. Go to cPanel > File Manger
2. Public_html (/) > wp-content > plugins
3. change folder name (that would deactive plugin)
4. Login to your website example: www.example.com/wp-admin.php

= How to change admin dashboard uri = 

1. Login to WordPress admin Panel
2. Go to Setting > permalink > Transfer wp-admin.php 
3. Change your wordpress admin uri

== Installation ==
 

   1. Go to Plugins › Add New.
   2. Search for Transfer wp-login.php.
   3. Look for this plugin, download and activate it.
   4. The page will redirect you to the settings. Transfer wp-login.php there.
   5. You can change this option any time you want, just go back to Settings › Permalinks › Transfer wp-login.php.

== Changelog ==
= 1.0 =
* Initial version.
* Fixed status code custom login page.



