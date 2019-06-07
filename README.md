# spark-nlp-conda

[![Version Status](https://anaconda.org/johnsnowlabs/spark-nlp/badges/version.svg)](https://anaconda.org/JohnSnowLabs/spark-nlp) [![Last Update](https://anaconda.org/johnsnowlabs/spark-nlp/badges/latest_release_date.svg)](https://anaconda.org/JohnSnowLabs/spark-nlp) [![Downloads](https://anaconda.org/johnsnowlabs/spark-nlp/badges/downloads.svg)](https://anaconda.org/JohnSnowLabs/spark-nlp/files)

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
conda build . --python=3.6
```

Example of uploading Conda package to Anaconda Cloud:

```bash
anaconda upload /anaconda3/conda-bld/noarch/spark-nlp-2.0.2-py36_0.tar.bz2
```

## Main repository

[https://github.com/JohnSnowLabs/spark-nlp](https://github.com/JohnSnowLabs/spark-nlp)

## Project's website

Take a look at our official spark-nlp page: [http://nlp.johnsnowlabs.com/](http://nlp.johnsnowlabs.com/) for user documentation and examples

## Slack community channel

[Join Slack](https://join.slack.com/t/spark-nlp/shared_invite/enQtNjA4MTE2MDI1MDkxLTM4ZDliMjU5OWZmMDE1ZGVkMjg0MWFjMjU3NjY4YThlMTJkNmNjNjM3NTMwYzlhMWY4MGMzODI2NDBkOWU4ZDE)

## License

Apache Licence 2.0
