
## Conda

Install locally from website and then complete the following steps:
1. Create Conda Env `conda env create -f pytorch_course_env.yml`
2. Activate `conda activate pytorchenv`

For some reason not all deps seem to get installed (and jupyter isnt specified), so may need to just install some manually like this 
```
conda install jupyter
```



## Jupyter 
when you are inside of the actiated environment.

Start the notebook:
```
$ jupyter notebook

  ...

[I 2024-02-09 11:54:07.465 ServerApp] Serving notebooks from local directory: /Users/nicholas/Code/udemy/deep_learning
[I 2024-02-09 11:54:07.465 ServerApp] Jupyter Server 2.10.0 is running at:
[I 2024-02-09 11:54:07.465 ServerApp] http://localhost:8888/tree?token=763e6ad9eaa4be396ccaf760a22957de88cdc510f43b840c
[I 2024-02-09 11:54:07.465 ServerApp]     http://127.0.0.1:8888/tree?token=763e6ad9eaa4be396ccaf760a22957de88cdc510f43b840c
[I 2024-02-09 11:54:07.465 ServerApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).
[C 2024-02-09 11:54:07.469 ServerApp] 
    
    To access the server, open this file in a browser:
        file:///Users/nicholas/Library/Jupyter/runtime/jpserver-64611-open.html
    Or copy and paste one of these URLs:
        http://localhost:8888/tree?token=<some uuid>
        http://127.0.0.1:8888/tree?token=<some uuid>
```

## Lessons 

- [x] Crash Course Topics
- [x] PyTorch Basics
- [ ] ANN - Artificial Neural Networks
- [ ] CNN - Convolutional Neural Networks
- [ ] RNN - Recurrent Neural Networks
- [ ] Using GPU
- [ ] NLP with PyTorch