# Version 2
### Version 2.2.0
- More code cleanup.
- Unsupported pages will now disable the script on that page instead of showing a big unstyled mess of HTML.
- Added support for Badges Info page.
- Added support for Avatar Editor page. (Actions don't work for now.)
- (Modern ROBLOX 3.0 and 4.0) Fixed play button not being centered and edit button being on the left of the play button instead of the right.
- (Login Page) Added support to "NewLogin" page. (Same page as regular login page, just diffferent url.)
- (BC Page) Fixed inaccurate gift card image for Modern ROBLOX 3.0 style.
- (ROBUX Page) Finally finished this page.
- (Profile Page) Fixed follow button not appearing for Modern ROBLOX 3.0 and 4.0 styles.
- (Game Details Page) Fixed uncopylocked icon not showing on modern layout.
- (Game Details Page) Fixed edit button not appearing on uncopylocked games for classic layout + Added edit button for uncopylocked games/games made by you for modern layout.
- (Game Details Page) On modern layout, fixed see more button for description appearing for descriptions that didn't need one.
- (Game Details Page) On modern layout, fixed descriptions that didn't need see more button not appearing.
- (Game Details Page) Added "scroller" thumbnails for games with more than one thumbnail on modern layout. Videos are also supported.
- (Items Page) The favorite button for classic styles (ROBLOX 2.0 and before) now functions correctly.
- (Items Page) Added "modern" favorite button for Modern ROBLOX 3.0 and 4.0.
### Version 2.1.2
- Added setting "Primary Currency". You can choose if you want ROBUX or Tickets as your primary currency. If you choose tickets, your robux amount will be displayed as your Tickets amount in the header and every item will cost Tickets instead of ROBUX.
- Added support for the Default page.
- Added support for the Badges page.
- (ROBLOX Classic) Fixed style not working.
- (Inventory) Fixed classic heads not displaying at all.
- (Inventory) Fixed classic faces not displaying thumbnail.
- (Login Page) Finished the lazily put together login page.
- (Catalog Page) The Collectibles category now properly displays Limited and Limited Unique items.
- (Items Page) Cleaned up some of the disasterous code of the Items Page.
- (Items Page) Recommended item creator link for groups now have the group url instead of user url.
- (Game Details Page) Fixed recommended games not showing for any game.
### Version 2.1.1
- Major code clean up (put most of the api functions into one function).
- Removed some pile of trash code that is litteraly just a pile of trash.
- Added support for "modern" layout for Inbox/Messages and PrivateMessages pages.
- Tweaked pager code to make it better when loading page.
- Some pagers now display a spinner when loading.
- "Added" Messages page. (It's essentially the Inbox page in modern 3.0/4.0 style as the /Inbox.aspx page was moved to /Messages.aspx when the modern style started being used.)
- (ROBLOX Classic) Removed the kinda useless and very annoying unfinished notice text above the header. (I also removed the notice for the 4.0 style as well in an earlier update but forgot to include it in the changelog.)
- (Home Page) System notifications will now display the correct number on the modern layout instead of always being 0.
- (Home Page) The feed will now load a little faster.
- (Home Page) In the modern layout, the name of the author of a group shout is now displayed instead of nothing.
- (Home Page) Removed classic group shouts code for the feed since it seems they were removed from the api.
- (Games Page) Fixed bug where the pages would load and reload pages for infinity even after the last page was reached.
- (Games Page) Added 2 categories for modern games page ("My Favorites" and "Recently Played") that are shown if you are logged in. (Classic games page didn't have these.)
- (Games Page) Added support for "My Favorites" category page for modern games page (Classic games page didn't have this).
- (Games Page) Added support for "Recently Played" category page for modern games page (Classic games page didn't have this).
- (Group Page) Fixed searchbar on modern layout not working.
- (PrivateMessages Page) Fixed bug where any "system account" that wasn't Roblox (builderman) was named Roblox as the author. (builderman is considered a system account in the api now but was still considered a regular account back then.)
- (PrivateMessages Page) Fixed missing title attribute for author username.
### Version 2.1.0
- Added support for the "modern" layout for home, game details, and group pages.
- Changed code that detects what page you're on by now making it target a more exact url.
- Renamed "General Layout" setting to "ROBLOX 3.0 Layout".
- (Catalog Page) Fixed page not reloading when an item is clicked.
- (Catalog Page) Fixed bundles going to the regular /catalog/ url instead of /bundles/.
- (Items + Game Details Page) Fixed bug for updated text where it would display hours instead of days even if it was updated more than 24 hours ago.
- (Items + Game Details Page) Made updated time ago text slightly more accurate to how long ago the date was by getting a more exact time it was last updated.
- (Game Details Page) Fixed bug that gave "undefined" text for creation date.
- (Game Details Page) Added support for group links for recommended games.
- (Game Details Page) Fixed basically every game displaying "genre enforced gear" in the gear section even if the game has gear disabled.
- (Groups Page) Added support for group announcements since it seems classic shouts were removed from the api.
### Version 2.0.2
This is basically an update I made a while ago but never uploaded until now. The reason why it took so long was because I was trying to figure out a way to get buying/getting catalog items working but it seems thats not really possible with this script so it probably will never support that unless I find some weird way to get it to work. Kinda rushed this one out. Sorry if you were expecting more after this long time. Next update I'm planning on finally adding support for modern layout.
- Added Inbox and PrivateMessages Pages, actions don't work for now.
- Added support for login page (Unfinished)
- Fixed the login links for some headers where it would take you to a page that doesn't exist.
- (Profile Page) Actually fixed Join Date in stats box not appearing if it's enabled this time.
- (User and Group Search Pages) Removed trash pager code and replaced with superior pager function code.
- (User Search Page) Fixed the BC icon not loading.
- (Groups Page) Removed the "All Members" role that appeared as "Members" and was very buggy.
- (Items Page) Added support for group creators.
- (Items Page) Fixed a rare bug that could happen where the creator's id would be completely wrong. (Mostly occured in groups?)
- (Items Page) Added functional modals for buying/getting an item. Actually buying/getting an item doesn't work right now and may or may not be something that will ever be made functional.
- (BC Page) Added support for the new Roblox Plus page.
- (Home Page) Fixed bug where if user has BC/Premium the icon wouldn't appear on their avatar.
### Version 2.0.1
- Minor bug fixes.
- Added support for "My Stuff/Inventory" page.
- Added modern and classic game launcher. (Changes based on what style you use.)
- Added the ability to favorite and unfavorite games and items. (To unfavorite games and items, go to your favorites in your profile and then press the delete button on a game or item. It can take a second for the favorite list to update so don't worry if the page reloads and the game/item is still there, it will update eventually.)
- Fixed the BC icon not loading the image in some places.
- (Game Details Page) If the creator is a group, their icon will now correctly display.
- (Game Details Page) Fixed(?) the updated time ago text displaying negative seconds if the game was updated very recently.
- (Game Details Page) Added missing genre icons.
- (Game Details Page) Fixed badges displaying "null" in the description if they have a blank description.
- (Inventory) Removed trash pager code for Stuff/Inventory and replaced with superior pager function code.
- (Inventory) Slightly changed inventory api to now display the selected user's serial number on Limited Unique items.
- (Inventory) Fixed duplicate items not appearing.
- (Inventory) Added support for decals, models, and places.
- (Inventory) Added recommendations for the ROBLOX Classic version.
- (User Friends Page) Removed trash pager code and replaced with superior pager function code.
- (User Friends Page) Added no friends message that appears if selected user has no friends.
- (User Friends Page) Condensed some HTML code.
- (Items Page) Added some missing item type names.
- (Items Page) Added support for the classic styles. (Classic, 1.0, and 2.0.)
- (Items Page) Added favorite button.
- (Items Page) Added the original price of a Limited Unique item to the details area.
- (Items Page) Fixed a bug where free items would display the buy button instead of take button.
- (Items Page) Removed genre/tags api function because apparently that api doesn't exist anymore.
- (Items Page) Added a generic "All Genres" icon to the genre box instead of it being empty.
- (Items Page) Added a remove button for items that you own. (Doesn't actually work.)
- (Items Page) Added working pager in Resellers box for Limited/Limited Unique items.
- (Items Page) Made a reseller's serial number more accurate by adding the total quanity of a limited/limited unique item.
- (Profile Page) Fixed Join Date in stats box not appearing if it's enabled.
- (Profile Page) Added pagination and working category switcher to favorites.
- (Profile Page) Added remove favorite button to favorited items if the user is on their own profile.
- (ROBLOX 4.0) Fixed missing report abuse icon.
### Version 2.0.0
- Definently will forget some stuff here.
- Complete rewrite.  
  **Compared to V1:**
- ROBLOX 2011 now has the ability to fully recreate the ROBLOX website with HTML and the ROBLOX api.
- ROBLOX 2011 is now just one Tampermonkey Script.
- ROBLOX 2011 no longer requires any ROBLOX extensions.
- ROBLOX 2011 now requires the Tampermonkey extension, instead of it being optional.
- ROBLOX 2011 now has an actual settings ui instead of having to manually set variables in the script.
- Every page that is supported is now a complete HTML recreation using ROBLOX api for information, meaning that these pages are as accurate as they can be.
- Much more accurate.
- Added the ability to disable the script from a menu item.
- New theme added: Test server.
- New option, "Sub-style": contains "ROBLOX Classic with background", "ROBLOX 1.0 Classic", "Early ROBLOX 3.0", "ROBLOX 3.0 Small Header", "Early 2012 ROBLOX 4.0".
- New option: Classic play buttons
- You can now set a fake status if you want. You can either set the status in the settings or from the actual site itself. Only you can see this as it is simply just saved information from the script's settings.
- Added support for group announcements for the feed on the home page. (The feed only supports group shouts and announcements right now.)
- Added more "logged in" parts of the site.
- The "ROBLOX 2011 BC Page" script is now part of the main script.
- (BC Page) The manage account box now shows if you have BC/Premium or not. (Can't show what type you have right now.)
- (BC Page) "Upgrade" buttons have been added to each BC button if the user is logged in.
- More accurate 2005-Early 2006 header.
- Tooltips for ROBLOX 3.0 and 4.0 now work.
- The group page is slightly more accurate.
- (Profile page) Added functionality to see your public profile page.
- A bunch of other stuff I forgot to put here.
- Less buggy.
# Version 1
### Version 1.8.1
- Some bug fixes.
### Version 1.8.0
(NOTE: Btroblox is now fixed and updated on chrome and firefox extension stores as of 8/15/25.)  
- The usual, bug fixes and page edits.
- Styled ROBLOX 2.0/1.0 page (slightly wip, some things might not look right and fake elements will still have 2011 look for now)
- Styled ROBLOX 2.0 OBC Page
- Made style compatible with new btroblox
- Made style compatible with new script version ([see script changelog here.]([hi.com](https://greasyfork.org/en/scripts/542803-roblox-2011/versions)))
- Facebook features are only shown on 3.0+ now as 2.0 and older didnt have facebook features
- Made groups page slightly better
- Made early 2011 home page friends more accurate
- ROBLOX 2.0/1.0 header now shows correct rss feed icon
- ROBLOX 4.0 header no longer shows rss feed icon
- Fixed spacing issue with javascript version of 4.0 header
- Fixed spacing issue between search bar and search dropdown for css header
- Fixed search dropdown not appearing on css 4.0 header
- Search dropdown is now styled on all css headers
- Fixed css footer missing background on groups page
- Added missing logged out css for small header and 4.0 header
- Added missing css for small header game genre dropdown
- Added option: Rename Robux to Tix
- Added option: Hide Games (Home)
- Removed option: Notifications in Home Page (The script now adds this by default.)
- Removed option: Games on right (If using late 2011 layout, games will now be on the right by default.)
### Version 1.7.0
(NOTE: Btroblox has now updated but the only way to get this update right now is from github as the extension store version is not updated yet. https://github.com/AntiBoomz/BTRoblox)  
- Many bug fixes
- Changed 'Version' of style options to 'ROBLOX'
- Made "ROBLOX 2.0" style slightly better
- Added "ROBLOX 1.0" and "ROBLOX Classic" styles
- Added themes for "ROBLOX Classic": Sports, Default 2008, Builderman for President, Christmas 2008, Default 2007, Halloween 2007, Christmas 2007, Default 2006, and Alpha 2006
- Added "Comic Sans", "Hide Messages", and "No Background" options for "ROBLOX Classic" style
- RSS Feed icon now shows on every "style"
- Added fake sorts section for games page
- Made game search page more accurate
- Made game thumbnail scroller slightly better
- Added fake status in home page
- Fixed spacing issue with friends and avatar in home page
- Made game servers tab much more accurate
- Recommended games no longer show above tabs in early 2011 layout (too buggy), must use script for that now
- Probably many other things that I forgot about
### Version 1.6.3
(NOTE: Btroblox profile is not working right now. I will wait a while before doing anything to the profile. If btroblox is still not updated in a few days then I will assume it's no longer updated and will style the regular profile page.)  
(PS: Make sure to reset your roseal sorts layout options, this is no longer supported.)
- More home page bug fixes.
- General bug fixes.
- Page edits.
- Styled tooltips.
- Changed style option names to their offical name, which is just version number.
- Changed "Recently Played" to "Recently Played Games" on early 2011 homepage.
- Added space between subheader and main content in some pages.
- Added fake facebook connect section in home page.
- Added facebook subscribe button (follow button).
- Added bug fixes and additions by 2013InternetLover.
- Kinda styled announcements, will finish in next update.
- Added option: Enable Facebook Features | Adds fake facebook share button in some places and possibly more eventually.
- Added option: Dont Stretch Game Image
- Added option: RSS Follow | Turns facebook subscribe button to rss version.
- Added option: Semi-Classic Thumbnail Scroller
- Added option: Notifications in home page | Move notifications in homepage like in 2011. (Only js for now)
- Removed code for wide games, roseal's way of implementing them is too buggy.
### Version 1.6.2
- Home page bug fixes.
### Version 1.6.1
- Many bug fixes.
- Many page edits.
- Added early 2011 game details layout.
- Made late 2011 game badges more accurate.
- Many other things.
### Version 1.6.0
- Added 2010 Themes.
- Added Late 2011 Home Page (wip)
- Added games on right option (late 2011)
- Many page edits and tweaks.
- Finally styled group search bar (js).
- Some bug fixes.
### Version 1.5.3
- Home page bug fixes.
- Rename connections on home page back to friends.
### Version 1.5.2
- Minor bug fixes.
### Version 1.5.1
- Styled more chat stuff.
- 2012 Style is now supported on javascript header.
### Version 1.5.0
- Styled account info settings page.
### Version 1.4.0
- Styled games page.
- Styled games search page.
- Add 'Game Page Layout' option. Grid is original 2011 layout, List is BC Game styled.
### Version 1.3.2
- Tweaked home page.
- Styled more of game details page.
- Fixed games on home page colliding with avatar when page is loading.
### Version 1.3.1
- Bug fixes.
- Tweaked item details styling.
- Styled 'free' item.
- Modals are now styled (wip).
- Hid loading transition things.
### Version 1.3.0.
- Added and fixed many things for the JS header.
- JS header now supports 2010 style.
### Version 1.2.0.
- Styled Robux and BC pages.
- Created JS BC Page script.
- Created main script.
- Added "Show Robux Header", "Show Fake Giftcard Ad (Mid 2010+)", and "Show BC Ad" options.
- Renamed "2009 - Mid 2010" style option to "Early - Mid 2010".
### Version 1.1.1
- Random bug fixes.
- Styled new groups sidebar, keeping old code for now in case others still have old sidebar.
### Version 1.1.0
- Styled Login and Signup Pages.
- Fixed buggy header when logged out (only 2010-2012 header for now).
- Added option to hide signup button when logged out.
### Version 1.0.0
- Rewrite.
