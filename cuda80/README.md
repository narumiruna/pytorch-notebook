# PyTorch Notebook with CUDA 8.0

## Build

```
$ docker build -t narumi/pytorch-notebook-cuda80 .
```

## Run

```
$ nvidia-docker run -it --rm -p 8888:8888 narumi/pytorch-notebook-cuda80
```