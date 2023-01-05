# am4894airflowutils

https://packaging.python.org/en/latest/tutorials/packaging-projects/

```
# Generating distribution archives
py -m build
```

```
# Upload to testpypi
py -m twine upload --repository testpypi dist/*
```

```
# Upload to pypi
py -m twine upload --repository pypi dist/*
```