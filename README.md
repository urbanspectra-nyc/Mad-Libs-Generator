# Mad Libs Generator
This is a simple Mad Libs HTML generator.

![example](http://i.imgur.com/BDeIxWi.png)

## Getting Started
/Applications/Utilities/![image](64px-Terminalicon2.png)
- To Use In [Terminal](https://en.wikipedia.org/wiki/Terminal_(macOS)),
copy each line verbatim AFTER THE DOLLAR SIGN, and paste and hit return:
  - $ cd ; git clone git@github.com:urbanspectra-nyc/Mad-Libs-Generator.git
  - $ cd Mad-Libs-Generator ; open .
  - Open the local index.html file in your browser.
  - Look in /examples/ dir for examples.

- To Contribute:
  - $ cd ; git clone git@github.com:urbanspectra-nyc/Mad-Libs-Generator.git ; open .
  - $ cd Mad-Libs-Generator
  - $ mkdir -p /examples/; cd $_
  - # Paste example ascii and html test files here.
  - $ cd .. ; git status ; git add . ; git commit -m 'Added some content.' ; git log # q to exit log
  - $ git push


### Generating Mad Libs
To use the mad libs generator, type your story into the leftmost text area. To insert a textarea, type the part of speech it should be surrounded by hard brackets, like so:

```
[adjective]
```

A preview will appear as you type on the right side of the screen, and you can copy and paste the source code from the middle.

Look at the sample .txt and ascii files for further guidance.