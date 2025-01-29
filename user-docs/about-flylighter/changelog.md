# Changelog

<details>

<summary>Feb 22, 2024</summary>

Today we've got a fresh new release, bringing our public build up to version 0.10.13!

This set of releases mainly focuses on stability, improved loading times, and additional elements Flylighter is able to capture from web pages.

You'll now see embedded YouTube videos as available elements in the Web Data plugin, and our article parser has received a lot of love under the hood as well.

We've also squashed a whole lot of bugs. Ever see the movie _Constantine_ with Keanu Reeves? That many bugs.

Check out the full changelog below if you're curious. You may also want to [check that you have the latest version of Flylighter](../in-depth/updating-flylighter-manually.md) in your browser.

For our next release, we'll be focusing on adding some **major** new features to Flylighter – including Flylighter accounts, which will lay the foundation for syncing Flows and Capture History between devices. Can't wait to share more soon!

#### Changes

* Improved loading times
* Added a `?` menu item for quick access to Help Docs, app version, and more
* Added Youtube Video embed to data picker in the content editor
* Made improvements to article parsing
* Added letter icons for Notion workspaces without an icon set
* When duplicating a Flow (copy) is now appended to the name
* Added better error messages when failing to capture
* Added an option to go back to the Flow if a capture fails
* Added a help menu to the Flow list page header with links to docs
* Select dropdowns now scroll into view
* Button-type database properties are no longer visible (we can’t interact with them via the Notion API yet anyway)

#### Fixes

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

<details>

<summary>01/29/2024 - v0.10.10</summary>

Three releases today, folks! 0.10.8, 0.10.9, 0.10.10. The latter two mostly consist of hotfixes for small bugs that popped up in testing.

#### Changes

* Improved ability to find article / full page
* When clicking the Flow name in the Flow Editor, the text is automatically selected
* Changing the Flow name in the Flow Editor now also saves when clicking away, not just on enter
* Renaming a Flow from the Flow List now also saves when clicking away, not just on enter
* Copy data button in Data Picker is no longer transparent
* Added a colored border to the Data Picker button on Properties to indicate if it is auto-filling
* Added a proper placeholder for the page selection dropdown
* Added detection for Author images and filtered them from article capture.
* Hid the Flow settings button in the content editor when using append capture
* Disabled destination and page dropdowns when using append capture
* Added hover effect on Folder icon to improve clarity

#### Fixes

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
* Fixed issue causing context menus to be cutoff in the Flow list
* Fixed selected dropdown options not using ellipsis overflow correctly
* Fixed and issue with highlights with only 1 piece of data causing Data Picker error
* Fixed Data Picker allowing for unneeded horizontal scrolling which also caused odd wrapping behavior with long text.
* Fixed youtube timestamp formatting
* Fixed issue where block merging function failed when multiple paragraphs were selected in a highlight

</details>