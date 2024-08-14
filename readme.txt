=== Phlush Permalinks ===
Contributors: deviodigital
Donate link: https://robertdevore.com/phlush-permalinks-wordpress-plugin/
Tags: permalinks, cron, flush, custom post types, seo
Requires at least: 4.8
Tested up to: 6.6.2
Stable tag: 1.0.0
Requires PHP: 5.6
License: GPLv3
License URI: https://www.gnu.org/licenses/gpl-3.0.html

Automate permalink flushing at custom intervals and trigger flushes on selected actions for improved site management.

== Description ==

Phlush Permalinks is a powerful WordPress plugin designed to automate the flushing of permalinks at custom intervals. It also allows you to select specific actions that will automatically trigger a permalink flush. This is particularly useful for websites with frequent changes to post types, taxonomies, or other structures relying on permalinks.

Key Features:
* Automatic flushing of permalinks at user-defined intervals.
* Select specific actions that trigger an automatic flush, including post creation, post edits, category changes, and more.
* Conditional support for popular plugins like WooCommerce, Yoast SEO, and Advanced Custom Fields (ACF).
* Easy configuration through the WordPress settings page, complete with a Select2-enhanced multi-select field.

Phlush Permalinks is ideal for developers and site administrators who want to ensure their permalinks remain up-to-date without manual intervention.

== Installation ==

To install the Phlush Permalinks plugin:

1. Upload the `phlush-permalinks` folder to the `/wp-content/plugins/` directory, or install the plugin directly through the WordPress plugins screen.
2. Activate the plugin through the 'Plugins' screen in WordPress.
3. Navigate to `Settings > Phlush Permalinks` to configure the plugin.
4. Set the desired flush interval (in minutes) and choose the actions that should trigger a permalink flush.
5. Save your settings.

The plugin will now automatically flush permalinks based on your configurations.

== Frequently Asked Questions ==

= Why should I use Phlush Permalinks? =

Phlush Permalinks is perfect for websites that frequently modify custom post types, taxonomies, or permalinks. It automates permalink management, reducing the need for manual flushing and ensuring that your site's URLs are always up to date.

= Does this plugin support WooCommerce and Yoast SEO? =

Yes, Phlush Permalinks includes conditional support for WooCommerce and Yoast SEO. You can trigger permalink flushes based on WooCommerce product changes and Yoast SEO post saves.

= What is the default flush interval? =

The default flush interval is 5 minutes, but you can customize this to suit your needs via the settings page.

= Can I manually flush permalinks using this plugin? =

No, you can do this by going to `Settings -> Permalinks` instead.

== Screenshots ==

1. **Settings Page** - Configure the flush interval and select actions to trigger automatic permalink flushes.

== Changelog ==

= 1.0.0 =
* Initial release of Phlush Permalinks.
