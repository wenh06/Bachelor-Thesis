# Bachelor Thesis

[![compile-test](https://github.com/wenh06/Bachelor-Thesis/actions/workflows/compile.yml/badge.svg)](https://github.com/wenh06/Bachelor-Thesis/actions/workflows/compile.yml)
![GitHub Release Date - Published_At](https://img.shields.io/github/release-date/wenh06/Bachelor-Thesis)
![GitHub commits since latest release (by SemVer including pre-releases)](https://img.shields.io/github/commits-since/wenh06/Bachelor-Thesis/latest)

Bachelor thesis on the problem of automorphic forms and the Langlands program.

## Usage

### Overleaf

One can compile via `Import from GitHub` using [Overleaf](https://www.overleaf.com/). This project is compiled successfully with

```
Compiler: XeLaTeX
Tex Live version: 2020
```

### Local

Run the following command to compile locally:

```python
python compile.py
```

then the compiled PDF file will be in the `build` directory.

Alternatively, one can use `latexmk` directly:

```bash
mkdir -p build
latexmk -xelatex -f main.tex
```
