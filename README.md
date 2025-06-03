# Continuous-Time Sequential Recommendation with State Space Models 

<!-- [![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/ss4rec-continuous-time-sequential/sequential-recommendation-on-amazon-sports)](https://paperswithcode.com/sota/sequential-recommendation-on-amazon-sports?p=ss4rec-continuous-time-sequential)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/ss4rec-continuous-time-sequential/sequential-recommendation-on-amazon-video)](https://paperswithcode.com/sota/sequential-recommendation-on-amazon-video?p=ss4rec-continuous-time-sequential)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/ss4rec-continuous-time-sequential/sequential-recommendation-on-movielens-1m)](https://paperswithcode.com/sota/sequential-recommendation-on-movielens-1m?p=ss4rec-continuous-time-sequential)

[Wei Xiao*](https://xiaowei-i.github.io), Huiying Wang*, Qifeng Zhou, Qing Wang

[Paper](https://arxiv.org/abs/2502.08132) -->

![image](https://github.com/Blank141/SS4Rec/blob/main/ss4rec.png)
## Requirements
```
s5-pytorch
mamba-ssm
causal-conv1d
recbole 1.0
torch
```

## Usage
Firstly, replacing recbole.data.sequential_dataset.py with SS4Rec/sequential_dataset.py
```
python run.py
```

### Other Related Projects
The code repository references [RecBole]https://github.com/RUCAIBox/RecBole and [Mamba4Rec]https://github.com/chengkai-liu/Mamba4Rec.
Thanks a lot for their work!

<!-- If you find our work helpful, please kindly cite us
```bibtex
@article{xiao2025ss4rec,
  title={SS4Rec: Continuous-Time Sequential Recommendation with State Space Models},
  author={Xiao, Wei and Wang, Huiying and Zhou, Qifeng and Wang, Qing},
  journal={arXiv preprint arXiv:2502.08132},
  year={2025}
}
``` -->