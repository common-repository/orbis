=== Orbis ===
Contributors: pronamic, remcotolsma, kjtolsma
Tags: orbis, intranet
Requires at least: 3.0
Tested up to: 4.3.1
Stable tag: 1.3.3

Orbis is a powerful, extendable plugin to boost up your business. Project Management, Customer Relation Management & More...

== Description ==

This plugin transforms your WordPress environment into a fully operating 
business tool. Orbis has some nice basic Project Management, Customer Relation 
Management & Intranet functionalities. Make Orbis even more powerfull with some 
cool additional plugins.

This plugin is built with idea to make business tools extendable. Every 
business is different. We believe in the power of WordPress and although 
WordPress may not be your first idea to serve as a framework for such a tool, 
we feel it has shown many advantages, particularly with extendability and 
control. 

Orbis comes with a front-end theme with the very orginal name, Orbis. This 
theme is based on Bootstrap and gives you all the front-end functionality you 
need. Easely extend this theme with child themes. We’ll try to release more
 themes.

[Download the Orbis theme for free.](http://www.pronamic.eu/themes/orbis/)

= Benefits at a glance =

*	Easily extendable with plugins
*	Fully translatable
*	The Orbis Framework is available for FREE
*	Various high quality themes
*	Fully manageable
*	Use you own hosting environment
*	Built on WordPress

= Core Features =

*	Manage Projects - Add projects and connect them to companies
*	Manage Persons - Add persons and connect them to companies
*	Manage Companies - Add companies
*	Pages - Use the standard WordPress functionality to add pages
*	Posts - Use posts for your intranet
*	Comments - Comment on Pages, Projects, Persons & Companies

= Extend =

The power of Orbis lays in the extendability and flexibility. Use plugins to 
add the functionality you need.

*	[Orbis Tasks](http://www.pronamic.eu/plugins/orbis-tasks/) - Add tasks to Persons and connect them to Projects
*	[Orbis Keychains](http://www.pronamic.eu/plugins/orbis-keychains/) - Alle your passwords im a save place
*	[Orbis Timesheets](http://www.pronamic.eu/plugins/orbis-timesheets/) - Submit your time en connect them to Projects.

= Get involved =

Want to contribute? Checkout the source code on the Orbis GitHub Repository.


== Functions ==

*	General
	*	orbis_format_seconds(  $seconds, $format = 'HH:MM' )

*	Projects
	*	orbis_project_get_the_time( $format = 'HH:MM' )
	*	orbis_project_the_time( $format = 'HH:MM' )

*	Flot
	*	orbis_flot( $id, $data, $options )


== Installation ==

Extract the zip file and just drop the contents in the wp-content/plugins/ directory of your 
WordPress installation and then activate the Plugin from Plugins page.


== Screenshots ==

1.	Home
2.	News
3.	Person
4.	Persons
5.	Project
6.	Projects
7.	WordPress


== Changelog ==

= 1.3.3 =
*	Tweak - Changed bussiness to business in README.
*	Fixed - Fix WP 4.3 deprecated WP_Widget method.
*	Tweak - WordPress Coding Standards optimizations.

= 1.3.2 =
*	Fixed - Fixed issue with project status change comments.

= 1.3.1 =
*	Fixed - Fixed issue with more project status change comments.

= 1.3.0 =
*	Added - Added daily recap email system.
*	Added - Added company category taxonomy.
*	Added - Added support for pound sterling.

= 1.2.2 =
*	Tweak - Adjusted WordPress admin company post type menu dashicon from 'network' to 'building'.
*	Test - Tested up to WordPress version 4.1.
*	Tweak - WordPress Coding Standards optimizations.

= 1.2.1 =
*	Tweak - Fixed notice on projects table view template.
*	Tweak - Added post publish date on the project table view template.

= 1.2.0 =
*	Tweak - Updates Select2 from v3.4.6 to v3.5.1.
*	Tweak - Use [Bower](http://bower.io/) for some libraries.
*	Tweak - Removed deprecated screen_icon() function call.
*	Tweak - Changed capability to 'manage_options' for now.
*	Tweak - WordPress Coding Standards optimizations.
*	Tweak - Added AngularJS libraries for Orbis Tasks plugin.

= 1.1.1 =
*	Tweak - Project finish modification dates are now stored in meta data for order by.  

= 1.1.0 =
*	Tweak - Switched from custom menu icons to the new WordPress [Dashicons](http://melchoyce.github.io/dashicons/).
*	Tweak - Everyone can now finish projects, the WordPress comment system is used to keep track of changes.
*	Tweak - Moved the person contact information meta box from the side to the normal edit area.
*	Tweak - Enabled WordPress custom fields functionality on the Orbis person, company and project post types.

= 1.0.5 =
*	Improved the orbis_price() template function.
*	Improved uninstall script.

= 1.0.4 =
*	Added support for an Orbis persons suggest field.

= 1.0.3 =
*	Added custom column 'e_mail' to the custom companies table.

= 1.0.2 =
*	Added custom Posts 2 Posts labels.

= 1.0.1 =
*	Added project finished field.

= 1.0.0 =
*	Initial release.


== Links ==

*	[WP-Admin Icons](http://wordpress.org/extend/plugins/wp-admin-icons/)
*	[Pronamic](http://pronamic.eu/)
*	[Remco Tolsma](http://remcotolsma.nl/)
*	[Markdown's Syntax Documentation][markdown syntax]

[markdown syntax]: http://daringfireball.net/projects/markdown/syntax
            "Markdown is what the parser uses to process much of the readme file"
