# ResNet-Test
pytorch code for resnet on CIFAR-10  

This implementation for studying the famous paper, "Deep Residual Learning for Image Recognition, Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun" 


# Details
I tried to make it exactly same way described in the paper, except these things.
1.  Traning/Valiation dataset spiltting(45k/5k) is not used
2.  per-pixcel mean substraction is not used, but instead I nomalized with (0.5,0.5)


# Training Result
||ResNet-20|ResNet-32|
|------|---|---|
|Test|91.66% (err 8.34%)|92.61% (err 7.39%)|
|Paper|91.25% (err 8.75%)|92.49% (err 7.51%)|

the training data 5k would have caused the better result.
![image02](https://user-images.githubusercontent.com/20814465/124218060-6c7f5a80-db34-11eb-9509-545ad54b83a9.png)
