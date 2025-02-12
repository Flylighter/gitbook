---
icon: sparkle
---

# What's New?

## Febuary 11, 2025

_02/11/2025 - v0.11.23_

A patch fixed some typos and smaller bugs.

<details>

<summary>Changes</summary>

* Added simple loading indicator to data recovery option.
* Added some descriptions to settings options that didn’t have them.

</details>

<details>

<summary><strong>Fixes</strong></summary>

* Fixed reordering folders not persisting
* Fixed capture history overflowing the window
* Fixed Gmail data items showing on other google pages
* Fixed extension locking up when you exit the tutorial modal
* Fixed being able to back out of the add/refresh connection process.
* Fixed a few typo

</details>



## January 28, 2025

_01/28/2025 - v0.11.22_

Just a couple bug fixes.

<details>

<summary>Fixes</summary>

* Fixed Flow search
* Potential fix for first Flows created after installing would cause a blank screen when selected.

**Insiders**

* Fixed an issue where multiple installations of Flylighter being setup prior to first sync only the first opened would sync, and the rest would be overwritten.

</details>

***

## January 25, 2025

_01/25/2025 - v0.11.21_

Updated the CSS Selector tabs appearance to match the rest of the data picker & a few other fixes.

<details>

<summary>Changes</summary>

* Updated the CSS selector tab to match the appearance of the rest of the data picker UI
* Some secret stuff 😏

</details>

<details>

<summary>Fixes</summary>

* Fixed long folder names causing visual issue in the create Flow modal
* Fixed some visual issues in the icon picker
* Fixed button alignment in some modals
* Fixed numerous instances of dark text in dark mode
* Fixed an issue preventing Flow duplication
* Fixed the search query for destinations persisting when it shouldn’t
* Fixed being unable to reopen Flylighter on the same page after capture
* Fixed extra line break and end of captured code blocks
* Fixed sign up and password reset for accounts
* Fixed onboarding appearing to freeze upon opening data picker on URL property
* Fixed odd behavior with multi-select and relation properties after removing an option
* Fixed certain data types missing from the content editor
* Fixed a rare issue where having Flylighter installed could cause some web pages to show up blank
* Fixed multiple circumstances that would cause a user to get signed out
* Handles some exceptions so Flylighter no longer logs false positive errors to the console
* Fixed typing to filter not working in relation properties

</details>

***

## January 8, 2025

_01/08/2025 - v0.11.18_

Hey everyone! Have a very big update for you today. The changes, fixes, and improvements are too many to list, but below is some of the most notable ones. We are gearing up to launch our first suite of paid features, which we’ll have a lot more info to share very soon. While nearly everything currently in Flylighter currently will remain part of the free offering, there are two exceptions:

* You will be limited to single Workspace/Account on the free plan. This will not be applied retroactively though, so any existing connections will continue to work.
* Capture History will be limited to viewing the ten most recent, and append capture limited to the 3 most recent.

As always, please report any bugs you find in ⁠bugs, and any ideas or feature requests you have in ⁠feedback-ideas, it is tremendously helpful.

<details>

<summary>Changes</summary>

The extension has received redesign to make things less cluttered, more readable, and make better use of the limited space. Let us know what you think!

**General**

* Sidebar mode should now be much improved, allowing you to capture content from multiple pages.
* Added the following options to the extension options page:
* Run Data Recovery \* This is an automated repair process of your user data should you run into an problem that is not being resolved by restarting your browser
* Re-register Context Menus \* If your right-click menu entries disappear, this will bring them back
* Added a plethora of tooltips to various elements.
* Improved opening performance
* Improved performance of the Icon Picker.

**Article capture**

* Article capture now captures image captions as actual image captions in Notion.
* Article capture now supports toggle elements in certain cases.

**Flow Editor**

* Improved the process of initial Flow load. This means less time waiting for things like Relation properties to load.
* You can now minimize sections in the Data Picker (Most useful if you’re using custom CSS selectors).
* Added validators to properties to indicate when there may be issues (I.E if a URL in URL property might be malformed or invalid).

**Appearance**

* The main menu now uses tabbed navigation.
* Added the full Tabler icon set (>5000 icons). Due to differences in identifiers between the old ones and the new, some Flows may lose their icon.
* Removed the accent color option (sorry to any that enjoyed it ![☹️](https://discord.com/assets/e4e349c57577f294.svg))
* Replaced the color slider for folder colors to be a fixed set of colors
* Existing folder colors will be set to their closes equivalent\
  The color math for this feature was complex, and performance heavy, and never found the result to be very nice. Perhaps I’ll come back to it down the line.
* Improved the appearance and smoothness of resizing animations of the main popup
* Tightened up all animations

</details>

<details>

<summary>Fixes</summary>

* Fixed numerous issues with article capture, including but not limited to:
  * various instances of image URLs to cause failure
  * Capturing extraneous content such as footers, headers, and links.
* Fixed an issue causing page icons to not appear in Flow
* Fixed renaming a Flow not “sticking” when renaming in the Flow list
* Fixed a number of sizing issues causing content to clip or overflow the popup
* Implemented a new drag and drop system in the Flow list and Flow Editor the fixes a number of issues
* Fixes to Flow and Database caching
* Fixed user data downloading
* Fixed tooltips sometimes getting “squished

</details>

***

## November 5, 2024

_11/05/2024 - v0.11.17_

This update should provide a much needed performance improvement, most notably to opening times. We’ve also improved the workflow for capturing highlights, and takes many less clicks to get going.

<details>

<summary>Changes</summary>

* Improved opening performance
* Taking a highlight with either the context menu or keyboard shortcut (`Alt (Win) / Ctrl (Mac) + Shift + S`) now prompts you to choose a Flow, then immediately opens the selected Flow to the content editor
* Changed context menu entries to reduce clicks
* Added various tooltips
* Improved context menu behavior and positioning
* Improved behavior of auto filling values for checkbox properties

</details>

<details>

<summary>Fixes</summary>

* Fixed capture button in the content editor having a very small click target
* Fixed numerous typos
* Fixed the “Capturing chunk” message persisting if you reopened a Flow in the same session
* Adjusted language in context menu when right clicking a Flow to clarify how to open the flow without capturing if it is set to Instant Capture
* Fixed numerous issues with icons and images causing Flows to fail. If you were having issues with this, let us know if this fixed it!
* Fixed capture failing when using page capture or appending with YouTube timestamps
* Fixed some issues where the Flylighter popup would be the incorrect size

</details>

***

## November 1, 2024

_11/01/2024 - v0.11.16_

This patch brings an overhaul of light mode, and a new design for the Data Picker. We would love everyone's feedback on both of these. Light mode is still a work in progress, so you may still find some areas that are dark mode.

Also in this patch is a number of other fixes and improvements found below.

<details>

<summary>Changes</summary>

\* Overhauled light mode UI \* Redesigned how data is organized in the Data picker \* Updated “Add Connection” button in Settings > Connections to say “Add/Refresh Connection for clarity. \* Added an image filter to Element Selection when applicable. (e.g. if using the Element selector to pick a page icon, it only highlights/accepts images. \* Allowed the Data Picker to take up more space in the Content Editor \* Added a dedicated way to minimize the Data Picker in the Content Editor

</details>

<details>

<summary>Fixes</summary>

\* Fixed the “Remove Connection” option in Connection Settings not working. \* Fixed an issue causing Page Capture to not display any pages when choosing a destination. \* Fixed account settings / login not showing up. (P.S. currently there is not much need or reason to create an account unless you’d like to export your user data) \* Fixed an issue with capturing images with the Element Selector if the image was source was from certain CDNs. \* Fixed an issue where changing the color of select/status/multi-select properties in Notion would cause captures to fail in certain circumstances. \* Enabled scrolling during tutorial to prevent getting stuck on small browser sizes.

</details>

***

## October 25, 2024

_10/25/2024 - v0.11.15_

<details>

<summary>Fixes</summary>

* Fixed bug causing database destinations to not appear

</details>

***

## October 25, 2024

_10/25/2024 - v0.11.14_

Light mode needs some love, and we’ll give it the attention it needs soon, but in the meantime this patch fixes the most notable issues with light mode.

<details>

<summary>Fixes</summary>

* Fixed light mode visibility issues in context menus and dropdown
* Fixed the light mode setting not persisting upon reopening Flylighter

</details>

***

## February 22, 2024

_02/22/2024 - v0.10.13_

Today we've got a fresh new release, bringing our public build up to version 0.10.13!

This set of releases mainly focuses on stability, improved loading times, and additional elements Flylighter is able to capture from web pages.

You'll now see embedded YouTube videos as available elements in the Web Data plugin, and our article parser has received a lot of love under the hood as well.

We've also squashed a lot of bugs. Ever see the movie _Constantine_ with Keanu Reeves? That many bugs.

Check out the full changelog below if you're curious. You may also want to [check that you have the latest version of Flylighter](../in-depth/updating-flylighter-manually.md) in your browser.

For our next release, we'll be focusing on adding some **major** new features to Flylighter – including Flylighter accounts, which will lay the foundation for syncing Flows and Capture History between devices. Can't wait to share more soon!

<details>

<summary>Changes</summary>

* Improved loading times
* Added a `?` menu item for quick access to Help Docs, app version, and more
* Added YouTube Video embed to data picker in the content editor
* Made improvements to article parsing
* Added letter icons for Notion workspaces without an icon set
* When duplicating a Flow (copy) is now appended to the name
* Added better error messages when failing to capture
* Added an option to go back to the Flow if a capture fails
* Added a help menu to the Flow list page header with links to docs
* Select dropdowns now scroll into view
* Button-type database properties are no longer visible (we can’t interact with them via the Notion API yet anyway)

</details>

<details>

<summary>Fixes</summary>

* Fixed being unable to scroll to the bottom of the Data Picker on a property
* Fixed number properties having unintended limitations
* Fixed a number of visual issues in properties
* Fixed capture history page not showing page icons
* Fixed color issues with the Data Picker
* Fixed an over-scroll issue in the Data Picker
* Fixed duplicating Flows without a folder creating two duplicates
* Fixed an infrequent issue that would result in Flylighter not opening when the toolbar button is pressed
* Fixed a hang when authenticating Notion when the connecting workspace did not have an icon set
* Fixed keyboard shortcuts assigned to Flows not working if the chosen key was a lowercase letter
* Fixed many instances of images in article not capturing.
* Fixed some visual issues in the quick capture dialogue
* Fixed Delete Flow in Flow settings not working
* Fixed an issue that resulted in freeze if parsed date values weren’t valid
* Popup height adjusted to properties with dropdowns are always fully visible
* Fixed being unable to open Flylighter on certain pages
* Fixed clicking the Data Picker button sometimes opening dropdown menus
* Fixed the scroll-into-view behavior from scrolling the incorrect view

</details>

***

## January 29, 2024

_01/29/2024 - v0.10.10_ Three releases today, folks! 0.10.8, 0.10.9, 0.10.10. The latter two mostly consist of hotfixes for small bugs that popped up in testing.

<details>

<summary>Changes</summary>

* Improved ability to find article / full page
* When clicking the Flow name in the Flow Editor, the text is automatically selected
* Changing the Flow name in the Flow Editor now also saves when clicking away, not just on enter
* Renaming a Flow from the Flow List now also saves when clicking away, not just on enter
* Copy data button in Data Picker is no longer transparent
* Added a colored border to the Data Picker button on Properties to indicate if it is autofilling
* Added a proper placeholder for the page selection dropdown
* Added detection for Author images and filtered them from article capture.
* Hid the Flow settings button in the content editor when using append capture
* Disabled destination and page dropdowns when using append capture
* Added hover effect on Folder icon to improve clarity

</details>

<details>

<summary>Fixes</summary>

* Fixed article / full page capture failures due to length
* Fixed append capture causing a crash
* Fixed changing a Flow to Page Capture mode sometimes causing a crash
* Fixed an infrequent freeze that would occur when typing to filter the list of databases
* Fixed being unable to scroll the Flow List when it overflows the popup
* Fixed Notion workspaces with an Emoji as the icon not appearing correctly
* Fixed Notion databases with custom image icons not appearing correctly
* Fixed dropdown properties overlapping open dropdowns above them
* Fixed the dropdown menu loading icon overlapping the text
* Fixed the database selection dropdown overlapping the page selector when Flow is in Page Capture mode
* Fixed a layout issue with page capture that didn’t allow you to view the Flows settings
* Fixed being unable to scroll Capture History when overflowing
* Fixed back button behavior in the Flow Editor when in page capture mode
* Fixed last segment of text in each paragraph of an article capture being duplicated
* Fixed emoji workspace icon on Settings > Flows
* Fixed issue causing context menus to be cut off in the Flow list
* Fixed selected dropdown options not using ellipsis overflow correctly
* Fixed and issue with highlights with only 1 piece of data causing Data Picker error
* Fixed Data Picker allowing for unneeded horizontal scrolling which also caused odd wrapping behavior with long text.
* Fixed YouTube timestamp formatting
* Fixed issue where block merging function failed when multiple paragraphs were selected in a highlight

</details>
