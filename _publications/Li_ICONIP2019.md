---
title: "Inpainting with Sketch Reconstruction and Comprehensive Feature Selection"
collection: publications
permalink: /publication/Li_ICONIP2019
excerpt: 'First author, Image inpainting paper in CCF C conference paper.'
date: 2019-12-12
venue: 'International Conference on Neural Information Processing (Novotel Sydney Manly Pacific, Sydney, Australia)'
paperurl: 'https://doi.org/10.1007/978-3-030-36802-9_8'
citation: 'Li, Siyuan, et al. "Inpainting with Sketch Reconstruction and Comprehensive Feature Selection." <i>International Conference on Neural Information Processing</i>. Springer, Cham, 2019.'
---
First author, Image inpainting paper in CCF C conference paper.
Introduction:  
 提出了新的图像修复方案和两个独立的模型来进行图像修复，采用一种深度学习的方法（此处使用预训练模型）来得出残缺图像的边缘图，这种生成的边缘图的边缘连接度更高，并且偏向识别边缘较明显的边缘轮廓，我们称其为概览图（Sketch）。文中把图像修复的过程划分为两个阶段：首先修补残缺图像的概览图，然后通过修复好的概览图和最原始的残缺图像来完成图像的整体修复。因此需建立两个特有的CNN模型，一个模型用来预测完整的概览图，另一种利用预测好的概览图和残缺图像对图片进行着色和整体修复。本文同时在模型的特征处理中加入通道级和空域级的注意力计算，提高了图像的修复质量和修复效果。  
[Download paper here](http://GuardSkill.github.io/files/Li_ICONIP2019.pdf)  
BibTex:  
```
@inproceedings{li2019inpainting,
  title={Inpainting with Sketch Reconstruction and Comprehensive Feature Selection},
  author={Li, Siyuan and Lu, Lu and Li, Zhijing and Xu, Kepeng and Claisse, Matthieu and Yu, Wenxin and He, Gang and Fan, Yibo and Yang, Zhuo},
  booktitle={International Conference on Neural Information Processing},
  pages={65--73},
  year={2019},
  organization={Springer}
}
```