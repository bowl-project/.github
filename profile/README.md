# The Bowl Project

This is the organization for the Bowl project - a concatenative programming language intended to be used as an operating system shell.

Because of its architecture, there are several relevant repositories to start with:
- The virtual machine is implemented in the repository named [bowl](https://github.com/bowl-project/bowl)
- The language kernel is implemented in the repository named [bowl-kernel](https://github.com/bowl-project/bowl-kernel)
- The internal API is contained in the repository named [bowl-api](https://github.com/bowl-project/bowl-api)

Beyond these, there are other fundamental repositories required for a rudimentary interface to the operating system:
- The repository [bowl-io](https://github.com/bowl-project/bowl-io) provides functions for file reading and writing
- The repository [bowl-system](https://github.com/bowl-project/bowl-system) provides functions that allow the creation of processes
