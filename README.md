# python-financial-research

Notebooks con pruebas/research sobre temas financieros

| Fecha creación | Título | Descripción |
| ------------- | ------------- | ------------- |
| 18/11/2019  | **[Estacionalidad NGAS](notebooks/Estacionalidad%20NGAS.ipynb)** | Análisis estacional NGAS usando [facebook prophet](https://facebook.github.io/prophet/) |
| 20/11/2019  | **[MT5 1m bars](notebooks/MT5%201m%20bars.ipynb)** | Construcción al vuelo de series OHLCV partiendo de velas 1m exportadas de MT5 |
| 22/11/2019  | **[Using d-tale](notebooks/Using%20d-tale.ipynb)** | Análisis interactivo de datasets usando [d-tale](https://github.com/manahl/dtale) |
| 22/11/2019  | **[Yahoo Finance - Market Data](notebooks/Yahoo%20Finance%20-%20Market%20Data.ipynb)** | Descarga de market data de Yahoo Finance usando la librería [yfinance](https://github.com/ranaroussi/yfinance) |
| 22/11/2019  | **[pandas-datareader - Market Data](notebooks/pandas-datareader%20-%20Market%20Data.ipynb)** | Descarga de market data usando la librería [pandas-datareader](https://github.com/pydata/pandas-datareader) |

## Levantar jupyter

```bash
workon financialresearch && \
cd ~/Repos/workspace_github/python-financial-research/notebooks && \
jupyter notebook
```

## Crear env y kernel jupyter

```bash
mkvirualenv -p python3 financialresearch
cd ~/Repos/workspace_github/python-financial-research
pip install -r requirements.txt
python -m ipykernel install --user --name financialresearch --display-name "Python 3 (financialresearch)"
```
