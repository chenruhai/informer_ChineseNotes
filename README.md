# informer_ChineseNotes

![Python 3.7](https://img.shields.io/badge/python-3.7-green.svg?style=plastic)
![PyTorch LTS](https://img.shields.io/badge/PyTorch-lts%20-%23EE4C2C.svg?style=plastic)
![cudatoolkit 11.1](https://img.shields.io/badge/cudatoolkit-11.1-green.svg?style=plastic)

[informer_ChineseNotes](https://github.com/chenruhai/informer_ChineseNotes) has added Chinese annotations and some visual additions to the [informer2020](https://github.com/zhouhaoyi/Informer2020) project.


## Requirements
- torch_lts
- pyecharts
- Python 3.7
- matplotlib
- numpy == 1.19.4
- pandas
- scikit_learn
- xlrd
- ....

You can install it directly from the environment pack version file:
```
pip install -r requirements.txt
or
conda env create -f torch_lts.yaml
```

## Requirements

## FAQ
If you run into a problem like `RuntimeError: The size of tensor a (98) must match the size of tensor b (96) at non-singleton dimension 1`, you can check torch version or modify code about `Conv1d` of `TokenEmbedding` in `models/embed.py` as the way of circular padding mode in Conv1d changed in different torch versions.

## Interesting and useful tool recommendations
* [streamlit](https://awesome-streamlit.org/)

## Quick Configuration Environment

### 方法一：
先在Anaconda Powershell Prompt (anaconda3)中创建虚拟环境：
```
conda create -n torch_lts python=3.7
```
然后进入该虚拟环境：
```
activate torch_lts
```
最后使用requirements.txt文件安装环境依赖包：
```
pip install -r requirements.txt

```

### 方法二
直接在Anaconda Powershell Prompt (anaconda3)中使用conda以及yaml文件创建虚拟环境以及安装依赖包：
```
conda env create -f torch_lts.yaml
```

### 在PyCharm中导入虚拟环境：
一定要注意在选择解释器的时候不要再新建虚拟环境了，直接使用已经创建好的虚拟环境：
![image](https://user-images.githubusercontent.com/47185449/176341835-506057a2-479b-414b-a88b-45ff0f1650db.png)


## Thank you
* Thanks to [@zhouhaoyi](https://github.com/zhouhaoyi) open source algorithm paper and code repository.


## reference
* Original repository: [informer2020](https://github.com/zhouhaoyi/Informer2020)
* Zhouhaoyi paper: [Informer：Beyond Efficient Transformer for Long Sequence Time-Series Forecasting (AAAI'21 Best Paper)](https://arxiv.org/abs/2012.07436)

## Tips
数据是网上找来的，已做脱敏处理，如有冒犯到您的请联系e-mail或者从[Tony's blog](https://blog.csdn.net/qq_42658739?type=blog)中私聊我侵删。

## To contact me
* e-mail：ruhai.chen@foxmail.com




