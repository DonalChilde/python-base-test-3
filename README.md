# Python Base Test 3

<!-- badges-begin -->
[![PyPI](https://img.shields.io/pypi/v/python-base-test-3.svg)][pypi status]
[![Status](https://img.shields.io/pypi/status/python-base-test-3.svg)][pypi status]
[![Python Version](https://img.shields.io/pypi/pyversions/python-base-test-3)][pypi status]
[![License](https://img.shields.io/pypi/l/python-base-test-3)][license]

[![Read the documentation at https://python-base-test-3.readthedocs.io/](https://img.shields.io/readthedocs/python-base-test-3/latest.svg?label=Read%20the%20Docs)][read the docs]
[![Tests](https://github.com/DonalChilde/python-base-test-3/workflows/Tests/badge.svg)][tests]
[![Codecov](https://codecov.io/gh/DonalChilde/python-base-test-3/branch/main/graph/badge.svg)][codecov]

[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)][pre-commit]
[![Black](https://img.shields.io/badge/code%20style-black-000000.svg)][black]

[pypi status]: https://pypi.org/project/python-base-test-3/
[read the docs]: https://python-base-test-3.readthedocs.io/
[tests]: https://github.com/DonalChilde/python-base-test-3/actions?workflow=Tests
[codecov]: https://app.codecov.io/gh/DonalChilde/python-base-test-3
[pre-commit]: https://github.com/pre-commit/pre-commit
[black]: https://github.com/psf/black

<!-- badges-end -->

## Features

- TODO

## Requirements

- TODO

## Quickstart

You can install _Python Base Test 3_ via [pip] from [PyPI]:

```console
pip install python-base-test-3
```

## Usage

Please see the [documentation] for details.

## Contributing

Contributions are very welcome.
To learn more, see the [Contributor Guide].


## Usage

Please see the [Command-line Reference] for details.

## Contributing

Contributions are very welcome.
To learn more, see the [Contributor Guide].

## License

Distributed under the terms of the [MIT license][license],
_Python Base Test 3_ is free and open source software.

## Issues

If you encounter any problems,
please [file an issue] along with a detailed description.

## Developer Setup

<!-- dev -->
### Individual commands

```bash
# From the project directory - 
python3 -m virtualenv ./.venv
source ./.venv/bin/activate
pip3 install -U pip, wheel
pip3 install -e .[dev,lint,doc,vscode,testing]
git init
git add .
git commit -m "initial commit"
git tag -a v0.0.0 -m "initial commit tag"
git remote add origin https://github.com/DonalChilde/python-base-test-3.git
git push -u origin master
git push origin v0.0.0
```

### Convenient one liners

```bash
python3 -m virtualenv ./.venv && source ./.venv/bin/activate && export PIP_REQUIRE_VIRTUALENV=true && pip3 install -U pip && pip3 install -e .[dev,lint,doc,vscode,testing]
```

```bash
git init && git add . && git commit -m "initial commit" && git tag -a v0.0.0 -m "initial commit tag"
```

```bash
git remote add origin https://github.com/DonalChilde/python-base-test-3.git && git push -u origin master && git push origin v0.0.0
```
<!-- end-dev -->
## Credits

This project was generated from [DonalChilde]'s [cookiecutter-python-base] template, which was inspired by [@cjolowicz]'s [Hypermodern Python Cookiecutter] template.

[@cjolowicz]: https://github.com/cjolowicz
[DonalChilde]: https://github.com/DonalChilde
[pypi]: https://pypi.org/
[hypermodern python cookiecutter]: https://github.com/cjolowicz/cookiecutter-hypermodern-python
[cookiecutter-python-base]: https://github.com/DonalChilde/cookiecutter-python-base
[file an issue]: https://github.com/DonalChilde/python-base-test-3/issues
[pip]: https://pip.pypa.io/

<!-- github-only -->

[license]: https://github.com/DonalChilde/python-base-test-3/blob/main/LICENSE
[contributor guide]: https://github.com/DonalChilde/python-base-test-3/blob/main/CONTRIBUTING
[documentation]: https://python-base-test-3.readthedocs.io/en/latest/
