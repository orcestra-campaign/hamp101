# HAMP 101: Tutorial and Post-Processing For Users

This repository is for scientists using HAMP, to understand what it is and how to

post-process the raw IQ data.

## Install
To (locally) reproduce this project simply clone the repository:
```
git clone git@github.com:orcestra-campaign/hamp101.git
```
and then create an environment with the necessary dependencies installed (e.g. using micromamba
or conda as listed in the environment.yaml):
```
micromamba env create -f environment.yaml
micromamba activate hamp101env
```
Finally you need to run ``pre-commit install`` but other than that everything should work out of
the box and you can now run & have fun with the project... If not, please raise an issue on the
GitHub repository.

## Documentation
Some documentation has been set up for this project which you should be able to find hosted online
here:

### https://orcestra-campaign.github.io/hamp101/

... If not, please raise an issue on the GitHub repository.

Alternatively, You can build and view the documentation locally. First build the .html files
using Sphinx, then view the .html in your default browser. E.g.

```
cd ./docs && mkdir build
make html
open build/html/index.html
```

Thank you and good luck!

## Contributors
- Clara Bayley
