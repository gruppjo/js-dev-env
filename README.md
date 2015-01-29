# js-dev-env
A convenient and opinionated help for setting up your javascript development environment

## System Tools
### Mac
- homebrew - the missing package manager for OS X - http://brew.sh/
- dotfile repositories
  - by mathiasbynens - https://github.com/mathiasbynens/dotfiles
  - other popular dotfile repositories - https://dotfiles.github.io/
  - some insight on what they do - http://code.tutsplus.com/tutorials/setting-up-a-mac-dev-machine-from-zero-to-hero-with-dotfiles--net-35449

## Tools
- git
- node (comes with mathiasbynens dotfiles setup) - http://nodejs.org/download/
  - yeoman - scaffolding - http://yeoman.io/
    - one of many great generators - http://yeoman.io/generators/
    - for instance generator-m - https://github.com/mwaylabs/generator-m
    - dont' forget to install their dependencies too!
  - bower - package manager for the web - http://bower.io/
  - task runner (depending on the generators you want to use)
    - gulp - http://gulpjs.com/
    - grunt - http://gruntjs.com/
  - jscs - https://github.com/jscs-dev/node-jscs
  - jshint - https://github.com/jshint/jshint

## Sublime
- sublime (newest version, right now it's 3) - http://www.sublimetext.com/3
- sublime package control - https://packagecontrol.io/installation
  - SublimeLinter3 - https://github.com/SublimeLinter/SublimeLinter3
  - SublimeLinter-jscs - https://github.com/SublimeLinter/SublimeLinter-jscs/
  - SublimeLinter-jshint - https://github.com/SublimeLinter/SublimeLinter-jshint
  - SublimeLinter-annotations - https://github.com/SublimeLinter/SublimeLinter-annotations
  - DocBlockr - https://github.com/spadgos/sublime-jsdocs
- sublime setting files
  - sublime `Preferences.sublime-settings`
    - open in sublime: `Preferences -> Settings - User`
    - add contents from `sublime-preferences/Preferences.sublime-settings` see [in this repo](https://github.com/gruppjo/js-dev-env/blob/master/sublime-preferences/Preferences.sublime-settings)
  - SublimeLinter3 `SublimeLinter.sublime-settings`
    - open in sublime: `Preferences -> Package Settings -> SublimeLinter -> Settings - User`
    - add contents from `sublime-preferences/SublimeLinter.sublime-settings` see [in this repo](https://github.com/gruppjo/js-dev-env/blob/master/sublime-preferences/SublimeLinter.sublime-settings)
- project files (if not provided by the generators you use for your projects)
    - add to root directory of every project
      - `.jscsrc` see [in this repo](https://github.com/gruppjo/js-dev-env/blob/master/project-files/.jscsrc)
      - `.jshintrc` see [in this repo](https://github.com/gruppjo/js-dev-env/blob/master/project-files/.jshintrc)