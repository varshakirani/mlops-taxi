# mlops-taxi

### Steps to prepare the conda env
```
conda create -n mlops-taxi python=3.8

conda activate mlops-taxi

pip install jupyterlab
pip install ipykernel

python -m ipykernel install --user --name mlops-taxi --display-name "mlops-taxi"
```

### Data

Download data from [NYC taxi dataset](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page) into data folder.

In this repo, we are using 2024-Green taxi trip records