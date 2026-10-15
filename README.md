
### Overlapping Pyramid Vision Transformer Enables Fine-Grained SAR Ship Detection and Classification

==== 
# # ISSC-dataset-and-model Usage Description
 ------- 
Ship detection from synthetic aperture radar (SAR) images has gained increasing attention recently due to the irreplaceable all-weather imaging capabilities of SAR. However, it remains unclear whether SAR imaging in combination with deep learning is capable of detecting and classifying ships at the instance level, which is hampered by the lack of datasets with multi-class instance-level annotations, the lack of accompanying ship detection methods and the high speckle noise level within SAR imaging data. To tackle these issues, we build a new multi-class instance-level SAR ship dataset ISSC and an efficient multi-scale model for instance-level SAR ship detection and classification. The ISSC dataset has a number of 2764 SAR images and 8466 ship instances, with five common categories. With this high-quality dataset that can reflect the diversity of ship scales, we further propose an efficient network for instance-level SAR ship detection and classification, which uses overlapping pyramid vision Transformer as the model backbone to extract multi-scale continuous feature global information and to suppress the speckle noise in complex background. Subsequently, two neck structures of convolution units are designed to refine the directional features representing various multi-class ships and amplify the local semantic information effect of the cascading process, respectively. As such, our model is a novel global-to-local detection network for SAR images. Experiments on the ISSC dataset and HRSID dataset demonstrate the superior performance of our model, compared to state-of-the-art models. Overall, we have demonstrated the feasibility of combining SAR imaging with the deep learning approach for instance-level ship classification. 
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
