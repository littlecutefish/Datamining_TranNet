# Augmenting Knowledge Transfer across Graphs

This is the pytorch implementation of _**TransNet**_.

### Datasets
Please download from the original paper listed in our paper.

### demo case:
```
 python ./src/transnet.py --datasets="M2+A1 --finetune_epoch=800 --mu=1e-2 --seed=100 --gnn='gcn' --few_shot=5  --epoch=2000  --batch_size=-1   --finetune_lr=0.01  --pre_finetune=200 --ratio=0.7 --disc='3' --_lambda=0.02  --_lambda=0.02 --_alpha=0.01 --_alpha=0.01  --only=True
```
