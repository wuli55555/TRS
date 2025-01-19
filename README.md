#  Semi-Supervised Teacher-Reference-Student Architecture for Action Quality Assessment

Our paper is available at [[Paper]](https://arxiv.org/pdf/2303.12332](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/09402.pdf))

## Abstract
 
>Existing action quality assessment~(AQA) methods often require a large number of label annotations for fully supervised learning, which are laborious and expensive. In practice, the labeled data are difficult to obtain because the AQA annotation process requires domain-specific expertise. In this paper, we propose a novel semi-supervised method, which can be utilized for better assessment of the AQA task by exploiting a large amount of unlabeled data and a small portion of labeled data. Differing from the traditional teacher-student network, we propose a teacher-reference-student architecture to learn both unlabeled and labeled data, where the teacher network and the reference network are used to generate pseudo-labels for unlabeled data to supervise the student network. Specifically, the teacher predicts pseudo-labels by capturing high-level features of unlabeled data. The reference network provides adequate supervision of the student network by referring to additional action information. Moreover, we introduce confidence memory to improve the reliability of pseudo-labels by storing the most accurate ever output of the teacher network and reference network. To validate our method, we conduct extensive experiments on three AQA benchmark datasets. Experimental results show that our method achieves significant improvements and outperforms existing semi-supervised AQA methods.

## Overview

![img](img/model.png)
 

## Citation
 
If you find this project useful for your research, please use the following BibTeX entry.

```
@inproceedings{yun2025semi,
  title={Semi-Supervised Teacher-Reference-Student Architecture for Action Quality Assessment},
  author={Yun, Wulian and Qi, Mengshi and Peng, Fei and Ma, Huadong},
  booktitle={European Conference on Computer Vision},
  pages={161--178},
  year={2025},
  organization={Springer}
}

```
