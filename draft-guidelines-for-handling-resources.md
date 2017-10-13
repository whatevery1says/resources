# Draft Guidelines for Handling Resources

## Definition of a Resource

Any document that we wish to archive on GitHub is considered a "resource". This applies in the following situations:

* It is desireable to implement version control on the document.
* The document is written in Markdown that we wish to display directly in a website page and/or on GitHub.
* The document is in a format that is not intended to be converted to HTML (e.g. Word, PDF), but which we wish to provide an external or download link to on the website.
* The document is intended for internal use and we wish to distribute it to project staff via GitHub.

## Blog Posts

Blog posts are generally not generally considered resources, and we can leave their archiving to the WP database. In general, however, they should be authored offline in Markdown and the Markdown text pasted into the WP text editor. The Jetpack plugin will convert the text to HTML and save the Markdown to the database's `filtered_content` column, from which it can be extracted easily. This procedure has the additional advantage of using Markdown to enforce simple, consistent formatting.

The [StackEdit](https://stackedit.io/) editor is probably is probably the most accessible Markdown editor. The text can be copied from there directly into the Wordpress text editor. (Eventually, StackEdit will probably have the ability to publish directly to Wordpress, but it is not there yet.) More advanced users should be encouraged to author text in a code editor that employs linting (see below under **Markdown Linting and Inline HTML**).

## Website Pages

Like blog posts, some page material on the website may not be appropriate to archive as a "resource". In this case, the instructions for blog posts should be followed. Otherwise, the conent should be authored in Markdown using [StackEdit](https://stackedit.io/) or a code editor. This will encourage simple, consistent formatting and make it easy to convert the text to other formats. More advanced users should be encouraged to author text in a code editor that employs linting (see below under **Markdown Linting and Inline HTML**).

For material intended only for the website, the content can be pasted directly into the WP text editor. However, most resources should be archived on GitHub. The best workflow will be to push the content to GitHub and then copy and paste the Markdown from there. It is possible to sync WP and GitHub content, but the process is clunky and may not be worth it at this stage. If material published to the web is updated on GitHub, it should be part of the workflow to paste the new content into WP and update the WP page. 

Non-textual assets (e.g. images) should be saved separately and archived on GitHub. The urls used to embed these assets in the web pages should be to the files archived on GitHub, not to the WP media library.

## Other Resources

Documents in formats other than Markdown or HTML should be archived on GitHub. In general, the "Markdown first" philosophy should be followed. That is, wherever possible, documents should be authored first in Markdown and then converted to other formats. This will encourage simple, consistent formatting, and make it easy to convert the text to other formats.

Conversion to Markdown to Word can be done by hand, but [Pandoc](http://pandoc.org/) does a very good job of automating the process. To use pandoc, install it and open a command line. Navigate to the folder containing the Markdown document and type `pandoc -s -o mydoc.docx mydoc.md`. This will create a new file called `mydoc.docx` baded on `mydoc.md`. The resulting Word document may need some hand editing, especially to introduce appropriate page breaks. This is an important step before converting to PDF format, which can be done using Word's `Save As` function.

Images can be embedded in Word and PDF files, but the originals should also be archived on GitHub.

In general, the Word files used to generate PDFs should be saved as "drafts". Minor changes to the formatting can then be made to the Word file and new PDFs generated. If the Word file is based on an original Markdown file, care should be taken to ensure that all changes to the text are made in both files. If there are drastic changes, only the Markdown should be edited, and the Word file should be regenerated based on the new copy. 

## Markdown Linting and Inline HTML

In order to ensure that Markdown renders correctly on GitHub, care should be taken that Markdown conforms to the rendering requirements of the [GitHub-Flavored Markdown spec](https://github.github.com/gfm/). This is a stricter standard than most web-based Markdown editors employ. For instance, the Markdown `#Heading1` will display as HTML `<h1>Heading1</h1>` in StackEdit, but not on GitHub. The most fool-proof method of doing this is to author Markdown in a code editor like Sublime, Atom, or VS Basic, using a Markdown editor plugin. These plugins employ "linting" a method of showing errors in code. Markdown linters will display errors where the markup does not conform to strict standards.

Most linters will enforce a rule that a Markdown document cannot contain inline HTML. For instance, GitHub-Flavored Markdown does not have a method of opening a link in a new tab. Hence, it is legitimate to replace a standard Markdown link like `[My Link](url)` with `<a href="url" target="_blank">My Link</a>`. In other cases, such as internal links for footnotes or special formatting, it may be useful to simply write the formatting rules in HTML and CSS directly within the Markdown document. Since the Markdown will be converted to HTML anyway on GitHub and the WE1S website, this is allowable. Therefore, users of Markdown linters may ignore the "no inline HTML" rule.

## Storage of Resources

All resources other than blog posts and some web content should be stored in the GitHub `whatevery1says/resources` repo. It is possible that we should create a parallel `development_resources` repo for internal documents, especially drafts and Word documents from which PDFs are created. Within the `resources` repo, there can be subfolders indicating the nature of the documents: reports, guidelines, and so on. No taxonomy is currently prescribed.

At the level of the individual document, we face challenges: assigning descriptive filenames and storing assets. I am considering whether it is possible to adopt the conventions of the [Frictionless Data](http://frictionlessdata.io/) specification to address these issues.