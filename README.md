<a id="readme-top"></a>
<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Last Commit][last-commit-shield]][last-commit-url]
<!-- [![Coverage][coverage-badge]][coverage-url] -->
<!-- ![Interrogate][interrogate-shield] -->
[![Contributors][contributors-shield]][contributors-url]
[![Unlicense License][license-shield]][license-url]
![Size][repo-size-shield]

<br />
<div align="center">
  <a href="https://github.com/HyPerNT/CookieCutterPython">
    <!-- <img src="https://upload.wikimedia.org/wikipedia/commons/c/c5/Wordle_Logo.svg" alt="Logo" width="80" height="80"> -->
  </a>

  <h3 align="center">Cookie Cutter Python</h3>

  <p align="center">
    A small repo meant to be copypastad for new Python projects.
    <br />
    <a href="https://hypernt.github.io/CookieCutterPython/"><strong>Explore the docs »</strong></a>
    <br />
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#running-tests">Running Tests</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

<!-- [![Product Name Screen Shot][product-screenshot]](https://example.com) -->

Simply clone this repo, and do the following:
1. Change each of `BLANK_README.md` and `blank_pyproject.toml` to instead be the _real_ `README.md` and `pyproject.toml`
2. Replace instances of `<PROJECT>` in all files with the Human-readable project name (sans whitespace)
3. Replace instances of `<PROJECT_REPO>` in all files with the GH repo URL.
4. Replace instances of `<PROJECT_DESC>` in all files with the short description of the project
5. Replace `<PROJECT_DEPS>` in `README.md` with the list of packages to install with `pip` and update them in `pyproject.toml`.
6. Update `<PROJECT_AUTHORS>` in `pyproject.toml` (also update them in `README.md`).
7. Update `<PROJECT_PACKAGES>` in `pyproject.toml` using the `{include = "...", from = "..."}` syntax.
8. Update `<PROJECT_KEYWORDS>` in `pyproject.toml` as appropriate.
9. Fill out the `README.md` as appropriate.
10. Do the installation steps below through step 6.
11. Nix the existing example files in `src/` and `tests/`, replacing them with _real_ code.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [Black](black-url)
* [Coverage](coverage-url)
* [Coverage-badge](coverage-badge-url)
* [Flake8](flake8-url)
* [Handsdown](hd-url)
* [Interrogate](int-url)
* [MkDocs](mkdocs-url)
* [MyPy](mypy-url)
* [Pre-commit-hooks](pch-url)
* [Pydocstyle](pds-url)
* [Pyroma](pyroma-url)
* [PyTest](pytest-url)
* [Xenon](xenon-url)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To get started, simply clone the repo:
```sh
git clone git@github.com:HyPerNT/CookieCutterPython.git
```

### Prerequisites

It's recommended that you run this repo in a python virtual environment, such as `pyenv`:
```sh
curl -fsSL https://pyenv.run | bash\n
```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/HyPerNT/CookieCutterPython.git
   ```
2. Create a new pyenv environment
   ```sh
   pyenv install 3.11.7
   pyenv shell 3.11.7
   pyenv local 3.11.7
   ```
3. Install required python modules with pip
   ```sh
   pip3 install <PROJECT_DEPS>
   ```
4. (Optional) Install additional python modules to support use of pre-commit hooks, tests, and coverage reports
   ```sh
   pip3 install poetry mypy flake8 flake8-pyproject black pyroma xenon interrogate handsdown mkdocs pytest coverage coverage-badge isort conventional-pre-commit dos2unix
   ```
5. (Optional) Setup pre-commit hooks.
   ```sh
   pip3 install pre-commit
   pre-commit install --install-hooks
   ```
6. Build the package to generate additional data used by the pre-commit hooks.
   ```sh
   python3 -m build
   ```
7. Change git remote url to avoid accidental pushes to base project
   ```sh
   git remote set-url origin <github_username>/<repo_name>
   git remote -v # confirm the changes
   ```

### Running Tests

In order to run tests, it is necessary to install the package in editable mode:
```sh
  pip3 install -e .
```

Then, tests should be executable readily by PyTest:
```sh
  pytest
```

For code coverage:
```sh
  coverage run -m pytest
  coverage report # For a short report in the command-line
  coverage html -d cov # For HTML coverage reports
```
<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Brenton Candelaria - [@HyPerNT](https://discord.com/users/198554971954872320) - brentoncandelaria@example.com

Project Link: [https://github.com/HyPerNT/CookieCutterPython](https://github.com/HyPerNt/CookieCutterPython)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[last-commit-shield]: https://img.shields.io/github/last-commit/HyPerNT/CookieCutterPython
[last-commit-url]: https://github.com/HyPerNT/CookieCutterPython/commits/main/
[contributors-shield]: https://img.shields.io/github/contributors/HyPerNT/CookieCutterPython
[contributors-url]: https://github.com/HyPerNT/CookieCutterPython/graphs/contributors
[license-shield]: https://img.shields.io/github/license/HyPerNT/CookieCutterPython
[license-url]: https://github.com/HyPerNT/CookieCutterPython/blob/main/LICENSE
[interrogate-shield]: ./badges/interrogate.svg
[repo-size-shield]: https://img.shields.io/github/languages/code-size/HyPerNT/CookieCutterPython
[coverage-badge]: badges/coverage.svg

<!-- URLs for packages used by this project -->
[pytest-url]: https://docs.pytest.org/en/stable/
[black-url]: https://github.com/psf/black
[pch-url]: https://github.com/pre-commit/pre-commit-hooks
[flake8-url]: https://flake8.pycqa.org/en/latest/
[mypy-url]: https://mypy-lang.org
[xenon-url]: https://pypi.org/project/xenon/
[pyroma-url]: https://pypi.org/project/pyroma/
[int-url]: https://interrogate.readthedocs.io/en/latest/
[pds-url]: https://www.pydocstyle.org/en/stable/
[hd-url]: https://github.com/vemel/handsdown
[coverage-url]: https://coverage.readthedocs.io/en/7.9.1/
[coverage-badge-url]: https://pypi.org/project/coverage-badge/
[mkdocs-url]: https://www.mkdocs.org
