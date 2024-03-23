# Magnetic-Tile-Surface-Defect-Detection-Dataset (MTS3D)

This dataset is collected by Precision Measurement |amp; Vision AI Lab. The magnetic tile dataset was collected from four actual manufacturing production lines.

Samples sourced from different manufacturers exhibit variations in terms of the photography environment (lighting, contrast), shooting angles (background), and sample arrangement (texture direction). Figure below visually demonstrates the discrepancies observed among samples originating from various sources.

![Samples from different manufacturing.](figs/diff_manu.png)

## Cleaning Strategy

During the dataset construction phase, we employed only the most fundamental cleaning strategy, primarily focusing on class filtering, to closely mimic the situations encountered in real industrial production settings. Through this strategy, our aim was to capture and replicate the challenges encountered in actual production scenarios. Our dataset offers significant advantages over currently available publicly accessible datasets in terms of quantity, quality, diversity, and fidelity to real-world scenarios in the industrial domain. By conducting experiments and evaluations using our dataset, we can comprehensively validate the performance of our methods in the task of industrial defect detection. Additionally, the inclusion of data that is not entirely “perfect” adds to the challenge of our task.

## Defect Types

Our dataset comprises six categories of surface defects:

1. impurity,
2. bump,
3. chamfer,
4. multifaceted,
5. under-grinding,
6. crack.

![Defects to be detected.](figs/defects.png)

## Dataset Statistics

Categorical distribution of the source and target domain.

| Defects | crack | bump  | multifaceted | chamfer | impurity | grind | total |
| ------- | ----- | ----- | ------------ | ------- | -------- | ----- | ----- |
| Source  | 5627  | 14917 | 4205         | 708     | 277      | 863   | 21700 |
| Target  | 1104  | 2432  | 1526         | 715     | 453      | 691   | 5927  |

## Citation

> We are actively working to advance the openness of our dataset, and it will be available online soon.

The MTS3D can be downloaded from [here](https://google.com/), and it is for the paper:

<!-- [Style Adaptation module: Enhancing detector robustness to inter-manufactur](https://doi.org/10.1016/j.compind.2024.104084) -->
[Style Adaptation module: Enhancing detector robustness to inter-manufactur](https://authors.elsevier.com/c/1ino~bquFYjLz)

Please cite the paper if you use this dataset:

```
@article{LI2024104084,
title = {Style Adaptation module: Enhancing detector robustness to inter-manufacturer variability in surface defect detection},
journal = {Computers in Industry},
volume = {157-158},
pages = {104084},
year = {2024},
issn = {0166-3615},
doi = {https://doi.org/10.1016/j.compind.2024.104084},
url = {https://www.sciencedirect.com/science/article/pii/S0166361524000125},
author = {Chen Li and Xiakai Pan and Peiyuan Zhu and Shidong Zhu and Chengwei Liao and Haoyang Tian and Xiang Qian and Xiu Li and Xiaohao Wang and Xinghui Li},
keywords = {Surface defect detection, Domain adaptation, Style transfer},
abstract = {In recent years, deep learning-based approaches for industrial surface defect detection have shown great promise. To address the domain shift issue among data from different sources in the industrial domain, we present a novel plug-and-play Style Adaptation (SA) module, which endows the equipped defect detector with the capability to exhibit robustness to diverse styles present within the samples. This module effectively leverages datasets sourced from diverse origins while possessing congruent data types. In contrast to other domain adaptation approaches lacking well-defined domain delineations, the SA module generates representations characterized by distinct practical implications and precise mathematical formulations. Moreover, incorporating attention mechanisms reduces the need for manual intervention, allowing the module to focus autonomously on crucial branches in it. Experimental results demonstrate the superior efficacy of our approach compared to state-of-the-art techniques. Furthermore, an authentic dataset from various manufacturers is publicly available for deep learning research and industrial applications. Access the dataset at: https://github.com/THU-PMVAI/MTS3D}
}
```

<!-- ## Contact

This dataset is for research use only. If you have any problem about this work or dataset, please contact with Prof. Xinghui at li.xinghui@sz.tsinghua.edu.cn. -->
