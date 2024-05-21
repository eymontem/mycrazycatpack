# tutorial2024

[![PyPI](https://img.shields.io/pypi/v/tutorial2024.svg)][pypi status]
[![Status](https://img.shields.io/pypi/status/tutorial2024.svg)][pypi status]
[![Python Version](https://img.shields.io/pypi/pyversions/tutorial2024)][pypi status]
[![License](https://img.shields.io/pypi/l/tutorial2024)][license]

[![Read the documentation at https://tutorial2024.readthedocs.io/](https://img.shields.io/readthedocs/tutorial2024/latest.svg?label=Read%20the%20Docs)][read the docs]
[![Tests](https://github.com/eymontem/tutorial2024/actions/workflows/python-test.yml/badge.svg)][tests]
[![Codecov](https://codecov.io/gh/eymontem/tutorial2024/branch/main/graph/badge.svg)][codecov]

[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)][pre-commit]
[![Black](https://img.shields.io/badge/code%20style-black-000000.svg)][black]

[pypi status]: https://pypi.org/project/tutorial2024/
[read the docs]: https://tutorial2024.readthedocs.io/
[tests]: https://github.com/eymontem/tutorial2024/actions?workflow=Tests
[codecov]: https://app.codecov.io/gh/eymontem/tutorial2024
[pre-commit]: https://github.com/pre-commit/pre-commit
[black]: https://github.com/psf/black

## Installation

You can install _tutorialpack_ via [pip] from [PyPI]:

```console
$ pip install tutorialpack
```

## Contributing

Contributions are very welcome.
To learn more, see the [Contributor Guide][Contributor Guide].

## License

Distributed under the terms of the [MIT license][License],
_tutorialpack_ is free and open source software.

## Issues

If you encounter any problems,
please [file an issue][Issue Tracker] along with a detailed description.


<!-- github-only -->

[command-line reference]: https://tutorial2024.readthedocs.io/en/latest/usage.html
[License]: https://github.com/eymontem/tutorial2024/blob/main/LICENSE
[Contributor Guide]: https://github.com/eymontem/tutorial2024/blob/main/CONTRIBUTING.md
[Issue Tracker]: https://github.com/eymontem/tutorial2024/issues


## Building the Documentation

You can build the documentation locally by installing the documentation Conda environment:

```bash
conda env create -f docs/environment.yml
```

activating the environment

```bash
conda activate sphinx_tutorial2024
```

and [running the build command](https://www.sphinx-doc.org/en/master/man/sphinx-build.html#sphinx-build):

```bash
sphinx-build docs _build/html --builder=singlehtml --jobs=auto --write-all; open _build/html/index.html
```