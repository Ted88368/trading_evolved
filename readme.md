# [Trading Evolved](https://www.followingthetrend.com/trading-evolved/)
[![Trading Evolved](https://m.media-amazon.com/images/I/41Ze8cqKMwL._SX260_.jpg)](https://amzn.to/2SphnLr)

I have created this repo to host the code of this awesome book, to make it easier to lookup the notebooks and i plan to add CoLab integration too, with permission from [Andreas Clenow](https://www.followingthetrend.com/trading-evolved/#comment-94720)


### 环境准备
#### Windows
```bash
# 放弃老版本
# Zipline currently supports Python 2.7, 3.5, and 3.6, and may be installed via either pip or conda.

# 新版本至少要要python3.8
# https://zipline.ml4trading.io/index.html
conda create -n quant python=3.10
# conda remove --name quant --all
conda activate quant

pip install ta-lib



```
#### 保存或者恢复环境
```bash
# 保存
conda env export > quant.yaml
# 恢复
conda env create -f quant.yaml
```


#### 参考资料
+ [《Windows10环境安装Python的Zipline包》](http://www.nohup.cc/article/340/)