# CV_MSDS_Assignment3
## Syed Saad Ullah Shah
## 400202

### Sentiment Analysis

#### Abstract
This paper investigates the effectiveness of using different backbone
models, including VGG11, VGG13, VGG19, and MobileNetV2, in com-
bination with the U-Net architecture for semantic segmentation on a city
dataset. The study compares the performance of these models and evalu-
ates their suitability for urban scene understanding. Experimental results
reveal the impact of each backbone model on segmentation accuracy
and computational efficiency, providing valuable insights for selecting
the most appropriate model in urban computer vision applications.

#### Architecture
![alt text](./images/unet.png)

#### Results
![alt text](./images/result_table1.PNG)
![alt text](./images/result_table2.PNG)
![alt text](./images/result_table3.PNG)
![alt text](./images/result_table4.PNG)

#### Traiing and Validation Graphs
##### UNet with VGG-11 Backbone
![alt text](./images/train_and_val_1.png)
![alt text](./images/train_and_val_loss.png)
![alt text](./images/train_and_val_miou.png)

##### UNet with VGG-13 Backbone
![alt text](./images/train_and_val_2.png)
![alt text](./images/train_and_val_loss2.png)
![alt text](./images/train_and_val_miou2.png)

##### UNet with VGG-19 Backbone
![alt text](./images/train_and_val_3.png)
![alt text](./images/train_and_val_loss3.png)
![alt text](./images/train_and_val_miou3.png)

##### UNet with MobiuleNet-V2 Backbone
![alt text](./images/train_and_val_4.png)
![alt text](./images/train_and_val_loss4.png)
![alt text](./images/train_and_val_miou4.png)

#### Testing Results
![alt text](./images/result1.png)
