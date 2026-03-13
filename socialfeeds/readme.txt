=== SocialFeeds ===
Contributors: softaculous
Tags: social feeds, instagram feed, youtube feed, social media, youtube videos
Requires at least: 5.0
Tested up to: 6.9
Requires PHP: 7.2
Stable tag: 1.0.3
License: GPLv2
License URI: https://www.gnu.org/licenses/gpl-2.0.html

YouTube feeds for WordPress with simple Setup and Settings options.

== Description ==

SocialFeeds is a lightweight and easy-to-use WordPress plugin designed to showcase Instagram and YouTube content directly on your website. With quick setup and shortcode support, you can display social media feeds anywhere on your site and keep your content fresh and engaging.

== SocialFeeds YouTube Free Features ==

- Display YouTube channel videos
- Quick and easy feed setup from the dashboard
- Show video title, description, play icon, lazy loading, and click-to-play action
- Apply hover effects on video items
- Display feed header with channel name, logo, description, custom logo, and banner
- Show YouTube subscribe button in the header
- Load more videos using the Load More button
- Basic layout and style customization
- Fully responsive and theme compatible

== Upgrade to SocialFeeds PRO for More Power ==

Unlock advanced capabilities with **SocialFeeds PRO**, such as:

- Connect multiple YouTube channels and Instagram accounts
- Display YouTube video duration, publish date, view count, like count, and comment count
- Show YouTube single videos, playlist feeds, and live stream videos
- Enable YouTube video search and advanced filtering options
- Apply advanced design customization for YouTube feeds including colors, fonts, spacing, and styling
- Display Instagram feeds using Grid, Carousel, and Masonry layouts
- Control Instagram feed columns for desktop, tablet, and mobile devices
- Set Instagram content limits and post loading options
- Customize Instagram feed header position, size, profile avatar, bio, follower count, and media count
- Enhance Instagram post experience with captions, likes, comments, posts, reels, icons, and play modes
- Enable Instagram hover states and interaction effects
- Add and customize Instagram follow button
- Customize Instagram Load More button behavior and design
- Sort Instagram posts by newest, most liked, or random order
- Filter Instagram posts by post type, content, and media format
- Control Instagram post spacing, alignment, and aspect ratio

== Why Use SocialFeeds? ==

- Increase visitor engagement with live social media content
- Promote your YouTube and Instagram profiles directly on your website
- Improve website appearance with modern and responsive feed layouts
- Easy integration with shortcodes and page builders

= Third Party API usage =

1. YouTube Search API: This plugin uses the YouTube Data API to retrieve publicly available YouTube videos based on search queries configured by the user. When enabled, the plugin sends the search term and the YouTube API key provided by the user to Google servers. The API returns public video data such as titles, descriptions, thumbnails, and video IDs.

2. YouTube Channels API: This plugin uses the YouTube Data API to retrieve publicly available information about a YouTube channel. When enabled, the plugin sends the channel ID and the YouTube API key provided by the user to Google servers. The API returns public channel data such as channel name, description, thumbnails, statistics, and other public metadata.

Service Provider: Google LLC (YouTube Data API v3)

Terms of Service: https://developers.google.com/youtube/terms/api-services-terms-of-service  
Privacy Policy: https://policies.google.com/privacy

== Installation ==

**Automatic Installation**
1. Go to WordPress Admin → Plugins → Add New
2. Search for **SocialFeeds**
3. Click **Install Now**, then **Activate**
4. Open SocialFeeds from the dashboard
5. Connect your YouTube or Instagram account
6. Add feeds using shortcodes

**Shortcodes**

Instagram Feed:
[socialfeeds id="1" platform="instagram"]

YouTube Feed:
[socialfeeds id="2" platform="youtube"]

**Manual Installation**
1. Download the plugin ZIP file
2. Go to Plugins → Add New → Upload Plugin
3. Upload `socialfeeds.zip`
4. Install and activate the plugin

== Frequently Asked Questions ==

= Can I display multiple feeds? =
Yes. The Pro version allows multiple feeds and accounts.

= Can I customize layouts and styles? =
Yes. Basic customization is available in the free version, with advanced controls in Pro.

= Is SocialFeeds compatible with all themes? =
Yes. SocialFeeds works with all standard WordPress themes and page builders.

== Screenshots ==
1. SocialFeeds dashboard
2. YouTube Feeds Type
3. Youtube Customize
4. Instagram Accounts
5. All Feeds

== Start Using SocialFeeds ==

Install SocialFeeds today to display your Instagram photos and YouTube videos on your WordPress website and keep your content always up to date.


== Changelog ==

= 1.0.3 =

* [Feature] Added option to customize the feed name.

= 1.0.2 =

* [Pro-Feature] Added YouTube and Instagram Gutenberg blocks.
* [Bug-Fix] Fixed an issue where the YouTube subscribe text could not be customized in the preview.
* [Bug-Fix] Fixed an issue with deleting Instagram feeds.

= 1.0.1 =

* [Bug Fix] The modal close button was not working this has been fixed.
* [Task] Added a notice for the YouTube API key.

= 1.0.0 =

* Initial release.