=== User Tags ===
Contributors: UmeshSingla
Tags: Tags, taxonomies, user taxonomy, user tags
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
Requires at least: 3.0
Tested up to: WordPress 3.8.1
Stable tag: trunk

Adds an admin option to allow creating User Taxonomies and create tags for different taxonomies.

== Description ==

Adds a **Taxonomies** option under **User** to create custom user taxonomy.
All taxonomies are listed in Profile page for all users which allows users to add tags for the taxonomy.
Each Tag is associated with a template, listing all users who added that tag in their profile.
Note:
Only admin can manage Taxonomies.
Users can add new tags.

== Installation ==

1. Upload the `wp-user-taxonomies` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Go to Taxonomies under Users option to create taxonomies for User

== Changelog ==

= 0.1.2 =
 Fixes Taxonomy length error

= 0.1.1 =
 Code formatting

= 0.1 =
 First Release

== Upgrade Notice ==

Requires Wordpress 3.0 atleast

== Frequently Asked Questions ==

= What if tags template are not working for me? =

You just need to save permalinks once, and it will work absolutely fine for you afterwards.

= Visit https://github.com/UmeshSingla/user-tags for support =

== Screenshots ==

1. Taxonomy Option under Users
2. Manage Tags for Custom User Taxonomy Food Like
3. Tags option in User profile Page
4. Template page for tag, listing all the associated users
== Other Notes ==

Filters Available
1. 'ut_template_heading' => Can be used to modify Template Page Heading 
2. 'ut_tepmplate_content' => Can be used to modify users list style, 
        args => 1 , $users => List of Users
3. 'ut_template_content_empty'  => Display custom message, if there are no users for term

Shortcode

[user_tags], will generate the User Tags UI in frontend and save the tags

== Credits ==
[Justin Tadlock][http://justintadlock.com/archives/2011/10/20/custom-user-taxonomies-in-wordpress]