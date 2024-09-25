# Open Source Python Packages in Hydrology
My attempt to list interesting open source python projects that can be used in the field of Hydrology. Suggestions as issues or pull requests are welcome!

UPDATE: The Pypa package authority has now added ["Hydrology" as a classifier](https://github.com/pypa/warehouse/issues/5728) so we can start [collecting python packages](https://pypi.org/search/?q=&o=&c=Topic+%3A%3A+Scientific%2FEngineering+%3A%3A+Hydrology) used by the hydrological community! If you are maintaining a python package, please add `Topic :: Scientific/Engineering :: Hydrology` to your setup.py so people can find your package.

Raoul A. Collenteur, Eawag.

## Hydrological Models
| Project Name | Description (Longer Header to Widen Column) | PyPI | Conda | Docs | CI | Version | Last Update | DOI Paper |
| ------------ | ------------------------------------------ | ---- | ----- | ---- | -- | ------- | ----------- | --------- |
| [CMF](https://github.com/philippkraft/cmf) | Catchment Modelling Framework, a hydrologic modelling toolbox. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/CMF/) |  |  |  |  |  |  |
| [TopoFlow](https://github.com/peckhams/topoflow) | A spatial hydrologic model (D8-based, fully BMI-compliant). |  |  |  |  |  |  |  |
| [VIC](https://github.com/UW-Hydro/VIC) | The Variable Infiltration Capacity (VIC) Macroscale Hydrologic Model. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/VIC/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/VIC) | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](http://vic.readthedocs.io) |  |  |  |  |
| [Xanthos](https://github.com/JGCRI/xanthos) | Xanthos is an open-source hydrologic model, written in Python, designed to quantify and analyze global water availability. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/Xanthos/) |  |  |  |  |  |  |
| [WRF-Hydro](https://github.com/NCAR/wrf_hydro_py) | wrfhydrpy is a Python API for the WRF-Hydro modelling system. |  |  | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://wrfhydropy.readthedocs.io/en/latest/?badge=latest) |  |  |  |  |
| [EXP-HYDRO](https://github.com/sopanpatil/exp-hydro) | EXP-HYDRO is a catchment scale hydrological model that operates at a daily time-step. It takes as inputs the daily values of precipitation, air temperature, and potential evapotranspiration, and simulates daily streamflow at the catchment outlet. |  |  |  |  |  |  |  |
| [RRMPG](https://github.com/kratzert/RRMPG) | Rainfall-Runoff modelling playground. |  |  | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](http://rrmpg.readthedocs.io/en/latest/index.html) |  |  |  |  |
| [LHMP](https://github.com/hydrogo/LHMP) | Lumped Hydrological Models Playground. |  |  |  |  |  |  |  |
| [SMARTPy](https://github.com/ThibHlln/smartpy) | Python implementation of the rainfall-runoff model SMART | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/SMARTPy/) |  |  |  |  |  |  |
| [PyStream](https://github.com/martibosch/pystream) | Python implementation of the STREAM hydrological rainfall-runoff model. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/PyStream/) |  |  |  |  |  |  |
| [HydPy](https://github.com/hydpy-dev/hydpy) | A framework for the development and application of hydrological models based on Python. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/HydPy/) |  | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://coverage.readthedocs.io) |  |  |  |  |
| [Catchmod](https://pypi.org/project/pycatchmod/) | CATCHMOD is widely used rainfall runoff model in the United Kingdom. It was introduced by Wilby (1994). |  |  |  |  |  |  |  |
| [wflow](https://github.com/openstreams/wflow) | wflow consists of a set of Python programs that can be run on the command line and perform hydrological simulations. The models are based on the PCRaster Python framework | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/wflow/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/wflow) | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://wflow.readthedocs.io) |  |  |  |  |
| [PyTOPKAPI](https://github.com/sahg/PyTOPKAPI) | PyTOPKAPI is a BSD licensed Python library implementing the TOPKAPI Hydrological model (Liu and Todini, 2002). | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/PyTOPKAPI/) |  |  |  |  |  |  |
| [mhmpy](https://github.com/MuellerSeb/mhmpy) | A Python-API for the mesoscale Hydrological Model. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/mhmpy/) |  |  |  |  |  |  |
| [SuperflexPy](https://github.com/dalmo1991/superflexPy) | SuperflexPy: A new open source framework for building conceptual hydrological models | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/SuperflexPy/) |  | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://superflexpy.readthedocs.io) |  |  |  |  |
| [NeuralHydrology](https://github.com/neuralhydrology/neuralhydrology) | Python library to train neural networks with a strong focus on hydrological applications. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/NeuralHydrology/) |  | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://neuralhydrology.readthedocs.io/) |  |  |  |  |
| [DRYP](https://github.com/AndresQuichimbo/DRYP) | Dryland Water Partition model. |  |  |  |  |  |  |  |
| [LuKars](https://github.com/dbittner87/LuKARS) | The LuKARS model is a lumped karst hydrological model to perform studies in karstic environments. |  |  |  |  |  |  |  |
| [SUMMA](https://github.com/CH-Earth/summa) | A hydrologic modeling framework that can be used for the systematic analysis of alternative model conceptualizations with respect to flux parameterizations, spatial configurations, and numerical solution techniques. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/SUMMA/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/SUMMA) | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](http://summa.readthedocs.io/) |  |  |  |  |

## Meteorological tools
| Project Name | Description (Longer Header to Widen Column) | PyPI | Conda | Docs | CI | Version | Last Update | DOI Paper |
| ------------ | ------------------------------------------ | ---- | ----- | ---- | -- | ------- | ----------- | --------- |
| [MetPy](https://github.com/Unidata/MetPy) | MetPy is a collection of tools in Python for reading, visualizing and performing calculations with weather data. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/MetPy/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/MetPy) |  |  |  |  |  |
| [PyEto](https://github.com/woodcrafty/PyETo) | PyETo is a Python library for calculating reference crop evapotranspiration (ETo), sometimes referred to as potential evapotranspiration (PET). The library provides numerous functions for estimating missing meteorological data. |  |  | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://pyeto.readthedocs.io/en/latest/index.html) |  |  |  |  |
| [pyfao56](https://github.com/kthorp/pyfao56) | A Python implementation of the FAO-56 dual crop coefficient approach for crop water use estimation and irrigation scheduling. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/pyfao56/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/pyfao56) |  |  |  |  |  |
| [Improver](https://github.com/metoppv/improver) | IMPROVER is a library of algorithms for meteorological post-processing and verification. |  | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/Improver) | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](http://improver.readthedocs.io/en/latest/) |  |  |  |  |
| [MetSim](https://github.com/UW-Hydro/MetSim) | MetSim is a meteorological simulator and forcing disaggregator for hydrologic modeling and climate applications. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/MetSim/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/MetSim) | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](http://metsim.readthedocs.io/) |  |  |  |  |
| [MELODIST](https://github.com/kristianfoerster/melodist) | MELODIST is an open-source toolbox written in Python for disaggregating daily meteorological time series to hourly time steps. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/MELODIST/) |  |  |  |  |  |  |
| [PyCat](https://github.com/wegener-center/pyCAT) | Climate Analysis Tool written in python | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/PyCat/) |  | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](http://pycat.readthedocs.io/en/latest/?badge=latest) |  |  |  |  |
| [PySteps](https://github.com/pySTEPS/pysteps) | pySTEPS is a community-driven initiative for developing and maintaining an easy to use, modular, free and open source Python framework for short-term ensemble prediction systems. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/PySteps/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/PySteps) | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://pysteps.readthedocs.io/en/stable/) |  |  |  |  |
| [Evaporation](https://github.com/openmeteo/evaporation) | Calculation of evaporation and transpiration. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/Evaporation/) |  | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://evaporation.readthedocs.io) |  |  |  |  |
| [rainymotion](https://github.com/hydrogo/rainymotion) | Python library for radar-based precipitation nowcasting based on optical flow techniques. |  |  | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](http://rainymotion.readthedocs.io) |  |  |  |  |
| [pyet](https://github.com/phydrus/pyet) | A python-package for calculating reference and potential evaporation. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/pyet/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/pyet) | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://pyet.readthedocs.io/) |  |  |  |  |
| [SPEI](https://github.com/martinvonk/SPEI) | A simple Python package to calculate and visualize some popular drought indices such as the SPI, SPEI and SGI. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/SPEI/) |  |  |  |  |  |  |

## Unsaturated Zone
| Project Name | Description (Longer Header to Widen Column) | PyPI | Conda | Docs | CI | Version | Last Update | DOI Paper |
| ------------ | ------------------------------------------ | ---- | ----- | ---- | -- | ------- | ----------- | --------- |
| [Pytesmo](https://github.com/TUW-GEO/pytesmo) | python Toolbox for the Evaluation of Soil Moisture Observations. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/Pytesmo/) |  | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://pytesmo.readthedocs.io) |  |  |  |  |
| [Phydrus](https://github.com/phydrus/phydrus) | Python implementation of the HYDRUS-1D unsaturated zone model | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/Phydrus/) |  | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://phydrus.readthedocs.io/) |  |  |  |  |
| [VS2DPY](https://github.com/martinvonk/VS2DPY) | Python implementation of the VS2D unsaturated zone model. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/VS2DPY/) |  |  |  |  |  |  |
| [pedon](https://github.com/martinvonk/pedon) | Python package for (unsaturated) soil properties including pedotransfer functions. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/pedon/) |  |  |  |  |  |  |

## Groundwater
| Project Name | Description (Longer Header to Widen Column) | PyPI | Conda | Docs | CI | Version | Last Update | DOI Paper |
| ------------ | ------------------------------------------ | ---- | ----- | ---- | -- | ------- | ----------- | --------- |
| [FloPy](https://github.com/modflowpy/flopy) | The Python interface to MODFLOW. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/FloPy/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/FloPy) | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://flopy.readthedocs.io) |  |  |  |  |
| [imod-python](https://deltares.gitlab.io/imod/imod-python/) | Make massive MODFLOW models. |  |  | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://pydata-sphinx-theme.readthedocs.io/en/stable/index.html) |  |  |  |  |
| [Idfpy](https://github.com/tomvansteijn/idfpy) | A simple module for reading and writing iMOD IDF files. IDF is a simple binary format used by the iMOD groundwater modelling software. |  |  |  |  |  |  |  |
| [WellApplication](https://github.com/utah-geological-survey/WellApplication) | Set of tools for groundwater level and water chemistry analysis. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/WellApplication/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/WellApplication) |  |  |  |  |  |
| [TIMML](https://github.com/mbakker7/timml) | A Multi-Layer, Analytic Element Model. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/TIMML/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/TIMML) | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://timml.readthedocs.io/) |  |  |  |  |
| [TTim](https://github.com/mbakker7/ttim) | A Multi-Layer, Transient, Analytic Element Model. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/TTim/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/TTim) | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://ttim.readthedocs.io) |  |  |  |  |
| [PyHELP](https://github.com/cgq-qgc/pyhelp) | A Python library for the assessment of spatially distributed groundwater recharge and hydrological components with HELP. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/PyHELP/) |  | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](http://pyhelp.readthedocs.io) |  |  |  |  |
| [Anaflow](https://github.com/GeoStat-Framework/AnaFlow) | A python-package containing analytical solutions for the groundwater flow equation | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/Anaflow/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/Anaflow) | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://anaflow.readthedocs.io) |  |  |  |  |
| [WellTestPy](https://github.com/GeoStat-Framework/welltestpy) | A python-package for handling well based field campaigns. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/WellTestPy/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/WellTestPy) | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://welltestpy.readthedocs.io) |  |  |  |  |
| [HydroGeoSines](https://github.com/HydroGeoSines/HydroGeoSines) | Signal In the Noise Exploration Software for Hydrogeological Datasets. |  |  |  |  |  |  |  |
| [nlmod](https://github.com/ArtesiaWater/nlmod) | Python code to process, build and visualize MODFLOW models in the Netherlands. Model data is stored in a xarray Datasets and geopandas GeoDataFrames. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/nlmod/) |  | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://nlmod.readthedocs.io) |  |  |  |  |

## Time Series (Analysis)
| Project Name | Description (Longer Header to Widen Column) | PyPI | Conda | Docs | CI | Version | Last Update | DOI Paper |
| ------------ | ------------------------------------------ | ---- | ----- | ---- | -- | ------- | ----------- | --------- |
| [Hydropy](https://github.com/stijnvanhoey/hydropy) | Analysis of hydrological oriented time series. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/Hydropy/) |  |  |  |  |  |  |
| [Pastas](https://github.com/pastas/pastas) | Analysis of hydrological time series using time series models. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/Pastas/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/Pastas) | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://pastas.readthedocs.io) |  |  |  |  |
| [Hydrostats](https://github.com/BYU-Hydroinformatics/Hydrostats) | Tools for use in comparison studies, specifically for use in the field of hydrology. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/Hydrostats/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/Hydrostats) | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://hydrostats.readthedocs.io/en/stable/) |  |  |  |  |
| [htimeseries](https://github.com/openmeteo/htimeseries) | This module provides the HTimeseries class, which is a layer on top of pandas, offering a little more functionality. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/htimeseries/) |  |  |  |  |  |  |
| [HydroAnalysis](https://github.com/dalmo1991/HydroAnalysis) | Python package to calculate indices and metrics useful in the everyday job of a hydrologist. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/HydroAnalysis/) |  | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://hydroanalysis.readthedocs.io/en/latest/) |  |  |  |  |
| [HydroPandas](https://github.com/ArtesiaWater/hydropandas) | Module for loading time series data into custom DataFrames | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/HydroPandas/) |  | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://hydropandas.readthedocs.io) |  |  |  |  |
| [traval](https://github.com/ArtesiaWater/traval) | Tools for applying automatic error detection schemes to timeseries | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/traval/) |  | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://traval.readthedocs.io/) |  |  |  |  |

## GIS Related
| Project Name | Description (Longer Header to Widen Column) | PyPI | Conda | Docs | CI | Version | Last Update | DOI Paper |
| ------------ | ------------------------------------------ | ---- | ----- | ---- | -- | ------- | ----------- | --------- |
| [PcRaster](http://pcraster.geo.uu.nl/) | Is a collection of software targeted at the development and deployment of spatio-temporal environmental models. |  | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/PcRaster) |  |  |  |  |  |
| [PyGeoprocessing](https://pypi.org/project/pygeoprocessing/) | A Python/Cython based library that provides a set of commonly used raster, vector, and hydrological operations for GIS processing. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/PyGeoprocessing/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/PyGeoprocessing) | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://pygeoprocessing.readthedocs.io/en/latest/) |  |  |  |  |
| [Pysheds](https://github.com/mdbartos/pysheds) | Simple and fast watershed delineation in python. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/Pysheds/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/Pysheds) |  |  |  |  |  |
| [Lidar](https://github.com/giswqs/lidar) | Terrain and hydrological analysis based on LiDAR-derived digital elevation models (DEM). | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/Lidar/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/Lidar) | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://richdem.readthedocs.io/) |  |  |  |  |

## Optimization, Uncertainty, Statistics
| Project Name | Description (Longer Header to Widen Column) | PyPI | Conda | Docs | CI | Version | Last Update | DOI Paper |
| ------------ | ------------------------------------------ | ---- | ----- | ---- | -- | ------- | ----------- | --------- |
| [LMFIT](https://github.com/lmfit/lmfit-py) | Non-Linear Least Squares Minimization, with flexible Parameter settings, based on scipy.optimize.leastsq, and with many additional classes and methods for curve fitting. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/LMFIT/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/LMFIT) |  |  |  |  |  |
| [SPOTpy](https://github.com/thouska/spotpy) | A Statistical Parameter Optimization Tool for Python. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/SPOTpy/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/SPOTpy) | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://spotpy.readthedocs.io/en/latest/) |  |  |  |  |
| [PyGLUE](https://github.com/julienmalard/pyGLUE/) | Generalised Likelihood Uncertainty Estimation (GLUE) Framework. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/PyGLUE/) |  |  |  |  |  |  |
| [Pyemu](https://github.com/jtwhite79/pyemu) | Python modules for model-independent uncertainty analyses, data-worth analyses, and interfacing with PEST(++). | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/Pyemu/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/Pyemu) | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://pyemu.readthedocs.io/en/latest/) |  |  |  |  |
| [HPGL](http://hpgl.github.io/hpgl/) | High Performance Geostatistics Library. |  |  |  |  |  |  |  |
| [HydroErr](https://github.com/BYU-Hydroinformatics/HydroErr) | Goodness of Fit metrics for use in comparison studies, specifically in the field of hydrology. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/HydroErr/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/HydroErr) | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://hydroerr.readthedocs.io/en/stable/) |  |  |  |  |
| [Climate-indices](https://github.com/monocongo/climate_indices) | Climate indices for drought monitoring, community reference implementations in Python. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/Climate-indices/) |  | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://climate-indices.readthedocs.io/en/latest/) |  |  |  |  |
| [HydroLM](https://github.com/mullenkamp/HydroLM) | The HydroLM package contains a class and functions for automating linear regressions OLS for hydrologists. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/HydroLM/) |  |  |  |  |  |  |
| [PySDI](https://bitbucket.org/pysdi/pysdi/src/master/) | Pysdi is a set of open source scripts that compute non-parametric standardized drought indices (SDI) using raster data sets as input data. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/PySDI/) |  |  |  |  |  |  |
| [xskillscore](https://github.com/xarray-contrib/xskillscore) | Metrics for verifying forecasts. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/xskillscore/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/xskillscore) | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://xskillscore.readthedocs.io/en/stable/) |  |  |  |  |

## Data Collection
| Project Name | Description (Longer Header to Widen Column) | PyPI | Conda | Docs | CI | Version | Last Update | DOI Paper |
| ------------ | ------------------------------------------ | ---- | ----- | ---- | -- | ------- | ----------- | --------- |
| [HKVFEWSPY](https://github.com/HKV-products-services/hkvfewspy) | Connection to the Delft FEWS servers. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/HKVFEWSPY/) |  |  |  |  |  |  |
| [Openradar](https://github.com/nens/openradar) | Library for processing a set of dutch, german and belgian precipitation radars into calibrated composites. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/Openradar/) |  |  |  |  |  |  |
| [Ecohydrolib](https://github.com/selimnairb/EcohydroLib) | Libraries and command-line scripts for performing ecohydrology data preparation workflows. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/Ecohydrolib/) |  |  |  |  |  |  |
| [Ulmo](https://github.com/ulmo-dev/ulmo/) | Clean, simple and fast access to public hydrology and climatology data. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/Ulmo/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/Ulmo) | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://ulmo.readthedocs.io/en/latest/?badge=latest) |  |  |  |  |
| [PyHIS](https://pypi.org/project/pyhis/) | PyHIS is a python library for querying CUAHSI*-HIS** web services. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/PyHIS/) |  |  |  |  |  |  |
| [Wetterdienst](https://github.com/earthobservations/wetterdienst) | Python Toolset For Accessing Weather Data From German Weather Service. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/Wetterdienst/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/Wetterdienst) | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://wetterdienst.readthedocs.io/) |  |  |  |  |
| [Dataretrieval](https://github.com/USGS-python/dataretrieval) | Dataretrieval is a Python package for obtaining USGS or EPA water quality data, streamflow data, and metadata directly from web services. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/Dataretrieval/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/Dataretrieval) |  |  |  |  |  |

## Miscellaneous
| Project Name | Description (Longer Header to Widen Column) | PyPI | Conda | Docs | CI | Version | Last Update | DOI Paper |
| ------------ | ------------------------------------------ | ---- | ----- | ---- | -- | ------- | ----------- | --------- |
| [ESMPY](https://github.com/esmf-org/esmf) | Earth System Modeling Framework (ESMF) Python interface. |  | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/ESMPY) |  |  |  |  |  |
| [PyHSPF](https://github.com/djlampert/PyHSPF) | Python extensions to the Hydrological Simulation Program in Fortran (HSPF). | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/PyHSPF/) |  |  |  |  |  |  |
| [PYWR](https://github.com/pywr/pywr) | Spatial allocation tool. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/PYWR/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/PYWR) |  |  |  |  |  |
| [SPHY](https://github.com/WilcoTerink/SPHY) | Spatial Processes in HYdrology (SPHY) model. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/SPHY/) |  | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://sphy.readthedocs.io/en/latest/) |  |  |  |  |
| [xsboringen](https://github.com/tomvansteijn/xsboringen) | (In Dutch) A python library for processing and plotting borehole and CPT data, developed for open data formats in the Netherlands. |  |  |  |  |  |  |  |
| [PyMT](https://github.com/csdms/pymt/) | PyMT is an Open Source Python package that provides the necessary tools used for the coupling of models that expose the Basic Model Interface (BMI). | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/PyMT/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/PyMT) | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://pymt.readthedocs.io/en/latest/?badge=latest) |  |  |  |  |
| [Landlab](https://github.com/landlab/landlab) | The Landlab project creates an environment in which scientists can build a numerical landscape model without having to code all of the individual components. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/Landlab/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/Landlab) | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://landlab.readthedocs.io/) |  |  |  |  |
| [EFlowCalc](https://github.com/ThibHlln/eflowcalc) | Calculator of Streamflow Characteristics. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/EFlowCalc/) |  |  |  |  |  |  |
| [IRIS](https://github.com/SciTools/iris) | A powerful, format-agnostic, and community-driven Python library for analysing and visualising Earth science data. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/IRIS/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/IRIS) | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://scitools-iris.readthedocs.io/en/stable/) |  |  |  |  |
| [Hydrointerp](https://github.com/mullenkamp/hydrointerp) | A Python package for interpolating hydrologic data. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/Hydrointerp/) |  | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://hydrointerp.readthedocs.io) |  |  |  |  |
| [Hydrofunctions](https://github.com/mroberge/hydrofunctions) | A suite of convenience functions for working with hydrology data in an interactive Python session. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/Hydrofunctions/) | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/Hydrofunctions) | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://hydrofunctions.readthedocs.io/en/latest/?badge=latest) |  |  |  |  |
| [Shyft](https://gitlab.com/shyft-os) | Shyft is the open-source toolbox for the energy-market domain, funded and supported by Statkraft. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/Shyft/) |  |  |  |  |  |  |
| [Hydroshare](https://github.com/hydroshare/hydroshare) | HydroShare is a collaborative website for better access to data and models in the hydrologic sciences. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/Hydroshare/) |  |  |  |  |  |  |
| [Hydrobox](https://github.com/VForWaTer/hydrobox) | Hydrological preprocessing and analysis toolbox build upon pandas and numpy. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/Hydrobox/) |  |  |  |  |  |  |
| [Wetland](https://github.com/giswqs/wetland) | Wetland is a toolset for mapping surface water and wetland hydrological dynamics using fine-resolution aerial imagery within Google Earth Engine (GEE). | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/Wetland/) |  | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://wetland.readthedocs.io/en/latest/?badge=latest) |  |  |  |  |
| [iRONS](https://github.com/AndresPenuela/iRONS) | iRONS (interactive Reservoir Operation Notebooks and Software) is a python package that enables the simulation, forecasting and optimisation of reservoir systems. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/iRONS/) |  |  |  |  |  |  |
| [Mesas](https://github.com/charman2/mesas) | Multiresolution Estimation of StorAge Selection functions. |  | [![Conda](https://img.shields.io/badge/-44A833?logo=anaconda&logoColor=white)](https://anaconda.org/conda-forge/Mesas) | [![Docs](https://img.shields.io/badge/Docs-217346?logo=readthedocs&logoColor=white)](https://mesas.readthedocs.io/en/latest/installation.html) |  |  |  |  |
| [pydsstools](https://github.com/gyanz/pydsstools) | Python library for simple [HEC-DSS](https://www.hec.usace.army.mil/software/hec-dss/) functions. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/pydsstools/) |  |  |  |  |  |  |
| [eWaterCycle](https://doi.org/10.5194/gmd-15-5371-2022) | Platform to do computational hydrology using many of the above mentioned models. | [![PyPI](https://img.shields.io/badge/-3776AB?logo=python&logoColor=white)](https://pypi.org/project/eWaterCycle/) |  |  |  |  |  |  |

