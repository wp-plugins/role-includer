=== Plugin Name ===
Contributors: justinticktock
Tags: roles, user, cms, groups, teams
Requires at least: 3.5
Tested up to: 4.1
Stable tag: 1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Simple settings page to allocate multiple roles to a user.

== Description ==

There are lots of plugins to handle roles and capabilities, however, none seem to provide a simple interface for multiple roles to be assigned only.

This plug plugin expects the complexity of capabilities to be handled by other plugins and the site Administrator, but provides any user with the 'promote_users' capability to handle allocation of roles.

So by simply create a new role, for example "staff" and add the 'promote_users' capability to this role.  Then for this example staff members will be able to handle role assignment.  
 

Also if you wish to hide/mask-out a particular role from "staff" ( such as "Administrator" ) then you can exclude these using the "role excluder" plugin available over at [justinandco.com](https://justinandco.com/plugins/)

== Installation ==

1. Upload `plugin-name.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Goto the admin Users menu..All Users, hover over a user name in the listing and select “Roles”
4. Select/De-select the roles required for the user.

== Frequently Asked Questions ==

= I have a new role how can I add it? =

You will need to use another plugin to manage roles and capabilities such as the [User Role Editor]( http://wordpress.org/extend/plugins/user-role-editor/ "User Role Editor" ) plugin.

= Is there a theme template I can modify in my child theme? =

Yes ... [Answer]( http://wordpress.org/support/topic/is-there-a-theme-template-i-can-modify-in-my-child-theme?replies=3#post-4929519)

== Screenshots ==

1. The Settings Screen.
2. A front end example Help Note for a user with the 'Proof Reader' role, also showing the user widget listing all proof readers.
3. Dashboard showing Help Notes at WordPress 3.8
4. The 'Appearance..Widgets' Admin screen using the 'Help Note Users' widget with the 'twenty fourteen' theme sidebar
5. The 'twenty fourteen' theme showing the Contents page for a user with 'Proof Reader' role access.

== Changelog ==

Change log is maintained on [the plugin website]( https://justinandco.com/plugins/role-based-help-notes-change-log/ "Role Based Help Notes Plugin Changelog" )

== Upgrade Notice ==

= 1.2.9.1 =
The User Widget has been changed to fix conflicts.  
Due to this you will need to replace the widget in your sidebar!