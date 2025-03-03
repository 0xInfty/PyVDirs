# PyVDirs

A simple package to manage directories locally, never explicitely defining them inside the code.

## About

PyVDirs manages directories under the hood in such a way that the code can always be executed, regardless of who and where.

Different users may have different distribution of directories. These can be specified inside a `dirs.json` index file. The code will then recognize the user's PC, load the correct directories from the index, and run.

Moreover, PyVDirs allows private users to never commit any of their personal filepaths, because the `dirs.json` index file can be stored locally: you just never commit this file, therefore not pushing it into the cloud.

## Getting Started

### Installation

This package can easily be installed using `pip`:

```bash
pip install pyvdirs
```

It is good practice to always create a Python virtual environment before installing new packages.

## Additional Information

### Main Author Contact

Valeria Pais - @vrpais - valeriarpais@gmail.com