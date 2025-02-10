About ninja-hep-ph-feedstock
============================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/ninja-hep-ph-feedstock/blob/main/LICENSE.txt)

Home: https://github.com/peraro/ninja

Package license: GPL-3.0-only

Summary: Ninja: Automated Integrand Reduction via Laurent Expansion for One-Loop Amplitudes

Development: https://github.com/peraro/ninja

Ninja implements the Laurent series expansion method for the computation of
one-loop integrals.

It is based on:
* P. Mastrolia, E. Mirabella and T. Peraro, "_Integrand reduction of
one-loop scattering amplitudes through Laurent series expansion_,"
JHEP 1206 (2012) 095
[arXiv:1203.0291 [hep-ph]](https://arxiv.org/abs/1203.0291)
DOI: [10.1007/JHEP06(2012)095](https://doi.org/10.1007/JHEP06(2012)095)
* T. Peraro, "_Ninja: Automated Integrand Reduction via Laurent Expansion
for One-Loop Amplitudes_," Comput. Phys. Commun. 185 (2014) 2771
[arXiv:1403.1229 [hep-ph]](http://arxiv.org/abs/1403.1229)
DOI: [10.1016/j.cpc.2014.06.017](https://doi.org/10.1016/j.cpc.2014.06.017)


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=24224&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/ninja-hep-ph-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=24224&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/ninja-hep-ph-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=24224&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/ninja-hep-ph-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_ppc64le_" alt="variant">
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
| [![Conda Recipe](https://img.shields.io/badge/recipe-ninja--hep--ph-green.svg)](https://anaconda.org/conda-forge/ninja-hep-ph) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/ninja-hep-ph.svg)](https://anaconda.org/conda-forge/ninja-hep-ph) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/ninja-hep-ph.svg)](https://anaconda.org/conda-forge/ninja-hep-ph) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/ninja-hep-ph.svg)](https://anaconda.org/conda-forge/ninja-hep-ph) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-ninja--hep--ph--static-green.svg)](https://anaconda.org/conda-forge/ninja-hep-ph-static) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/ninja-hep-ph-static.svg)](https://anaconda.org/conda-forge/ninja-hep-ph-static) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/ninja-hep-ph-static.svg)](https://anaconda.org/conda-forge/ninja-hep-ph-static) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/ninja-hep-ph-static.svg)](https://anaconda.org/conda-forge/ninja-hep-ph-static) |

Installing ninja-hep-ph
=======================

Installing `ninja-hep-ph` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `ninja-hep-ph, ninja-hep-ph-static` can be installed with `conda`:

```
conda install ninja-hep-ph ninja-hep-ph-static
```

or with `mamba`:

```
mamba install ninja-hep-ph ninja-hep-ph-static
```

It is possible to list all of the versions of `ninja-hep-ph` available on your platform with `conda`:

```
conda search ninja-hep-ph --channel conda-forge
```

or with `mamba`:

```
mamba search ninja-hep-ph --channel conda-forge
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search ninja-hep-ph --channel conda-forge

# List packages depending on `ninja-hep-ph`:
mamba repoquery whoneeds ninja-hep-ph --channel conda-forge

# List dependencies of `ninja-hep-ph`:
mamba repoquery depends ninja-hep-ph --channel conda-forge
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
[Azure](https://azure.microsoft.com/en-us/services/devops/), [GitHub](https://github.com/),
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/),
[Drone](https://cloud.drone.io/welcome), and [TravisCI](https://travis-ci.com/)
it is possible to build and upload installable packages to the
[conda-forge](https://anaconda.org/conda-forge) [anaconda.org](https://anaconda.org/)
channel for Linux, Windows and OSX respectively.

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


Updating ninja-hep-ph-feedstock
===============================

If you would like to improve the ninja-hep-ph recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/ninja-hep-ph-feedstock are
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

* [@matthewfeickert](https://github.com/matthewfeickert/)

