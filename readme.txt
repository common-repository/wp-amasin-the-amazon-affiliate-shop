=== WP AmASIN - The Amazon Affiliate Shop ===
Contributors: websupporter
Tags: amazon, affiliate, asin, ecommerce, marketing, shop
Requires at least: 3.0.1
Stable tag: 0.9.7
Tested up to: 3.8.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This plugin sets up a Amazon Affiliate Store and delivers some Shortcodes to integrate Amazon Affiliate functions.

== Description ==

WP AMAZON enables you to open your own Amazon Affiliate Shop at your Blog. You can easily search for products to
add to your shop. The Plugin works with all Amazon Affiliate Programs including:
* www.amazon.com
* www.amazon.ca
* www.amazon.de
* www.amazon.co.uk
* www.amazon.co.jp
* www.amazon.cn
* www.amazon.es
* www.amazon.it
* www.amazon.in
* www.amazon.fr

We have developed a whole new Post Type (called 'products') in order not to mix your Blogposts with Productposts. You can easily adjust
the Layout of this Post Type with our Template Generator (works with ~90% of all Themes). By Widgets and Shortcodes you can make
your Shop browseable for your visitors. You can define, which information will be displayed on the single product page and add your
Custom Styles if you like.

After you have added a product, it automatically contains the pictures, the description and the product data which will be delivered in
a table. For every posted product, you can decided, which information you want to display. In order to fasten your application, the data
is stored in your database. By using WP Cronjobs or regular Cronjobs, you can automatically update them!

WP AMAZON includes a complete shopping cart system, you can integrate by Shortcode and Widget. We deliver more than three different Widgets,
a complete new Sidebar to create your own Product-Sidebar and more than four Shortcodes.

The product page includes all available information, customer reviews, similar products and a beautiful picture gallery.

For more information please visit our WP Amazon Page: http://www.websupporter.net/wp-amazon/

Available languages: English, Deutsch, German, Spanish, Espanol

== Installation ==

1. Upload the Plugin to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Enter your Amazon Keys (Affiliate and API Keys) in WP-Amazon > Settings > Amazon
1. Create a new Template in WP-Amazon > Settings > Template
1. Add products in WP-Amazon > Products
1. Update your Permalink Structure
1. Set up the WP-Amazon Sidebar and include the Shoppingcart Widget
1. Create a Startpage for your Shop and use our Shortcodes to make your product categories browsable

== Frequently Asked Questions ==

= Where do I find more information? =

Visit our WP Amazon Page under http://www.websupporter.net/wp-amazon/


= There is no Sidebar in my Template =
Have you generated your template with the Template Generator? If you are still missing a Sidebar, you will find the Template in the directory
'includes\products'. The name of the template will be 'template-[Name Of The Theme].php'.
Here you can add a Sidebar by using this code: <?php dynamic_sidebar( 'wp-amazon-product' ); ?>

= There is no Title in my Template =
See the answer above. Use this code instead:
<h1><?php the_title(); ?></h1>

= I need help with my Template =
Visit our Support Forum (http://websupporter.net/wp-amazon/forum). Here you can ask for a template. Please provide us with the following information:
* Name of Theme
* Version of Theme
* Your Website
We will try to provide you with a better Template

= I don't like my product category pages =
How the product categories are displayed depends on your Theme. But we want to build a repository with different styles for different themes. Contact
us through our Support Forum (http://websupporter.net/wp-amazon/forum)


== Changelog ==

= 0.9.7 =
* Security Fix at the Amazon Review Integration
* Got rid of the "Share program"
* Bugfix for empty Country, empty Categories etc.
* Redirect after "Add to Cart"

= 0.9.6 =
* incl. Spanish language 
* Standard-Template update
* Line Break Bug fixed
* "Read More"-Bug fixed
* Added support for Amazon India
* Minor Database Error concerning wpdb->prefix
* Fixed Updating-Problem: Updates used to delete the template-file.
* Added the GBP-Symbol

= 0.9.5 =
* Fixed Meta-Data

= 0.9.4 =
* Fixed Cronjob Bug
* Deleted some unnecessary files
* Adjust WP AmASIN Icon

= 0.9.2 =
* Updated Template-Generator
* Fixed bug in Product Search
* Fixed some bugs

= 0.9.1 =
Update to fix some broken links in the script.

= 0.9 =
First release.