环境：linux--python3.10

## deepwalk

原仓库：https://github.com/phanein/deepwalk.git

源代码中有些库在后面的python版本中改了，在`__main__.py`里面有一个word2vec参数size改为vector_size

本仓库`deepwalk.zip`里面是已经改好的，可以直接下载使用

需要numpy和scipy

安装:

```shell
cd deepwalk
pip install -r requirements.txt
python setup.py install
```

## HERec

`git clone https://github.com/librahu/HERec.git`

源代码有些是python2的print语法，需要改一下

`updatedCode4HERec.zip`里面改好了，可以解压覆盖

程序运行过程见：`生产实习.ipynb`
