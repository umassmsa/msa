# McCormack Sports Analytics

## Welcome MSA Officers!  This is the github repository for the website.

There are two main ways you can interact with this website.
1) Ideally, use a text editor like VSCode and use git commands: add, commit, and push to modify this github, and thus the website
2) Otherwise, you can edit the "raw files" of each page.  This method does not have "version control" meaning you cannot go back and restore older versions if you want to make a change down the line.  Click the icon that looks like a pencil to make these changes to the raw files.

One important note: this website is predominantly written in markdown.
Markdown is essentially like a google doc.
However, wherever we want to format something cool, like an image to readjust its size based on the width of a browser, then we use a block of HTML.
For likely 100% of this uses of HTML, you can use ChatGPT to write the HTML for you.

Ok, now where do I make changes?

### Changing the navigation bar:
The "settings.yml" file in the "data" folder.
The section of code starting with "menu" creates each tab on the website.
If you want to create a new tab, just follow the form of existing pages:
- { name: "Name of new page", url: "veryImportant" }
We'll get to what this "url" means in a moment.

### Adding pages:
The pages are the content of the website.  Inside the aptly named "pages" folder, this is where you will interact the homepage or literally any new page you want to add in the navigation bar (or a page that you can't reach from a navigation bar!).

Notice that the file name is of the form: <name>.md
Here, we can see the page is written in "Markdown"

At the top of each page, you see something like:
layout: page
title: NFL GM Challenge '23
permalink: /gm

The layout should be page, for pages.
The title will appear at the top of the page on the website.
**The permalink is that with which you called "url" in the navigation bar.**
This permalink is how other pages in the website can reference this page.

### Inserting media:
This is the most likey place you will run into the need for HTML.

### Uploading media:
Inside of the folder "assets" lies the images for the website.  
You can simply upload more files into this folder.

### Small things to consider!
Your changes may take at least 2-3 minutes to load, so don't worry if you don't seem them right away.
The internet is your friend!  As this website is written in markdown and HTML, feel free to rely on resources to help fill out the code.


Created from Millennial Template by Paul Le.
