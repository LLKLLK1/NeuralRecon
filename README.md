# NeuralRecon
使用深度学习方式，对室内三维模型进行重建，得到室内三维模型，但该模型不可以进行量测
# ios app 开发
每个文件的作用 http://t.zoukankan.com/sunflower-lhb-p-4849374.html
# python数值计算，齐次方程组解算
https://blog.csdn.net/u012958850/article/details/125284113
# 镜像源更改
一、Windows更改pip镜像源
(1)在windows文件管理器中,输入 %APPDATA%
(2)会定位到一个新的目录下，在该目录下新建pip文件夹，然后到pip文件夹里面去新建个pip.ini文件
(3)在新建的pip.ini文件中输入以下内容，搞定文件路径：
“C:\Users\Administrator\AppData\Roaming\pip\pip.ini”

[global]
timeout = 6000
index-url = https://pypi.tuna.tsinghua.edu.cn/simple
trusted-host = https://pypi.tuna.tsinghua.edu.cn/simple

二、在linux系统中更新pip源的方式
1、在用户的家目录下面创建名为.pip文件夹
2、在创建好的.pip文件夹中创建名为pip.conf的文件
3、在pip.conf文件中输入以下内容

[global]
timeout = 6000
index-url = https://pypi.tuna.tsinghua.edu.cn/simple
trusted-host = https://pypi.tuna.tsinghua.edu.cn/simple

三、镜像源

1、中国科学技术大学 : https://pypi.mirrors.ustc.edu.cn/simple
2、清华：https://pypi.tuna.tsinghua.edu.cn/simple
3、豆瓣：http://pypi.douban.com/simple/
4、华中理工大学 : http://pypi.hustunique.com/simple
5、山东理工大学 : http://pypi.sdutlinux.org/simple
