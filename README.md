# spark-nlp-conda

## Setup

Before you start, install anaconda-client and conda-build:

```bash
conda install anaconda-client conda-build
```

Make sure you are logged in as JohnSnowLabs

```bash
conda login
```

## Build

Purge the previous builds:

```bash
conda build purge
```

Turn off auto-upload:

```bash
conda config --set anaconda_upload no
```

Build `spark-nlp` from the latest PyPI tar:

```bash
conda build .
````

Example of uploading Conda package to Anaconda Cloud:

```bash
anaconda upload ~/anaconda3/conda-bld/osx-64/spark-nlp-1.8.1-py36_3.tar.bz2 --froce
```
