# MAPAL
 Python library for mapping features and properties of alloys over compositional spaces

### Create wheel package for distribution & installation

```
python3 setup.py sdist bdist_wheel && rm -r mapal.egg-info build
```

This creates a dist directory with the wheel file. It also removes the egg-info and build directories to clean up the working directory.

### Install the mapal package

```
pip install dist/mapal-1.0-py3-none-any.whl
```

