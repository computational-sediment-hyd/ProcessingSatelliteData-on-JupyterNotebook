# ProcessingSatelliteData-on-JupyterNotebook
Processing Satellite Data (ALOS/AVNIR2) on Jupyter Notebook

![demo](/page/top.png)

## Requirement
 - Windows 10
 - Python(Anaconda)

## Python environment

On Anaconda

```Bash
conda create -y -n sate python=3.7
conda activate sate
conda install -y -c conda-forge bokeh=1.4.0
conda install -y -c pyviz geoviews=1.7.0
conda install -y -c pyviz hvplot=0.5.2
conda install -y -c conda-forge rasterio=1.0.21
```

## Original data

ALOS/AVNIR2 ALOS-ORI(in Japanese)
[https://www.eorc.jaxa.jp/ALOS/alos-ori/index.html]

Click "Data" the following URL
[https://www.eorc.jaxa.jp/ALOS/en/alos-ori/data/av2ori.r05/p071D/f2900p3p00.000/ALAV2A200132900-OORIRFU-D071P3-20091027-001.html]

## Jupyter Notebook on nbviewer

 - [Preprocessing](https://nbviewer.jupyter.org/github/computational-sediment-hyd/ProcessingSatelliteData-on-JupyterNotebook/blob/master/preClipAndOverlay.ipynb)
 - [Rendering](https://nbviewer.jupyter.org/github/computational-sediment-hyd/ProcessingSatelliteData-on-JupyterNotebook/blob/master/renderingSatelliteData.ipynb)

## Licence

[MIT](/LICENCE)

## Author

[computational-sediment-hyd](https://github.com/computational-sediment-hyd)

