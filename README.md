About make
==========

Home: https://www.gnu.org/software/make/

Package license: GPLv3

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/make-feedstock/blob/master/LICENSE.txt)

Summary: GNU Make is a tool which controls the generation of executables and other non-source files of a program from the program's source files.

Documentation: https://www.gnu.org/software/make/manual/

Current build status
====================


<table><tr>
    <td>Travis</td>
    <td>
      <a href="https://travis-ci.com/conda-forge/make-feedstock">
        <img alt="macOS" src="https://img.shields.io/travis/com/conda-forge/make-feedstock/master.svg?label=macOS">
      </a>
    </td>
  </tr><tr>
    <td>Drone</td>
    <td>
      <a href="https://cloud.drone.io/conda-forge/make-feedstock">
        <img alt="linux" src="https://img.shields.io/drone/build/conda-forge/make-feedstock/master.svg?label=Linux">
      </a>
    </td>
  </tr>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=615&branchName=master">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/make-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_target_platformlinux-64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=615&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/make-feedstock?branchName=master&jobName=linux&configuration=linux_64_target_platformlinux-64" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_target_platformlinux-aarch64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=615&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/make-feedstock?branchName=master&jobName=linux&configuration=linux_aarch64_target_platformlinux-aarch64" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_target_platformlinux-ppc64le</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=615&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/make-feedstock?branchName=master&jobName=linux&configuration=linux_ppc64le_target_platformlinux-ppc64le" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_target_platformosx-64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=615&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/make-feedstock?branchName=master&jobName=osx&configuration=osx_64_target_platformosx-64" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_target_platformosx-arm64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=615&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/make-feedstock?branchName=master&jobName=osx&configuration=osx_arm64_target_platformosx-arm64" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_target_platformwin-64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=615&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/make-feedstock?branchName=master&jobName=win&configuration=win_64_target_platformwin-64" alt="variant">
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
| [![Conda Recipe](https://img.shields.io/badge/recipe-make-green.svg)](https://anaconda.org/conda-forge/make) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/make.svg)](https://anaconda.org/conda-forge/make) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/make.svg)](https://anaconda.org/conda-forge/make) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/make.svg)](https://anaconda.org/conda-forge/make) |

Installing make
===============

Installing `make` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
```

Once the `conda-forge` channel has been enabled, `make` can be installed with:

```
conda install make
```

It is possible to list all of the versions of `make` available on your platform with:

```
conda search make --channel conda-forge
```


About conda-forge
=================

[![Powered by NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](http://numfocus.org)

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


Updating make-feedstock
=======================

If you would like to improve the make recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/make-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@asmeurer](https://github.com/asmeurer/)
* [@scopatz](https://github.com/scopatz/)

