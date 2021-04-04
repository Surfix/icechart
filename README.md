# IceChart


[![image](https://img.shields.io/pypi/v/icechart.svg)](https://pypi.python.org/pypi/icechart)
[![image](https://img.shields.io/conda/vn/conda-forge/icechart.svg)](https://anaconda.org/conda-forge/icechart)
[![image](https://pepy.tech/badge/icechart)](https://pepy.tech/project/icechart)
[![image](https://img.shields.io/twitter/follow/survix?style=social)](https://twitter.com/survix)
[![image](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)



**A python package for icesat data analysis**


-   Free software: MIT license
-   Documentation: https://Surfix.github.io/icechart
    


## Installation

### Pip 
The easiest way to install icechart is using pip

```
pip install icechart
```
This is the preferred method to install icechart, as it will always install the most recent stable release. If you don't have pip installed, this [Python installation guide](https://docs.python-guide.org/starting/installation/) can guide you through the process.
### conda
The package is under review by conda-forge channel and if approved, there will be option to install using conda package manager. 
```
conda install icechart -c conda-forge
```
### From sources
The sources for icechart can be downloaded from the Github repo.

You can clone the public repository:
```
git clone git://github.com/Surfix/icechart
```
## Features


Icechart is a python library developed to simplify the querying, acquisition and analysis of major satellite altimetry data (such as icesat-2, cryosat-2) towards facilitating scientific discovery and insights into the ice and snow covered regions. In its full development, the package will provide the following features:

- Convert spatial data format between shapefile to GeoJSON
- Display Earth Engine data layers for interactive mapping.
- Support Earth Engine JavaScript API-styled functions in Python, such as Map.addLayer(), Map.setCenter(), Map.centerObject(), Map.setOptions().
- Retrieve satellite altimetry data around user defined ROI from NSIDC platform
- Add the data to interactive map
- Plot and analyze the data

## Citation

I spent much of my day and weekend working on this package. Quality time which otherwise would have gone into writing journal papers or spent with my babe. So, if you find this tool useful, consider citing my articles:

- **Adebisi, N.**, Balogun, A.-L., Min, T.H., Tella, A., 2021. Advances in estimating Sea Level Rise: A review of tide gauge, satellite altimetry and spatial data science approaches. Ocean & Coastal Management 208, 105632. [DOI: https://doi.org/10.1016/j.ocecoaman.2021.105632](https://doi.org/10.1016/j.ocecoaman.2021.105632)
- Abdul-Lateef Balogun & **Naheem Adebisi** (2021). Sea level prediction using ARIMA, SVR and LSTM neural network: assessing the impact of ensemble Ocean-Atmospheric processes on models’ accuracy, Geomatics, Natural Hazards and Risk, 12:1, 653-674, [DOI: 10.1080/19475705.2021.1887372](https://www.tandfonline.com/doi/full/10.1080/19475705.2021.1887372)

## Submit a Feedback
The best way to send feedback is to file an issue at https://github.com/Surfix/icechart/issues.

If you are proposing a feature:
- Explain in detail how it would work.
- Keep the scope as narrow as possible, to make it easier to implement.
- Remember that this is a volunteer-driven project, and that contributions are welcome :)


## Credits

This package was created with [Cookiecutter](https://github.com/cookiecutter/cookiecutter) and the [giswqs/pypackage](https://github.com/giswqs/pypackages) project template.
