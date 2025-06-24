# The Plant Humanities Lab and Juncture

Juncture is a web platform using GitHub, Markdown, and custom viewers for creating interactive web pages. The Plant Humanities Lab is a website built using Juncture that explores the cultural histories of plants and their influence on human societies.

Using Juncture, feature-rich websites can be created easily at no cost.

## Getting Started

Follow these four simple steps to create and view your first Juncture page.

### 1. Sign up for a free GitHub account

1. Go to [github.com](https://github.com/) and click **Sign up**.  
2. Choose a username, enter your email, and create a secure password.  
3. Verify your email address to activate your account.

### 2. Create a GitHub repository

1. From your GitHub dashboard, click **New repository**.  
2. Give it a name (e.g., \`my-juncture-site\`) and an optional description.  
3. Select **Public** so your Markdown files are accessible to Juncture.  
4. (Optional) Initialize with a \`README.md\` if you’d like a landing page.

### 3. Add your first Markdown file

1. In your new repo, click **Add file** → **Create new file**.  
2. Name the file \`README.md\`, \`index.md\`, or any other \`.md\` filename.  
3. Paste in your Markdown content (see example below), including any Juncture tags.  
4. Commit your changes to the default branch (\`main\` or \`master\`).

    ```markdown
    <param ve-config layout="vtl" title="Common Sunflower" banner="wc:Sunflower_in_Toole_County_MT_banner.jpg">

    # Common sunflower

    The **common sunflower** (_Helianthus annuus_) is a species of large annual forb of the daisy family Asteraceae. The common sunflower is harvested for its edible oily seeds, which are often eaten as a snack food. They are also used in the production of cooking oil, as food for livestock, as bird food, and as plantings in domestic gardens for aesthetics. Wild plants are known for their multiple flower heads, whereas the domestic sunflower often possesses a single large flower head atop an unbranched stem.[^1]
    <param ve-image src="wc:Sunflower_sky_backdrop.jpg">

    [^1]: Wikipedia contributors. (2025, June 24). Common sunflower. In Wikipedia, The Free Encyclopedia. Retrieved 21:57, June 24, 2025, from [https://en.wikipedia.org/w/index.php?title=Common_sunflower](https://en.wikipedia.org/w/index.php?title=Common_sunflower&oldid=1297100912)
    ```

### 4. View your page in Juncture

1. Open your browser and use this URL template:

   ```php-template
   https://v3.juncture-digital.org/<GitHub-username>/<repository>/<path-to-file>`
   ```
   
   For example:  
   https://v3.juncture-digital.org/rsnyder/demo/README.md

2. If your file is named `README.md` or `index.md`, you can omit the filename:

   https://v3.juncture-digital.org/rsnyder/demo

3. **Optional bookmarklet:**  

   Drag this link to your bookmarks bar to create a “**View in Juncture**” bookmarklet.  
   Clicking it on any GitHub page with a Markdown file will open that file in Juncture.

   <a href="javascript:(function()%7Bhttps%3A%2F%2Fv3.juncture-digital.org%3Fgithub%3D%22%2Bdocument.URL%7D)()%3B%7D)()%3B">🔗 View in Juncture</a>

That’s it—your Markdown content will render as a fully featured Juncture page with interactive viewers. Enjoy exploring and extending your new site!  
