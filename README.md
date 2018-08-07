# UCSB Gradescope Tools

This webpage documents the repos that are available in the github.com organization <https://github.com/ucsb-gradescope-tools>

These repos are also backed up at <https://github.ucsb.edu/ucsb-gradescope-tools>

# Overview

We support several approaches to autograding with gradescope:


| Language | Method | Example (on github.com) | Example (on github.ucsb.edu) |
|----------|--------|---------|------|
| Python   | `unittest` |  [sample-python-unittest-autograder](https://github.com/ucsb-gradescope-tools/sample-python-unittest-autograder) |  [sample-python-unittest-autograder](https://github.ucsb.edu/ucsb-gradescope-tools/sample-python-unittest-autograder) | 
| C++      | `tddFuncs.h` |   [sample-cpp-tddFuncs-autograder](https://github.com/ucsb-gradescope-tools/sample-cpp-tddFuncs-autograder)  |   [sample-cpp-tddFuncs-autograder](https://github.ucsb.edu/ucsb-gradescope-tools/sample-cpp-tddFuncs-autograder) |  
| Python   | diff (Python script)|  [sample-python-pydiff-autograder](https://github.com/ucsb-gradescope-tools/sample-python-pydiff-autograder) |   [sample-python-pydiff-autograder](https://github.ucsb.edu/ucsb-gradescope-tools/sample-python-pydiff-autograder) | 
| C++      | diff (Python script) |  [sample-cpp-pydiff-autograder](https://github.com/ucsb-gradescope-tools/sample-cpp-pydiff-autograder) |  [sample-cpp-pydiff-autograder](https://github.ucsb.edu/ucsb-gradescope-tools/sample-cpp-pydiff-autograder) | 
| Python   | diff based (bash script) |   [sample-python-diff-autograder](https://github.com/ucsb-gradescope-tools/sample-python-diff-autograder) |   [sample-python-diff-autograder](https://github.ucsb.edu/ucsb-gradescope-tools/sample-python-diff-autograder) | 
| C++      | diff based (bash script)|  [sample-cpp-diff-autograder](https://github.com/ucsb-gradescope-tools/sample-cpp-diff-autograder) |  [sample-cpp-diff-autograder](https://github.ucsb.edu/ucsb-gradescope-tools/sample-cpp-diff-autograder) | 
| C++      | diff based (bash script)|  [sample-cpp-seeded-diff-autograder (WORK IN PROGRESS)](https://github.com/ucsb-gradescope-tools/sample-cpp-seeded-diff-autograder) |  TBD | 
| Java |  | [sample-java-junit-ant-autograder](https://github.com/ucsb-gradescope-tools/sample-java-junit-ant-autograder| | 

We also support a way of linking a Gradescope autograder.zip file to a Github repo, via the [link-gs-zip-with-repo](https://github.com/ucsb-gradescope-tools/link-gs-zip-with-repo) tool.

The `link-gs-zip-with-repo` tools is backed up at <https://github.ucsb.edu/ucsb-gradescope-tools/link-gs-zip-with-repo>.

Notes:
* `tddFuncs.h` is a  unit testing library for C++ developed locally at UCSB by Phill Conrad, and used in several assignments in CMPSC 16,24 and 32.
