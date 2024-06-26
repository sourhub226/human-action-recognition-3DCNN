# Human Action Recognition using 3D CNN

* Video classification problem on spatiotemporal dimensions
* Used concept of Separable Kernels to split 3D CNN into (2+1)D 
CNN to reduce number of parameters.
* Custom ResNet model with each 2D conv layer replaced by a 
(2+1)D conv layer
* Achieved test accuracy >70%

Dataset: [UCF101 - Action Recognition Data Set](https://www.crcv.ucf.edu/data/UCF101.php)

![image](https://github.com/sourhub226/human-action-recognition-3DCNN/assets/58329492/45faea5b-53fa-4208-bdb9-d09f84344218)

## References

[1] D. Tran, H. Wang, L. Torresani, J. Ray, Y. LeCun, and M. Paluri, ‘A Closer Look at Spatiotemporal Convolutions for Action Recognition’, arXiv [cs.CV]. 2018.

[2] D. Tran, L. Bourdev, R. Fergus, L. Torresani, and M. Paluri, ‘Learning Spatiotemporal Features with 3D Convolutional Networks’, arXiv [cs.CV]. 2015.

[3] C. Feichtenhofer, A. Pinz, and R. P. Wildes, ‘Spatiotemporal Residual Networks for Video Action Recognition’, CoRR, vol. abs/1611.02155, 2016.


