Fluid Lint Utility
==================

[![Build Status](https://img.shields.io/travis/NamelessCoder/TYPO3.Fluid.Lint.svg?style=flat-square)](https://travis-ci.org/NamelessCoder/TYPO3.Fluid.Lint)
[![Coverage](https://img.shields.io/coveralls/NamelessCoder/TYPO3.Fluid.Lint.svg?style=flat-square)](https://coveralls.io/r/NamelessCoder/TYPO3.Fluid.Lint)

Checks the basic syntax of Fluid template files.

Installation
------------

```bash
composer require typo3fluid/fluid-lint
```

Usage
-----

```bash
./vendor/bin/fluidlint /path/to/files-or-file
```

If you are linting for a project that uses a custom RenderingContext, specify the RenderingContext class as last argument:

```bash
./vendor/bin/fluidlint /path/to/files-or-file MyVendor\\MyPackageName\\Rendering\\MyRenderingContext
```
