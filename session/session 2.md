# Session 2

pooling : max pooling, average pooling ---> 简化

padding : zero padding ---> 扩充

stride : 步长



## Convolutional Neural Network

### example

```
Input --> [[Conv -> Relu]*N --> Pool?]*M --> [FC -> Relu]*K --> FC

* FC : Fully-Connected
```





## Recurrent Neural Network

> RNN : 处理有时序关系`Input`的模型

```

outputs        y^(1)        y^(2)        y^(3)       ...
(optional)      ^            ^            ^
          h^(1) |      h^(2) |      h^(2) |
              +---+        +---+        +---+
hidden states |   | ---W-> |   | ---W-> |   | ---W-> ...
              +---+        +---+        +---+
                ^            ^            ^
                |            |            |
input          x^(1)        x^(2)        x^(3)       ...
sequence
(any length)
```


$$
h_t = \sigma(W^{hh}h_{t-1}+W^{hx}x_{[t]})\\
\bar{y}_t = softmax(W^{(S)}h_{t})
$$
















