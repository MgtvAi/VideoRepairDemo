# 首届 "马栏山"杯国际音视频算法大赛 画质赛道参赛帮助

## 赛题说明

视频/图像损伤修复是一个比较综合的范畴，包括去伪影/去块/去噪(artifacts reduction, deblocking, denoising)。为帮助选手对赛题快速理解，这里借用了Artifacts Reduction Convolutional Neural Network供选手参考。

# Artifacts Reduction Convolutional Neural Network

This is a Tensorflow implementation of [Artifacts Reduction Convolutional Neural Network](https://arxiv.org/abs/1504.06993).

## Data Processing

* Download [BSDS500](http://www.eecs.berkeley.edu/Research/Projects/CS/vision/grouping/BSR/BSR_bsds500.tgz) dataset, rename the dataset folder as `BSDS500` and put it in `./data` directory

* Download [LIVE1](http://live.ece.utexas.edu/research/quality/release2/databaserelease2.zip) dataset, rename the dataset folder as `databaserelease2` and put it in `./data` directory

* change matlab working directory to `the/repository/path/data/code/source`

* run `extract_data` on matlab console

## Training

* `cd src`

* `python train.py`

## Testing

* `cd src`

* `python test.py`
