## Docs Home

- Proposed Documentation Tree
  - [/docs/README.md](docs/) => All support+training+design docs: [ tech edu i18n ]
    - [/docs/edu-docs/README.md](docs/edu-docs/) => Support docs for Educational Github Project Contributors
      - [Edu Assessment Design](docs/edu-docs/assessment-design/)
      - [Edu Instructional Design](docs/edu-docs/instructional-design/)
      - [Edu Curriculum Design](docs/edu-docs/curriculum-design/)
      - [Edu Faculty Onboarding](docs/edu-docs/faculty-onboarding/)
      - [Educational Project Manager Onboarding](docs/edu-docs/educational-project-manager-onboarding/)
    - [/docs/i18n-docs/README.md](docs/i18n-docs/) => Support docs for Technical Github Project Translators
      - [/docs/i18n-docs/us-english/](docs/i18n-docs/us-english/)
      - [/docs/i18n-docs/uk-english/](docs/i18n-docs/uk-english/)
      - [/docs/i18n-docs/dutch/](docs/i18n-docs/dutch/)
      - [/docs/i18n-docs/castillian-spanish/](docs/i18n-docs/castillian-spanish/)
      - [/docs/i18n-docs/mexican-spanish/](docs/i18n-docs/mexican-spanish/)
      - [/docs/i18n-docs/hebrew/](docs/i18n-docs/hebrew/)
      - [/docs/i18n-docs/japanese/](docs/i18n-docs/japanese/)
      - [/docs/i18n-docs/chinese/](docs/i18n-docs/japanese/)
      - [/docs/i18n-docs/thai/](docs/i18n-docs/thai/)
      - [/docs/i18n-docs/india/](docs/i18n-docs/india/)
      - [/docs/i18n-docs/fallback-locales/](docs/i18n-docs/fallback-locales/)
    - [/docs/tech-docs/README.md](docs/tech-docs/) => Support docs for Technical Github Project Contributors
      - [Technical Git Ops Training](docs/tech-docs/git-ops-training/)
      - [Technical Project Planning](docs/tech-docs/project-management/)
      - [Technical Project Management](docs/tech-docs/project-planning/)
      - [Technical Project Execution](docs/tech-docs/]/project-execution/)
      - [Technical Project Tracking](docs/tech-docs/]/project-tracking/)
      - [Technical Project Reporting](docs/tech-docs/project-reporting/)


### Docs Enhancements
- [x] Site map tree under docs/ proposed.
- [x] [Venn diagram](https://drive.google.com/file/d/1mmJeqvg1rx78H5ckg01997OjNhADhAG9/view?usp=sharing) regarding criteria of primary target language selection created.
- [ ] Walk Paige thru the github docs video.
- [ ] Walk Paige thru osx setup for linuxification.
- [ ] Complete git ops docs for three contributors.
- [ ] Use gists for rapid ghmd editing.
- [ ] Clean up multilingual mad libs repo content example.
- [ ] Make maximum use of icons and diagrams in that example.
- [ ] Translate repo content example to primary target languages.
- [ ] List target words below.  Use hint rather than part of speech?
- [ ] Open Source Licensing
- [ ] Use mini vocab sets.
- [ ] [Pick some git ops vocabulary?](https://docs.github.com/en/get-started/quickstart/github-glossary)
- [ ] [Pick some heroku vocabulary?](https://devcenter.heroku.com/articles/glossary-of-heroku-terminology)
- [ ] Commit to several languages.
- [ ] Top down design
- [ ] Bottom up design
- [ ] Test-driven design
- [ ] ZenHub


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

