---
permalink: /
title: "Welcome To My Home Page"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# About Me

I'm an incoming CS Ph.D. student at [Cornell University](https://www.cornell.edu).
Currently, I'm a senior student in [Turing class](https://cfcs.pku.edu.cn/research/turing_program/introduction1/index.htm) at the [School of Computer Science](https://eecs.pku.edu.cn), [Peking University](https://english.pku.edu.cn). 
I'm interested in Robotics and 3D Vision. 

Previously, I am a research intern at [CCVL](https://ccvl.jhu.edu/team/), supervised by Bloomberg Distinguished Professor [Alan Yuille](https://www.cs.jhu.edu/~ayuille/). Before that, I was a research intern at Hyperplane Lab, 
[Center on Frontiers of Computing Studies](https://cfcs.pku.edu.cn/english/), advised by [Prof. Hao Dong](https://zsdonghao.github.io).
I'm also collaborating with [Dr. Kaichun Mo](https://kaichun-mo.github.io) (NVIDIA) on articulated object manipulation.

You can find my CV here: [Chuanruo Ning's CV](https://tritiumr.github.io/assets/CV.pdf)

Research
======
(\* denotes equal contribution)
- **Part321: Recognizing Object Parts in 3D from a 2D Image Using 1-Shot Annotations**
  * **Under review**
  * **Chuanruo Ning**, Jiawei Peng, Yaoyao Liu, Jiahao Wang, Yining Sun, Alan Yuille, Adam Kortylewski, Angtian Wang
  * We achieve zero-shot object part segmentation that only requires one 3D annotation for part definition. With one 
  training, our framework could directly generalize to any part definition without any adaption. We establish the 3D to 
  3D correspondence for part transfer across meshes and 3D to 2D correspondence for render-and-compare based part detection.

<div align="center">
<img src="https://tritiumr.github.io/assets/picture/corr.png" width = "600" height = "160" title="Few-shot on novel category">
</div>

- **Broadcasting Support Relations Recursively from Local Dynamics for Object Retrieval in Clutters**
  * **RSS 2024**
  * Yitong Li\*, Ruihai Wu\*, Haoran Lu, **Chuanruo Ning**, Yan Shen, Guanqi Zhan, Hao Dong
  *  we study retrieving objects in complicated clutters via a novel method of recursively broadcasting the accurate 
  local dynamics to build a support relation graph of the whole scene, which largely reduces the complexity of the 
  support relation inference and improves the accuracy.
  * [Paper](https://arxiv.org/abs/2406.02283) / Project Page (coming soon)

<div align="center">
<img src="https://tritiumr.github.io/assets/picture/clutter.png" width="650" height="150" title="Support relation broadcasting">
</div>

- **Where2Explore: Few-shot Affordance Learning for Unseen Novel Categories of Articulated Objects**
  * **NeurIPS 2023**
  * **Chuanruo Ning**, Ruihai Wu, Haoran Lu, Kaichun Mo, Hao Dong
  * Explore the cross-category few-shot learning task, where the model is required effectively explores novel categories 
  with minimal interactions on a limited number of instances. Propose ‘Similarity’ to measure semantic similarity between 
  local geometries across different categories. Enable the model to perform few-shot learning on novel categories by 
  discovering uncertain yet important areas.
  * [Paper](https://arxiv.org/abs/2309.07473) / [Project Page](https://tritiumr.github.io/Where2Explore/)

<div align="center">
<img src="https://tritiumr.github.io/assets/picture/w2e.png" width = "600" height = "160" title="Few-shot on novel category">
</div>

- **Learning Environment-Aware Affordance for 3D Articulated Object Manipulation under Occlusion**
  * **NeurIPS 2023**
  * Ruihai Wu\*, Kai Cheng\*, Yan Shen, **Chuanruo Ning**, Guanqi Zhan, Hao Dong
  * We propose an environment-aware affordance framework that incorporates both object-level actionable priors and environment 
  constraints. A novel contrastive affordance learning framework is introduced, which is capable of training on scenes containing 
  a single occluder and generalizing to scenes with complex occluder combinations.
  * [Paper](https://arxiv.org/abs/2309.07510) / [Project Page](https://chengkaiacademycity.github.io/EnvAwareAfford/)

<div align="center">
<img src="https://tritiumr.github.io/assets/picture/env.png" width = "600" height = "120" title="Environment-aware Affordance">
</div>

- **Learning Foresightful Dense Visual Affordance for Deformable Object Manipulation**
  * **ICCV 2023**
  * Ruihai Wu\*, **Chuanruo Ning**\*, Hao Dong
  * We propose to learn dense visual representation for deformable object manipulation
, which reveals the dynamic and kinematic property of deformable objects.
By training in a reversed step-by-step manner, we enable the representation to be aware of 
`value' of states, thus finding the global optimal action for deformable object manipulation tasks. 
  * [Paper](https://arxiv.org/abs/2303.11057) / [Project Page](https://hyperplane-lab.github.io/DeformableAffordance/) / [Video](https://www.youtube.com/watch?v=DiZ9aXjK_PU) / [Video(real-world)](https://www.youtube.com/watch?v=aYneBzwhOGs)

<div align="center">
<img src="https://tritiumr.github.io/assets/picture/deformable.png" width="650" height="150" title="Manipulation demonstration in the real world">
</div>

Talks
=====
Title: Part Detection via Render-and-compare Method \
Date: 2023-8-18 \
Location: Malone Hall, Johns Hopkins University, Baltimore, United States \
[Slides](https://tritiumr.github.io/assets/ppt/Part_Detection.pdf)

Title: Occlusion Reasoning for Manipulation \
Date: 2022-8-4 \
Location: Center on Frontiers of Computing Studies, Beijing, China \
[Slides](https://tritiumr.github.io/assets/ppt/Occlusion_Reasoning.pdf)

Title: In-hand Reorientation \
Date: 2022-2-20 \
Location: Center on Frontiers of Computing Studies, Beijing, China \
[Slides](https://tritiumr.github.io/assets/ppt/In-hand_Reorientation.pdf)

# Services
- Program Committee: Annual AAAI Conference on Artificial Intelligence (AAAI 2024)
- Reviewer: Conference on Computer Vision and Pattern Recognition (CVPR 2024)

Awards and Honors
======
- 2023: Huatai Securities Scholarship
- 2023: Peking University Merit Student
- 2022: John Hopcroft Scholarship
- 2022: Peking University Dean's Scholarship
- 2020: Peking University Freshman Scholarship



