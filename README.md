
# partbrowser

[![Build Status](https://travis-ci.org/drewsherlock/partbrowser.svg?branch=master)](https://travis-ci.org/drewsherlock/partbrowser)
[![codecov](https://codecov.io/gh/drewsherlock/partbrowser/branch/master/graph/badge.svg)](https://codecov.io/gh/drewsherlock/partbrowser)


widget to view X3D files

## Installation

You can install using `pip`:

```bash
pip install partbrowser
```

Or if you use jupyterlab:

```bash
pip install partbrowser
jupyter labextension install @jupyter-widgets/jupyterlab-manager
```

If you are using Jupyter Notebook 5.2 or earlier, you may also need to enable
the nbextension:
```bash
jupyter nbextension enable --py [--sys-prefix|--user|--system] partbrowser
```
