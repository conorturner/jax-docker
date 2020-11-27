# jax-docker
GPU and CPU docker images for jaxlib

## Basic Usage

CPU:
```bash
docker run -it conorturner/jax-cpu bash
```

GPU with CUDA 11:
```bash
docker run --runtime nvidia -it conorturner/jax-cuda-11 bash
```
