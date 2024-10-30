=== Image Licensing Schema – Structured Data for Google Images ===
Contributors: audrasjb
Tags: structured data, image license, schema, licensing, Google Images, schema.org
Requires at least: 5.4
Tested up to: 6.4
Stable tag: 1.3
Requires PHP: 5.6
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
Donate link: https://paypal.me/audrasjb

Provide proper Licensing for your images, using Schema.org structured data for Google Images.

== Description ==

Google Images now supports "license" Schema.org Structured Data.

It's useful for website owners, as they can use those structured data to show the preferred Licensing Policy for the images used on their website. They can also use this plugin to appear on top of the Google Image search tool for specific license filtered searches.

This plugin provides Licensing for your website images, using Schema.org structured data for Google Images. And even if your images are not free to use, it’s always interesting to appear on Google Images, with the right license and a nice link to your website Image license policy page (which is most of the time your Legal Notice page).

For more information, see the related resources:

- [Google Search Console FAQ about Image licensing structured data](https://support.google.com/webmasters/thread/31516792)
- [Google Structured Data Documentation](https://developers.google.com/search/docs/data-types/image-license-metadata)

### Current implementation and roadmap/next steps

For the moment, this plugin supports all the Creative Commons licenses. Plus, you can select your very own license policy (requires a custom licensing policy page).

The plugin also builds a specific image policy link that will be displayed on Google Image. So if they want to use your image, people will be asked to give you proper credits, according to your licensing policy.

Next steps:

- Support more licenses: feel free to ask for specific licenses in the [support forum](https://wordpress.org/support/plugin/image-licensing-schema/)!
- Provide a Licensing Policy Page builder, just like WordPress Core does with the Privacy Policy page.

== Screenshots ==

1. Plugins default settings are located in Settings > Media.
2. On both Gutenberg and Classic Editor, you can edit your image license image by image.
3. On Google Images search results: your images will be showing a "Licensable" badge.
4. And there will be a link to your license and a link to your License Policy Page.
5. Specific image policy link page is displayed when Google Images users will click on the "Acquire license" link.

== Changelog ==

= 1.3 =
- Adds post thumbnails support. Thanks to @cembtw for their feature request.

= 1.2 =
- Adds the ability to manage licensing on an image by image basis on all post types. Thanks to @agneskarikaturen for their feature request.

= 1.1.1 =
- Adds an omitted conditional statement to check if the current post contains images. Thanks Samy Rabih for the bug report.
- Lower required PHP version

= 1.1 =
- Adds the specific image licensing policy feature.

= 1.0.2 =
- Fixes some Jetpack compatibility issues. Thanks Samy Rabih for the bug report.

= 1.0.1 =
- Fixes an issue with some transients.

= 1.0 =
- Initial release.