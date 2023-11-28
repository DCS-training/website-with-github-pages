# Build your personal or project website with GitHub Pages

**Last updated**: November 2023
**Authors**: Aislinn Keogh and Sarah Schöttler

## Week 1: Getting started with an HTML template

For this course, we'll be using templates from [HTML5 UP](https://html5up.net/).
There are plenty of other options out there (or you can even make one yourself!) but HTML5 UP is a nice place to start as their templates are free, easy to use, and offer a wide variety of functionality.

### Step 1: Pick a template

Have a look through the options on [HTML5 UP](https://html5up.net/).
You can click on 'Live Demo' to see any template in action with placeholder content.
Bear in mind that some of the demo sites look quite busy (because they're showing off everything that's available in the template); don't let this put you off as you can always strip it back to basics!

### Step 2: Download your template

Click on 'Free Download' next to the template you like.
Then, navigate to wherever the ZIP folder has downloaded on your computer (probably your Downloads folder) and unzip it into a more useful location (e.g. your Documents folder).

When you open the unzipped template folder, you'll see a variety of files and folders.
Different templates will vary a bit, but they'll all have some aspects in common:

- `/assets`: For the purposes of this course, **you can ignore this**. This folder contains the [CSS](https://codeinstitute.net/blog/what-is-css-and-why-should-i-learn-it/), [SASS](https://www.w3schools.com/sass/sass_intro.php), [JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript) and font files for your website. You'll only need to touch these if you're doing some pretty serious customisation!
- `/images`: This folder will contain any placeholder images that are used on the demo site. It's also where we'll add our own image files later.
- `LICENSE.txt`: The Creative Commons Attribution for the template.
- `README.txt`: A quick description of the template from its creator.
- `index.html`: **The most important file**: this is your website's homepage!

If you've chosen a multi-page template, you may have some other `.html` files; the filenames will correspond to page names in the menu.

### Step 3: Download a text editor

In order to edit the content on your website, you'll need a text editor.
We recommend [Visual Studio Code](https://code.visualstudio.com/) but if you already have one you prefer, you can use that instead.
The nice thing about VS Code is that it has GitHub integration, which will be useful for us next week!
N.B. If you're on Windows and you can't find VS Code in your start menu after installing it, follow [these instructions](https://softdev.ppls.ed.ac.uk/online_experiments/editor_hunt.html).

### Step 4: Start adding content!

Just to keep things clean, I suggest you make a copy of the `index` file and rename the original to `template`.
You can then delete things you don't want from your working copy of the homepage, safe in the knowledge that they're in the original template file if you ever want to use them in future.

To see the current status of your website at any time (e.g. after you make any changes), double click on the `index` file to open it up in your browser.
It's important to understand that this is just a local copy of your website; if you look at the address bar, you'll see a path to a folder on your computer rather than a real URL.
This means that no one else can see your website and you can't share this link.
Next week, we'll show you how to get it up on GitHub and get a real URL!

Open up your `index` file in your text editor.
This is an HTML file, so you'll need to use HTML tags to make your text and images appear how you want them.
[Here's a cheatsheet](https://developer.mozilla.org/en-US/docs/Learn/HTML/Cheatsheet) for HTML syntax.

#### Change the title

To change the title that appears on the browser tab when you open your website, find a line that's enclosed in `<title> </title>` tags.
Change the text in between these tags to your name (or the name of your project).

To change the main header text on the webpage itself, look for a section that starts with `<!-- Header -->`.
Depending on which template you've chosen, this may correspond to a header in the middle of the page or one in a sidebar; if you look at the code alongside the page in your browser, you should be able to match the text up.
Try changing the main header text (probably enclosed in `<h1> </h1>` tags) to your name (or the name of your project).

Save the file and reload it in your browser; can you see your name?

#### Add your own image

First, copy an image file you want to put on your website into the `/images` folder.
Next, in your browser, find a section with an image that you want to replace with your own.
You can work out which image file it is by right-clicking, opening it in a new tab and looking at the file name in the address bar.

In your text editor, find a line of code which looks like this: `<img src="images/IMAGE_NAME.jpg" alt = "" />`.
Replace `IMAGE_NAME.jpg` with the name and file extension of the image you've just copied over.
If you want any alt text, add that in between the quote marks after `alt = `.

Save the file and reload it in your browser; can you see your image?

#### Add your bio

In your browser, find a section of text you want to replace with your bio.
Then, find that text in the file in your text editor.
Note that the code is in order i.e. if it's the first paragraph on the page, it will be somewhere near the top of the code!
Replace the placeholder text with your own text.

Have a look at the [HTML cheatsheet](https://developer.mozilla.org/en-US/docs/Learn/HTML/Cheatsheet) to see how to format your text e.g. with bold, italics, underlining, heading styles.
Each paragraph should be enclosed in `<p> </p>` tags.
Different paragraphs will have a chunk of whitespace in between them; if you just want a line break without all that space, you can put a `<br>` tag at the end of a sentence.

Save the file and reload it in your browser; can you see your text?

#### Add some links

There are various things you might want to link to on your website, such as:

- Your lab, research group or school website
- Your social media pages
- Your publications

Anything can be a link in HTML: text, images, buttons, icons etc.
Text is the simplest, so we'll start with that.
A text link looks like this: `<a href="www.some-website.com">your text here</a>`.
To make the link open in a new tab (usually advisable!), add `target="_blank"` after the URL i.e. `<a href="www.some-website.com" target="_blank">your text here</a>`.

Try adding a link to your bio.
For example, `I work at the <a href="https://www.ed.ac.uk/" target="_blank">University of Edinburgh</a>`.

Save the file and reload it in your browser; can you see and click on your link?

#### Change the menu

Somewhere in your `index` file (it depends on the template!), you should be able to find a list of the page names that are in the menu you see in your browser.
They'll each be enclosed in `<li> </li>` tags and the whole list will be enclosed in `<ul> </ul>` tags; these tags are for an unordered (i.e. bullet-pointed rather than numbered) list.

You'll see that each line contains a link to another HTML file; this is the file containing the content for that page.
If you want to add a new page to the menu, make sure there's a corresponding HTML file!
You can also delete any line from the list to remove that page from the menu, or move the lines around to change the order of the menu.

Try adding/removing some pages from the menu.
Save the file after each change and reload it in your browser; can you see your menu changing?

## Week 2: Getting it on GitHub

Content coming soon!

## Further resources

- [Short (1-2 hour) tutorial on building a website using an HTML template](https://www.natecation.com/making-a-website-for-free/) (covers much of the same content we went through in Week 1)
- [CSS cheatsheet for extended customisation](https://www.geeksforgeeks.org/css-cheat-sheet-a-basic-guide-to-css/)

## Feedback

If you attended this course, please fill out our [feedback form](https://forms.office.com/r/YYNrqvuNr8).

[![License: CC BY-NC 4.0](https://licensebuttons.net/l/by-nc/4.0/80x15.png)](https://creativecommons.org/licenses/by-nc/4.0/)
