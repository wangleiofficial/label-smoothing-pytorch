# label smoothing PyTorch implementation

### Requirements

```
pytorch > 1.0
```

### Install

```
git clone https://github.com/wangleiofficial/label-smoothing-pytorch.git
```


### Usage

```
import LabelSmoothingCrossEntropy
criterion = LabelSmoothingCrossEntropy(reduction='sum')
loss = criterion(preds, labels)
```

### License
[MIT](LICENSE)

### Citation
Müller, Rafael, Simon Kornblith, and Geoffrey E. Hinton. "[When does label smoothing help?](https://arxiv.org/abs/1906.02629)." Advances in Neural Information Processing Systems. 2019.
