---
layout: wiki
title: Using Jupyter Notebook in Azure
categories: Cloud
description: 简单在Azure云配置jupyter notebook
keywords: jupyter, azure
---
### 本地系统及远程系统均为ubuntu 14.04.

> step 1: 安装 anaconda

> step 2: conda install ipython, conda install ipython-notebook

> step 3: 远程登陆服务器

> step 4: 生成配置文件

```
    $jupyter notebook --generate-config
```

> step 5: 生成密码, 打开ipython，创建一个密文的密码：

```
    In [1]: from notebook.auth import passwd
    In [2]: passwd()
    Enter password:
    Verify password:
    Out[2]: 'sha1:ce23d945972f:34769685a7ccd3d08c84a18c63968a41f1140274'
```
把生成的密文‘sha:ce…’复制下来

> step 6: 修改默认配置文件

```
    $vim ~/.jupyter/jupyter_notebook_config.py进行如下修改：

    c.NotebookApp.ip='*'
    c.NotebookApp.password = u'sha:ce...刚才复制的那个密文'
    c.NotebookApp.open_browser = False
    c.NotebookApp.port =8888 #随便指定一个端口
```

> step 7: 启动jupyter notebook：

```
    $jupyter notebook
```
此时terminal会显示所连到的端口, 设为port1.

> step 8: 建立ssh通道, 并远程访问

    在本地建立一个ssh通道：在本地终端中输入

```
    ssh username@address_of_remote -L127.0.0.1:8888:127.0.0.1:port1
```

便可以在localhost:8888直接访问远程的jupyter了。
