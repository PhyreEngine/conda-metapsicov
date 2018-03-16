This repository contains a [conda][conda] recipe for building [MetaPSICOV][mp],
a meta-tool for predicting residue-residue contacts from correlated mutations.

## Prerequisites

1. You will need an installation of [conda][miniconda].

2. Your root conda installation must have the `conda-build` installed.

## Building

You should be able to build this package by simply running `conda build .`.

## Patches

The default MetaPSICOV package comes with a perl script called
`run_metapsicov`. This package replaces that script with a heavily edited
version that provides better error reliability, error messages and portability.

[conda]: https://conda.io
[miniconda]: https://conda.io/miniconda.html
[mp]: http://bioinf.cs.ucl.ac.uk/MetaPSICOV/
