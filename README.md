# MAPAL
Python library for mapping features and properties of alloys over compositional spaces

### Publication details:
[MAPAL: A python library for mapping features and properties of alloys over compositional spaces]()
- **Authors** : [Dishant Beniwal](https://github.com/d-beniwal) [^1], Pratik K. Ray [^1]
- **Journal** : 
- **DOI** : 
[^1]: Department of Metallurgical and Materials Engineering, Indian Institute of Technology Ropar, Rupnagar 140001, Punjab, India


### RECOMMENDED INSTALLATION:

The latest stable version of MAPAL can be directly installed using pip

```
pip install mapal
```

### ALTERNATIVE:

The source code here can be used to create wheel package for distribution & installation. Run the following command in terminal:

```
python setup.py sdist bdist_wheel && rm -r mapal.egg-info build
```

This creates a dist directory with the wheel file. It also removes the egg-info and build directories to clean up the working directory.

Install the mapal package using wheel file by running the below command:

```
pip install dist/mapal-1.0-py3-none-any.whl
```

