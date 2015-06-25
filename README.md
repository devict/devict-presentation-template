# devICT Presentation Template

This repo is intended to serve as a quick starting point for putting together a
presentation. Presenters are welcome to use this template or roll their own
presentation.

This starter kit uses the [reveal.js presentation framework][reveal-repo].

## Setup
* Download this package. Either clone the repo or download and unpack the
  [zip](repo-zip).
 * If you clone the repo I would recommend that you remove the `.git` folder
   and init a new project as you will likely make a repo just for your
   presentation.
* cd to the "presentation" directory and start serving the presentation with
  `python -m SimpleHTTPServer`
* Browse to `http://localhost:8000`

## Folder structure

    .
    ├── app          # A sample application for your presentation if included
    └── presentation # The web root of the presentation
        ├── css      # Custom stylsheets
        ├── img      # Presentation images
        └── lib      # Third party libraries like reveal.js

# Setup Checklist

Whether you use this template or not, be sure to review the following items
before your presentation.

* All members of devICT (especially presenters) are bound by the [devICT Code
  of Conduct][code-of-conduct]. Be sure that your presentation abides by this
  code.
* We would like to stream your presentation to our remote members and record it
  for our archives. Our Preferred method is to use Google Hangouts On Air.
  Ensure you can start a Hangout On Air by going to
  https://plus.google.com/hangouts/onair and trying to initiate one. The first
  time you do this you will have to go through some steps to create and/or
  connect a YouTube account and agree to a license agreement.
* Ensure the device you will be using has a good microphone available. If you
  do not have a microphone one can be provided for you.
* Ensure you can connect your display to our projector using an HDMI cable
  (that we will provide).


[reveal-repo]: https://github.com/hakimel/reveal.js "reveal.js framework"
[repo-zip]: https://github.com/devict/devict-presentation-template/archive/master.zip "template zip"
[code-of-conduct]: http://devict.org/conduct "devICT Code of Conduct"
