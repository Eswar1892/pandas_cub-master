
# Conda commands
Create an environment from .yml  
```bash
conda env create -f environment.yml
```

List all the environments 
```bash
conda env list
```



# pytest commands
To run all the test 
```bash
pytest tests/test_dataframe.py
```

To run a specific test 
```bash
pytest tests/test_dataframe.py::TestDataFrameCreation
```


# Python commands
To set ipython kernel: 
```bash
python -m ipykernel install --user --name pandas_cub --display-name "Python (pandas_cub)"
```

# Jupyter commands:
To list all the available jupyter kernels:
```bash
jupyter kernelspec list
```