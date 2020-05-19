# PANDA-Challenge
Notebooks and scripts for Prostate Cancer Grade Assessment Challenge (kaggle)

## Task

Classifying whole-slide images of digitized prostate biopsies as not containing cancer (0) or one of six ISUP grades indicating different levels of cancer severity (1 least - 5 most severe). 

## Metric

The quadratically weighted kappa (QWK) is a measure of agreement (or disagreement) between two raters. It varies from 0 (random agreement) to 1 (complete agreement). More information found [here](https://www.kaggle.com/c/prostate-cancer-grade-assessment/overview/evaluation). 

## Models

### A first simple baseline model: QWK = 0.53
1. Downsample slide to 256 x 256
2. Transform with horizontal flip, vertical flip, normalization
3. Feed to ResNet34 pretrained on ImageNet
4. Train for 10 epochs (plan to do more..)
5. Inference 



