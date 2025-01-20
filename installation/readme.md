## Section 1: Installation Guide

The first step towards installation is to create a virtual env for the fastAPI.

- Check the python version 
```python --version```
- Install the virtual env package.
```pip install virtualenv```
- Create virtual env.
```python3 -m venv fastapi-env```
- Activate the virtual env.
```source fastapi-env/bin/activate```
- Install fastAPI package.
```pip3 install fastapi```

We also need a server to run fastapi.
- Install UVICORN server package.
```pip3 install uvicorn```
- Check uvicorn version
```uvicorn --version```

Run fastAPI app
```uvicorn main:app```