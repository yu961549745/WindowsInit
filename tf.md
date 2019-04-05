# TensorFlow 安装
查看已有环境
```
conda info -e
```

安装
```
conda install tensorflow-gpu
```

+ PowerShell 会 activate 失败
+ cmd 能成功, 但是不会永久生效
+ 还是装载默认环境吧


测试代码
```python
import tensorflow as tf
tf.__version__
sess=tf.Session()
sess.run(tf.constant(1))
```

其它常用命令
```
conda create -n XXX
conda list
conda activate xxx
conda env remove -n xxx
```
