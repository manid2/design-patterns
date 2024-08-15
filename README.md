Design Patterns in C++
======================

Example implementations of design patterns in C++ to help prepare for
interviews and use it software development tasks.

Build & test
------------

This repository uses Gnu Makefile to build & test, format source code.

```bash
make Singleton        # build a test binary from .cpp source file
make Singleton-check  # run the test binary
make Singleton-format # format .cpp source file

SHOW_TEST_OUTPUT=1 make Singleton-check # run test with debug output
```

Test output format
------------------

```text
$ make <DP-name>-check  # run the test binary
Test <DP-name> Design Pattern with N tests.
```

Credits
-------

* [pezy/DesignPatterns] (https://github.com/pezy/DesignPatterns)
