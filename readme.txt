=== CASA Reference ===
Contributors: tomalrussell
Tags: ucl, publications, references
Requires at least: 4.3
Tested up to: 4.3
Stable tag: 1.0.2
License:            MIT License
License URI:        http://opensource.org/licenses/MIT

Create or upload references, and associate them with posts.

== Description ==

This plugin is intended to provide a simple bibliography management tool,
creating a 'reference' post and associating it with posts or pages.

= Usage: =

- Create a new reference from 'References' in the admin sidebar.
- Edit a page, add a reference using the 'References' metabox.
- A list of properly-formatted references will be appended to the content of the page.


== Installation ==

1. Upload the plugin files to the `/wp-content/plugins/wp-casa-reference` directory,
   or install the plugin through the WordPress plugins screen directly.
1. Activate the plugin through the 'Plugins' screen in WordPress


== Frequently Asked Questions ==

No questions so far.


== Changelog ==

= 1.0.2 =
Bump version number to prompt update.

= 1.0.1 =
Bugfix: use $wpdb->posts parameter for correct table when updating a reference title.

= 1.0 =
First release.


== Upgrade Notice ==

= 1.0.2 =
Fixes bug that affects saving references on multisite blogs.

= 1.0 =
First release.
