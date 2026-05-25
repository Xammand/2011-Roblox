# Roblox 2011
[Download](#download) | 
[Issues](#issues) | 
[Settings](#settings) | 
[Changelog](https://github.com/Xammand/2011-Roblox/blob/main/changelog.md) | 
[Userstyles.world (V1)](https://userstyles.world/style/3344/2011-roblox)  
This script tries to make the Roblox website look as 2011 as possible!  
**This script is not finished! You may see some bugs and/or unsupported pages.**  
**This script is english only. There is no way to change the language right now.**

### Credits
- Xammand: Author of Style
- 2013InternetLover: Bug fixer/suggestor
- Wayback Machine: Reference for old roblox styling and images
- YouTube: Old videos that show logged in pages/other related things
- Roblox Wiki: Some old header banners
- Robloxopolis' Webcache Archives: Archives of logged in pages from 2011-2012
- GM_Config: Settings ui for this script.
# Issues
Please submit any issues you have with this script [here](https://github.com/Xammand/2011-Roblox/issues).
# V2
V2 is finally out! It is a complete rewrite that fully recreates the 2011 site as best it can with custom HTML and CSS. It doesn't depend on the modern site elements much like V1 did, which means the only real reason why a supported page could break is from a change in the ROBLOX api. As of V2.0.0, only a few pages are supported. This will obviously change in the future as more updates come out. You can see what pages are supported right now below. If there is a page you go on that is unsupported, you can disable the script in the Tampermonkey menu. Right now, this script is very unfinished and you will probably see some bugs. There are not very many settings options right now either. I have spent a lot of time making this script in a short amount of time and tried to release the first version as fast as possible so sorry if it seems rushed right now. It will obviously get better over time. It should be better than V1, atleast. Now go ahead and try it. For more information about V2, check the [changelog](https://github.com/Xammand/2011-Roblox/blob/main/changelog.md).

This script does not support the site chat as I cannot chat and do not plan on verifying to enable it. I don't know what the chat looks like with this script so it may or may not look broken.
### Supported Pages (As of V2.2.0)
- Default Page
- Login Page
- Home Page
- Inbox/Messages Page
- PrivateMessages Page
- Profile Page
- Profile Friends Page
- Badges Info Page
- Avatar Editor Page (Actions don't work yet as of V2.2.0)
- Games Page
- Game Details Page
- Games Search Page (Part of Catalog)
- Catalog
- Asset Details Page
- User and Group Search Page
- Builders Club Page
- ROBUX Page
- My Stuff/Inventory Page
- Groups Page  
  **Note:** Right now, most, if not all, these pages are kinda unfinished. You may notice some pages missing features such as actions like making a group primary or friending/unfriending someone.
## Download
**Note:** This script was created in Firefox, Marble Browser V128.12.0esr to be exact. You may or may not experienece issues downloading this script if you are using a non-Firefox browser.
1. Get Tampermonkey ([Firefox](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)) ([Chrome](https://chromewebstore.google.com/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo))
2. [Get This Script.](https://github.com/Xammand/2011-Roblox/raw/refs/heads/main/roblox2011.user.js)
3. Please disable any Roblox extensions you may have to avoid any issues they may create as this script isn't compatible with any Roblox extensions.
4. To fully utilize the feed on the home page, make sure to turn on all group notifications.
5. **For Google Chrome/Chromium Browsers:** You must enable developer mode in "chrome://extensions/" and enable "Allow user scripts" in Tampermonkey by right clicking on the icon and clicking "Manage extension." Otherwise, the script won't load at all.
## Settings
Unlike V1, you can now set settings using a UI part of the script. You can find the settings by clicking the Tampermonkey icon, going to the ROBLOX 2011 script, and clicking "ROBLOX 2011 Settings." You can now also temporarily disable the script if you want by pressing "Disable ROBLOX 2011."  
![alt text](https://i.imgur.com/3kIoCDW.png "Settings")
- **General Style:** Sets the style you want to use. Each style is based on how the ROBLOX site looked like from 2006-2012.
   - **ROBLOX Classic:** Sets the style to what the ROBLOX website looked like in 2006-2009.
   - **ROBLOX 1.0:** Sets the style to what the ROBLOX website looked like in 2009.
   - **ROBLOX 2.0:** Sets the style to what the ROBLOX website looked like in 2010.
   - **ROBLOX 3.0:** Sets the style to what the ROBLOX website looked like in 2011.
   - **ROBLOX 4.0:** Sets the style to what the ROBLOX website looked like in 2012.
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
- **ROBLOX 3.0 Layout**: Sets the layout for the ROBLOX 3.0 layout as this style saw two different layouts.
   - **Classic:** Sets the layout to the classic layout used before late 2011.
   - **Modern:** Sets the layout to the more modern looking layout used from late 2011 to 2013.
- **Primary Currency**: Sets the main Roblox currency you want to use.
   - **ROBUX**: Sets the primary currency as ROBUX.
   - **Tickets**: Sets the primary currency as Tickets. Your ROBUX count will be displayed as your tickets count and every item will cost Tickets.
- **Builders Club Logo**: Lets you pick what BC logo to use since ROBLOX doesn't display tiers anymore.
- **Fake Status:** A text box that lets you add a fake status to your home and profile page. Only you can see this. You can also add a fake status on the site itself.
- **Enable Header Twitter Button:** (1.0-Early 4.0) Enables the hidden Twitter button in the header next to the news link.
- **Classic Play Buttons:** (Classic+) Enables the classic play buttons used from before 2009.
- **Show Display Names on Profiles:** Shows the user's display name on their profile.
- **Show More Stats:** More information that wasn't displayed in 2011 is displayed in the stats on the profile page.
# V1 (Deprecated)
If you want to download V1 or any other old version for some reason, you can find it [here](https://github.com/Xammand/2011-Roblox-Archive).
