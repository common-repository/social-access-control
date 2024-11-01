=== Social Access Control ===
Contributors: Justin at Multinc
Donate link: http://multinc.com/wp/donate
Tags: social privacy, social, privacy, private, protect, restrict, restriction, permit, permission, permissions, rights, allow, access, categories, post, url
Requires at least: 2.0.2
Tested up to: 2.6.3
Stable tag: 1.1

Based on the 3rd-party Category Access, this plugin provides the core functionality for restricting the access permissions of posts.  This gives you the ability to permit only specific registered users to read certain posts or certain categories of posts.

This plugin is part of the [Social Privacy](http://wordpress.org/extend/plugins/social-privacy/) set of plugins and it's recommended that you install the entire set at one time to get complete control over access to your posts on your blog.

== Description ==

Based on the 3rd-party Category Access, this plugin provides the core functionality for restricting the access permissions of posts.  This gives you the ability to permit only specific registered users to read certain posts or certain categories of posts.

This plugin is part of the [Social Privacy](http://wordpress.org/extend/plugins/social-privacy/) set of plugins and it's recommended that you install the entire set at one time to get complete control over access to your posts on your blog.

= Differences between the original plugin and our plugin =

The 3rd-party [Category Access](http://www.coppit.org/blog/archives/173) plugin provides the core functionality for restricting the access permissions of posts to certain registered users.  For each user you can list the categories that he or she should have access to.

New features have been added to our version of this plugin to allow access to be restricted to specific users on a per-post basis, regardless of the categories.  The plugin has also been enhanced to work well with the other plugins in [Social Privacy](http://wordpress.org/extend/plugins/social-privacy/) set, which add similar restriction capabilities to email and feeds.

If you decide to stop using this plugin, there is an additional feature that lets you make all your protected posts "private" so that they're not suddenly exposed to the public once the plugin is deactivated.

== Installation ==

1. Upload `social-access-control` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

= Configuration =

* For general settings and to control per-category access, go to the Admin 'Settings' page and select 'Social Access Control'.
* To control per-post access, go to the 'Social Access Control' section on the Write/Manage Post page.
* To control per-category a user-by-user basis, edit the user's profile.
* For other settings and issues, refer to the original Category Access readme file (`readme-old.txt`)

= Uninstallation =

If you decide to deactivate this plugin, you may not want all your restricted posts to suddenly become visible to everyone.  If that's the case, you can convert all the restricted posts to the standard WordPress "private" mode before deactivating the plugin.

To privatize posts before deactivating the plugin (or to undo):

1. Make sure to activate the sub-plugin 'Social Access Control - Privatize Posts'.
1. Go to the 'Manage' tab and select the 'Privatize Posts' page.

== Frequently Asked Questions ==

= What happens if I decide to deactivate or uninstall this plugin? =

Your protected posts can remain hidden from public view.  See the [Installation instructions](http://wordpress.org/extend/plugins/social-access-control/installation/)

== Screenshots ==

1. Controlling per-category access
2. Controlling per-post access
3. Controlling per-category access on a user-by-user basis
4. To privatize posts before deactivating this plugin (or to unprivatize posts after re-activating this plugin)
