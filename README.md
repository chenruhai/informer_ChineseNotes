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

## FAQ
If you run into a problem like `RuntimeError: The size of tensor a (98) must match the size of tensor b (96) at non-singleton dimension 1`, you can check torch version or modify code about `Conv1d` of `TokenEmbedding` in `models/embed.py` as the way of circular padding mode in Conv1d changed in different torch versions.

## Interesting and useful tool recommendations
* [streamlit](https://awesome-streamlit.org/)



## Thank you
* Thanks to [@zhouhaoyi](https://github.com/zhouhaoyi) open source algorithm paper and code repository.


## reference
* Original repository: [informer2020](https://github.com/zhouhaoyi/Informer2020)
* Zhouhaoyi paper: [Informer：Beyond Efficient Transformer for Long Sequence Time-Series Forecasting (AAAI'21 Best Paper)](https://arxiv.org/abs/2012.07436)


## To contact me
* e-mail：ruhai.chen@foxmail.com




