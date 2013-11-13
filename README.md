# UpFront Wichita Presentation Template

This repo is intended to serve as a quick starting point for putting together a
presentation. Presenters are welcome to use this template or roll their own
presentation.

## Setup
* Download this package. Either clone the repo or download and unpack the
  [zip](repo-zip).
 * If you clone the repo I would recommend that you remove the `.git` folder
   and init a new project as you will likely make a repo just for your
   presentation.
* cd to the "presentation" directory and start serving the presentation with
        python -m SimpleHTTPServer
* Browse to "http://localhost:8000"

## Folder structure

    .
    ├── app          # A sample application for your presentation if included
    └── presentation # The web root of the presentation
        ├── css      # Custom stylsheets
        ├── img      # Presentation images
        └── lib      # Third party libraries like reveal.js


[repo-zip]: https://github.com/upfrontwichita/upfront-presentation-template/archive/master.zip
