# Notes

- the palettes in the window menu
- the managers in the edit and page menus
- the properties palette
- navigating the document
  - zoom
  - changing page
- raster and vector images
- master pages, guides and the scrapbook
- page size, margins and bleeds
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
