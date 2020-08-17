# robinunhood
Utilities for working with the Robinhood stock trading platform

* deployed to pypi using steps described here: https://medium.com/@joel.barmettler/how-to-upload-your-python-package-to-pypi-65edc5fe9c56

## To create new release
* bump version and download_url in setup.py 
* push code to github from local
* draft a new release from https://github.com/sanzgiri/robinunhood/releases, provide a new tag (same as new version) and optionally title and description
* upload new release to pypi 
```
python setup.py sdist
twine upload dist/*
```