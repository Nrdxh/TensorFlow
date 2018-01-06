[TensorFlow Official Website](http://www.tensorflow.org) 
<br>（请参照官网的最新版本，以下以python3.5为例）
# How to install TensorFlow on Windows
1. Install *Anaconda3-4.2.0-Windows-x86_64.exe* (python 3.5)
<br>https://repo.continuum.io/archive/index.html
<br>https://mirror.tuna.tsinghua.edu.cn/help/anaconda/

- 在安装*anaconda*过程中需要勾选一下两个选项
> - Add anconda to my PATH environment variable
> - Register Anconda as my default Python 3.5

![](https://github.com/Nrdxh/TensorFlow/blob/master/Install/image/anaconda-install.png?raw=true)

2. Install *TensorFlow*
> - Cmd运行语句conda
> - Cmd运行python --version查看对应的python版本

<br>![](https://github.com/Nrdxh/TensorFlow/blob/master/Install/image/python.jpg?raw=true)

> - Cmd输入pip install tensorflow进行tensorflow的安装
> - 在Cmd中进入python输入import tensorflow as tf，如果未报错，即tensorflow安装成功

# Test applet
```python
import tensorflow as tf
a = tf.constant('hello TF')
sess = tf.Session()
print(sess.run(a))
```

<br>![](https://github.com/Nrdxh/TensorFlow/blob/master/Install/image/run.jpg?raw=true)

### Result
<br>![](https://github.com/Nrdxh/TensorFlow/blob/master/Install/image/result.jpg?raw=true)
