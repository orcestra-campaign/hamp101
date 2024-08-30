# Template for Good Python and C++ Scientific Project

This code is adapted from [this template](https://juliadynamics.github.io/DrWatson.jl/stable) for
Julia Language to make a reproducible scientific project for Python and C++ code in light of the
guidelines from [this Good Scientific Code Workshop](https://www.youtube.com/watch?v=x3swaMSCcYk) by
George Datseris.

## Install
To (locally) reproduce this project simply clone the repository:
```
git clone https://github.com/orcestra-campaign/hamp101.git
```
and then create an environment with the necessary dependencies installed (e.g. using micromamba
or conda as listed in the environment.yaml):
```
micromamba env create -f environment.yaml
micromamba activate goodsciproj_env
```
Finally you need to run ``pre-commit install`` but other than that everything should work out of
the box and you can now run & have fun with the project... If not, please raise an issue on the
GitHub repository.

## Documentation
Some documentation has been set up for this project which you should be able to find hosted online
here:
### https://yoctoyotta1024.github.io/GoodSciProjTemplate/
... If not, please raise an issue on the GitHub repository.

Alternatively, You can build and view the documentation locally. First build the .xml
files using Doxygen followed by .html files using Sphinx, then view the .html in your default
browser. E.g.

```
cd ./docs && mkdir build && mkdir build/doxygen
doxygen doxygen/doxygen.dox && make html
open build/html/index.html
```

Thank you and good luck!

## Contributors
- Clara Bayley

## Acknowledgements
- Lukas Kluft
- George Datseris
