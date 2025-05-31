# SCMAlgebras

SCMAlgebras is a Macaulay2 package to check whether a module or an ideal is sequentially Cohen-Macaulay, by checking the modules of deficiency or the filter ideals.

For a more detailed description of the package check out the [paper](https://arxiv.org/pdf/2409.15134) on arXiv.

## List of functions
The functions introduced in the package are listed down below.

| **Function** | **Description** |
|   :---  |   :--- |
| `deficiencyModule(M,i)` | Computes the ith module of deficiency of M |
| `canonicalModule(M)` | Computes the canonical module of M |
| `minimumDimension(I)` | Computes the minimum dimension of the ideal I |
| `filterIdeal(I,i)` | Computes the ith filter ideal of the ideal I |
| `unmixedLayer(I,i)` | Computes the ith unmixed layer of the ideal I |
| `isUnmixed(I)` | Checks if the ideal I is unmixed |
| `isSCM(M)` | Checks if M is sequentially Cohen-Macaulay |
| `isCCM(M)` | Checks if M is canonically Cohen-Macaulay |