                                                
                                                
                                                
                                                
                                                
                                                个人主页


super resolution

人脸图像8倍超分辨率

采用ResNet+DenseNet生成网络，采用WGAN-gp对抗网络结构

loss:mse loss,perceptual Loss(VGG),adv-loss

![face_8ffx](https://github.com/high426/high426.github.io/blob/master/face_8x.png)

自然场景中去雾

采用残差网络+wgan-gp网络

loss：mse loss

![dehazy](https://github.com/high426/high426.github.io/blob/master/dehazy.png)

利用图像修复实现人脸去遮挡

canny_feature+encoder_feature --- decoder

![inpainting](https://github.com/high426/high426.github.io/blob/master/inpainting.jpg)
