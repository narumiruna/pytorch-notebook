# PyTorch Notebook with CUDA 9.0

## Build

```
$ docker build -t narumi/pytorch-notebook-cuda90 .
```

## Run

```
$ nvidia-docker run -it --rm -p 8888:8888 narumi/pytorch-notebook-cuda90
```