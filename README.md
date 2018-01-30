# Algorithms 
Idea of this repository is to document my progress in learning algorithms usin
 [this](http://www.algorist.com/) book.

## Building
To build project, create and enter build directory and run command 
 `cmake .. -GNinja` (I use [Ninja](https://ninja-build.org/) build tool). 
 After that, `ninja` command run in the same directory will compile all changed 
 files.

## Testing
Tests are written using [Criterion](https://github.com/Snaipe/Criterion)
 framework. To run them, simply execute `ctest` command in build directory.
