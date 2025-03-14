# SAMResNet
This project documents our approach to image classification
on the CIFAR-10 dataset. We implemented a modified
ResNet architecture enhanced with Squeeze-and-Excitation
(SE) blocks, MixUp data augmentation, and Exponential
Moving Average (EMA). Our final model achieves 92.99%
accuracy on the test set while maintaining a reasonable pa-
rameter count (5.02M). We explore various data augmenta-
tion techniques and inference strategies, demonstrating that a
combination of MixUp during training and test-time augmen-
tation (TTA) significantly enhances model performance. Our
analysis highlights the trade-offs between model complexity,
regularization strength, and performance gains, providing in-
sights for efficient deep learning model design for image clas-
sification tasks on resource-constrained platforms.
