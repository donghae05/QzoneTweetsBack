# 空间说说恢复

**原理：**
qq空间删除的内容是你的说说，而“与我相关”部分的内容没有删除
可以利用“与我相关”的内容来找到自己以前发过的说说（甚至能看到谁评论谁点赞了，发现许多走散的朋友）

**使用方法**

1. 电脑端登录自己的qq空间
2. 按F12或者右键点击“检查”打开审查页面，打开审查页面的网络部分
3. 点击空间里面的”与我相关“，找到这个请求

![image](https://user-images.githubusercontent.com/52132083/179441069-751a4270-ae10-4b53-b8bb-84f46ff3c13f.png)



注意：看一下url链接，需要带有offset参数

1. 在左边那一栏右键点击选中的请求，选择复制→复制为cURL(bash)
2. 打开网页[https://curlconverter.com/#python](https://curlconverter.com/#python)，将复制好的内容丢进输入框
3. 将输出框内除最上面一行和最下面一行的内容复制到params.py文件当中去替换掉原来的内容
4. 运行run.py即可（需利用pip安装必要的库）
5. 生成的data.csv即是所有空间的动态，代码运行完毕之后从下往上即是按时间从前往后浏览自己的说说和动态

**希望你们都能被自己尬死（bushi**

**希望你们都能找回逝去的青春**
