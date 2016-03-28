=== WDS Shortcodes ===
Contributors:      WebDevStudios
Donate link:       http://webdevstudios.com
Tags:              shortcode button, shortcodes, cmb2, utility
Requires at least: 4.3
Tested up to:      4.3
Stable tag:        0.1.3
License:           GPLv2
License URI:       http://www.gnu.org/licenses/gpl-2.0.html


== Description ==

WDS-Shortcodes gives developers the ability to easily register shortcodes with a corresponding button, so never again will your client ask, `What's that shortcode again?` Not only can you easily handle the button and shortcode registration, this also supports self-closing and wrapping shortcodes with a simple config flag.

Additionally, there is also built-in [CMB2](http://wordpress.org/plugins/cmb2/) support so you can use all your favorite fields.

For more info, [check out the wiki](https://github.com/WebDevStudios/WDS-Shortcodes/wiki).

To see a demo plugin, check out "[Cool Shortcode](https://github.com/jtsternberg/Cool-Shortcode)".

== Installation ==

= Manual Installation =

1. Upload the entire `/wds-shortcodes` directory to the `/wp-content/plugins/` directory.
2. Activate WDS Shortcodes through the 'Plugins' menu in WordPress.

== Frequently Asked Questions ==

* None as of yet

== Screenshots ==
1. Preview of a working CMB2 metabox

== Changelog ==

= 0.1.3 =
* Update composer lock file and zip file after updating Shortcode_Button dependency.

= 0.1.2 =
* New method, `WDS_Shortcode::maybe_json()` which automatically converts attributes from the modifed JSON string [created by Shortcode_Button](https://github.com/jtsternberg/Shortcode_Button/commit/c186e98b2f94a1e565d85593033d9b2a499d9e8e#diff-6846d1b0c8144484af006af499cd053dR397) into a normal PHP array.

= 0.1.1 =
* Fix issues with ajax hooks not working (as they get hooked too late)

= 0.1.0 =
* First Release

== Upgrade Notice ==

= 0.1.3 =
* Update composer lock file and zip file after updating Shortcode_Button dependency.

= 0.1.2 =
* New method, `WDS_Shortcode::maybe_json()` which automatically converts attributes from the modifed JSON string [created by Shortcode_Button](https://github.com/jtsternberg/Shortcode_Button/commit/c186e98b2f94a1e565d85593033d9b2a499d9e8e#diff-6846d1b0c8144484af006af499cd053dR397) into a normal PHP array.

= 0.1.1 =
* Fix issues with ajax hooks not working (as they get hooked too late)

= 0.1.0 =
* First Release
