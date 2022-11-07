## Building A CI/CD in C++ ##

For unit tests we will be using `CppUnit` which will run via GitHub actions everytime a pull request is opened.

For linting we will use `clang-format` which formats code according to a coding style used by Google, Mozilla and other large organizations.

For compiling (building) the code, we shall use `GCC` which will allow us to turn our code into an executable which we can then run on systems.

Due to the size of this project we will be setting up a cloud-based CI/CD as it won't require any complicated setup outside of GitHub actions.

If the project grows too big then it might be a good idea to change the CI/CD to something that allows more configuration such as `Jenkins`, `Travis CI`, or `TeamCity`