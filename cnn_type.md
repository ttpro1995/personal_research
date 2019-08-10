### Some Special Convolution



## Dilated Convolution 

### Effect:

Increase reception field.

![increase reception field ](img/cnn_reception_field.png)

Dilated Convolution (with dilated_rate > 1) can replace Convolution (with dilated_rate = 1) + Max Pooling to increase reception field without losing spatial information. 



### How it work 

![dilated cnn animation](img/dilated_cnn.gif)



**Ref** 

* https://towardsdatascience.com/review-dilated-convolution-semantic-segmentation-9d5a5bd768f5
* Multi-Scale Context Aggregation by Dilated Convolutions https://arxiv.org/abs/1511.07122



## Deformable Convolution 

### Effect

![standard convolution vs deformable convolution](img/deformable_vs_cnn.png)



![type of deformable convolution](img/type_of_deformable_cnn.png)

"The receptive field sizes of deformable filters are correlated with object sizes" 

![The receptive field sizes of deformable filters are correlated with object sizes](img/deformable_cnn_activation_unit.png)

### How it work

![deformable convolution](img/deformable_cnn.png)

Ref:

* Deformable Convolutional Networks https://arxiv.org/abs/1703.06211  doi: 10.1109/ICCV.2017.89 

* https://towardsdatascience.com/review-dcn-deformable-convolutional-networks-2nd-runner-up-in-2017-coco-detection-object-14e488efce44