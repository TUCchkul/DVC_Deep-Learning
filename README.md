# DVC_Deep-Learning
### Create a new environments
```bash
conda create --prefix ./env python==3.7 -y
```

### Activate the environments 
```bash
source activate ./env
```
### DVC initialization
```bash
dvc init
```
### Create some empty files 
```bash
mkdir -p src/utils
touch dvc.yaml setup.py
```
### install src
```
pip install -e .
```