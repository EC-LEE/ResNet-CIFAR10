# ResNet-CIFAR10
pytorch code for resnet on CIFAR10  

This implementation is for studying the famous paper, "Deep Residual Learning for Image Recognition, Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun (2015)".
 

# Details
I tried to make it the same as described in the paper, but except for these things..<br/>
~~1.  Traning/Valiation dataset spiltting(45k/5k) is not used. I used all 50k data for training.~~<br/>
2.  per-pixcel mean substraction is not used, but instead I nomalized with (0.5,0.5).


# Results
||ResNet-20|ResNet-32|
|------|---|---|
|Test|91.66% (err 8.34%)|92.61% (err 7.39%)|
|Paper|91.25% (err 8.75%)|92.49% (err 7.51%)|

Additional 5k training data would have caused the better result.
![image02](https://user-images.githubusercontent.com/20814465/124218060-6c7f5a80-db34-11eb-9509-545ad54b83a9.png)
