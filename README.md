# Fashion MNIST Classification 
## Environments
Python: 3.6  
PyTorch: 1.1  
  
## Dataset  
[Fashion MNIST](https://github.com/zalandoresearch/fashion-mnist)

## Reference  
### Model  
[CondenseNet](https://github.com/ShichenLiu/CondenseNet)  
### Augmentation  
[Random Erasing](https://github.com/zhunzhong07/Random-Erasing)  
  
## Performance  
Environment: CPU - Intel® Core™ i7-7700HQ CPU @ 2.80GHz × 8, GPU - GeForce GTX 1060/PCIe/SSE2  
| | Resnet18 | MobileNet v2 | CondenseNet | CondenseNet + Random Erasing |  
| :---: | :---: | :---: | :---: | :---: |  
| Parameters | 11M | 2M | 0.2M | 0.2M |  
| Accuracy |  | 90.04% | 92.80% | 93.88% |  
| Time(ms) |  | 5.4 | 16.7 | 18.3 |  
