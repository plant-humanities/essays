# The Plant Humanities Lab and Juncture

Juncture is a web platform using GitHub, Markdown and custom viewers for creating interactive web pages.  The Plant Humanities Lab is a web site built using Juncture that explores the cultural histories of plants and their influence on human societies.

Using Juncture, feature-rich web sites can be created easily at no cost.

# Getting Started

## 1. Sign-up for a (free) GitHub account

## 2. Create a GitHub repository

Create a new repositoru to host the Markdown files that are used by Juncture.  These Markdown files include text and simple tags for formatting and Juncture viewer definition.

## 3. Create a Markdown file

Using Juncture v1 syntax, below is Markdown text for a simple web page.  It includes text and a Juncture tag for including an image hosted by Wikimedia Commons.  Below is an example of Juncture compatible Markdown source file.  It includes a Markdown heading and Markdown formatting tags for bold and italicized text, a hyperlink, and a footnote.  It also includes two Juncture tags, a `ve-config` tag defining the header and layout, and an `ve-image` tag to include an interactive image viewer using a Wikimedia Commons image.

```markdown
<param ve-config layout="vtl" title="Common Sunflower" banner="wc:Sunflower_in_Toole_County_MT_banner.jpg">

# Common sunflower

The **common sunflower** (_Helianthus annuus_) is a species of large annual forb of the daisy family Asteraceae. The common sunflower is harvested for its edible oily seeds, which are often eaten as a snack food. They are also used in the production of cooking oil, as food for livestock, as bird food, and as plantings in domestic gardens for aesthetics. Wild plants are known for their multiple flower heads, whereas the domestic sunflower often possesses a single large flower head atop an unbranched stem.[^1]
<param ve-image src="wc:Sunflower_sky_backdrop.jpg">

[^1]: Wikipedia contributors. (2025, June 24). Common sunflower. In Wikipedia, The Free Encyclopedia. Retrieved 21:57, June 24, 2025, from [https://en.wikipedia.org/w/index.php?title=Common_sunflower](https://en.wikipedia.org/w/index.php?title=Common_sunflower&oldid=1297100912)
```

## 4. View the Juncture rendered web page

There are various ways to render the Markdown file as a web page, but the easiest is to simply use the Juncture site using a URL syntax that includes the name of the GitHub account and repository hosting the Markdown file and the Markdown file path within the repository.  https://v3.juncture-digital.org/`<GitHub username>/<GitHub repository>/<Markdown file path>`.  For instance - https://v3.juncture-digital.org/rsnyder/demo/README.md.  In this example the shorter form  https://v3.juncture-digital.org/rsnyder/demo will also work.  (When the Markdown file name is `README.md` or `index.md` it may be omitted)

As a convenience, drag this link to your bookmarks bar - [🔗 View in Juncture](javascript:(function()%7Bwindow.location.href%3D%22https%3A%2F%2Fv3.juncture-digital.org%3Fgithub%3D%22%2Bdocument.URL%7D)()%3B).  This will create a special bookmark (bookmarklet) in your browser toolbar.  Clicking on this bookmark when on a GitHub page associated with a Markdown file will open the Markdown file using Juncture.