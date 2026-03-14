# Roblox 2011
This script tries to make Roblox look as 2011 as possible!

This script is not finished! You may see some bugs and/or unsupported pages.  
[Download](#download) | 
[Issues](#issues) | 
[Settings](#settings) | 
[Changelog](https://github.com/Xammand/2011-Roblox/blob/main/changelog.md) | 
[Userstyles.world (V1)](https://userstyles.world/style/3344/2011-roblox) | 
[ROBLOX 2011 Script (V1)](https://greasyfork.org/en/scripts/542803-roblox-2011)

### Credits
- Xammand: Author of Style
- 2013InternetLover: Bug fixer/suggestor
- Wayback Machine: Reference for old roblox styling and images
- YouTube: Old videos that show logged in pages/other related things
- Roblox Wiki: Some old header banners
- Robloxopolis' Webcache Archives: Archives of logged in pages from 2011-2012
# Issues
Please submit any issues you have with this script [here](https://github.com/Xammand/2011-Roblox/issues).
# V2
V2 is finally out! It is a complete rewrite that fully recreates the 2011 site as best it can with custom HTML and CSS. It doesn't depend on the modern site elements much like V1 did, which means the only real reason why a supported page could break is from a change in the ROBLOX api. As of V2.0.0, only a few pages are supported. This will obviously change in the future as more updates come out. You can see what pages are supported right now below. If there is a page you go on that is unsupported, you can disable the script in the Tampermonkey menu. Right now, this script is very unfinished and you will probably see some bugs. There are not very many settings options right now either. I have spent a lot of time making this script in a short amount of time and tried to release the first version as fast as possible so sorry if it seems rushed right now. It will obviously get better over time. It should be better than V1, atleast. Now go ahead and try it. For more information about V2, check the [changelog](https://github.com/Xammand/2011-Roblox/blob/main/changelog.md).

This script does not support the site chat as I cannot chat and do not plan on verifying to enable it. I don't know what the chat looks like with this script so it may or may not look broken.
### Supported Pages (As of V2.0.0)
- Home Page
- Profile Page
- Profile Friends Page
- Games Page
- Game Details Page
- Games Search Page (Part of Catalog)
- Catalog
- Asset Details Page
- User and Group Search Page
- Builders Club Page
- ROBUX Page
- Groups Page  
  **Note:** Right now, most, if not all, these pages are kinda unfinished. You may notice some pages missing features such as actions like making a group primary or friending/unfriending someone.
## Download
1. Get Tampermonkey ([Firefox](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)) ([Chrome](https://chromewebstore.google.com/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo))
2. [Get This Script.](https://github.com/Xammand/2011-Roblox/raw/refs/heads/main/roblox2011.user.js)
3. To fully utilize the feed on the home page, make sure to turn on all group notifications.
## Settings
Unlike V1, you can now set settings using a UI part of the script. You can find the settings by clicking the Tampermonkey icon, going to the ROBLOX 2011 script, and clicking "ROBLOX 2011 Settings." You can now also temporarily disable the script if you want by pressing "Disable ROBLOX 2011."  
![alt text](https://i.imgur.com/3kIoCDW.png "Settings")
- **General Style:** Sets the style you want to use. Each style is based on how the ROBLOX site looked like from 2006-2012.
   - **ROBLOX Classic:** Sets the style to what ROBLOX looked like in 2006-2009.
   - **ROBLOX 1.0:** Sets the style to what ROBLOX looked like in 2009.
   - **ROBLOX 2.0:** Sets the style to what ROBLOX looked like in 2010.
   - **ROBLOX 3.0:** Sets the style to what ROBLOX looked like in 2010-2012.
   - **ROBLOX 4.0:** Sets the style to what ROBLOX looked like in 2012.
- **Sub-Style:** Sets an additional style for a style from a closer period of time.
   - **Default:** Nothing is added.
   - **ROBLOX Classic BKG**: Adds the 1.0-2.0 background to the classic style, this sub-style would've been used towards the end of the ROBLOX Classic style in 2009.
   - **ROBLOX 1.0 Classic:** Sets the ROBLOX 1.0 style to an earlier version that used the ROBLOX Classic header and slight css changes.
   - **Early ROBLOX 3.0:** Sets the ROBLOX 3.0 style to an earlier version from 2010 that used a layout closer to the 1.0 and 2.0 layout.
   - **ROBLOX 3.0 Small Header:** Adds the small version of the header to the ROBLOX 3.0 style.
   - **Early 2012 ROBLOX 4.0:** Sets the ROBLOX 4.0 style to an earlier version from early 2012 that used a "brighter" header.
- **Theme:** Sets a theme for the selected style, not all listed themes can be used for all styles.
   - **OBC:** (1.0+) Adds the OBC theme that was used for the supported styles.
   - **Parent Edition:** (2.0+) Adds the Parent Edition banner that was used when you logged into a parent account back then.
   - **Test Server:** (Classic+) Adds the Test Server background that was used for the supported styles which was used for ROBLOX test sites back then.
   - **Christmas 2011:** (3.0) Adds the Christmas banner, background, and logo that was used in 2011.
   - **Thanksgiving 2011:** (3.0) Adds the Thanksgiving banner, background, and logo that was used in 2011.
   - **Halloween 2011:** (3.0) Adds the Halloween banner, background, and logo that was used in 2011.
   - **Christmas 2010:** (3.0) Adds the Christmas banner, background, and logo that was used in 2010.
   - **Thanksgiving 2010:** (3.0) Adds the Thanksgiving banner, background, and logo that was used in 2010.
   - **Halloween 2010:** (3.0) Adds the Halloween banner, background, and logo that was used in 2010.
   - **Early 2009 Banner:** (Classic) Adds the banner that was used in early 2009.
   - **Christmas 2008 Banner:** (Classic) Adds the christmas banner that was used in 2008.
   - **Default 2008 Banner:** (Classic) Adds the default banner that was used in 2008.
   - **"Builderman for President" Banner:** (Classic) Adds the banner from Early 2008 that was made to celebrate the 2008 U.S. election.
   - **Christmas 2007 Banner:** (Classic) Adds the Christmas banner used in 2007.
   - **Halloween 2007 Banner:** (Classic) Adds the Halloween banner used in 2007.
   - **Default 2006-2007 Banner:** (Classic) Adds the default banner used in 2006-2007.
   - **2005-Early 2006:** (Classic) Adds the default header used in 2005-Early 2006.
   - **2005-Early 2006 Alpha:** (Classic) Adds the default header used in 2005-Early 2006 with "Alpha test" text on the banner.
- **General Layout**: Sets the layout. (Modern layout is not supported yet as of V2.0.0)
   - **Classic:** (Classic-3.0) Sets the layout to be the classic layout used before late 2011.
   - **Modern** (3.0+) Sets the layout to be the more modern looking layout used from late 2011 to 2013.
- **Builders Club Logo**: Lets you pick what BC logo to use since ROBLOX doesn't display tiers anymore.
- **Fake Status:** A text box that lets you add a fake status to your home and profile page. Only you can see this. You can also add a fake status on the site itself.
- **Enable Header Twitter Button:** (1.0-Early 4.0) Enables the hidden Twitter button in the header next to the news link.
- **Classic Play Buttons:** (Classic+) Enables the classic play buttons used from before 2009.
- **Show Display Names on Profiles:** Shows the user's display name on their profile.
- **Show More Stats:** More information that wasn't displayed in 2011 is displayed in the stats on the profile page.
# V1 (Deprecated)
V1 will no longer recieve updates but I will keep the download information and everything for it here until V2 is more "finished".
## Download
1. Get Extensions:
   - Better Roblox ([Firefox](https://addons.mozilla.org/en-US/firefox/addon/btroblox/)) ([Chrome](https://chromewebstore.google.com/detail/btroblox-making-roblox-be/hbkpclpemjeibhioopcebchdmohaieln))
   - Stylus ([Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/)) ([Chrome](https://chromewebstore.google.com/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne))
   - (Optional) RoSeal ([Firefox](https://addons.mozilla.org/en-US/firefox/addon/roseal/)) ([Chrome](https://chromewebstore.google.com/detail/roseal-augmented-roblox-e/hfjngafpndganmdggnapblamgbfjhnof))
   - (Optional) Tampermonkey ([Firefox](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)) ([Chrome](https://chromewebstore.google.com/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo))
3. Set Extension Settings:
   - [Better Roblox Settings](https://i.imgur.com/NXqYEMC.png)
   - Roseal Settings: Open [this link](https://raw.githubusercontent.com/Xammand/2011-Roblox/refs/heads/main/roseal/roseal.json) ([this link](https://raw.githubusercontent.com/Xammand/2011-Roblox/refs/heads/main/roseal/roseal_script.json) if using script) and right click in the empty space and select 'Save Page As...' and download the file. Then, go to Roseal settings on Roblox, make sure you are on the 'Management' tab, click Browse in the 'Import Data' section, select the file you just downloaded, then press the 'Import Data' button. That's it! (thanks, DemaeMan)
5. IMPORTANT NOTE: As of 1.6.3, the roseal sorts layout settings are no longer supported. Please make sure to reset the sorts layout settings to ensure no bugs. New users do not have to worry about this.
6. NOTE: As of 1.8.0, Roseal is no longer required. If you are just using the style you must get the extension for the header in the homepage. If you have the script, it now adds its own header so you no longer need to have Roseal. If you still want Roseal with the script, make sure to import the script version of the Roseal settings.
7. Turn Roblox Theme to light mode if not already, otherwise issues will occur. (If you want a dark mode then you can use the OBC theme.)
8. [Get This Style.](https://github.com/Xammand/2011-Roblox/raw/refs/heads/main/roblox2011.user.css)

That is it unless I forgot something.
## Scripts
There is a script for this style that can be used if wanted. It is highly recommended to use as it makes Roblox look even more 2011! You can find it [here](https://greasyfork.org/en/scripts/542803-roblox-2011).
### 2011 BC Page
There is also a script that restores the 2011 Builders Club page. You can find it [here](https://greasyfork.org/en/scripts/542802-roblox-2011-bc-page).
## Settings
Note: Some settings are only for a selected style. Those will have the style name in parentheses. EX: (3.0), (Classic)  
Others will be CSS or Javascript only. EX: (CSS), (JS)
- Header
  - CSS: Set if just using this style.
  - Javascript: Set if using this style and the script.
- General Style: Set of 4 different themes you can pick.
  - ROBLOX Classic
  - ROBLOX 1.0
  - ROBLOX 2.0
  - ROBLOX 3.0
- Comic Sans (Classic)
- Hide Messages (Classic)
- No Background (Classic)
- Old Background (3.0)
- General Layout: The layout of the site that you can choose.
  - 2010 - Mid 2011
  - Late 2011
- Theme: What theme the site will have.
  - Default
  - Halloween 2010 (3.0)
  - Thanksgiving 2010 (3.0)
  - Christmas 2010 (3.0)
  - Halloween 2011 (3.0)
  - Thanksgiving 2011 (3.0)
  - Christmas 2011 (3.0)
  - OBC (2.0+)
  - Parent Edition (2.0-3.0)
  - Sports (Classic)
  - Default 2008 (Classic)
  - Builderman for President (Classic)
  - Christmas 2008 (Classic)
  - Default 2007 (Classic)
  - Halloween 2007 (Classic)
  - Christmas 2007 (Classic)
  - Default 2006 (Classic)
  - Alpha 2006 (Classic)
- Builders Club Icon: The BC icon you wish to have for anyone with Premium.
  - Builders Club
  - Turbo Builders Club
  - Outrageous Builders Club
- Rename BC Badge: Renames the "Welcome to the Club" badge to the selected Builders Club name, will also change the icon.
- Holiday Greeting Text (CSS): Enables the holiday greeting text used for holiday themes.
- Hide Signup Button (CSS): Roblox didnt have a signup button back then, so this option lets you chose to have one or not.
- Small Header (CSS): Enables the small header for ROBLOX 3.0.
- 2011 Footer Text (CSS): Enables the footer legal text to show the text used in 2011.
- Hide Searchbar (CSS)
- Show Header Twitter Link (JS): Roblox has a hidden Twitter link in the header, this option enables it.
- Hide Avatar/Item Buttons: Hides "3D", "Show Items", etc. buttons as Roblox didnt have them back then.
- Classic Report Link: Enables the classic report link used before 2011.
- Don't Stretch Game Images: Game pictures are no longer widescreen (how they were back then) so they are stretched to be widescreen. This option makes the image not be stretched if you do not like that.
- Enable Facebook Features (3.0+): Roblox used to have many Facebook features on its site, this option will add fake share buttons and other related things when enabled. Roblox 2.0 and older did not have facebook features.
- **Home** Show All Games (Late 2011): Shows all games on the right side instead of just five.
- **Home** Hide Games (Early 2011): Hide games in early 2011 layout as they weren't there back then.
- **Profile** More accurate About Header: Enables a more accurate profile header instead of the modern styled one.
- **Profile** Hide Top Configure Button: Hides the configure button on the top of the profile page, as it wasnt there in 2011.
- **Inventory** Ungroup Tabs: Shows every inventory tab as their own button instead of being grouped together.
- **Inventory** Hide Tabs: Lets you hide certain tabs if you want.
  - Off
  - Modern Tabs
  - Modern & Less Modern Tabs
  - Only 2011 Tabs: Only shows tabs present in 2011. Removes any that aren't.
- **Inventory** 2011 Tab Labels: Names every tab as they were named in 2011.
- **Avatar** Hide Modern Item Tabs: Hides tabs for modern labels. (EX: Layered clothing, 3d faces, etc.)
- **Game** Fake Avatar on Details (CSS): Adds a fake avatar next/above the game details. Only for CSS as the script now adds the creator's avatar.
- **Game** Hide Modern Stats: Removes any stats that weren't present in 2011.
- **Game** Facebook-styled Like & Dislikes: Styles the like and dislikes as Facebook buttons, like how they were in 2011.
- **Game** Hide Dislikes (Facebook): Hides dislikes. Facebook does not have a dislike button. Facebook-styled like and dislikes option must be on.
- **Game** RSS Follow: Styles the follow button to like an RSS Follow link.
- **Game** Semi-Classic Thumbnail Scroller: Enables an attempt at recreating the classic thumbnail scroller with pure css.
- **Group** Hide Forums: Hide the modern forums that may show in some groups.
- **Robux** Show Robux Header: Enables the classic Robux header used before 2011.
- **Robux** Show Fake Giftcard Ad (3.0+): Enables giftcard ad used after late 2011.
- **BC** Show BC Ad: Shows the BC ad that always appeared on the BC page.
