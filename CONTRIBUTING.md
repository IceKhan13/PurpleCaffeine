# Contributing

**We appreciate all kinds of help, so thank you!**

## Contributing to PurpleCaffeine

Specific details for contributing to this project are outlined below.

### Reporting Bugs and Requesting Features

Users are encouraged to use GitHub Issues for reporting issues and requesting features.

### Ask/Answer Questions and Discuss Quantum Prototype Template

Users are encouraged to use GitHub Discussions for engaging with researchers, developers, and other users regarding this project and the provided examples.

### Tox commands

In order to run any tox command, you need to declare in which part of the project you want to run `tox`.
To do so, set up a variable first :

```shell script
export FOLDER="client"
#export FOLDER="api_server"
```

### Project Code Style

Code in this repository should conform to PEP8 standards. Style/lint checks are run to validate this. Line length must be limited to no more than 88 characters.

### Pull Request Checklist

When submitting a pull request and you feel it is ready for review,
please ensure that:

1. The code follows the _code style_ of this project and successfully
   passes the _unit tests_. This project uses [Pylint](https://www.pylint.org) and
   [PEP8](https://www.python.org/dev/peps/pep-0008) style guidelines.

   You can run
   ```shell script
   tox -elint
   ```
   from the root of the repository clone for lint conformance checks.

### Tox commands available

- Run for style checks <code> tox -elint </code>
- Run for tests <code> tox -epy39 </code>
- Run coverage <code> tox -ecoverage </code>
- Run black <code> tox -eblack </code>
- To Fix the black violation <code> black <PATH_FILE_YOU_WANT_TO_FIX> </code>
