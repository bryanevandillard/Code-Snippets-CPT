=== Code Snippets CPT ===

Plugin Name: Code Snippets CPT  
Plugin URI: http://dsgnwrks.pro/plugins/code-snippets-cpt  
Contributors: jtsternberg  
Donate link: http://j.ustin.co/rYL89n  
Author URI: http://jtsternberg.com/about  
Author: Jtsternberg  
Tags snippets, code, code snippets, syntax highlighting, shortcode  
Requires at least: 3.8.0  
Tested up to: 4.1.0  
Stable tag: 1.0.5  
License: GPLv2 or later  
License URI: http://www.gnu.org/licenses/gpl-2.0.html  

A WordPress plugin for managing and displaying code snippets.

== Description ==

A WordPress plugin for managing and displaying code snippets

Adds a custom post type for managing your code snippets with taxonomies for classifying the snippets. Embed snippets with syntax highlighting to posts or pages via a handy shortcode insert button that allows you to pick from the most recent snippets. Syntax highlighting provided by the [Ace Code Editor](http://ace.c9.io/#nav=about).

Feel free to [fork or contribute on Github](https://github.com/jtsternberg/Code-Snippets-CPT).

== Installation ==

1. Upload the entire `/code-snippets-cpt` directory to the `/wp-content/plugins/` directory.
2. Activate Code Snippets CPT through the 'Plugins' menu in WordPress.
3. Create a snippet.
4. Insert a snippet shortcode via the snippet tinymce button.

== Screenshots ==

1. Code Snippets admin listing
2. Editing code snippet
3. Code snippet shortcode in a post
4. Code snippet insert button/modal

== Changelog ==

= 1.0.5 =
* Add C# as available language.

= 1.0.4 =
* BUG FIX: Remove 'html_entity_decode' around snippet output, as it will cause the page display to break under certain circumstances.

= 1.0.3 =
* Replace shortcode button's usage of ids with slugs because ids can change during a migration.
* Added filter, 'dsgnwrks_snippet_display'.
* Better handling of WordPress-converted html entities.
* By default, convert tabs to spaces for better readability. Can be disabled with: `remove_filter( 'dsgnwrks_snippet_content', 'dsgnwrks_snippet_content_replace_tabs' );`
* Added title attribute to `pre` element to display title of snippet on hover.

= 1.0.2 =
* Add more languages
* Add lang parameter to shortcode attributes.
* Use selected snippet language to set the shortcode lang parameter.
* Allow shortcode to specify line number to start with

= 1.0.1 =
* WP editor buttons for inserting snippet shortcodes

= 1.0.0 =
* First Release

== Upgrade Notice ==

= 1.0.5 =
* Add C# as available language.

= 1.0.4 =
* BUG FIX: Remove 'html_entity_decode' around snippet output, as it will cause the page display to break under certain circumstances.

= 1.0.3 =
* Shortcodes now use slugs, new filter added, 'dsgnwrks_snippet_display', Better handling of WordPress-converted html entities, convert tabs to spaces for better readability, & Added title attribute to `pre` element to display title of snippet on hover.

= 1.0.2 =
* Add more languages, add lang parameter to shortcode attributes, selected snippet language is set on shortcode lang parameter automatically, and allow shortcode to specify line number to start with.

= 1.0.1 =
* WP editor buttons for inserting snippet shortcodes

= 1.0.0 =
* First Release
