=== Payment Gateway for ClicToPay on WooCommerce ===
Contributors: khlilturki97
Tags: WooCommerce, Payment gateway, clictopay
License: GPLv3
License URI: https://www.gnu.org/licenses/gpl-3.0.html
Tested up to: 5.5

ClicToPay Payment Gateway for WooCommerce (designed for stores in Tunisia)

== Description ==
This plugin adds a payment gateway to your store to allow receiving payments from ClicToPay gateway

1. Create an account with ClicToPay
2. Install the plugin and enable it
3. Configure the payment gateway with your credentials

== 3rd party ==
[ClicToPay](http://www.clictopay.com.tn/) is a banking service based in Tunisia which allows credit card payments through its gateway.
Please consider reading [ClicToPay Legal Page](http://www.clictopay.com.tn/pages/mentions-legales) before using this plugin.

== Changelog ==

= 1.0.3 =
* Hotfix for v1.0.2, fix for confirm order after payment. The order id stored in clictopay has been changed to "<order id>__<sub string of domain name><timestamp in format "YmdHis">"

= 1.0.2 =
* Change order name stored in ClicToPay system to <order id in woocommerce><domain name><timestamp in YmdHis format>, this allows to use the same ClicToPay account for multiple shops
* Fix payment confirmation page display

= 1.0.1 =
* Remove hard coded url
* Fix failed payment redirection by adding failed payment page
* Fix duplicate "Check Payment page"

= 1.0.0 =
* Initial version


== Upgrade Notice ==

= 1.0.1 =
This version fixes a redirection bug, upgrading is essential