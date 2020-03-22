# Analyzing Covid-19 data via Python/Jupyter

The underlying data is dynamically imported from
[2019 Novel Coronavirus COVID-19 (2019-nCoV) Data Repository by Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19)

# Purpose

The repository contains a Python/Jupyter notebook to import COVID-19 data, to enrich and visualize it.

The current code focuses on deriving the relative daily change (in percentage resp. change rate) as this number needs to be
minimized to prevent COVID-19 turning into more than a global nightmare.

The countries to be analyzed can be configured in the section "Adaptation". For some countries/regions the underlying data 
is further subdivided into provinces/states. The code supports only some of these countries.

The prediction is - of course - just a very wild guess. It is not meant to be really used, I just added it so get a very
rough idea (to myself) which countries are heading to the worst case.

Notebook can be used via:
[Binder Notebook](https://mybinder.org/v2/git/https%3A%2F%2Fgithub.com%2Frpreiss07%2Fcovid19.git/master?filepath=index.ipynb)

# License

The LICENSE covers the direct content of this repository. The data source has its own independent terms of use (see link above)
to be applied on top.

Feel free to use the content of this repository for any humanitarian purpose if you share the idea that we need to work
together to fight COVID-19 - independent from where we come from.





