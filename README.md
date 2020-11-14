# PyTorch Dynamic Quantization

```
docker build -f docker/pytorch.Dockerfile --no-cache --tag=pytorch:1.7.0 .
```

```
docker run -it --rm --gpus device=0 -v $(pwd):/mnt pytorch:1.7.0
```

```
python qa.py
```