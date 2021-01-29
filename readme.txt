=== Regenerate product lookup table for WooCommerce ===
Contributors: metalfreek
Donate link: http://sumanbhattarai.com.np/
Tags: woo, woo commerce
Requires at least: 5.3
Tested up to: 5.6
Requires PHP: 7.2
Stable tag: 1.0.1
License: GPLv3
License URI: https://www.gnu.org/licenses/gpl-3.0.html

This plugin auto regenerates Woocommerce product lookup table which is helpful when product sorting functionality is
not working as expected.

== Description ==

If you are using Woocommerce for you store and having trouble with sorting function in products page of Woocommerce, this plugin might help. This sort issue
is seen especially when there is automated script pulling in products to the store. This plugin adds cron to regenerate product lookup table which Woocommerce users to quickly sort your products.

== Installation ==

1. Upload the plugin files to the `/wp-content/plugins/wc-regenerate-product-lookup` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress
3. Go to **Settings->Woocommerce regenerate product lookup table** page to configure the plugin


== Frequently Asked Questions ==

= What is the default cron run duration =

By default plugin adds cron twice a day. If its not working for you change the duration to lower time (possibly once an hour).

== Screenshots ==

1. Regenerate product lookup table for WooCommerce plugin option

== Changelog ==

= 1.0.0 =
* First Release date: January 31, 2021