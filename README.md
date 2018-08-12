# Dog_Project
*用神经网络预测狗狗品种


项目概述
欢迎进入该卷积神经网络 (CNN) 项目！在此项目中，你将学习如何构建一个管道来处理现实生活中用户提供的图片。给定狗类图片后，你的算法将预测犬类品种。如果你提供的是人类图片，代码将识别出相似的狗类品种。
这个是对这个project大致简历

- Build convolutional neural networks (CNNs) to classify an image into one of 133 dog breeds.
- Made a CNN from scratch with random initialization (44.9761% test accuracy).
- Transferred learning CNN using bottleneck features from ResNet50 pre-trained on ImageNet (81.94% test accuracy).
- Detected either a dog or a clearly visible human face. (On my linkedin)

project improve
1. 模型融合（Model Ensembling）
通过利用一些机器学习中模型融合的技术，如voting、bagging、blending以及staking等，可以显著提高模型的准确率与鲁棒性，且几乎没有风险。你可以参考我整理的机器学习笔记中的Ensemble部分。
2. 更多的数据
对于深度学习（机器学习）任务来说，更多的数据意味着更为丰富的输入空间，可以带来更好的训练效果。我们可以通过数据增强（Data Augmentation）、对抗生成网络（Generative Adversarial Networks）等方式来对数据集进行扩充，同时这种方式也能提升模型的鲁棒性。
3. 更换人脸检测算法
尽管OpenCV工具包非常方便并且高效，Haar级联检测也是一个可以直接使用的强力算法，但是这些算法仍然不能获得很高的准确率，并且需要用户提供正面照片，这带来的一定的不便。所以如果想要获得更好的用户体验和准确率，我们可以尝试一些新的人脸识别算法，如基于深度学习的一些算法。
4. 多目标监测
更进一步，我们可以通过一些先进的目标识别算法，如RCNN、Fast-RCNN、Faster-RCNN或Masked-RCNN等，来完成一张照片中同时出现多个目标的检测任务。
