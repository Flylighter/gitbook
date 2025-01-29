# Auto-Filling Flows

{% hint style="info" %}
_This page is under construction, and may have screenshots from a previous version of our UI._
{% endhint %}

Most properties in a Flow can be **auto-filled** with data, which makes captures even faster. Some properties – like Title, URL, Page Icon, and Page Cover – automatically set themselves to auto-fill when you choose an option from the Data Picker.

You'll almost always want to auto-fill dynamic data from the page for these properties, so we made these properties automatically auto-fill just to make setting up new Flows faster. But you can always open the Data Picker back up and set auto-fill to **Nothing** if you don't want something to auto-fill.





A few Notion property types automatically set themselves to auto-fill with dynamic data in Flylighter:

* Name (the title property in a database)
* URL
* Page Icon
* Page Cover

For any other property type (e.g. Select, Number, Relation, etc.), you can set the auto-fill&#x20;

##

##

## Data Items & Input Items

To understand how Flows save data for auto-filling, we'll make a distinction between two types of data:

* **Data Items** are items chosen from the **Data Picker**, like page titles, urls, etc.
* **Input Items** are items that are either manually input, or derived from your existing properties like selects, statuses, etc.

## Auto-Filling

By default, Flylighter will save a **Data Item** as the default fill when you select it. When a data Item is saved, you can edit it freely without effecting the auto fill. For example removing an unwanted part of a page title.

**Input Items** must be manually saved for auto-fill if you want it to remain the same across captures. For example, to save a select option to auto-fill, first select the value, then open the Data Item globe, and hit the **Save Value** button.

Similarly, for **Data Items** you can choose to save the **Exact Value** as default, or clear the saved value from here as well by choosing **None.**

<div align="center" data-full-width="false"><figure><img src="../.gitbook/assets/Frame 67.png" alt="" width="383"><figcaption><p>The save button on an Input Item</p></figcaption></figure> <figure><img src="../.gitbook/assets/Frame 68.png" alt="" width="385"><figcaption><p>The save button on a Data Item</p></figcaption></figure></div>

The automatic saving of auto-fill values for **Data Items** can be changed in the main extension settings.
