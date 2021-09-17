# Trading Strategy Backtrader

This is patched and bug fixed version for [Backtrader library](https://pypi.org/project/backtrader/). This package is a dependency for [trading-strategy](https://github.com/tradingstrategy-ai/client) package.

The `backtrader` project was forked and the fork released on a different PyPi package name `trading-strategy-backtrader` because the original was unmaintained and unusable as a PyPi package dependency.

[Show package information on PyPi](https://pypi.org/project/trading-strategy-backtrader/).

[For more information see the original Backtrader website](https://www.backtrader.com/) and [Trading Strategy website](https://tradingstrategy.ai/).

## Release

How to release this package on PyPi.

Update `setup.py` version.

::

       rm -rf dist
       python3 -m pip install --upgrade build
       python3 -m build
       python3 -m pip install --upgrade twine
       python3 -m twine upload dist/*

[How to publish Python packages](https://packaging.python.org/tutorials/packaging-projects/)
