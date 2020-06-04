# 音乐特征提取和流派分类

本项目本项目使用Python语言，使用 [GTZAN genre collection](http://opihi.cs.uvic.ca/sound/genres.tar.gz) 数据集，通过 [LibROSA](https://librosa.github.io/librosa/index.html) 音频处理库对数据集进行音频特征提取，再结合numpy, sklearn, keras等库构建神经网络模型对音乐进行分类。

## 环境配置

推荐使用Linux系统，使用conda管理环境，Python为3.7或以上。首先使用conda创建一个Python环境：

```shell
conda create --name mir python=3.7
```

然后安装依赖的库

```shell
pip install librosa numpy sklearn tensorflow keras
```

为了方便开发，这里还使用了VS Code，安装官方的[Python依赖](https://marketplace.visualstudio.com/items?itemName=ms-python.python)，创建JupyterNotebook编写脚本并存储运行结果，当然也可以直接使用JupyterNotebook.