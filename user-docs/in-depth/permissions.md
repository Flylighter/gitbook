---
icon: list-check
---

# Extension Permissions

Flylighter has access to all sites by default. If you'd like to restrict Flylighter's permissions, you can do so using your browser's Site Access tools, which are available on all extensions.&#x20;

However, **Flylighter needs to be able to talk to the Notion API in order to capture data to Notion.** This means that choossing the "When You Click the Extension" option from the Site Access menu will cause Flylighter stop working.

Fortunately, there's a way around this!

First, **right-click** Flylighter and head to **Manage Extension.**

<figure><img src="../.gitbook/assets/CleanShot 2025-06-03 at 12.57.10@2x.png" alt=""><figcaption></figcaption></figure>

Under **Site Access:**

1. Choose **On Specific Sites.**
2. Add `https://api.notion.com` to the list.

<figure><img src="../.gitbook/assets/CleanShot 2025-06-03 at 12.58.53@2x.png" alt=""><figcaption></figcaption></figure>

Once you've done this, Flylighter will be able to make requests to the Notion API in order to capture pages from the web for you.

{% hint style="info" %}
Flylighter uses the official Notion API to make captures, unlike some other web clippers which use unofficial, unapproved methods. This is why Flylighter supports these site access settings.
{% endhint %}

All sites not listed in the Specific Sites list will function as **"When You Click the Extension"** sites – but Flylighter will also retain the ability to communicate with the Notion API.
