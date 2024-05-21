# dds-spring-school-2024-demo

[![PyPI](https://img.shields.io/pypi/v/dds-spring-school-2024-demo.svg)][pypi status]
[![Status](https://img.shields.io/pypi/status/dds-spring-school-2024-demo.svg)][pypi status]
[![Python Version](https://img.shields.io/pypi/pyversions/dds-spring-school-2024-demo)][pypi status]
[![License](https://img.shields.io/pypi/l/dds-spring-school-2024-demo)][license]

[![Read the documentation at https://dds-spring-school-2024-demo.readthedocs.io/](https://img.shields.io/readthedocs/dds-spring-school-2024-demo/latest.svg?label=Read%20the%20Docs)][read the docs]
[![Tests](https://github.com/Depart-de-Sentier/dds-spring-school-2024-demo/actions/workflows/python-test.yml/badge.svg)][tests]
[![Codecov](https://codecov.io/gh/Depart-de-Sentier/dds-spring-school-2024-demo/branch/main/graph/badge.svg)][codecov]

[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)][pre-commit]
[![Black](https://img.shields.io/badge/code%20style-black-000000.svg)][black]

[pypi status]: https://pypi.org/project/dds-spring-school-2024-demo/
[read the docs]: https://dds-spring-school-2024-demo.readthedocs.io/
[tests]: https://github.com/Depart-de-Sentier/dds-spring-school-2024-demo/actions?workflow=Tests
[codecov]: https://app.codecov.io/gh/Depart-de-Sentier/dds-spring-school-2024-demo
[pre-commit]: https://github.com/pre-commit/pre-commit
[black]: https://github.com/psf/black

## Installation

You can install _dds_spring_school_2024_demo_ via [pip] from [PyPI]:

```console
$ pip install dds_spring_school_2024_demo
```

## Contributing

Contributions are very welcome.
To learn more, see the [Contributor Guide][Contributor Guide].

## License

Distributed under the terms of the [MIT license][License],
_dds_spring_school_2024_demo_ is free and open source software.

## Issues

If you encounter any problems,
please [file an issue][Issue Tracker] along with a detailed description.


<!-- github-only -->

[command-line reference]: https://dds-spring-school-2024-demo.readthedocs.io/en/latest/usage.html
[License]: https://github.com/Depart-de-Sentier/dds-spring-school-2024-demo/blob/main/LICENSE
[Contributor Guide]: https://github.com/Depart-de-Sentier/dds-spring-school-2024-demo/blob/main/CONTRIBUTING.md
[Issue Tracker]: https://github.com/Depart-de-Sentier/dds-spring-school-2024-demo/issues


## Building the Documentation

You can build the documentation locally by installing the documentation Conda environment:

```bash
conda env create -f docs/environment.yml
```

activating the environment

```bash
conda activate sphinx_dds-spring-school-2024-demo
```

and [running the build command](https://www.sphinx-doc.org/en/master/man/sphinx-build.html#sphinx-build):

```bash
sphinx-build docs _build/html --builder=html --jobs=auto --write-all; open _build/html/index.html
```