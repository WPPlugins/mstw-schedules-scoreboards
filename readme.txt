=== MSTW Schedules & Scoreboards ===
Contributors: MarkODonnell
Donate link: http://shoalsummitsolutions.com
Tags: sports,games,schedule,sports teams,team schedule,countdown timer,scoreboards  
Requires at least: 3.9.2
Tested up to: 4.7
Stable tag: 1.4.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Manages multiple sports team schedules and scoreboards. Displays schedule tables, schedule sliders, scoreboards, and countdown timers.

== Description ==

The MSTW Schedules & Scoreboards plugin manages multiple sports team schedules and scoreboards. It includes a rich Teams table with logos, colors, sports, venues, and other fields. A variety of shortcodes and widgets are available to display schedule tables, schedule sliders, scoreboards, and countdown timers. An extensive set of display settings is available through the admin screens to customize these displays. Displays may be further customized via the plugin's stylesheet. 

= NEW IN MSTW SCHEDULES & SCOREBOARDS =

The MSTW Schedules & Scoreboards replaces (MSTW) Game Schedules and Game Locations plugins. All users, especially users of the (MSTW) Game Schedules and Game Locations plugins, are encouraged to review [What's New in Schedules & Scoreboards](http://shoalsummitsolutions.com/ss-whats-new/) before getting started.

Need team logos for website? Logo sets for your favorite leagues at [the MSTW Store](http://shoalsummitsolutions.com/logo-sets/). Whether you don't have the graphics skills, don't have the interest, or just don't have the time, you can jump start your website's database of teams with perfectly sized logos for schedule tables, schedule sliders, and scoreboards.

= Helpful Links =
* [**See what the plugin in action on the MSTW Dev Site**](http://dev.shoalsummitsolutions.com/)
* [**Read the (site admin) user's manual at shoalsummitsolutions.com**](http://shoalsummitsolutions.com/category/ss-plugin)

== Installation ==

All the normal installation methods for WordPress plugins work. See [the installation manual page](http://shoalsummitsolutions.com/ss-installation/) for details.
*Upon installation make sure the WP default timezone is set correctly in the Wordpress Settings->General screen.*

**IMPORTANT!** MIGRATION FROM GAME SCHEDULES AND/OR GAME LOCATIONS
If you are upgrading, please read the migration manual page to prevent data loss.

== Frequently Asked Questions ==

[The FAQs may be found here.](http://shoalsummitsolutions.com/ss-faq/)

== Screenshots ==

1. Sample Schedule Table [shortcode]
2. Sample Schedule Slider [shortcode]
3. Sample Countdown Timer [shortcode]
4. Sample Scoreboard [shortcode]
5. Sample Single Game Page [single-game.php template]
6. Sample Game Venues Table [shortcode]
7. Sample Scoreboard Ticker [shortcode]
8. Scoreboard Settings Tab (Settings admin screen)

== Upgrade Notice ==

The current version of MSTW Schedules & Scoreboards has been tested on WP 4.1.1 with the [Underscores starter theme.](http://underscores.me/) If you use older version of WordPress, the plugin may or may not function properly. If you are using a newer version, please let me know how the plugin works, especially if you encounter problems.

== Changelog ==

= 1.4.1 =
* Corrected a bug that prevented the schedule slider from starting at the current game.
* Corrected bugs with the slider custom date & time formats
* Updated the master translation file /lang/msw-schedules-scoreboards-en_US.pot

= 1.4 =
* Added the ability to show the ("schedule team") sport for each game to both the schedule table and schedule slider.
* Added a control for the default schedule to CSV Import. Games in a CSV file without a schedule slug default to the specified schedule.
* Removed the control for the logo import directory. Logos can now be automatically moved from their previous site/location to the new site's media library.
* Increased control of the schedule slider via CSS, including schedule specific styles.
* Corrected some errors with admin notices in the MSTW Utility Library.

= 1.3 =
* Updated CSS stylesheet loading, so customizations can be loaded from a separate file from the plugin's mstw-ss-styles.css. Changes to that file are no longer required, so the plugin upgrade process should be simpler (and safer).
* Added css tag for home games to all widgets & shortcodes, not just the schedule table.
* Added four team colors to each team. (For eventual use in several plugins.)
* Corrected bug - schedule sliders with only one game displayed on them slide correctly.
* Corrected bug - settings link on plugins page now goes to the settings page.
* Removed some annoying PHP notices from the CDT widget.

= 1.2 =
* Added a scoreboard 'ticker' shortcode - a slider of games & scores intended for the top of pages. 
* Added a Scoreboard Settings tab to the plugin's Settings admin screen. 
* Added CSV Import support for hand-entered schedules using man-readable game dates & times.
* All data tables EXCEPT SCHEDULES generate default slugs from titles if slug column is omitted.
* Updated the default .pot file with some new strings.

= 1.1 =
* Added Sports to the CSV import function.
* Added Venue Groups (taxonomy) to Venues import and Scoreboards (taxonomy) to Games import.
* Removed 'invalid referer' message when deleting (move to Trash) or restoring schedules, teams, games, sports, and venues.
* Removed extraneous debug message from admin screens when importing CSV files
* Added internationalization to some strings and re-generated the default .pot file

= 1.0 =
* Initial release.