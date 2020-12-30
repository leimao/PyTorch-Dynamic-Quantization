# PyTorch Dynamic Quantization

## Introduction

PyTorch dynamic quantization example for BERT-QA.

## Usages

### Build Docker Image

```
$ docker build -f docker/pytorch.Dockerfile --no-cache --tag=pytorch:1.7.0 .
```

### Run Docker Container

```
$ docker run -it --rm --gpus device=0 -v $(pwd):/mnt pytorch:1.7.0
```

### Run BERT-QA

```
$ python qa.py
```

## References

* [PyTorch Dynamic Quantization](https://leimao.github.io/blog/PyTorch-Dynamic-Quantization/)
* [Quantization for Neural Networks](https://leimao.github.io/article/Neural-Networks-Quantization/)