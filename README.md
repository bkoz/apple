# Pytorch on Apple Silicon

[Pytorch installation for Apple Silicon](https://developer.apple.com/metal/pytorch/)

```bash
pip3 install -U --pre torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/nightly/cpu
```
Testing
```bash
python -m torch.utils.collect_env
```
```bash
python 02-optimization_tutorial.py
```

Model|Training Time(sec)
-----|-------------
Macbook Air M1 16Gi|26.373 
MacMini M1 8GB     |24.612 
MacbookPro Intel/AMD 8GB |81.245 
Macbook Air M2 8GB       |23.542   
iMac M3 16GB |     18.832       

