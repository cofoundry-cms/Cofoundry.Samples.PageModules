# Cofoundry.Samples.PageBlockTypes

***NB: The term 'Page Module' has been changed in Cofoundry 0.2 and is now 'Page Block Type'. This repository will be re-named accordingly when Cofoundry 0.2 is released.***

A bare website showing various examples of how to implement page block types.

If you have any requests for example block types, [let us know](https://github.com/cofoundry-cms/cofoundry/wiki/Feedback-&-Community).

#### To get started:

1. Create a database named 'Cofoundry.Samples.PageBlockTypes' and check the Cofoundry connection string in the config file is correct for you sql server instance
2. Run the website and navigate to *"/admin"*, which will display the setup screen
3. Enter an application name and setup your user account. Submit the form to complete the site setup. 
4. Log in and add a page with the *General* template, click on save and edit to go to the visual editor and play around with the page block types.

####  Example Page Block Types:

- **DirectoryList:** Lists pages in a specific directory. Demonstrates searching for pages using `IPageRepository` and using the `WebDirectoryAttribute` data model attribute.
- **HorizontalLine:** A very simple block type that adds a variable width horizontal line (wrapped hr tag).
- **PageList:** An orderable list of links to pages. Demonstrates quering for caches page routes using `IPageRepository`, the `PageCollectionAttribute` data model attribute and generating links to pages from page objects.
- **PageSnippet:** Displays summary information about a page. Demonstrates the `PageAttribute` data model attribute, querying and manipulating block data and handling availability of linked entities (due to draft status).
- **Quotation:** A quotation block that is output as blockquote with an optional cite tag.
- **TextList:** A list of text items that displays in an html unordered list, or optional in an ordered list.
- **VimeoVideo:** Embeds a vimeo video.
- **YouTubeVideo:** Embeds a you tube video.



