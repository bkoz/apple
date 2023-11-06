# Pytorch on Apple Silicon

[Pytorch installation for Apple Silicon](https://developer.apple.com/metal/pytorch/)

```
pip3 install -U --pre torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/nightly/cpu
````
Testing
```
python -m torch.utils.collect_env
```
```
python 02-optimization_tutorial.py
```

Model|Training Time|Inference Time|Accuracy
-----|-------------|--------------|--------
Macbook Air M1 16Gi| 26.373s | | 71.3%
MacMini M1 8GB | |  |
Macbook Air M2 8GB |         | |
iMac M3 16GB | | |

