This generates the [github pages](http://pages.github.com/) site for
[doctorjane.github.com](http://doctorjane.github.com/).


## PROJECT LAYOUT ##

This [middleman](http://middlemanapp.com/) project,
build_doctorjane.github.com, contains the source files that get
transformed into the final html, images, etc and committed in the
other project, doctorjane.github.com. The config.rb file assumes the
following directory structure:

    ~/workspace/build_doctorjane.github.com
    ~/workspace/doctorjane.github.com
    

## BUILD UPDATED SITE ##

    build_doctorjane.github.com> middleman build --verbose --clean

You can view the newly built site by moving there

    build_doctorjane.github.com> cd ~/workspace/doctorjane.github.com
    
and running "adsf"

    doctorjane.github.com> adsf
     
Then visit http://localhost:3000 in your browser.
     
## DEPLOY UPDATED SITE ##
     
Move to ~/workspace/build_doctorjane.github.com, commit and push.

