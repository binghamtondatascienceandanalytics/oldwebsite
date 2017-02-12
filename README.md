# [BUDataScienceandAnalytics.Github.io](https://budatascienceandanalytics.github.io)
Information and resources for a new student organization
## How to make changes to the website
* The website content is in the `md` files above (except for README.md which is this file)
* Index.md has the content for the main page
* Click on the name of the file to see the formatted content
* Then click on the pencil icon to edit the content with markdown formatting
* You can click "Preview changes" to see the formatted content without saving
* When finished, click "Commit changes" at the bottom to save changes

### Markdown formatting
* Headings start with #, ##, and ###
* Paragraphs are separated by a blank line, line breaks by two spaces at the end of a line
* Character formatting is \*italic\*=*italic* \*\*bold\*\*=**bold** and \`monospace\`=`monospace`
* Bullet lists start with a "\*" on each line, numbered lists start with "1." etc.
* Links are created with `[link](http://example.com)`=[link](http://example.com)

### Creating a new page
* Clink on `Create new file`
* Give it a short name (no spaces) ending with `.md`
* Add your content
* Make sure there is a link back to `https://budatascienceandanalytics.github.io`
* Save the new page by clicking "Commit changes"
* Add a link from the main page to `https://budatascienceandanalytics.github.io/newpage.html`
* Note that changing the `.md` page causes the `.html` page to be updated

### Changing the website style
* Click on the settings tab at the top of the page
* Scroll down to "Github Pages" and "Theme chooser"
* Click on "Change theme"
* You can choose from 12 themes and see them previewed below
* Click on "Select theme" to save your selection
* Refresh the webpage to see the results

### Changing the webpage headers
* The text for the headers (title and description) are in the `_config.yml` file

## One *slight* problem with everything above
* it is considered very bad practice to "commit to the master" and you don't want to make a habit of it
* You want to make your changes to a branch and then merge it with the master when it is ready to go live
*
