=== Favorite Toots ===
Contributors:      cdevroe
Tags:              block, mastodon, favorites
Tested up to:      6.5
Stable tag:        0.2.4
License:           GPL-2.0-or-later
License URI:       https://www.gnu.org/licenses/gpl-2.0.html

Add a list of your favorite toots from Mastodon to any page on your website using a block.

== Description ==

Use the Favorite Toots block to quickly add a list of your favorite toots from Mastodon to any page on your website. The toots appear as a fully styled list. You can see how it looks by [viewing my favorite toots on my website](https://cdevroe.com/favorite-toots).

== Frequently Asked Questions ==

= Why does this plugin exist? =

By default Mastodon does not expose an account's favorite toots. By using this plugin, you're able to share your favorite toots on your website.

= How do I determine my Mastodon instance URL? =

Your Mastodon instance URL is usually the domain name that appears in your username. For example, my Mastodon username is [@cdevroe@mastodon.social](https://mastodon.social/@cdevroe) so my instance URL is mastodon.social.

= Where do I get an Mastodon API key? =

1. Log into your Mastodon instance.
2. Click Preferences > Development
3. Choose "New application"
4. Application name: Favorite Toots WordPress (or, anything you'd like)
5. Application Website: Your website URL
6. Redirect URI: (leave as-is)
7. Scopes: read:bookmarks read:favourites read:statuses
8. Click Save.
9. Copy and paste your "Access Token" into the settings of the Favorite Toots plugin at Settings > Favorite Toots.

= Where can I provide feedback? =

I welcome feedback, code, and feature suggestions! You can submit a thread to the WordPress Support Forums or [on GitHub](https://github.com/cdevroe/favorite-toots) as an issue.

== Screenshots ==
1. The Favorite Toots block and its options
2. Your favorite toots need to be seen by the world
3. Great toots need to be seen
4. An unheard song... you get the point, show off your toots!

== Toots in screenshots ==

- Screenshot 2: [@elengale@mastodon.social](https://mastodon.social/@elengale/112174709734505255), [@tomnorthfilm@photog.social](https://photog.social/@tomnorthfilm/112151440420302765)
- Screenshot 3: [@jontofski@mastodon.art](https://mastodon.art/@Jontofski/112124829992254349)
- Screenshot 4: [@salginatobel@go5.dev](https://go5.dev/@salginatobel/112136436959884868), [@microseasons@botsin.space](https://botsin.space/@microseasons/112130969075940516)

== Changelog ==

= 0.2.4 =
* Updates related to submission requests from the WordPress Plugin reviewers

= 0.2.3 =
* Updates related to submission requests from the WordPress Plugin reviewers
* Readme Updates

= 0.2.2 =
* Renamed to Favorite Toots

= 0.2.1 =
* Added nonce check to cache buster during block settings update

= 0.2.0 =
* Multiple instances of the block will now cache independently
* Updating a Mastodon Favorites Block's settings will destroy that instance of the Block's cache
* Updated the text-domain per WordPress.org "Plugin Check" test results.
* Fixed temporary Editor Block icon SVG
* New styling for Editor Block in the Editor

= 0.1.0 =
* Release

== About this Plugin ==

One of the primary ways I find new accounts to follow is by eavesdropping on other people’s favorites. Many platforms make favorites public but Mastodon doesn't (yet?). I wanted to show my favorite toots publicly so that people can look through them. I’m hoping you'll make your favorite toots public this way too.
