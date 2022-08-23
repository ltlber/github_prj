# **<u>Anoconda之jupyter notebook学习笔记</u>**

## 一、更换jupyter notebook默认工作目录

通过anaconda proompt命令行窗口输入jupyter notebook进入的目录和通过直接点击jupyter notebook图标进入的工作目录，如果要修改的话，是需要各自单独修改的。

![image-20220823223625405](C:\Users\lt\AppData\Roaming\Typora\typora-user-images\image-20220823223625405.png)



### 1.修改anaconda proompt命令行窗口进入的工作目录

<img src="C:\Users\lt\AppData\Roaming\Typora\typora-user-images\image-20220823222013717.png" alt="image-20220823222013717" style="zoom: 80%;" />

1.1首先通过Anaconda 命令行窗口，输入jupyter notebook --generate-config

在用户目录下生成.jupyter目录下的配置文件jupyter_notebook_config.py

1.2修改配置文件
生成配置文件以后，我们来打开它，用搜索工具找到包含c.NotebookApp.notebook_dir的这一行。然后将''修改为'C:\\\Users\\\lt\\\Desktop\\\Anaconda_Jupyter'，并取消注释。
---不同的系统里面，文件路径的符号是不一样的，windows是双斜杠(\\\\)，linux是反斜杠(/)。

### 2.通过修改jupyter notebook图标属性修改工作目录



![在这里插入图片描述](https://img-blog.csdnimg.cn/20200623165612674.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2N1dGVfYm95Xw==,size_16,color_FFFFFF,t_70)