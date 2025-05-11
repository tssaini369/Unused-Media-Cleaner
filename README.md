=== Unused Media Cleaner ===
Contributors: TeeJay
Author URI: https://nexlifylabs.com/
Requires at least: 5.0
Tested up to: 6.8
Version: 1.0.8
Stable tag: 1.0.8
Requires PHP: 7.4
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

== Description ==

**Unused Media Cleaner** helps you keep your WordPress site lean by finding and removing media files that are not used anywhere on your site. This plugin is designed for professional use and is available only to paid users.

== Features ==

- **Scan for Unused Media:** Quickly scan your media library to find files that are not referenced anywhere in your content.
- **Selective File Type Scanning:** Filter and scan by images, videos, audio, PDFs, or all media types.
- **Bulk Actions:** Move unused media to trash or delete them permanently with one click.
- **Safe Trash:** Move files to trash before permanent deletion for extra safety.
- **Pagination and Sorting:** Easily browse, sort, and manage large media libraries.
- **Detailed References:** See exactly where each media file is used before deleting.
- **Improved Error Handling:** Enhanced error handling for media deletion.
- **WooCommerce Support:** Added support for detecting product variation images.
- **Export Media:** Select and export unused, used, or trashed media as a ZIP file with one click.
- **Secure Export Storage:** Exported ZIP files are stored in a protected folder and cannot be accessed directly from the web.
- **Automatic ZIP Cleanup:** Exported ZIP files are automatically deleted after 1 hour to keep your server clean and secure.
- **Advanced Used Image Detection:** Improved logic for detecting images in use across your site, reducing false positives and missed files.

== What Does It Check? ==

Unused Media Cleaner checks for media usage in:

- **Post Content:** Finds media referenced in the content of posts, pages, and custom post types.
- **Featured Images:** Detects media set as featured images (thumbnails) for posts and pages.
- **ACF Fields:** Scans Advanced Custom Fields for media references.
- **Elementor Data:** Searches Elementor page builder data for media usage.
- **Theme Mods:** Looks for media used in theme customizer settings.
- **Custom Fields:** Checks all custom fields for media references.
- **Serialized Data:** Handles serialized and JSON-encoded data in meta fields.
- **URL References:** Finds direct URL references to media files.
- **Repeater Fields:** Supports ACF and other repeater fields containing media.
- **Elementor CSS:** Scans Elementor-generated CSS for background images and other media.

== Installation ==

1. Purchase and download the plugin from https://nexlifylabs.com/
2. Upload the plugin ZIP file via the WordPress admin Plugins > Add New > Upload Plugin.
3. Activate the plugin.
4. Enter your license key to unlock all features.

== Frequently Asked Questions ==

= Is this plugin safe to use on a live site? =
Yes, but always back up your site before deleting media. Use the trash feature for extra safety.

= Does it support custom post types and fields? =
Yes, it scans all post types and custom fields, including ACF and Elementor.

= Can I restore media from trash? =
Yes, you can restore media files from the trash before permanent deletion.

= How can I contact support? =
For support inquiries, please visit https: https://nexlifylabs.com/support/ or email us at support@nexlifylabs.com

== Changelog ==

= 1.0.8 =
* Improved the admin interface for better usability

= 1.0.7 =
* Improved detection of media in WPBakery Templates


= 1.0.6 =
* Added support for Elementor's new dynamic tags
* Improved detection of media in Elementor templates and global widgets
* Fixed issues with serialized data in custom fields
* Delete button and Restore button Fixed

= 1.0.5 =
* Fixed Export feature: Exported ZIP files are now stored in a protected folder and cannot be accessed directly from the web

= 1.0.4 =
* Added advanced used image detection logic for improved accuracy
* New Export feature: Download selected media as a ZIP archive
* Secure export: Exported ZIP files are stored in a protected folder and are not publicly accessible
* Automatic cleanup: Exported ZIP files are automatically deleted after 1 hour for security and storage efficiency
* Minor UI and performance improvements
* Media Inspector: Added a new feature to inspect media usage in detail
* Added a new "Used Media" tab to view all media currently in use

= 1.0.3 =
* Added support for Elementor's new dynamic tags
* Improved detection of media in Elementor templates and global widgets
* Fixed issues with serialized data in custom fields
* Delete button and Restore button Fixed

= 1.0.2 =
* Added WooCommerce product variation image detection
* Improved handling of serialized data in custom fields
* Fixed false positives in Divi Theme Builder scans
* Optimized database queries for better performance
* Added pagination for large media libraries

= 1.0.1 =
* Added comprehensive Divi Builder compatibility:
    - Detects images used in Divi Theme Builder global headers, footers, and templates
    - Scans Divi Library layouts and reusable sections
    - Detects images in Divi modules, galleries, and custom fields
    - Handles Divi shortcodes and serialized data
* Improved detection logic to reduce false positives

= 1.0.0 =   
* Initial release with core scanning functionality

== Upgrade Notice ==
1.0.8 - Improved the admin interface for better usability
1.0.7 - Improved detection of media in WPBakery Templates
1.0.6 - Added support for Elementor's new dynamic tags and improved detection of media in Elementor templates.
1.0.5 - Fixed Export feature: Exported ZIP files are now stored in a protected folder and cannot be accessed directly from the web.
1.0.4 - Adds advanced image detection and secure export as ZIP.
1.0.3 - Elementor dynamic tags support added.
1.0.2 - Performance improvements and WooCommerce support.
1.0.1 - Improved Divi detection accuracy.
1.0.0 - Initial release.

== Roadmap ==
* Scheduled automatic scanning
* Cloud storage integration
* Advanced reporting features


== License ==

This plugin is proprietary and available only to paid users.
