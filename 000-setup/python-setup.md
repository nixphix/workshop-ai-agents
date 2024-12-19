## Create python environment

```sh
brew instal miniconda
conda create -n sentinel python=3.12
conda init
```

## Activate enviroment and install dependencies

```sh
conda activate sentinel
pip install -r dev.txt
```

## Add conda environment to jupyter

```sh
python -m ipykernel install --user --name=sentinel
```
