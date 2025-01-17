=== MCE Table Buttons ===
Contributors:      10up, jakemgold, helen, thinkoomph
Donate link:       http://10up.com/plugins-modules/wordpress-mce-table-buttons/
Tags:              tables, table, editor, WYSIWYG, buttons, tinymce, classic editor
Requires at least: 4.0
Tested up to:      5.9
Stable tag:        3.3.1.2
Requires PHP:
License:           GPLv2 or later
License URI:       https://www.gnu.org/licenses/gpl-2.0.html

Adds table editing controls to the visual content editor (TinyMCE).

== Description ==

Adds table editing controls to the visual content editor (TinyMCE).

A light weight plug-in that adds the table editing controls from the full version of TinyMCE, optimized for WordPress. Note that this may not work in conjunction with other plug-ins that significantly alter or replace the visual editor's default behavior.

Note that the table controls are contained in the “kitchen sink” toolbar, toggled with the last button on the first row of controls.

== Installation ==

1. Install easily with the WordPress plugin control panel or manually download the plugin and upload the folder
`mce-table-buttons` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Show the toolbar in the editor by opening the "kitchen sink" (the last button in the first row)

== Screenshots ==

1. The editor with the added table editing controls.

== Changelog ==

= 3.3.1 =
**Note that this release replaces references of `master` with `trunk` so please plan to update any references you have from `master` to `trunk` to ensure you continue to receive the latest updates on this plugin.**

* **Changed:** Bump WordPress version “tested up to” 5.8 (props [David Chabbi](https://profiles.wordpress.org/davidchabbi/), [@jeffpaul](https://github.com/jeffpaul), [@ciprianimike](https://github.com/ciprianimike)).
* **Changed:**  Updated documentation including new GitHub Actions (props [@jeffpaul](https://github.com/jeffpaul), [@dinhtungdu](https://github.com/dinhtungdu)).
* **Fixed:** Issues reported by PHPCS WPCS v2.3.0 (props [@ciprianimike](https://github.com/ciprianimike), [@dinhtungdu](https://github.com/dinhtungdu)).

= 3.3 =
* Significantly update TinyMCE plugin from 4.1.x to 4.7.11
* Drop support for WordPress 3.x, which means dropping TinyMCE 3.x and 4.0.x

= 3.2 =
* WordPress 4.0 support, including a much newer TinyMCE plugin, with many new features, including background color and horizontal alignment
* Dramatically improved support for paragraphed content inside of a cell (paragraph breaks no longer disappear on save)

= 3.1 =
* Updated core TinyMCE table plugin from 4.0.20 to 4.0.21 in sync with WordPress - mostly bug and accessibility fixes
* Refactored for compatibility with plugins like Advanced Custom Fields that do not use the_editor hook

= 3.0 =
* Support for WordPress 3.9 and newer, which includes a major visual editor upgrade (TinyMCE 4)

= 2.0 =
* New button icons that better conform with WordPress's editor design
* Retina (HiDPI) ready button icons!
* Upgraded to latest version of TinyMCE tables plugin (fixes a lot of edge case bugs)
* Rewrote code for hiding / display toolbar with kitchen sink (now a TinyMCE plug-in instead of a workaround) - the table buttons no longer briefly appear before page loading is finished

= 1.5 =
* Table toolbar is hidden or displayed along with the kitchen sink (yay!)
* Minor clean up to code base and files; optimized for WordPress 3.3

= 1.0.4 =
* Updated TinyMCE table plug-in to corresponding TinyMCE update in WordPress 3.1 (still supports <3.1 too)

= 1.0.3.1 =
* Updated support / developer information

= 1.0.3 =
* Code clean up, 3.1 testing

= 1.0.2 =
* Fixed editor save warning appearing for unchanged content when the table is at the bottom of the editor
* Minor code clean up

= 1.0.1 =
* Fixed issue with WebKit browsers (Safari and Chrome) - TinyMCE bug

== Upgrade Notice ==

= 3.3.1 =
This release replaces references of `master` with `trunk` so please plan to update any references you have from `master` to `trunk` to ensure you continue to receive the latest updates on this plugin.

= 1.5 =
REQUIRES WordPress 3.3 or higher. Finally links table buttons row to kitchen sink!
