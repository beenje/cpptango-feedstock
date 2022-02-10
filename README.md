About cpptango
==============

Home: https://www.tango-controls.org

Package license: LGPL-3.0-or-later

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/cpptango-feedstock/blob/master/LICENSE.txt)

Summary: Tango-Controls C++ library

Development: https://gitlab.com/tango-controls/cppTango

Documentation: https://tango-controls.github.io/cppTango-docs

This is the Tango-Controls C++ library (a.k.a. cppTango).
Tango-Controls is a software toolkit for building control systems.


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=11614&branchName=master">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/cpptango-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=11614&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/cpptango-feedstock?branchName=master&jobName=linux&configuration=linux_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=11614&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/cpptango-feedstock?branchName=master&jobName=win&configuration=win_64_" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-cpptango-green.svg)](https://anaconda.org/conda-forge/cpptango) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/cpptango.svg)](https://anaconda.org/conda-forge/cpptango) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/cpptango.svg)](https://anaconda.org/conda-forge/cpptango) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/cpptango.svg)](https://anaconda.org/conda-forge/cpptango) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-cpptango--dbg-green.svg)](https://anaconda.org/conda-forge/cpptango-dbg) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/cpptango-dbg.svg)](https://anaconda.org/conda-forge/cpptango-dbg) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/cpptango-dbg.svg)](https://anaconda.org/conda-forge/cpptango-dbg) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/cpptango-dbg.svg)](https://anaconda.org/conda-forge/cpptango-dbg) |

Installing cpptango
===================

Installing `cpptango` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `cpptango, cpptango-dbg` can be installed with:

```
conda install cpptango cpptango-dbg
```

It is possible to list all of the versions of `cpptango` available on your platform with:

```
conda search cpptango --channel conda-forge
```


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/)
and [TravisCI](https://travis-ci.com/) it is possible to build and upload installable
packages to the [conda-forge](https://anaconda.org/conda-forge)
[Anaconda-Cloud](https://anaconda.org/) channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating cpptango-feedstock
===========================

If you would like to improve the cpptango recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/cpptango-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@beenje](https://github.com/beenje/)
* [@bourtemb](https://github.com/bourtemb/)

