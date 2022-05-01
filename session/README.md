# COVID-19 Fake News Detection

> This project is based on the theory and practice of NLP to realize the detection and identification of fake news of the COVID-19

## Environment Preparation

> Colab based on Google Drive.
>
> 相关blog链接：
>
> 1. 环境配置 1：https://zhuanlan.zhihu.com/p/54389036
> 2. 环境配置 2：https://www.cnblogs.com/jiaxin359/p/10234946.html
> 3. GitHub 代码挂载：https://blog.csdn.net/tan123456987321/article/details/104777049/

* 更改`Colab`的字体

  在 Google Chrome --> Settings --> 外观 --> 等宽字体设置为`DejaVu Sans Mono`

* 安装`pytorch`方法：

  ```Python
  !pip3 install torch torchvision torchaudio  # 省事
  ```

* 如果要安装其他的包，框架，或者某一版本的方法和我们在Linux环境下安装几乎没有差别 只需要注意在运行前加上“!”，换计划说你可以把Google Colab看成是一个Linux系统的页面。

* 如果利用GPU不运用自己本地的数据集，而是跑跑框架自带的MNIST这些数据已经是够了的。 如果要跑自己的数据集就需要将自己的数据先上传到Google Colab云盘上面去。

  **注意**：如果是比较大的数据集，将本地数据上传上去就需要安装一个连接本地计算机与Google Colab的一个名为**备份与同步**的软件，这时候你只需要选择本地文件夹，然后点击同步，然后只需等待即可。我本人上传过CoCo，大概花了四五个夜晚吧，因为是去年暑期上传的具体花费的时间也不太记得清楚了。

  如果是比较小的数据集直接点击桌面文件拖到Google Colab界面等待上传即可。