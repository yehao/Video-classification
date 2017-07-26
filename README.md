# 视频分类模型整理

## 视频特征
### Handcrafted Feature
- HOG(Histogram of Grident)
- HOF(Histogram of Feature)
- BoF(Bag of Feature)
- Dense Point Trajectory
- Motion Boundary History(MBH)
- Trajectory Fisher Vector

### Spatial-Temporal Feature
- ConvNet Feature
- Stacked OpticalFlow

### Audio Feature
- MFCC

## 视频分类方法
### Trajectory-Based
- Action Recognition by Dense Trajectories. [[Paper](https://hal.inria.fr/inria-00583818/document)] [[Code](https://lear.inrialpes.fr/people/wang/dense_trajectories)]
- Dense trajectories and motion boundary descriptors for action recognition. [[Paper](https://hal.inria.fr/hal-00725627/document)] [[Python Code](https://github.com/anenbergb/CS221_Project)]
### CNN-based
- Large-scale Video Classification with Convolutional Neural Network. [[Project](http://cs.stanford.edu/people/karpathy/deepvideo/)]
- Learning SpatialTemporal Feautres with 3D Convolutional Networks. [[Paper](https://arxiv.org/abs/1412.0767)]
- 3D Convolutional Neural Networks for Human Action Recognition. [[Paper](https://ai2-s2-pdfs.s3.amazonaws.com/3c86/dfdbdf37060d5adcff6c4d7d453ea5a8b08f.pdf)]
- Two-Stream Convolutional Networks for Action Recognition in Videos. [[Paper](https://arxiv.org/abs/1406.2199)][[Code](https://github.com/yjxiong/caffe)]
- Two-Stream SR-CNNs for Action Recognition in Videos. [[Paper](http://www.bmva.org/bmvc/2016/papers/paper108/paper108.pdf)][[Code](https://github.com/yifita/action.sr_cnn)]
- Trajectory-Pooled Deep Convolutional Descriptor. [[Paper](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Wang_Action_Recognition_With_2015_CVPR_paper.pdf)]
- Temporal Segment Networks: Towards Good Practices for Deep Action Recognition. [[Paper](http://arxiv.org/abs/1608.00859)]
## 动作检测
- Finding Action Tubes. [[Paper](https://arxiv.org/abs/1411.6031)] [[Code](https://github.com/gkioxari/ActionTubes)]

## 特征融合
- Real-time Action Recognition with Enhanced Motion Vector CNNs.[[Project](http://zbwglory.github.io/MV-CNN/index.html)]
