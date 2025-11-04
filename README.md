# MAPAL
Python library for mapping features and properties of alloys over compositional spaces

<hr />

### Publication details:
[MAPAL: A python library for mapping features and properties of alloys over compositional spaces](https://www.sciencedirect.com/science/article/pii/S0927025625007037)
- **Authors** : [Dishant Beniwal](https://github.com/d-beniwal) [^1], Pratik K. Ray [^1]
- **Journal** : Computational Materials Science
- **DOI** : [10.1016/j.commatsci.2025.114360](https://doi.org/10.1016/j.commatsci.2025.114360)
[^1]: Department of Metallurgical and Materials Engineering, Indian Institute of Technology Ropar, Rupnagar 140001, Punjab, India

<hr />

### TECHNICAL NOTES

The technical notes for MAPAL (with examples) are available as [supplementary material](https://ars.els-cdn.com/content/image/1-s2.0-S0927025625007037-mmc1.pdf) to the published article.

<hr />

### RECOMMENDED INSTALLATION:

The latest stable version of MAPAL can be directly installed using pip

```
pip install mapal
```

<hr />

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

