# Seeds for EB corbos Linux

EB corbos Linux makes use of seeds to define the pool of supported  and qualified Canonical Ubuntu base packages.
In addition to these base packages, non Canoncial packages like _crinit_ and _elos_ are added to EB corbos Linux releases, as post-processing steps.

The working name of the base distribution, which contains only the Caninical packages, is nemos.

The seeds are structured in the following way:

- _prod_: These are the root packages for usage in production software, i.e. these packages, and all their dependencies are qualified for mass production and get security and bug fixes for up to 15 years.
- _dev_: These packages are only approved as development tooling, i.e. they get support and security and bug fixes, but they are not qualified for mass production and not intended for usage in produciton software.

The **main** branch of this repo is the **official and only source of truth for EB corbos Linux supported Canonical packages**. All **changes to the main branch have to be approved and alinged by EB corbos Linux product management and Canonical** in advance.
