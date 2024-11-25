# [Trading Evolved](https://www.followingthetrend.com/trading-evolved/)
[![Trading Evolved](https://m.media-amazon.com/images/I/41Ze8cqKMwL._SX260_.jpg)](https://amzn.to/2SphnLr)

I have created this repo to host the code of this awesome book, to make it easier to lookup the notebooks and i plan to add CoLab integration too, with permission from [Andreas Clenow](https://www.followingthetrend.com/trading-evolved/#comment-94720)


### 环境准备
#### Windows
```bash
# Zipline currently supports Python 2.7, 3.5, and 3.6, and may be installed via either pip or conda.
conda create -n quant python=3.6
# conda remove --name quant --all
conda activate quant

# export CYTHON_LANGUAGE_LEVEL=3
set CYTHON_LANGUAGE_LEVEL=3

pip install zipline


```
#### 保存或者恢复环境
```bash
# 保存
conda env export > quant.yaml
# 恢复
conda env create -f quant.yaml
```
