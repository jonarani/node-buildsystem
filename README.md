# Thinnect build system

GNU Make based build system for embedded projects.

## Installation and usage

```
$ git submodule add git@bitbucket.org:thinnect/buildsystem.git thinnect.buildsystem
$ cp thinnect.buildsystem/make/Makefile.sample Makefile
```

Edit Makefile and
* Add your own sources (.c files) to variable SOURCES
* Add your own include directories to variable INCLUDES
* Add your header file locations to variable ALL_HEADERS_EVER
* Set your version in VERSION_xxx variables
* Set your application UUID in variable UUID_APPLICATION
* Update make targets to make sense for your application

Try to make your target. Fix errors or complain to author.
