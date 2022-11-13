# ECML_VQRIM

_Automated Cancer Subtyping via Vector Quantization Mutual Information Maximization_

Zheng Chen, Lingwei Zhu, Ziwei Yang, and Takashi Matsubara

Paper link: https://arxiv.org/abs/2206.10801

![alt text](https://github.com/zhengchen3/ECML_VQRIM/files/9996692/pca_brca_lgg.pdf)

![alt text](https://github.com/zhengchen3/ECML_VQRIM/files/9996697/Ablation2.pdf)

![alt text](https://github.com/zhengchen3/ECML_VQRIM/files/9996693/label_flows.pdf)

## Setup

You can install the required dependencies using pip.

```bash
pip install -r requirements.txt
```

If you're using other than CUDA 10.2, you may need to install PyTorch for the proper version of CUDA. See [instructions](https://pytorch.org/get-started/locally/) for more details.

## Citation

If you find our work relevant to your research, please cite:

    @inproceedings{VQRIMECML22,
	author  = {Chen, Zheng and Zhu, Lingwei and Yang, Ziwei and Takashi, Matsubara},
	year    = {2022},
  	title   = {Automated Cancer Subtyping via Vector Quantization Mutual Information Maximization},
  	booktitle={Machine Learning and Knowledge Discovery in Databases, {ECML-PKDD}}, 
  	pages   = {1-16},
	}
