# Example of how to use the geemap package for the Python API of Google Earth Engine

This repo contains a Jupyter Notebook for learning the funcitons of `geemap`. The `geemap` package is useful because it provides interactive mapping and visualization functions which are not natively available in the GEE Python API. A description of geemap can be found [here](https://geemap.org/)

The authors of the notebook, Qiusheng Wu and Kel Markert, prepared it for use in association with a video tutorial given at GeoPython 2021 conference, which is available [here](https://www.youtube.com/watch?v=wGjpjh9IQ5I). It was lightly modified from the authors' original notebook for NGI to include notes and minor bug fixes. The user will benefit by following the video while running the notebook for explanations not described in the notes.

## Usage
The notebook includes instructions for preparing a virtual environment using either conda (per the original authors) or pip (per NGI's recommended Python setup). The code for the conda environment is included in the notebook or [here](https://geemap.org/workshops/GeoPython_2021/#:~:text=Miniconda%20or%20Anaconda-,Set%20up%20a%20conda%20environment,-%C2%B6).

To install using pip, you can clone this repo into a terminal by typing

 ```
C:\Users\<USERNAME>>git clone https://ngi001@dev.azure.com/ngi001/NGI%20Natural%20Hazards/_git/GEE-Python-geemap-package-example
```

Change into the new directory
```
C:\Users\<USERNAME>> cd GEE-Python-geemap-package-example 
```

and start a virtual environment from the command line (and if that doesn't work, try `python -m pipenv shell`)
```
C:\Users\<USERNAME>\GEE-Python-geemap-package-example> pipenv shell
```

finally, install the dependencies of the virtual environment.
```
C:\Users\<USERNAME>\GEE-Python-geemap-package-example> pipenv install
```

It should be noted that the conda environment supports a bonus map making module within the notebook that a pip environment does not support. This is due to a dependency written in a non-Python language within the module. The functionality of GEE is still fully available without the bonus map making module.

## Dependencies
To run the notebook in a pip environment, the user should have installed:
- pyenv, [NGI-adapted guide](https://ngiwiki.slite.com/app/docs/KXWBnnQrSS_Uu4)
- pipenv, [NGI-adapted guide](https://ngiwiki.slite.com/app/docs/tO10k0gX_U-6Ve)

The code in this repo has successfully been run on:
- cmd Windows 10