# EEL5544
Documents and examples for EEL5544 students

## Further reading

* [Real Python](https://realpython.com)
* [Scipy Lecture Notes](http://www.scipy-lectures.org)
* [Numpy Quickstart Tutorial](https://docs.scipy.org/doc/numpy/user/quickstart.html)
* [Pandas Cookbook](https://mybinder.org/v2/gh/jvns/pandas-cookbook/master)
* [Matplotlib Tutorial](https://matplotlib.org/users/tutorials.html)

## Convert notebooks into other formats

The [nbconvert tool](https://github.com/jupyter/nbconvert) converts jupyter
notebooks into multiple *static* formats like html/pdf.  To use nbconvert,
type:

```$ jupyter nbconvert --to <output format> <input notebook>```

in command line where ```<output formant>``` the the desired output format and
```<input notebook>``` is the full filename of the notebook to be converted.  For
example, to convert scipy-stats.ipynb into html, the command 

```$ jupyter nbconvert --to html scipy-stats.ipynb```

will do the job.

A copy of ```pandoc``` is required for conversion.  To install pandoc, run

```$ sudo apt-get install pandoc```

in linux or 

```$ brew install pandoc```

in macOS.
