# Week 5<br>Getting Data Part 1:Working with APIs

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MUSA-620-Fall-2019/week-5/master?filepath=lecture-5.ipynb)

## Updating your local environment

First, download the `environment.yml` file in this repository to your computer.

**Important**: if you are on a Windows machine, make sure that `.txt` wasn't appended to the file name when you downloaded it. If so, you will need to rename it so the file ends in `.yml`.

Then you can run, from either the Anaconda Prompt (Windows) or Terminal app (MacOS):

```
conda env update --file environment.yml --name musa-620
```

where `musa-620` should be the name of the environment you have been using.

Then you can activate the environment and start a notebook

```
conda activate musa-620
```

## New Packages

- [`census`](https://github.com/datamade/census)
- [`us`](https://github.com/unitedstates/python-us)
- [`textblob`](https://github.com/sloria/textblob)
- [`carto2gpd`](https://github.com/PhiladelphiaController/carto2gpd)
- [`esri2gpd`](https://github.com/PhiladelphiaController/esri2gpd)

## Useful Links

- [American Factfinder](https://factfinder.census.gov)
- [US Census Data via NHGIS](https://www.nhgis.org/)
- [Data USA](https://datausa.io/)
- [Census Reporter](https://censusreporter.org/)
- [Racial Dot Map](https://demographics.coopercenter.org/Racial-Dot-Map)

## Reference Materials

- [Census API User Guide](https://www.census.gov/data/developers/guidance/api-user-guide.html)
- [Census API Tutorial](https://www.census.gov/content/dam/Census/programs-surveys/acs/guidance/training-presentations/20180614_API.pdf)
- [Variable Names for Census Fields](https://api.census.gov/data.html)
- [`census` Documentation](https://github.com/datamade/census/blob/master/README.rst)
- [Census Geographic Identifiers](https://www.census.gov/geo/reference/geoidentifiers.html)
- [NHGIS Tutorial](https://www.nhgis.org/sites/www.nhgis.org/files/using_the_nhgis_data_finder.pdf)
- [Twitter Developer Docs](https://developer.twitter.com/en/docs/basics/getting-started)
- [Customizing Twitter searches](https://developer.twitter.com/en/docs/tweets/rules-and-filtering/overview/standard-operators)
- [`textblob` Documentation](https://textblob.readthedocs.io/)
- [`tweepy` Documentation](https://tweepy.readthedocs.io/)
