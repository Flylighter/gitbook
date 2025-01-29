# Install Flylighter

Flylighter is a browser extension [available on the Chrome Web Store](https://chromewebstore.google.com/u/6/detail/flylighter/dlmdffmkcggiicjbfnjcnikkpahgplmd).&#x20;

It lives up in your web browser's toolbar, where you can click it to easily run any of your Flows and capture any information on the page you're visiting.

As a Chrome extension, Flylighter is compatible with any Chromium-based web browser, including:

* Google Chrome
* Microsoft Edge (Thomas's pick)
* Arc (Eli's pick)
* Opera

{% hint style="warning" %}
Flylighter is currently in beta! Our small team actively develops and tests the extension primarily on Chrome, Edge, and Arc.&#x20;

If you're part of our beta testing group and notice a bug on another supported browser, please let us know in our [testing community](https://community.thomasjfrank.com/c/flylighter-testers/). If you're not part of our beta and discovered this doc site on your own 😉, feel free to use [this bug report form](https://tally.so/r/woGLgx).
{% endhint %}

## Install the Extension

You can find and install Flylighter directly from the Chrome Web Store:

{% embed url="https://chromewebstore.google.com/u/6/detail/flylighter/dlmdffmkcggiicjbfnjcnikkpahgplmd" %}

Currently, we've only published Flylighter in the Chrome Web Store. It's not yet on the Microsoft Edge Add-ons store, but you can install the Chrome Web Store version on Edge (and any other supported browser).

Once you've installed Flylighter, you may want to also **pin** it in your browser's toolbar by clicking the puzzle piece icon, then clicking the icon next to the Flylighter entry:

<figure><img src="../.gitbook/assets/CleanShot 2024-02-11 at 10.22.42@2x.jpg" alt=""><figcaption></figcaption></figure>

## Connect Your Notion Account

After you've installed Flylighter, go to any normal webpage that _isn't_ a Chrome Web Store page – such as this very page, or this article on the [PARA method of digital organization](https://thomasjfrank.com/productivity/how-to-easily-organize-your-life-with-the-para-method/).

Click the Flylighter icon and then click **Login with Notion** to connect your Notion account.

<figure><img src="../.gitbook/assets/PixelSnap 2024-02-11 at 10.24.24@2x.jpg" alt=""><figcaption></figcaption></figure>

Flylighter uses the [official Notion API](https://developers.notion.com/), so if you've used any other Notion-connected tools in the past, you'll likely be familiar with the next part!

First, choose the Notion workspace you'd like the connect – and don't worry, you can connect multiple others later!

<figure><img src="../.gitbook/assets/PixelSnap 2024-02-11 at 10.26.26@2x (1).jpg" alt=""><figcaption></figcaption></figure>

Next, choose the **pages** and/or **databases** you'd like to connect to Flylighter. A few useful notes on this:

* If you grant access to a page, any pages and databases inside that page will also be included (you can revoke permission to specific pages or databases later, directly in Notion).
* You can give Flylighter access to other pages later directly in Notion by going to the ••• menu, then finding Flylighter in the **Add Connections** sub-menu.
* If you want to be able to work with **Relation properties** that connect to separate databases, make sure you grant access to those databases too. Otherwise, Flylighter won't be able to see that those Relation properties even exist.

<figure><img src="../.gitbook/assets/PixelSnap 2024-02-11 at 10.28.44@2x.jpg" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**Tip from Thomas:** I capture most things to my notes database in [Ultimate Brain](https://thomasjfrank.com/brain/) (my all-in-one productivity template for Notion), so I give Flylighter access to my entire Ultimate Brain page. That way, it gets access to all the databases it needed.

If you don't already have your own note-taking setup in Notion, you can use my free [Ultimate Notes](https://thomasfrank.notion.site/Ultimate-Notes-615417469d764e4c8136944371f21da1?pvs=4) template, which is similar to Ultimate Brain's notes dashboard.
{% endhint %}

{% hint style="warning" %}
**Note:** If you give Flylighter access to a lot of databases, it can take a while to index them when you're setting up your first Flow. We're working on improving the performance of this process, but you can speed it up yourself by hand-picking only a few databases or pages.
{% endhint %}

Once you've connected your Notion account, you can [create your first Flow](create-your-first-flow.md). (Alternatively, you can [watch our tutorial videos](watch-the-tutorials.md))

Flows are what you'll use to quickly capture web pages, articles, highlights, and more to Notion.
