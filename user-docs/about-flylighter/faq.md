---
icon: circle-question
---

# FAQ

## How is Flylighter different from other Notion web clippers?

Flylighter is focused on speed, flexibility, and security.

#### Speed

You can configure Flows more quickly in Flylighter than you can build forms in other web clippers because we don't separate Flow configuration from Flow use.

This means you can build and change a Flow on the fly – you can set properties to autofill every time you capture, but you can also add custom data on individual captures.

Additionally, you can set Flows to **Instant Capture** to run them in one click, and define **custom keyboard shortcuts** to run Flows right from your keyboard.

#### Flexibility

Flylighter is also quite a bit more capable when it comes to capturing web data. It can capture:

* Entire articles
* Highlights
* Screenshots
* Images – from your clipboard or local file system via drag-and-drop
* Specific HTML elements – both with our Element Selector, and via CSS classes
* YouTube timestamps

The Content Editor in Flylighter lets you pick and save **multiple** elements and highlights – not just one. This applies both to the page body in Notion, as well as to supported Notion database properties.

You can also add annotations (e.g. notes) to your highlights – in fact, the Content Editor functions almost like a Notion, letting you take basic notes right inside the extension.

#### Security

Flylighter uses the [official Notion API](https://developers.notion.com/) to send your capture data to Notion. This means two things:

* Flylighter can only add content within the specific Notion pages and databases you explicitly allow it to access
* When Flylighter takes an action in your Notion workspace, such as creating a new page, it is acting as Flylighter – not you.

Some other 3rd-party Notion web clippers require you to be logged into Notion in the browser. Why?

The reason is that they _don't_ use the official Notion API. Instead, they use your **user session token** to literally act as you. They use unofficial workarounds to take actions in Notion as if they were you, not an integration.

While this does allow them to get around certain limitations (the Notion API doesn't support image uploading, for example), it also makes them riskier to use. Their access to your workspace is not limited, like an integration's access should be.

## Is Flylighter secure?

Yes. Flylighter runs locally in your browser, and currently only sends data outside your browser's local storage in the following cases:

* When sending your capture data to your desired Destination (e.g. your Notion account)
* Telemetry (anonymized bugs, error logs, and similar usage data) – you can disable this in Settings → Privacy.
* If you're subscribed to our Pro or Insider plans, our Sync feature will sync your flows, capture history, and settings across your devices and browsers.

User data synced on the Pro and Insider plans is stored securely in [Supabase](https://supabase.com/).

Additionally, Flylighter uses the [official Notion API](https://developers.notion.com/). As mentioned above, some other web clippers not developed by Notion use unofficial means to access your Notion account, like using your **user session token** in your browser.

## Can I limit Flylighter's access in my browser?

Yes. See [permissions.md](../in-depth/permissions.md "mention") for more details!
