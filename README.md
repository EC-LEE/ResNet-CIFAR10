# ResNet-CIFAR10
pytorch code for resnet on CIFAR10  

This implementation is for studying the famous paper, "Deep Residual Learning for Image Recognition, Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun (2015)".
 

# Details
I tried to make it the same as described in the paper, but except for these things.<br/>
1.  per-pixcel mean substraction is not used, but instead I nomalized with (0.5,0.5).


# Results
||ResNet-20|ResNet-32|
|------|---|---|
|Test|91.52% (err 8.48%)|92.54% (err 7.46%)|
|Paper|91.25% (err 8.75%)|92.49% (err 7.51%)|

![제목 없음](https://user-images.githubusercontent.com/20814465/124390020-b29b1080-dd24-11eb-99a7-d5b3c7d89d7a.png)
