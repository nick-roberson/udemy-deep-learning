Create Conda Env
```
% conda env create -f pytorch_course_env.yml 

Collecting package metadata (repodata.json): done
Solving environment: failed

ResolvePackageNotFound: 
  - python
  - torchvision
  - matplotlib
  - numpy
  - pandas
  - scikit-learn
  - pip
  - pytorch
  - pillow
```

Activate

```
conda activate pytorchenv
```

For some reason not all deps seem to get installed (and jupyter isnt specified), so may need to just install some manually like this 
```
conda install jupyter
```
when you are inside of the actiated environment.

Start the notebook:
```
jupyter notebook
```