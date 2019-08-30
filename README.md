# Learn Ruby

This is a fork of http://testfirst.org/

## Setup

1. Install Ruby on your Laptop:

- [rvm and ruby on mac](http://curriculum.railsbridge.org/installfest/osx_rvm)
- [rvm and ruby on linux](http://curriculum.railsbridge.org/installfest/linux)
- [railsinstaller on windows](http://curriculum.railsbridge.org/installfest/windows)
- you are done when you have ruby, gem and bundler on your
  commandline

2. clone this repository

3. now you are ready!

## Exercise

The goal of this execise is to learn about the main featuers of
Ruby. There are tests given, you fulfill the tests by writing
very short programs.

Beware: the problems get expontentially harder!

### How to run and fulfill the tests

- on the commandline: go into the subfolder, there you will find a \*\_spec.rb file
  containing the test. sometimes there are hints in this file.
- run `rake` → you will get an error
  saying that a file (for example `hello.rb`) is missing
- create the missing file, run `rake` again → you will get an
  error saying that a specific function (for example `hello`) does not return an expected value
- in file hello.rb write an implementation for the function, run `rake` again
- now and again run `rubocop` to see recommendations on coding conventions, or `rubocop -a` to automatically apply them to your code
- once you are satisfied with your solution: commit to branch a1
- in file NOTES.md write up what you learned about ruby. compare ruby to other languages you know, put references to documentation or stackoverflow articles here. (If you keep your own programming labbook, just do it there)  

repeat for the other tests and other folders.

when you are finished you should have a lot of running tests,
a basic understanding and a lot of notes on Ruby.

