# How to Work with Markdown

Markdown is a lightweight text markup system that uses punctuation marks to indicate formatting instructions. It is human-readable but also easy to convert to other formats, most commonly HTML. It is also _very_ easy to learn because it is simple and straightforward. Markdown allows only a limited number of styling possibilities, which ensures that text written in Markdown is consistent and easy to convert. Writing in Markdown is a good idea because it forces you to keep your formatting simple. You can author Markdown documents in a simple text editor.

Converting documents from other formats _to_ Markdown is more complicated and hard to automate because it generally involves eliminating complex and inconsistent formatting. It works best if the original document was produced using only styling and layout features that are allowable in Markdown. This is actually good practice for writing. Keep your text simple and streamlined without a lot of extra formatting. For instance, if you are using Word to write a document, be aware that tabs, centering, and multiple spaces are not allowable in Markdown. Markdown also provides a system of hierarchical semantic headings. Word does too (you can find them in *Styles* section in the Toolbar), but few people use them. But this is a practice you should cultivate instead of formatting headings in bold, italics, or larger fonts. Let Word's built-in styles handle this (Word also allows you to create custom styles).

Note: For Windows, there is a plugin called [Writage](http://www.writage.com/) that allows you to write Markdown directly in Word. This simply has some built-in styles. It is possible still possible to write Markdown in Word without the plugin.

It is highly recommended to author documents in Markdown and then convert to other formats, but in some cases, documents in Word or HTML format may need to be converted to Markdown, especially for use in the WE1S project. This guide provides practical advice on how to use Markdown, convert between formats, and move documents in and out of a GitHub repository.

## How to Write Markdown

It is conventional to save files written in Markdown with the extension `.md`. Most editors will recognize these files as Markdown and will highlight the formatting to make the text more readable.

There are _many_ options for writing Markdown. A good place to start is simply by learning Markdown from a cheat sheet. The following websites are extremely useful.

* [https://daringfireball.net/projects/markdown/syntax](https://daringfireball.net/projects/markdown/syntax)
* [https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* [https://en.wikipedia.org/wiki/Markdown](https://en.wikipedia.org/wiki/Markdown)

Note that there are several dialects of Markdown. Wherever possibly, GitHub-flavored Markdown should be used so that it renders nicely on the GitHub website.

There are numerous WYSIWYG Markdown editors online, and you should experiment with them to get a feel for how Markdown renders as HTML. One of the best is [Dillinger](https://dillinger.io/). This allows you to edit Markdown and see the rendered text side by side, changing in real time.

You can also use a code editor (e.g. Sublime Text, VS Code, Atom, and so on) to write Markdown. Most code editors come with plugins to allow you to write and preview Markdown. See the section on **Advanced Usage** for some of the amazing things you can do if you write Markdown using a code editor.

## Converting from Other Formats

Here are some websites for converting from other formats:

* [Word-to-Markdown](https://word-to-markdown.herokuapp.com/)
* [HTML-to-Markdown](https://domchristie.github.io/to-markdown/)
* [Pandoc](https://pandoc.org/try/)

Note that these sites will be more successful if the formatting of the original Word or HTML document is consistent and contains only formatting allowable in Markdown. You may have to hand edit the results afterwards.

## Markdown on the WE1S Website

The WE1S website uses the Jetpack plugin to handle text written in Markdown. You can write your pages and posts directly in Markdown format in the web editor. Wordpress will automatically convert it to HTML when you save, and the HTML is displayed on the public website. Wordpress stores both the rendered HTML and the original Markdown.The [Markdown-Editor](https://wordpress.org/plugins/markdown-editor/) plugin provides preview functionality similar to [Dillinger](https://dillinger.io/).

## Markdown on GitHub

GitHub is a cloud-based service that provides repositories for code and documents. It also provides a wiki and discussion forum (called "Issues") for each repository. Any Markdown document deposited in GitHub is automatically rendered in beautiful HTML on the GitHub website. The [document you are reading](https://github.com/whatevery1says/resources/blob/master/how-to-work-with-markdown.md) is an example. If you wish to see the original Markdown, you can click the [`Raw`](https://github.com/whatevery1says/resources/raw/master/how-to-work-with-markdown.md) button available on any GitHub page.

GitHub uses the `git` version control system to keep track of changes made to files. This is not the place for a full git/GitHub tutorial, but the basic workflow is follows:

1. Create and publish a new repository on GitHub **or** if the repository already exists on GitHub, "clone" it to make a _local_ copy on your computer.
2. If you have a cloned repository, "pull" the latest version in case someone else on the team has made modifications.
3. Create or edit files in your cloned repository.
4. "Commit" the changes. This "stages" the changes for merging with the _remote_ copy on GitHub.
5. "Push" the commit to the remote repository on GitHub.

Steps 1, 2, 4, and 5 can all be accomplished using `git` from the command line, but this has a learning curve. An easier approach is to download the [GitHub desktop client](https://desktop.github.com/). Also, many code editors allow you to execute `git` commands from within the editor. See the section on **Advanced Usage** for further details.

For a full tutorial on getting up and running with GitHub aimed at digital humanists, see the Programming Historian's [An Introduction to Version Control Using GitHub Desktop](https://programminghistorian.org/lessons/getting-started-with-github-desktop).

## WE1S Workflow

This is just a running list of ideas and notes:

* The [Mytory Markdown Wordpress plugin](https://wordpress.org/plugins/mytory-markdown/) allows you to maintain a Markdown document on GitHub and provide a link to the `Raw` url in Wordpress posts and pages. With this, everything is stored in GitHub (I am not sure if content is also copied to the WP database). Theoretically, this could slow loading times (but would you notice with Wordpress) and content might not be available in the unlikely event that GitHub goes down. But it's worth exploring. This also assumes that all authoring takes place offline.

## Word to Markdown to GitHub to Wordpress: A Workflow

### Converting from Word to Markdown

1. When authoring in Word, restrict formatting to the following:

* Headings 1-5
* Emphasis (italics)
* Strong emphasis (bold)
* Strikethrough

1. Do use different fonts or font sizes, except if they are changed by Words heading styles.
1. Do not use indentation or text justification unless it is created by Word's heading, list, or table functions.
1. Make sure you use Word's bullet and numbering list functions.
1. Keep tables very small and simple.
1. Use as few images as possible.
1. Avoid the use of footnotes.

The last two require some explanation. It is possible to attach images to a Markdown file, but in converting from Word, they will be lost. So images will have to be added after conversion. Although some dialects of Markdown support footnotes, GitHub-flavored Markdown does not. There is a workaround using inline HTML, but it also generally needs to be implemented after the document is converted.

## Advanced Usage

* Code linting
* Source control
* Inline HTML