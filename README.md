# ISSC Dataset and Model

**Overlapping Pyramid Vision Transformer Enables Fine-Grained SAR Ship Detection and Classification**

## Overview

Synthetic aperture radar (SAR) supports maritime observation across weather and
illumination conditions, but locating ships alone does not reveal the composition
of a scene. Identifying individual ship types requires distinguishing subtle
target features amid speckle noise, complex coastal backgrounds, dense ship
arrangements, and substantial scale variation.

ISSC brings ship localization and fine-grained recognition into a shared
instance-level setting. The dataset contains 2,764 SAR images and 8,466 annotated
ship instances across five categories, providing bounding boxes and category
labels for the joint study of detection and classification. The accompanying
model combines an overlapping pyramid vision Transformer with direction-aware
multiscale refinement and semantic guidance, connecting global scene information
with local ship features while addressing feature discontinuity and speckle
interference. Evaluations on ISSC and HRSID examine both fine-grained ship analysis
and ship detection. Together, the dataset and model provide a basis for moving
from ship presence and location toward instance-level descriptions of ship types
and their spatial distribution in SAR imagery.

## 中文介绍

合成孔径雷达（SAR）能够在不同天气和光照条件下开展海上观测，但仅定位舰船还不足以揭示场景中的舰船类型构成。在相干斑噪声、复杂近岸背景、密集舰船排列和显著尺度差异的共同影响下，识别单个舰船的类别需要从细微的目标特征中提取有效信息。

ISSC将舰船定位与细粒度识别纳入统一的实例级研究场景。数据集包含2,764幅SAR图像和8,466个标注舰船实例，覆盖五个类别，通过边界框与类别标签支持检测和分类的联合研究。配套模型结合重叠金字塔视觉Transformer、方向感知的多尺度特征细化与语义引导，将全局场景信息与局部舰船特征连接起来，同时应对特征不连续和相干斑干扰。ISSC与HRSID上的评估分别考察细粒度舰船分析和舰船检测能力。数据集与模型共同为SAR图像分析从判断舰船是否存在、位于何处，进一步走向单个舰船类型及其空间分布的实例级描述提供基础。

## Citation

If you use the ISSC dataset in your research, please cite the following paper:

Zequn Sun, Jiajie Ma, Chunning Meng, Lijun Zhao, Lianzhi Huo, Tao Li, Zhiqing Zhang, and Shengjiang Chang.
**Overlapping Pyramid Vision Transformer Enables Fine-Grained SAR Ship Detection and Classification.**
*IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing*, vol. 19, pp. 18999-19016, 2026.
DOI: [10.1109/JSTARS.2026.3695474](https://doi.org/10.1109/JSTARS.2026.3695474).

```bibtex
@article{sun2026overlapping,
  author = {Sun, Zequn and Ma, Jiajie and Meng, Chunning and Zhao, Lijun and Huo, Lianzhi and Li, Tao and Zhang, Zhiqing and Chang, Shengjiang},
  title = {Overlapping Pyramid Vision Transformer Enables Fine-Grained {SAR} Ship Detection and Classification},
  journal = {IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing},
  year = {2026},
  volume = {19},
  pages = {18999--19016},
  doi = {10.1109/JSTARS.2026.3695474}
}
```

##  Dataset download
link: https://pan.baidu.com/s/1-XmOV3p0rqsQr8Hd1S05og code: r526
