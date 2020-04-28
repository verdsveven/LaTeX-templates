# My LaTeX templates

## Basics
* These are LaTeX templates that I have created over time by simply using LaTeX and seeing which packages, settings and options I use.
* These are still work in progress; I am constantly updating them and finding errors in them as I use them.
* These are set to A4 by default as us Europeans use the proper paper standard :D (just kidding guys; no hard feelings xD)
	* These are easily changeable and editable (it is possible to set it to whatever paper format you would want).
* Additionally, the bibliography is in APA style, but this is obviously changeable to one's liking
* There are sub-templates which are tailored for specific use cases (general purpose, essay, article, IA and EE (these last two are still in progress as I haven't started writing those properly yet; I might merge them into one and then make specific templates for each subject)).

### A little note on usage
* If you are on a UNIX-like OS:
	* Copy the file to whatever location renaming it in the process if you want
```
cp /PATHTOCLONEDIR/TEMPLATEOFCHOICE.tex /DIROFCHOICE/NAMEOFCHOICE.tex
```

	* If you use VIM as your text editor, simply use the read command (:r)
		* Also possible with VIM on Windows, but use windows paths instead
```
:r /PATHTOCLONEDIR/TEMPLATEOFCHOICE.tex
```

* You can also just open the file and copy the contents into a new document (on any OS)

## General purpose template
* What can you say really, this one is made to be expanded; it just contains the document class (article, as that is the most common, but it is easily changeable) and the begin and end document. This is essentially the basic LaTeX syntax; in essence the minimum to get your document compiled properly.

## Article template
* Just a generic article template with bibliography and the like
* It also includes an abstract, table of contents and a first section (without a title).
* Includes the url package to show urls properly and url style is set to same (the same as the default for the document)

## EE+IA template
* Now combined into a single template
* They contain all the stuff that is contained within the article template, but the title page, the abstract page and the contents page are on separate pages and the two sections (one extra one added as opposed to the article template) are automatically titled Introduction and conclusion (those are typical to use so I put them there).
* These might get edited and probably merged into one.

## Essay template
* This just the article template, but without the abstract, table of contents and sections. Additionally, everything is on the same page except the bibliography (which is probably best to keep separately to be honest).
* I made this to write essays and I found that I really didn't need separate pages for things and I didn't really need an abstract.

### Closing statement:
* I am still working on them and editing.
* Please let me know if there is something that can be done better or improved in any way.
