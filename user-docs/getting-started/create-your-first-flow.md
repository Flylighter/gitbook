---
icon: paper-plane-top
---

# Create Your First Flow

Say you stumble upon a really cool web page about [accelarated learning](https://fs.blog/learning/), and you'd like to save it to Notion so you don't lose it.

This is a job for a Flow!

**Flows** are preset workflows for capturing information, including:

* **Web data** – URLs, page titles, full articles, metadata
* **Notion property values** – icons, page covers, tags, Relations, dates, and more
* **Page content** – nearly any web data can be capture to a Notion page.

With Flows, you can ensure whatever you're capturing goes to the _right place, right away._

For capturing our article on accelarated learning, perhaps we set up a Flow that:

* Captures to your **Notes database** in Notion
* Grabs the article's title, URL, and cover image
* Applies your **Learning** tag page, so you see the article in the filtered notes view on that page in your note-taking system.

In fact, let's do just that!

{% hint style="info" %}
**Tip:** If you don't already have a note-taking system, you can use my free [Ultimate Notes](https://thomasfrank.notion.site/Ultimate-Notes-615417469d764e4c8136944371f21da1?pvs=4) template, which ready for this tutorial right out of the box.

_If you're already using_ [_Ultimate Brain_](https://thomasjfrank.com/brain/)_, you've already got the most advanced version this same note-taking system (along with extra features)._
{% endhint %}

## Create Your First Flow

Click **Create New Flow** or hit **New** → **New Flow** to create your first Flow. You can also hit **New** → **New Folder** if you'd like to create a folder for it.

<figure><img src="../.gitbook/assets/PixelSnap 2024-02-11 at 12.08.30@2x.jpg" alt=""><figcaption></figcaption></figure>

Give your Flow a name, as well as an icon if you wish. The **book** icon is a good choice. But you do you.

### Choose a Database

Next, hit **Select an Option** to choose a Notion database. This will be your capture destination.

<figure><img src="../.gitbook/assets/PixelSnap 2024-02-11 at 12.11.28@2x.jpg" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Remember that Flylighter needs access to a Notion database before you'll see it in the list of choices. If the database you want doesn't show up, you can manually give Flylighter permission to access it by going to the database in Notion, hitting the ••• menu in the top-right corner, and then clicking **Flylighter** in the **Add Connections** sub-menu.
{% endhint %}

Once you've chosen your database, all of the database's visible properties will show up in the Flow editor.

### Add Web Data

When you're capturing to a database, you can set three types of values in Notion database properties:

* **Web data** – e.g. actual data from the web page you're visiting, like the title, URL, etc.
* **Existing/new property options** – e.g. options in a Select, Multi-Select, or Relation property. You can choose existing values or create new ones (in the latter case, some properties require your database to be unlocked).
* **Text, numbers, checkbox states, dates** – in certain property types, you can simply type or set your own custom values manually.

Let's start by adding some **web data** to your first capture. Typically, you'll want to use web data – usually the web page's **title** – when capturing that page.

On each property, you can click the **globe icon** to open up the **Data Picker.**

<figure><img src="../.gitbook/assets/PixelSnap 2024-02-11 at 12.15.41@2x.jpg" alt=""><figcaption></figcaption></figure>

The Data Picker is a powerful tool that lets you fill the selected property with web data from the current page. _(Technically, it's a suite of **plugins** – but we'll dig into those later!)_

Try clicking on the globe icon for the _Name_ property – this is pulled from your Notion database, so if you renamed it to something else (e.g. "Title"), it'll be labeled accordingly.

Next, pick the value in the **Title** section. This should be the title of the web page.

Note how the icon lets you know that value has been **Saved.** It's now set to auto-fill, which means it'll automatically grab the title of the web page the next time you run this Flow.

Also note the blue border on the globe icon; this lets you know that the property has an auto-fill setting applied.

<figure><img src="../.gitbook/assets/PixelSnap 2024-02-11 at 20.43.34@2x.jpg" alt=""><figcaption></figcaption></figure>

If your Notion database also has a URL property, I'd recommend doing the same for it – that way, your Flow will auto-fill the URL of the web page you're capturing.

{% hint style="info" %}
**Tip:** Head to the [Auto-Filling Flows](auto-filling-flows.md) page to learn more about how you can set rule for auto-filling properties with web data! **Title** and **URL** properties set themselves to auto-fill by default.
{% endhint %}

### Set Existing Property Options

Some Notion properties will also have a small 🔽 icon, which will let you set existing options from those properties – such as an option in a **Select** property, or a page in a **Relation** property.

You can also create new options in these properties right from Flylighter! Just start typing to bring up that option in supported properties.

{% hint style="warning" %}
**Note:** For some property type, like Select and Multi-Select, your database needs to be unlocked before you'll be able to create _new_ options. [Learn how to unlock a Notion database here](https://support.thomasjfrank.com/customizing-your-templates/78ZReSibJg7dV9R7ouqQrS/how-to-unlock-notion-databases/muCk11PNirQRjH5xaQRs9V).
{% endhint %}

Here, I'm selecting the Learning page inside a Relation property called Area/Resource, which I use effectively as a tagging system. _These terms come from_ [_the PARA Method_](https://thomasjfrank.com/productivity/how-to-easily-organize-your-life-with-the-para-method)_._

<figure><img src="../.gitbook/assets/PixelSnap 2024-02-11 at 20.48.32@2x.jpg" alt=""><figcaption></figcaption></figure>

You can also see that I've opened up the Data Picker and set this property to auto-fill to the **Exact Value** I've set. Anytime I run this Flow in the future, my Learning page will be set in this Relation property.

Finally, note how I've also added the **Web Clip** option in **Type**, which is a Select-type property.

Other property types will give you other options. In Text properties, you can simply type whatever you want (or use the Data Picker to grab dynamic data). Checkbox properties have a toggle you can set.

### Set the Page Cover and Icon

You can also set the Cover Image and Icon in the Notion page that will be created from your Flow.

<figure><img src="../.gitbook/assets/PixelSnap 2024-02-11 at 20.59.38@2x.jpg" alt=""><figcaption></figcaption></figure>

Near the top of the Flow builder, note the Icon and Cover options. These work similarly to the Notion properties below them; click them to open the Data Picker, and you'll see several options:

* **Icon:** In the Web Data plugin, you can choose the site's favicon. You can also use the arrows to navigate over to the Feather Icon and Emoji sections if you prefer those instead.
* **Cover:** If the page contains a featured image, cover image, or social media image, you'll see it here.

Icon and Cover values automatically set themselves to auto-fill with **Data Type.** This means you'll be able to automatically capture each web page's favicon and featured/social media image, if they exist.

## Capture the Page

Once you've set your properties the way you want them, you can hit **Capture** to run your Flow and capture the current page to Notion.

<figure><img src="../.gitbook/assets/PixelSnap 2024-02-11 at 21.02.13@2x.jpg" alt=""><figcaption></figcaption></figure>

Hit **Open in Notion** if you'd like to see your shiny, newly-captured page.

At this point, your Flow is also set up and can be re-used at any time. Any value you've set to **auto-fill** will do so on each new capture – and you'll still be able to set additional values that may be unique on a per-capture basis.

## Build Additional Flows

Keep in mind that you can do a _lot_ more with Flows. Here are a few more example Flows you could build:

* **Inbox Flow** – use Flylighter's Instant Capture feature and a keyboard shortcut to instantly capture a page to your notes inbox in Notion, without any tags. You can even set this to capture _full article text._
* **Research Flow** – open a Flow that allows you to select your tag on-the-fly, then open the Content Editor where you can capture highlights and add annotations to them.
* **Recipe Flow** – use Flylighter's Element Selector or Advanced Data plugins to select the recipe element at the bottom of your favorite cooking blog, and skip the 50,000-word story about how grandma used to make this recipe for me back when we lived in Ottumwa, Iowa. Back then, my grandfather worked at the cement plant, and he'd come back from a long day at the plant hungrier than a 2-ton bull hippopotamus. I think it was the summer of 1962 when she managed to grow a particularly big tomato crop, and so we spent a whole day in the garden harvesting....

##
