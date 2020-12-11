## Pip

### Upgrading pip
```
pip install --upgrade pip
```

### Installing a package ith pip
```
pip install package_name
```

## Dealing with virtual environments

### Create a virtual environment
```
python -m venv .venv
```

### Freeze a virtuak environment to a requirements.txt file
```
pip freeze > requirements.txt
```

### Load a virtual environment from a requirements.txt file
```
pip install -r requirements.txt
```