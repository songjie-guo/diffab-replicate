This repo is to replicate [Diffab](https://github.com/luost26/diffab).

I created a notebook to easily use the model for Designing Antibodies. 

Try it!

<a href="https://colab.research.google.com/drive/1XMr_XzBMCyPfzz5vfceJjkVVJ1TFSeg4?usp=sharing" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

**Table of time taking**

| function    | model | time taking|
| -------- | ------- | ------- |
| design_pdb | codesign_single     | 9min
| design_pdb | codesign_multicdrs  | 45min
| design_pdb | abopt_singlecdr     | 11min
| design_pdb | fixbb               | 45min
| design_pdb | strpred             | 44min
| design_dock | codesign_single     |
| design_dock | codesign_multicdrs  | 1h57min
| design_dock | abopt_singlecdr     |
| design_dock | fixbb               |
| design_dock | strpred             | over 1h

```bibtex
@inproceedings{luo2022antigenspecific,
  title={Antigen-Specific Antibody Design and Optimization with Diffusion-Based Generative Models for Protein Structures},
  author={Shitong Luo and Yufeng Su and Xingang Peng and Sheng Wang and Jian Peng and Jianzhu Ma},
  booktitle={Advances in Neural Information Processing Systems},
  editor={Alice H. Oh and Alekh Agarwal and Danielle Belgrave and Kyunghyun Cho},
  year={2022},
  url={https://openreview.net/forum?id=jSorGn2Tjg}
}
```
