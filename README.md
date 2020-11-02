# label smoothing PyTorch implementation

### INSTALL

```
git clone https://github.com/wangleiofficial/label-smoothing-pytorch.git
```


### USAGE

```
import LabelSmoothingCrossEntropy
criterion = LabelSmoothingCrossEntropy(reduction='sum')
loss = criterion(preds, labels)
```

### LICENSE
[MIT](LICENSE)

### citation
[When Does Label Smoothing Help?](https://arxiv.org/abs/1906.02629)
