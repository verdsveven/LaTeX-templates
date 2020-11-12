# My LaTeX templates
* Work in progress **LaTeX** templates that I have created over time by simply using LaTeX and seeing which packages, settings and options I use (let me know what I should improved)
* **Paper format** set to A4 by default, but are easily changeable and editable
* **Bibliography** set to APA style by default, but this is obviously changeable to one's liking
* **Sub-templates** tailored for specific use cases (essay, article, thesis, etc.).

## A little note on usage
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

## Templates
### Essay template
* Contains: basic declarations, biblatex package with bibliography and url package to make urls look better
* Everything is on the same page except the bibliography (which is probably best to keep separately to be honest)

### Article template
* Same as the essay template, but it also includes an abstract, table of contents and a first section (without a title)

### Thesis template
* Same as the article template, but the title page, the abstract page and the contents page are on separate pages and the two sections (one extra one added as opposed to the article template) are by default titled Introduction and Conclusion (those are typical to use so I put them there)
