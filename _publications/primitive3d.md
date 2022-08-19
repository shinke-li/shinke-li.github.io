---
title: "Primitive3D: 3D Object Dataset Synthesis From Randomly Assembled Primitives"
collection: publications
permalink: /publication/primitive3d
excerpt: ''
date: 2022-06-19
venue: 'CVPR'
paperurl: ''
citation: 'Xinke Li, Henghui Ding, Zekun Tong, Yuwei Wu, Yeow Meng Chee.'
#citation: 'Xinke Li, Henghui Ding, Zekun Tong, Yuwei Wu, Yeow Meng Chee (2022). &quot;Primitive3D: 3D Object Dataset Synthesis From Randomly Assembled Primitives.&quot; <i>Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2022, pp. 15947-15957</i>.'
---
[paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_Primitive3D_3D_Object_Dataset_Synthesis_From_Randomly_Assembled_Primitives_CVPR_2022_paper.pdf) [code](https://github.com/shinke-li/Primtive3D)
## Abstract
Numerous advancements of deep learning can be attributed to access to large-scale and well-annotated datasets. However, such a dataset is prohibitively expensive in 3D computer vision due to the substantial collection cost. To alleviate this issue, we propose a cost-effective method for automatically generating a large amount of 3D objects with annotations. In particular, we synthesize objects simply by assembling multiple random primitives. These objects are thus auto-annotated with part-based labels originating from primitives. This allows us to perform multi-task learning by combining the supervised segmentation with unsupervised reconstruction. Considering the large overhead of learning on the generated dataset, we further propose a dataset distillation strategy to remove redundant samples regarding a target dataset. We conduct extensive experiments for the downstream tasks of 3D object classification. The results indicate that our dataset, together with multi-task pretraining on its annotations, achieves the best performance compared to other commonly used datasets. Further study suggests that our strategy can improve the model performance by pretraining and fine-tuning scheme, especially for a dataset with a small scale. In addition, pretraining with the proposed dataset distillation method can save 86% of the pretraining time with negligible performance degradation. We expect that our attempt provides a new data-centric perspective for training 3D deep models.
