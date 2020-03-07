<p align="center">
<img src="https://mesonbuild.com/assets/images/meson_logo.png">
</p>
Meson® is a project to create the best possible next-generation
build system.

#### Status

[![PyPI](https://img.shields.io/pypi/v/meson.svg)](https://pypi.python.org/pypi/meson)
[![Travis](https://travis-ci.org/mesonbuild/meson.svg?branch=master)](https://travis-ci.org/mesonbuild/meson)
[![Build Status](https://dev.azure.com/jussi0947/jussi/_apis/build/status/mesonbuild.meson)](https://dev.azure.com/jussi0947/jussi/_build/latest?definitionId=1)
[![Codecov](https://codecov.io/gh/mesonbuild/meson/coverage.svg?branch=master)](https://codecov.io/gh/mesonbuild/meson/branch/master)
[![Code Quality: Python](https://img.shields.io/lgtm/grade/python/g/mesonbuild/meson.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/mesonbuild/meson/context:python)
[![Total Alerts](https://img.shields.io/lgtm/alerts/g/mesonbuild/meson.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/mesonbuild/meson/alerts)

#### Dependencies

 - [Python](https://python.org) (version 3.5 or newer)
 - [Ninja](https://ninja-build.org) (version 1.5 or newer)

#### Installing from source

Meson is available on [PyPi](https://pypi.python.org/pypi/meson), so
it can be installed with `pip3 install meson`.  The exact command to
type to install with `pip` can vary between systems, be sure to use
the Python 3 version of `pip`.

If you wish you can install it locally with the standard Python command:

```console
python3 -m pip install meson
```

For builds using Ninja, Ninja can be downloaded directly from Ninja
[GitHub release page](https://github.com/ninja-build/ninja/releases)
or via [PyPi](https://pypi.python.org/pypi/ninja)

```console
python3 -m pip install ninja
```

More on Installing Meson build can be found at the
[getting meson page](https://mesonbuild.com/Getting-meson.html).

#### Running

Meson requires that you have a source directory and a build directory
and that these two are different. In your source root must exist a
file called `meson.build`. To generate the build system run this
command:

`meson setup <source directory> <build directory>`

Depending on how you obtained Meson the command might also be called
`meson.py` instead of plain `meson`. In the rest of this document we
are going to use the latter form.

You can omit either of the two directories, and Meson will substitute
the current directory and autodetect what you mean. This allows you to
do things like this:

```console
cd <source root>
meson setup builddir
```

To compile, cd into your build directory and type `ninja`. To run unit
tests, type `ninja test`.

More on running Meson build system commands can be found at the
[running meson page](https://mesonbuild.com/Running-Meson.html)
or by typing `meson --help`.

#### Contributing

We love code contributions. See the [contribution
page](https://mesonbuild.com/Contributing.html) on the website for
details.


#### IRC

The irc channel for Meson is `#mesonbuild` over at Freenode.

You can use [FreeNode's official webchat][meson_irc]
to connect to this channel.

[meson_irc]: https://webchat.freenode.net/?channels=%23mesonbuild

#### Further info

More information about the Meson build system can be found at the
[project's home page](https://mesonbuild.com).

Meson is a registered trademark of ***Jussi Pakkanen***.
