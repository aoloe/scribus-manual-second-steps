# Notes

- the palettes in the window menu
- the managers in the edit and page menus
- the properties palette
- navigating the document
  - zoom
  - changing page
- raster and vector images
- master pages, guides and the scrapbook
- page size, margins and bleeds, orientation
- embedding and outlining fonts in a PDF
- imposition
- add a text frame and write
- add an image frame and load an image (external)
- italic and bold (with an explanation of the matching terms... slanted, ... "bold" means "gras"...)
- don't print: create a pdf and then print it.
- pages: scribus does not dynamically add the pages
  - define the number of pages at document creation (for shorter brochures)
  - adding the pages from the `page > insert` menu.
  - facing pages: defined in the `file > new` dialog or in `file > document settings`; first left / right
  - page numbers: add from menu into a text frame on the master page. (adding pages numbers / running headers would be a good tutorial for working with master pages / scrapbook / ...)
- transparencies: if you have transparencies, you have to very careful when creating the pdf. you have to check that the pdf version you have chosen does support transparencies (hint: use the right pdf version in the preflight verifier (the dialog that pops up when creating the pdf): you will then know if the transparencies are a problem or not). if you're distributing the PDF through the internet, and you have to know that not all the pdf viewers support transparencies. and not all print shops support transparencies either... even if they say that they accept PDFs with transparencies in them. ah, and last but not least, scribus cannot flatten the transparencies, but will leave them in the PDF, if the PDF version you use allows transparencies.
- spelling and hyphenating:
  - in the preferences choose your main language for both the spelling and the hyphenation
  - spelling dictionaries can be downloaded through the preferences dialog. on debian and ubuntu (and probably most unix system, you should rather install the wanted hunspell dictionaries through your package manager)
  - hyphenation dictionaries should be provided by scribus or, on debian and ubuntu, can be added from the package manager by installing the `hyphen-languagecode` packages.
changing the preferences is for

## preferences and document settings
- preferences that are independent from the current document (like the
  UI language)
- settings for the documents that you will be creating in the future

the preferences dialog mostly behaves the same, if a document is open or
not (except for things like manipulating the list of fonts, iirc)

on the other side, changes in the "document setup" only apply to the
current document.

## Gloassary

Some concept you can look up to feel at home

### Master pages

In Scribus, Master Pages are some sort of "page backgrounds". They're not really much more than that, although you can also use them to apply the same guides to different pages.

Starting from Scribus 1.6, you can interleave layer from Master Pages with the ones on the pages.

## Editing and formatting text

[GarryP says in the forums](http://forums.scribus.net/index.php/topic,2249.msg10304.html#msg10304):

The first thing I can say is that you should leave the Properties Palette open at all times. Once it's open don't close it. It remains active while you edit your document and the available tools change according to what you have selected. (If it makes things easier to understand you can think of the Properties Palette as an "Object Inspector".) I don't really know why the PP can be closed as Scribus isn't usable - in any meaningful way - if it's not open.

The next thing to say is that text formatting changes are easy (if you keep the PP open). First, don't use the Story Editor; it's not very good for most purposes. It has its uses in some circumstances but - for most use cases - it's pretty bad. Use inline editing instead. Inline editing means making changes within the text frame itself.

To make formatting changes to the whole of the text in the text frame just select the frame and use the PP Text tab options/tools to make the changes necessary.

To make formatting changes to specific text within a text frame, double-click the frame to enter inline editing mode. When you're in this mode, select the text you want to change - as you would do with any word processing software - and use the PP Text tab to make the changes in the same way as you would to change the formatting of the whole text as mentioned above.

See the attached "video" where changes are first made at a 'frame level' then, after a double-click, at a 'character level'.

Once you're comfortable making formatting changes this way I would suggest looking at learning about Styles which make formatting changes much quicker when you need to make changes at a 'document level'.

## Good habits

- using grids is a sign of looking for order. In most cases, for layout jobs it's better to use guides.

## Avoid beginner errors

- If you're doing your first steps with graphics, colors can be a hard topic:
  - Don't use colors that do not print reliably: gold, and list of a few others...
- Don't use transparencies, gradients and shadows: print shop still have issues with them.
