
RandAugment for Image Classification for Improved Robustness

Data augmentation is a very useful technique that can help to improve the translational invariance of convolutional neural networks (CNN). RandAugment is a stochastic data augmentation routine for vision data and was proposed in RandAugment: Practical automated data augmentation with a reduced search space. It is composed of strong augmentation transforms like color jitters, Gaussian blurs, saturations, etc. along with more traditional augmentation transforms such as random crops.

These parameters are tuned for a given dataset and a network architecture. The authors of RandAugment also provide pseudocode of RandAugment in the original paper (Figure 2).

Recently, it has been a key component of works like Noisy Student Training and Unsupervised Data Augmentation for Consistency Training. It has been also central to the success of EfficientNets.
