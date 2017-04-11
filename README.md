# python-vis-landscape

Code for my talk at PyCon 2017

## Basic Requirements

Set up with conda:

    $ conda create -n vis-talk python=3.5 jupyter notebook numpy
    $ source activate vis-talk

## Individual Packages

Install [matplotlib](http://matplotlib.org/):

    $ conda install matplotlib

Install [seaborn](https://seaborn.pydata.org/):

    $ conda install seaborn

Install [pandas](http://pandas.pydata.org):

    $ conda install pandas

Install [ggpy](http://yhat.github.io/ggpy/):

    $ pip install ggplot

Install [bokeh](http://bokeh.pydata.org/):

    $ conda install bokeh

Install [plotly](https://plot.ly/python/)

    $ pip install plotly

Install [holoviews](http://holoviews.org/)

    $ conda install --channel conda-forge holoviews

Install [bqplot](http://bqplot.readthedocs.io/):

    $ conda install --channel conda-forge bqplot

Install [altair](http://altair-viz.github.io/):

    $ conda install --channel conda-forge altair

## Others

- Leaning toward domain-specific: Mayavi, GlueViz, YT, yellowbrick, scikit-plot

- JS in the Jupyter notebook: ipyvolume, pythreejs, ipyleaflet

- Large-scale viz: VisPy, Datashader, Vaex, glumpy