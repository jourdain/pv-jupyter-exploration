# How to use ParaView in Jupyter

This project aims to explain how to use ParaView within JupyterLab using a local virtual-environment. 

## Local virtual-environment setup

You need to use the same python version as ParaView for your environment. 

| -------- | ------ |
| ParaView | Python |
| -------- | ------ |
| 5.11     | 3.9.x  |
| -------- | ------ |
| 5.12     | 3.10.x |
| -------- | ------ |

```
python3.10 -m venv .venv
source .venv/bin/activate
pip install -U pip
pip install -r ./requirements/pv-5.12.0.txt
```

## Activate your ParaView installation

__On Linux__

```
source activate-linux.sh /path/to/paraview-5.12
```

__On MacOS__

```
source activate-mac.sh /Applications/ParaView-5.12.0-RC2.app
```

## Run Jupyter Lab

```
jupyter lab
```