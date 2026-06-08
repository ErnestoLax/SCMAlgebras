 SCMAlgebras
=========

**SCMAlgebras** is a _Macaulay2_ package to check whether a module or an ideal is sequentially Cohen-Macaulay, by computing modules of deficiency and filter ideals.

For a more detailed mathematical description of the package, see the accompanying [paper](https://arxiv.org/pdf/2409.15134) on _arXiv_.  


## Main functionalities
| **Function / Type** | **Description** |
|:---|:---|
| `PrimaryDataList` | New type that stores primary decomposition datas used for computations |
| `getPrimaryData(I)` | Computes a `PrimaryDataList` of the ideal $I$ |
| `deficiencyModule(M,i)` | Computes the $i$-th module of deficiency of $M$ |
| `canonicalModule(M)` | Computes the canonical module of $M$ |
| `minimumDimension(I)` | Computes the minimum dimension of the ideal $I$ |
| `filterIdeal(I,i)` | Computes the $i$-th filter ideal of $I$ |
| `unmixedLayer(I,i)` | Computes the $i$-th unmixed layer of $I$ |
| `isUnmixed(I)` | Checks whether the ideal $I$ is unmixed |
| `isSCM(M)` | Checks whether $M$ is sequentially Cohen–Macaulay |
| `isCCM(M)` | Checks whether $M$ is canonically Cohen–Macaulay |


## Reference
If you use this package, please cite:
- arXiv preprint: https://arxiv.org/pdf/2409.15134
- package repository: https://github.com/ErnestoLax/SCMAlgebras


## Notes
This version of the package was tested with version 1.26.05 of _Macaulay2_.