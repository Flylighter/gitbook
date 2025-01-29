# No Destinations Found

If you've given Flylighter permission to access a Notion page and its set of sub-pages, but you're not seeing one or more of those pages (or databases) in the Destination Picker, it may be due to a common Notion API issue.

We've found that when you give an integration permission to a large set of pages via the Notion API (which is what Flylighter uses), sometimes Notion will _show_ that the integration has been added to those pages – but won't actually grant the permissions. This is likely a bug on their end, which we've reported.

Fortunately, there's an easy fix while we wait for it to get patched.

Navigate to the page or database you're want to use in Flylighter. Click the ••• menu at the top-right of the page, then navigate to the **Connections** sectio&#x6E;**.**

If you see Flylighter listed there, hover over it and then hit **Disconnect.**

Then go to the **Connect To** sub-menu and choose **Flylighter** once again.

<figure><img src="../../.gitbook/assets/CleanShot 2024-03-12 at 08.57.58@2x.png" alt=""><figcaption></figcaption></figure>

It's unclear why this works, but manually removing and re-adding the connection seems to fix the issue with the Notion API.
