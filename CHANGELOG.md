# Changelog

Key:

* `*` means modification
* `+` means addition
* `-` means deletion

## v2.11.3

```diff
+ Add avocado emoji divider
```

## v2.11.2

```diff
* Improved documentation a lot more
+ Exposed the "blacklisted" dividers list
+ Added maintainer field to setup.py
+ Added Python version constraints to setup.py to prevent unsupported Python version installs
```

## v2.11.1

```diff
+ Added API Refrence documentation page
+ Updated tests to work with new Python version
* Changed copyright header
+ Updated Sphinx version
```

## v2.11.0

```diff
+ Added 14 new dividers
```

## v2.10.0

```diff
+ Added 9 new dividers
+ Made area4.utils.get_raw_file() cache the file contents
* Fixed certain dividers confusing GitHub
+ Added more splitter tests
+ Added test for area4.utils.markdown_horizontal() function
+ Added partially working duplicate divider checking
  (disabled due to failures that would be breaking changes)
```

## v2.9.0

```diff
+ Added markdown horizontal divider
- Removed rdillib dependency
* Updated docs
```

## v2.8.0

```diff
* Updated documentation
* Updated CI to use slim images
- Removed SafetyCI checks, description validation, and old Markdown check
* Updated EditorConfig
- Removed area4.util_module and area4.theArray aliases
* Renamed area4.author to area4.__author__
+ Added 'text' keyword
- Removed pipenv dependency
```

## v2.7.0

```diff
- Removed util.check function
* Fixed dead links
+ Added integer check
```

## v2.6.0

```diff
+ Added test for area4.area4info
* Refactor and fix area4.area4info (formatting issue and wrong data fixed)
```

## v2.5.9

```diff
- Don't include changelogs in builds
```

## v2.5.8

```diff
* Updated documentation
```

## v2.5.7:

```diff
* Shortened author value
```

## v2.5.6

```diff
- Remove stepped down maintainers
```

## v2.5.5

```diff
+ Improved docs
```

## v2.5.4

```diff
* Built with newer version of setuptools
```

## v2.5.3

```diff
+ Added our first ever runtime dependency - RDILLib (for dynamic emails)
- Removed pycodestyle config from setup.cfg
```

## v2.5.2

```diff
- Removed all dist-info related code
* Updated docs
```

## v2.5.1:

```diff
* Changed Reddit divider function name to match style guide
* Updated tests
```

Version 2.5.0:
• Shoutout to N8python for helping get this release out!
* Made divider function strip newlines from output
* Made all dividers 12 characters (except for a select few)

Version 2.4.0:
+ Added new divider

Version 2.3.9:
* Updated copyright years in documentation
* Updated Makefile

Version 2.3.8:
- Removed clone tool as it had no use
* Updated extras

Version 2.3.7:
- virtualenv is no longer required

Version 2.3.6:
* Updated Sphinx
* Updated contributing guidelines

Version 2.3.5:
* Packaged with newer version of setuptools

Version 2.3.4:
+ Added more unit tests
* Updated package info function

Version 2.3.3:
* Built on newer version of setuptools

Version 2.3.2:
* Moved tests to unittest module
* Fixed bug

Version 2.3.1:
+ Added reddit horizontal divider to utilities module

Version 2.3.0:
- Removed class based system

Version 2.2.0:
* Code cleanup

Version 2.1.9:
* Fixed a compatibility issue
* Fixed CI caching
* Updated CodeOwners
* Updated virtualenv and pyflakes

Version 2.1.8:
- Removed BrewMake tool due to lack of use
+ Blacklisted certain dividers from the get_divider_character utility function

Version 2.1.7:
+ Added get_divider_character utility function

Version 2.1.6:
+ Added releasing guidelines for maintainers
+ Added tests for utility module
+ Added markdown spellchecking

Version 2.1.5:
* Made tests way faster
+ Added documentation tests
* Cleaned up documentation
+ Added documentation requirements

Version 2.1.4:
+ Added BrewMake tool
* Fixed broken links
* Updated contributing guidelines

Version 2.1.2 AND 2.1.3:
* Moved library to area4lib organization!!

Version 2.1.1:
* Fixed an issue in the code with the splitter function

Version 2.1.0:
+ Added eye emoji dividers
+ Added splitter function (finally!)
* Moved reduce_to_unit function to utility module

Version 2.0.9:
+ Added CI auto-deploying
* Updated GitIgnore
+ Added release schedule

Version 2.0.8:
+ Added clone tool
* Fixed linting issues
* Updated badges
* Migrated CI tests to macOS

Version 2.0.7:
* Fixed linting issues
* Moved the utilities module to the main package
* Moved linting tests to Cirrus CI
* Made package info function work on all Python3 versions

Version 2.0.4 AND 2.0.5 AND 2.0.6:
* Fixed Python 3.4 and 3.5 compatibility issues
* Lots of code cleanup
* Moved tests onto GNU make
+ Added semicolon dividers
* Updated EditorConfig

Version 2.0.3:
* Updated flake8 to the latest version
* Updated documentation config
+ Added suggested extensions in VSCode
- Deactivated wikis

Version 2.0.2:
* Updated package build tools
* Updated EditorConfig
* Updated GitIgnore
* Updated support information
* Updated issue templates
* Updated Probot config
* VSCode now suggests you install markdown lint
* Updated contributing guidelines
* Updated twine to latest version

Version 2.0.1:
+ Added new 6 dividers
* Cleaned up docs
- Removed egg building tool
* Updated CodeOwners
* Made code follow PyDocStyle
* Removed Travis CI, moved on to Cirrus CI
* Updated GitIgnore
* Updated MarkdownLint rules
* Added dependency bumping bot

Version 2.0.0:
* Completely changed the divider addition system
* Removed most of the GitHub apps, added new ones
* Redid docs
+ Gave the util module its own package so the import system isn't really odd
* Made the main module class based ( /!\ VERY BREAKING CHANGES ALERT /!\ )
* Made sure the wheel is not built universally
* Added actual code testing with Travis CI
+ Added build tools
- Removed VCS lists
* Updated the contributing guidelines
+ Added markdown linting

Version 1.3.0:
* Fixed issues with package info function
* Moved check function to util module
* Documented check function
* Updated Stale bot config
* Reformatted changelog
+ Added some VCS stuff

Version 1.2.9:
* EditorConfig file now included in sdists
* Updated author Email

Version 1.2.8:
* Re-did all the docs
+ Added link check task for markdown files
* Made almost all code fit PEP8

Version 1.2.7:
+ Added potato dividers
+ Added shrimp dividers
+ Added an EditorConfig
+ Added Other OS classifier
* Updated all ReadTheDocs links to go to the stable version

Version 1.2.6:
- Dropped Python2 support fully
+ Added project-wide settings for sublime text

Version 1.2.5:
+ Added dice divider
+ Added bowling ball and pins divider
+ Added cookie dividers!
+ Added snowman dividers

Version 1.2.4:
+ Re-activated GitHub pages for the readme
* Cleaned up some code
* Updated issue templates
* Updated the git ignore
+ Added workspace settings for VSCode
* Now forcing CIs to use older pip version
+ Added🕴dividers
+ Added PyPy3.5 support classifiers
* Made some changes to the docs

Version 1.2.3:
+ Added pin emoji dividers
* Fixed some stuff in the docs
+ Added another PR check

Version 1.2.2:
* Big bug fix

Version 1.2.1 (lots of random stuff):
* Now distributing .tar.gz and.zip formats for source code
* Did some small manifest changes
* Fixed some stuff with CIs
* Updated issue templates
+ Added new badge to README file
* Updated stale tags
+ Added new tag
* Fixed some compatibility issues
* Made the git ignore longer

Version 1.1.9:
+ Added keywords to package

Version 1.1.8:
+ Added lots more emojis
+ Added issue templates
+ Added check to see if the libraries latest version installs without error
+ Added PyCharm IDE files
* Fixed some things with the docs

Version 1.1.7:
+ Added some emoji dividers
* Fixed bug with manifest.in and setup.py (PR #42)
* Manifest now includes the CodeAuthors file

Version 1.1.6:
+ Added alphabet dividers

Version 1.1.5:
+ Added MANIFEST.in
+ Added config for new apps
+ New divider (`s)

Version 1.1.4:
* Code cleanup
+ Added random number dividers
* Updated contributing guidelines
+ Added Cirrus CI along with Travis CI

Version 1.1.3:
+ Added a lot of dividers (https://github.com/area4lib/area4/pull/27/files)
- Removed un-used import to speed up code a tiny bit

Version 1.1.2:
+ Added shrug emoji dividers
* The make_div function received an upgrade
* Fixed a few typos in the docs

Version 1.1.1:
+ Added contributing guidelines
+ Added lenny dividers
+ Added cthulhu dividers
+ Added backslash dividers
+ Added make_div framework (see docs, thanks @ninexball!)
* Configured Discord webhook (not important)
+ Added coffee cup dividers
+ Added and-sign dividers
+ Added up arrow dividers

Version 1.1.0 (Contains Breaking Changes):
+ Added tilde (~) dividers
+ Added broken bar dividers
+ Added slash dividers
* Functions now return the variable rather then print it
+ Added repo status badge

Version 1.0.7:
+ Added star / asterisk (*) dividers
+ Added comma (,) dividers

Version 1.0.6:
- Disabled GitHub pages (not needed)
+ Added docs!
+ Added hashtag (#) dividers
* Updated badges in readme

Version 1.0.5:
+ Added equal sign dividers
+ Added GitHub pages config (site down now)
+ Added more project links to setup.py file

Version 1.0.4:
+ Added up arrow emoji dividers
+ Added down arrow emoji dividers
+ Added CodeFactor badge to the readme file
+ Added new classifiers to setup.py file

Version 1.0.3:
+ Added Travis CI (and .travis.yml file)
+ Added custom dividers!!

Version 1.0.2:
* Updated project description
+ Added example section to readme
+ Added divider looks section to readme
* Updated the info command because of an annoying text issue

Version 1.0.1:
* Readme fixes & badges
+ Added changelog

Version 1.0.0:
* First release!