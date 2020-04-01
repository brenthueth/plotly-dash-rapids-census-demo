Plotly-RAPIDS Census 2010 Demo

![](./demo.png)


![](./demo1.png)

# Steps to reproduce

## Running the plotly demo

```bash
cd plotly_demo

conda env create --name plotly_env --file environment.yml
source activate plotly_env

python app-covid.py
```


## Dependencies

- plotly=4.5
- cudf
- dash=1.8
- pandas=0.25.3
- cupy=7.1
- datashader=0.10
- dask-cuda=0.12.0
- dash-daq=0.3.2
- dash_html_components
- gunicorn=20.0
- requests=2.22.0+
- pyproj


## Acknowledgements

- 2010 Population Census and 2018 Population Estimate data used with permission from IPUMS NHGIS, University of Minnesota, [www.nhgis.org](www.nhgis.org) ( not for redistribution )
- Hospital data is from [HIFLD](https://hifld-geoplatform.opendata.arcgis.com/datasets/hospitals) (10/7/2019) and does not contain emergency field hospitals
- COVID-19 data is from the [Johns Hopkins University](https://coronavirus.jhu.edu/) data on [GitHub](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_daily_reports) (updated daily)
- Base map layer provided by [mapbox](https://www.mapbox.com/)
- Dashboard developed with Plot.ly [Dash](https://dash.plotly.com/)
- GPU accelerated with [RAPIDS](https://rapids.ai/) [cudf](https://github.com/rapidsai/cudf) and [cupy](https://cupy.chainer.org/) libraries
- For more information reach out on this [Covid-19 Slack Channel](https://join.slack.com/t/rapids-goai/shared_invite/zt-2qmkjvzl-K3rVHb1rZYuFeczoR9e4EA)
- For source code visit our [GitHub](https://github.com/rapidsai/plotly-dash-rapids-census-demo)
