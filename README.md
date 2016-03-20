Visualising Image Classification Models and Saliency Maps
========

Implementation by Chainer. Original paper is [Deep Inside Convolutional Networks: Visualising Image Classification Models and Saliency Maps](http://arxiv.org/pdf/1312.6034.pdf).

# Requirements

- [Chainer 1.5+](https://github.com/pfnet/chainer) (Neural network framework)
- numpy 1.9+
- OpenCV 2.4+



# Start training

Just run:

```
nohup python scripts/train.py > AlexNet_flic.log 2>&1 < /dev/null &
```
