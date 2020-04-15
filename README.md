# Some tools for H2 research.

## To Start in Conda environment with environment.yml

A Binder-compatible repo with an `environment.yml` file.

Access this Binder by clicking the blue badge above or at the following URL:

https://mybinder.org/v2/gh/timostravels/H2/master?filepath=interpolate.ipynb
https://mybinder.org/v2/gh/timostravels/H2/master?filepath=BT-properties20200415.ipynb

### Notes
The `environment.yml` lists all Python libraries on which your notebooks
depend (only these ones will be available), specified as though they were created using the following `conda` commands:

```
source activate example-environment
conda env export --no-builds -f environment.yml
```

### Sources
 - https://github.com/binder-examples/conda
