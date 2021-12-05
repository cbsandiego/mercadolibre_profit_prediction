# MercadoLibre Stock Prediction
![MERCADOLIBRE](images/ml.jpg)

This is a time series model that allows users to analyze MercadoLibre's financial and user data to grow the company.

---
## Tools

* [Google Colab](https://colab.research.google.com/) - an IDE that allows users to run Jupyter Notebooks in the cloud.

---
## Installations

In terminal, with your conda `dev` environment active, run:

* Install pystan

```python
pip install pystan
```

* Install fbprophet

In terminal, with your conda `dev`  environment active, run:

```python
conda install fbprophet
```

When working with CSV files in Google Colab, user must upload:
```python
from google.colab import files
uploaded = files.upload()
```

To render hvPlots on Google Colab, use following line before each hvPlot:
```python
hv.extension('bokeh')
```
---
## Contributors
Christina San Diego [LinkedIn](https://www.linkedin.com/in/christinabuted)