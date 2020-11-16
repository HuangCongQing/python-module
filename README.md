# python-module
python直接install安装不了一些python包，下载的whl文件集合

## 已迁徙至：https://github.com/HuangCongQing/python-libraries

### whl文件集合

#### python35

* [numpy](./python3/numpy-1.13.3+mkl-cp35-cp35m-win_amd64.whl)
* [scipy](./python3/scipy-1.0.0rc1-cp35-cp35m-win_amd64.whl)
* [xgboost](./python3/xgboost-0.6-cp35-cp35m-win_amd64.whl)
* [matplotlib](./python3/matplotlib-1.5.0-cp35-none-win_amd64.whl)
* [wordcloud](./python3/wordcloud-1.4.1-cp35-cp35m-win_amd64.whl)

#### python2





### 下载库文件

如果是python2(python2.exe) 
`python2 -m pip install 库名`

如果是python3（python3.exe） 
`python3 -m pip install 库名`

如果不能下载报错，尝试下面两种方式

### 其他下载库文件两种方式

#### 一、下载whl文件方式

1. 命令行执行
`pip install wheel `

2. 下载相应版本的lxml后缀为.whl的文件
www.lfd.uci.edu/~gohlke/pythonlibs/

3. 安装

到包含`.whl`的文件夹下，打开命令行窗口
命令行执行

`pip install 文件名.whl`

完成



#### 二、下载库文件安装压缩包

1. 下载对应库文件的压缩包

2. 将压缩包解压到对应位置

3. 安装（解压文件夹里有setup.py）

执行
`python setup.py install`

安装完成





