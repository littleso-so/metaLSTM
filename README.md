<p align="center"><img width="100%" src="images/catnlp_logo.png" /></p>

--------------------------------------------------------------------------------

# metaLSTM

Meta Learning for LSTM

## 1 参考资料

- [x] [(1) pytorch_workplace/rnn](https://github.com/DingKe/pytorch_workplace/tree/master/rnn)
- [x] [(2) Pytorch Doc](http://pytorch.org/docs/0.3.1/)
- [x] [(3) HyperNetworks](https://arxiv.org/pdf/1609.09106.pdf)
- [x] [(4) supercell](https://github.com/hardmaru/supercell)
- [x] [(5) Meta Multi-Task Learning for Sequence Modeling](https://arxiv.org/pdf/1802.08969.pdf)
- [x] [(6) Optimization As a Model For Few-Shot Learning ](https://openreview.net/pdf?id=rJY0-Kcll)

## 2 环境

```
pip install -r requirements.txt
```

## 3 实验

### 3.1 测试集MNIST

[MNIST官网](http://yann.lecun.com/exdb/mnist/)
MNIST是一个手写数字数据集，训练集有60，000个例子，测试集有10，000个例子。

#### 3.1.1 标准RNN和RNN

- [x] 实验结果

<p align="center"><img width="100%" src="images/base_RNN_MNIST.PNG" /></p>

#### 3.1.2 标准LSTM和LSTM

<p align="center"><img width="100%" src="images/base_LSTM_MNIST.PNG" /></p>

## 4 待完成

- ~~metaRNNs~~
- ~~简单测试RNNs和MetaRNNs~~
- ~~在MNIST上测试RNNs~~
- 在MNIST上测试MetaRNNs
- 在NER上测试RNNs
- 在NER上测试MetaRNNs
- 双向RNNs和双向MetaRNNs
- Normalization(Batch, Layer, Dropout)
- Attention