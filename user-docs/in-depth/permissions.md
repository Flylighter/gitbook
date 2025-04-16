---
icon: list-check
---

# Extension Permissions

Flylighter has access to all sites by default. This access helps you capture content and use keyboard shortcuts without friction.

If you'd like to restrict Flylighter's permissions, you can do so using your browser's Site Access tools, which are available on all extensions. To access them:

1. Right-click the Flylighter icon in your toolbar, or hit the  ••• button next to it in your extensions list.
2. Hover over the **This Can Read and Change Site Data** option.
3. Choose the permission setting you want.

<figure><img src="../.gitbook/assets/CleanShot 2025-04-16 at 13.11.31@2x.png" alt=""><figcaption></figcaption></figure>

Choose **When You Click the Extension** if you'd like to prevent Flylighter from accessing anything until you explicitly click the extension icon.

Note that changing this setting will prevent certain features from working properly, including:

* Keyboard shortcuts to open Flylighter/Flows
* Context menu shortcuts when Flylighter is closed
* Sidebar mode
* Persistent highlights

These features require an active background script that loads at the same time as the current page's content.

**However, Flylighter's core functionality will continue to work.** You'll still be able to open the extension, run flows normally, and even capture highlights and elements from the page once Flylighter is open.

We can continue to offer this core functionality because **Flylighter uses the official Notion API for captures.**&#x20;

Some other third-party web clippers use unofficial, unapproved methods for capturing data, which depend on you being logged into Notion within your active browser. They need persistent access to your logged-in Notion account, which means you can't restrict extension permissions without fully breaking the extension. This is one of the key reasons we decided to build Flylighter in the first place.
