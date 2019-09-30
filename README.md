# build python interface of c module using swig

## install swig on MacOS
brew install swig

## example

```
swig -python example.i
python setup.py build_ext --inplace
```

## test
```
import example
example.fact(5) #120
```

## reference
https://stackoverflow.com/questions/25882150/python-h-not-found-using-swig-and-anaconda-python
