# Mad Libs Generator
This is a simple Mad Libs HTML generator.

![example](demo-screenshot.png)

## Getting Started

- /Applications/Utilities/Terminal
- To Use In [Terminal App](https://en.wikipedia.org/wiki/Terminal_(macOS)) ![image](64px-Terminalicon2.png),
copy each line verbatim AFTER THE DOLLAR SIGN, then paste into terminal and press return:
  - $ cd ; git clone git@github.com:urbanspectra-nyc/Mad-Libs-Generator.git
  - $ cd Mad-Libs-Generator ; open .
  - Open the local index.html file in your browser.
  - Look in /examples/ dir for examples.

- To Contribute As An Educator: What is your github id?
  - $ git fork # Now you have your own copy in your github account.
  - $ cd ; git clone git@github.com:[github-id]/Mad-Libs-Generator.git ; open .
  - $ cd Mad-Libs-Generator
  - $ mkdir -p /examples/[github-id]/; cd $_
  - $ git branch # Branch naming standards.
  - Paste example ascii and html test files here.
  - $ cd .. ; git status ; git add . ; git commit -m 'Changed some content.' ; git log # q to exit log
  - $ git push # Now go to your fork and see how to make a pull request.

- To Contribute As Project Tech Team Member:
  - $ cd ; git clone git@github.com:urbanspectra-nyc/Mad-Libs-Generator.git ; open .
  - $ cd Mad-Libs-Generator
  - $ mkdir -p /examples/[github-id]/; cd $_
  - $ git branch # Branch naming standards.
  - Change code here.
  - $ cd .. ; git status ; git add . ; git commit -m 'Changed some code.' ; git log # q to exit log
  - $ git push # Someone else will clone + fetch + merge + push!!


### Generating Mad Libs
To use the mad libs generator, type your story into the leftmost text area. To insert a textarea, type the part of speech it should be surrounded by hard brackets, like so:

```
[adjective]
```

- A preview will appear as you type on the right side of the screen.
- We can copy and paste the html source code from the middle column.
- Look at the sample .txt and ascii files under /examples/ for further guidance.

### Enhancements
- [ ] Debug Three Getting Started Instruction Sets => Tech First
- [ ] Debug Three Getting Started Instruction Sets => Edu Second
- [ ] Debug Three Getting Started Instruction Sets => i18n 3rd
- [ ] Use mini vocab set.
- [ ] Commit to several languages.
- [ ] List target words below.  Use hint rather than part of speech?

