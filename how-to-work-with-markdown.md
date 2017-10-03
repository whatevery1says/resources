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
