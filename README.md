About xpdconf
=============

Home: 

Package license: 

Feedstock license: BSD 3-Clause

Summary: 



Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=185&branchName=master">
        <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/xpdconf-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-xpdconf-green.svg)](https://anaconda.org/nsls2forge/xpdconf) | [![Conda Downloads](https://img.shields.io/conda/dn/nsls2forge/xpdconf.svg)](https://anaconda.org/nsls2forge/xpdconf) | [![Conda Version](https://img.shields.io/conda/vn/nsls2forge/xpdconf.svg)](https://anaconda.org/nsls2forge/xpdconf) | [![Conda Platforms](https://img.shields.io/conda/pn/nsls2forge/xpdconf.svg)](https://anaconda.org/nsls2forge/xpdconf) |

Installing xpdconf
==================

Installing `xpdconf` from the `nsls2forge` channel can be achieved by adding `nsls2forge` to your channels with:

```
conda config --add channels nsls2forge
```

Once the `nsls2forge` channel has been enabled, `xpdconf` can be installed with:

```
conda install xpdconf
```

It is possible to list all of the versions of `xpdconf` available on your platform with:

```
conda search xpdconf --channel nsls2forge
```




Updating xpdconf-feedstock
==========================

If you would like to improve the xpdconf recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`nsls2forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `nsls2forge` channel.
Note that all branches in the nsls-ii-forge/xpdconf-feedstock are
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


