## Git Ops Tech Docs

- The following tech docs are in this folder:
  - 1. [The Story of Git](story-of-git.md)
  - 2. [Choose Architecture to Run Git](choose-architecture-to-run-git.md)
  - 3. [Git Solo Local](git-solo-local.md)
  - 4. [Git Solo Remote](git-solo-remote.md)
  - 5. [Team Git Ops](team-git-ops.md)
  - 6. [Team Dev Dojo](team-dev-dojo.md)

- [Return to Repo Root](../..)
  -  [Return to Doc Root](..)


## Jumpstart For Github Project Contributors

- This documentation is provided to support git ops training.

#### Table of Contents
- [The Story of Git](#the-story-of-git)
- [Installation + Configuration](#installation-+-configuration)
- [Solo Local Git](#solo-local-git)
- [Solo Remote Git](#solo-remote-git)
- [Team Git Ops](#team-git-ops)
- [Git Ops Certifications](#git-ops-certifications)
- [Team Dev Dojos](#team-dev-dojos)
- [Git Ops Vocabulary]()
- [References]()
- [Enhancements]()

#### The Story of Git

The [story of git](docs/tech-docs/) gives us historical context for these tools and skills.

#### Installation + Configuration

- Architectural Choices
  - Run latest version of free desktop app, such as GithubDesktop or SourceTree.
  - Run git on the command line.
    - Running via Shell on Linux (Ubuntu20Server).
    - Running via Terminal App on OSX.

- Several overlapping learning efforts 

We are here to learn 

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

