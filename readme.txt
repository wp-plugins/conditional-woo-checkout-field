=== Conditional Woo Checkout Field ===
Contributors: scott.deluzio
Tags: plugin, woocommerce, checkout, custom, customer, input, input field
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=W9AUXQM352ZY6
Requires at least: 3.1.0
Tested up to: 3.9.2
Stable tag: 1.0.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Display a custom field at checkout in your WooCommerce store if a certain product is in the customer's cart.

== Description ==
If you sell a product through your WooCommerce store that requires you to collect some additional information from your customers before they complete their purchase, this plugin is exactly what you need.

This plugin lets you configure an additional field to be displayed at checkout for your customer to fill out provided a certain product is in the customer's cart. The plugin allows you to customize this additional field's

* Title
* Input type (text box, text area, or select/drop down menu)
* Label
* Placeholder text
* CSS Class
* Whether or not the field is required (and the error message to display if it is required but not filled out)
* Whether or not to add the customer's input to the order email or invoice

This plugin requires your site to have WooCommerce installed in order to work. It is not compatible with other e-commerce plugins.

== Installation ==
1. Download archive and unzip in wp-content/plugins or install via Plugins – Add New.
2. Activate the plugin through the Plugins menu in WordPress.
3. In your WordPress dashboard, click on WooCommerce > Conditional Field.
4. Enter the information for your custom field, and click Save Changes.

== Frequently Asked Questions ==
= Where do I get the Product ID? =

Product IDs are found in your WordPress admin dashboard, by clicking Products > Products in the left menu. Hover your mouse over a product, and the ID number will be displayed directly below the product name next to the Edit links.

= How do I add options to the select menu =

In the Input Type column, choose Select from the dropdown menu. Then add the options as you want your customers to see them at checkout in the Select Options box directly below the menu. Enter one option per line. Do NOT use commas to separate your options.

= Why would I want to have an extra field at checkout? =

There are a number of reasons why you might want to have an extra field at checkout. Sometimes the default fields provided are not enough and there is extra information you need to collect from your customers.

A few examples include:

* Gift wrap options for a birthday, holiday, anniversary, etc.
* Allow customers to include a note with a gift.
* When customers need to provide a guest's name if purchasing tickets to an event.
* To indicate food preferences or allergies when food is included in the item being purchased, such as when booking a trip, or event.
* Find out how your customers heard about your store.


== Screenshots ==
1. Easily create a custom field at checkout for your customers to fill out.
2. Your custom checkout field will show up right after the other checkout fields for billing, shipping, and order notes.
3. Custom checkout field with Title, Field Label, and Text Box options. Field is set to be required as indicated by the asterisk.
4. Custom checkout field with Title, Field Label, and Text Area options. Field is set to be required as indicated by the asterisk.
5. Custom checkout field with Title, Field Label, and Select Menu options. Field is set to be required as indicated by the asterisk.
6. Custom error message displayed after the customer attempts to checkout without completing your required field.

== Changelog ==
= 1.0.2 =
* Bug fix to allow the field to not be required.

= 1.0.1 =
* Included POT file for translations.

= 1.0 =
* Initial release.

== Upgrade Notice ==
= 1.0.2 =
* Bug fix to allow the field to not be required.