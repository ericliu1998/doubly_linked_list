Doubly-linked List
===

You should have received a detailed handout for this project.  Be sure
to read it, as well as all of the given code, before you begin working.

Repository Layout
---

The files `src/list.c` and `src/validate.c` will contain your
implementation.  They currently have only empty functions and usage
comments equivalent to the API description in the project handout.

The files in `tests` implement some unit-style trivial tests for your
code.  You should implement additional tests in this directory.

As usual, this README and the project Makefile are in the top-level
directory.  For this project you will probably want to modify the
Makefile (so that `make test` is maximally useful), and so it is
extensively commented for your understanding.

Testing
---

You are required to write one testing function in `src/validate.c`, but
_strongly encouraged_ to write other testing functions in test
executables in `tests/`.  Any `.c` file in `tests/` will be built into
an executable and run with `make test` if it is correctly added to the
`TESTS` variable in the Makefile.  See the comments in the Makefile for
instructions on how to accomplish this.

Submission
---

Per usual, `make submission` will create the file `submission.tar` to be
submitted to Autograder.
