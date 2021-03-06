# DenseNet-121 Implementation 

Dataset: Cifar100

<img src="images/DenseNet.png" width = "500" >

<!-- <img src="images/model_architecture.png" width = "500" > -->


Model Evaluation:
---


     
Platform: Colaboratory using GPU.


    Total parameters: 7,145,892
    Trainable parameters: 7,064,420
    Non-trainable parameters: 81,472
   

    Epoch = 10
    Training accuracy: 0.7513
    Training loss    : 0.8085 
    
    Test accuracy    : 0.4152
    Test loss        : 2.8083
    
    Discussion: Clearly overfitting the training data

    
    Epoch = 18 (with early stopping, monitoring accuracy)
    Training accuracy: 0.9171
    Training loss    : 0.2588 
    
    Test accuracy    : 0.3235
    Test loss        : 5.5440
    
    Discussion: Clearly overfitting the training data
    


###  TODO
* [ ] Provide proper documentation in README.md
* [ ] Rerun with cifar100 and present the accuracy and loss for train, validation and test
* [ ] Implement DenseNet-169, DenseNet-201 and DenseNet-264 (report the evaluation respectively)
* [ ] Report the difference in performance between DenseNet and my previous vanilla CNN implemention w.r.t cifar100.
* [ ] Implement with @tf.function to speed things up (both training and testing)
---





Reference:

1. Huang, Gao, et al. “Densely Connected Convolutional Networks.” ArXiv:1608.06993 [Cs], Jan. 2018. arXiv.org, http://arxiv.org/abs/1608.06993.


2. https://github.com/Machine-Learning-Tokyo/CNN-Architectures/tree/master/Implementations/DenseNet


