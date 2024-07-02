# VFM Knowledge Transfer

This repository provides information about the datasets used in the paper 
"Knowledge Transfer from Vision Foundation Models for Efficient Training of Small Task-specific Models", ICML 2024. 
https://arxiv.org/abs/2311.18237v2

## Contents

The `datasplits` directory contains the training, validation and test subsets of [[ADE20K]](https://groups.csail.mit.edu/vision/datasets/ADE20K/),
[[EuroSAT]](https://github.com/phelber/eurosat), [[HAM10K]](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T),
[[ImageNet]](https://www.image-net.org),and [[Places365]](http://places.csail.mit.edu) datasets used in the paper. 
Each data subset is specified using a text file that consists of the filenames of the images in that subset. 
Please download the actual images directly from the corresponding dataset hosts.

## Citation

If you find this repo useful, please cite the following paper:

```
@inproceedings{knowledgetransfer2024,
  title={Knowledge Transfer from Vision Foundation Models for Efficient Training of Small Task-specific Models},
  author={Raviteja Vemulapalli, Hadi Pouransari, Fartash Faghri, Sachin Mehta, Mehrdad Farajtabar, Mohammad Rastegari, Oncel Tuzel},
  booktitle={International Conference on Machine Learning (ICML)},
  year={2024},
}
```

   