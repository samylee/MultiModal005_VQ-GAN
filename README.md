# MultiModal005_VQ-GAN
MultiModal005: VQ-GAN using pytorch

## 使用说明
### 要求
> Python >= 3.6 \
> PyTorch >= 1.10 \
> albumentations == 1.3.0 
### 训练
#### 第一阶段
```shell script
python training_vqgan.py  
```
#### 第二阶段
```shell script
python training_transformer.py  
```
### 生成
```shell script
python sample_transformer.py  
```
## 参考  
https://github.com/dome272/VQGAN-pytorch  
https://blog.csdn.net/samylee  
