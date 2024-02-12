# MPh-Arm64
This is a fork of MPh library that apparently works Apple Mac Arm (M1, M2, M3) devices in which only discovery.py file is modified.
This fork is only tested for COMSOL Multiphysics 6.0.0.318 on Mac M1. It does not work for the latest COMSOL version 6.1 at the moment, though I was able to make it work locally on Mac M2 but I have not updated the code to do so.

### Usage
Assuming you have `git` and `pip` installed in your environment:

    pip install git+https://github.com/The-Alley/MPh-Arm64.git

To import the package, simply use:

    import mph

If you encountered  `Attempt to deallocate stack guard pages failed` and `Attempt to protect stack guard pages failed` warnings just ignore them.


## Original README

# MPh
*Pythonic scripting interface for Comsol Multiphysics*

[Comsol] is a commercial software application that is widely used in
science and industry for research and development. It excels at modeling
almost any (multi-)physics problem by solving the governing set of
partial differential equations via the finite-element method. It comes
with a modern graphical user interface to set up simulation models and
can be scripted from Matlab or its native Java API.

MPh brings the dearly missing power of Python to the world of Comsol.
It leverages the Java bridge provided by [JPype] to access the Comsol
API and wraps it in a layer of pythonic ease-of-use. The Python wrapper
covers common scripting tasks, such as loading a model from a file,
modifying parameters, importing data, to then run the simulation,
evaluate the results, and export them.

Comsol models are marked by their `.mph` file extension, which stands
for multi-physics. Hence the name of this library. It is open-source
and in no way affiliated with Comsol Inc., the company that develops
and sells the simulation software.

Find the full [documentation on Read-the-Docs][docs].

[Comsol]: https://www.comsol.com
[JPype]:  https://github.com/jpype-project/jpype
[docs]:   https://mph.readthedocs.io

[![release page](
https://img.shields.io/pypi/v/mph.svg?label=release)](
https://pypi.python.org/pypi/mph)
[![download statistics](
https://img.shields.io/pypi/dm/MPh)](
https://pypistats.org/packages/mph)
[![scientific citation](
https://zenodo.org/badge/264718959.svg)](
https://zenodo.org/badge/latestdoi/264718959)
[![coverage report](
https://img.shields.io/codecov/c/github/MPh-py/MPh?token=02ZZ8ZJH3M)](
https://codecov.io/gh/MPh-py/MPh)
[![latest documentation](
https://readthedocs.org/projects/mph/badge/?version=latest)](
https://mph.readthedocs.io/en/latest)
