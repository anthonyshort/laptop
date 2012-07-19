Laptop
======

Laptop is a script to set up your Max OS X laptop as a web development machine.

Requirements
------------

* A C compiler, such as GCC, LLVM, or Clang.

Download a compiler from [OS X GCC Installer](https://github.com/kennethreitz/osx-gcc-installer/) if you're on Snow Leopard (OS X 10.6) or [Command Line Tools for XCode](https://developer.apple.com/downloads/index.action) if you're on Lion (OS X 10.7).


Install
-------

Run the script:

    curl -s https://raw.github.com/anthonyshort/laptop/master/mac | sh

What it sets up
---------------

* SSH public key (for authenticating with services like Github and Heroku)
* Homebrew (for managing operating system libraries)
* Git
* PhantomJS (For headless JavaScript testing)
* Ack (for finding things in files)
* ImageMagick (for cropping and resizing images)
* RVM (for managing versions of the Ruby programming language)
* Ruby language (for writing general-purpose code)
* Bunch of commonly used gems (Sass, Compass, Stitch etc...)
* Node (The awesome Javascript runtime)
* NPM (Node package manager)
* Coffeescript
* Bunch of commonly-used node packages

It should take about 30 minutes for everything to install, depending on your machine.
