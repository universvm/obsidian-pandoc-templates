# Book
##  A simple, minimalist template to make books
I absolutely adore exporting things using the Obsidian Enhancing Export plugin, however, it lacked a nice and easy way to export text that resembles modern books.
This template hopes to address this gap. A simple, minimalist template with no complex working. It is very simple, and works instantly without making any changes to your document.
## Features :
- Plug and Play -> No need to faff around with YAML. Exports directly without hassle. 
- Features the actual font used in many modern books (tgpagella), and can be swapped for other fonts if the user chooses.  (See subheading 'More' for instructions)
- Pretty header and footer lines, adding a sense of formality.
- The header also features small text showing the current H1 Heading. 
- Dynamic page numbers at the bottom of the page, aligned with the footer line.
- Clickable (and hidden) links. (See subheading 'More')
- Removed heading numbers for a cleaner feel.
- Auto hyphenates words
## Drawbacks
- No language support (English only)
- No Image support (not tested)
If you have any solutions for these, do let me know. I am more than happy to incorporate them into this.
> *Note : I am not an expert LATEX user. This is my first ever LATEX template. As a result, criticm is very welcome. Feel free to send me an email at elbowsparse@gmail.com any time, suggest changes, and suggest fixes to existing code.*
## Instructions Of Use
- Assuming you are using the Obsidian Enhancing Export plugin, then this should already be incorporated in the default PDF export.
- Select "Book" from the dropdown menu of Latex Template, and then export.
- The rest will be handled by PDFLatex.
- Happy Exporting!
> *Note : For a proper paragraph break, you must press enter two times, such that there is a one line gap between one paragraph and the next. Otherwise, they will appear in the same line. See the example.*
## More
### Using this outside of Obsidian Enhancing Export.
[See this article](https://betterhumans.pub/obsidian-tutorial-for-academic-writing-87b038060522). Use `book.tex` instead of the file mentioned. Be sure to change the corresponding lines in the arguements section too.
> *Note : You might want to include `-f markdown+wikilinks_title_after_pipe+mark+lists_without_preceding_blankline` at the start of `Arguements` so that the links function and are well hidden.*
### Changing the font.
- Open `book.tex` locally with an editor of your choice.
- Find the following lines
		`\usepackage{tgpagella}`
		and
		`{\fontfamily{qpl}\selectfont$body$} % Content goes here`
- Replace `tgpagella` with any item from "Font Package Name" and `qpl` with the corresponding item from "Font Code" in [this article](https://www.overleaf.com/learn/latex/Font_typefaces).
- Happy exporting!

