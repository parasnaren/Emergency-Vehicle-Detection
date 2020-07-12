# Emergency-Vehicle-Detection
A image detection model that is used to differentiate between regular vehicles and emergency vehicles.

Model is developed using the **Inception-v3** model weights. Custom output layers are trained on the images, by freezing the pre-trained weights. Validation accuracy of **~95%** is achieved.


## Sample Images

**Emergency Vehicles**

![emergency-1](https://user-images.githubusercontent.com/29833297/87247800-a9f65e00-c473-11ea-8110-6a9bf4f215e2.jpg) ![emergency-2](https://user-images.githubusercontent.com/29833297/87247812-b5498980-c473-11ea-881c-c2190d19ecdb.jpg) ![109](https://user-images.githubusercontent.com/29833297/87247940-57697180-c474-11ea-973b-73096c460da3.jpg) ![167](https://user-images.githubusercontent.com/29833297/87247965-7d8f1180-c474-11ea-8c46-0c520d5cca7a.jpg)

**Non Emergency Vehicles**

![non-emergency-1](https://user-images.githubusercontent.com/29833297/87247821-c1354b80-c473-11ea-95a7-d4510a14ba61.jpg) ![non-emergency-1](https://user-images.githubusercontent.com/29833297/87247874-08234100-c474-11ea-939b-c9a8808a86f3.jpg) ![non-emergency-3](https://user-images.githubusercontent.com/29833297/87247906-3274fe80-c474-11ea-9ebb-505581540d28.jpg) ![1399](https://user-images.githubusercontent.com/29833297/87247959-77009a00-c474-11ea-92dc-a431514096bd.jpg)
