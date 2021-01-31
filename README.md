# Learning-to-Purify-Noisy-Labels-via-Meta-Soft-Label-Corrector
AAAI'21: Learning to Purify Noisy Labels via Meta Soft Label Corrector(Official Pytorch implementation for noisy labels).
This is the code for the paper: Learning to Purify Noisy Labels via Meta Soft Label Corrector
Yichen Wu,Jun Shu Qi Xie,  Qian Zhao, Deyu Meng* To be presented at AAAI 2021.


If you find this code useful in your research then please cite  
```bash
@article{wu2020learning,
  title={Learning to Purify Noisy Labels via Meta Soft Label Corrector},
  author={Wu, Yichen and Shu, Jun and Xie, Qi and Zhao, Qian and Meng, Deyu},
  journal={arXiv preprint arXiv:2008.00627},
  year={2020}
}
``` 


## Setups
The requiring environment is as bellow:  

- Linux 
- Python 3+
- PyTorch 0.4.0 
- Torchvision 0.2.0


## Running Meta-Weight-Net on benchmark datasets (CIFAR-10 and CIFAR-100).
Here is an example:
```bash
python main.py --dataset cifar10 --corruption_type unif(flip2) --corruption_prob 0.6
```

The default network structure is Resnet34



## Acknowledgements
We thank the Pytorch implementation on glc(https://github.com/mmazeika/glc) and learning-to-reweight-examples(https://github.com/danieltan07/learning-to-reweight-examples).


Contact: Yichen Wu (wuyichen.am97@gmail.com); Deyu Meng(dymeng@mail.xjtu.edu.cn).
