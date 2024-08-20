# Python-Installation-Instraction


教程以最新的Python 3.x版本为基础。

进入Python的官方下载页面
http://www.python.org/download/

![image](https://github.com/user-attachments/assets/179a850e-a25d-463f-8de8-2ba2dd47a121)


出现很多版本的，我们选择版本3.9.0+
![image](https://github.com/user-attachments/assets/0f579360-edcc-4430-bbbd-411cea462d39)


下载完成后点击运行，会出现安装界面，记得勾上
![image](https://github.com/user-attachments/assets/1aef6e89-59bb-4f00-826e-333887bfb29b)


出现这个就安装成功了
![image](https://github.com/user-attachments/assets/5114ffb8-5304-498a-9e1b-49e914296108)



运行Python
安装成功后，打开命令提示符窗口（win+R,在输入cmd回车），敲入python后，会出现两种情况：

情况一：
![image](https://github.com/user-attachments/assets/7c78467b-e285-46d4-adcd-7ca85095b3fc)

出现这个表示python安装成功。你看到提示符 >>> 就表示我们已经在Python交互式环境中了，可以输入任何Python代码，回车后会立刻得到执行结果。现在，输入exit()并回车，就可以退出Python交互式环境（或直接关掉命令行窗口也可以）。

情况二： 得到一个错误：

我这里就不演示了，因为我是安装成功的，我还是演示一下，用错误的pythonn来代替python来用，这样才会提示出错误信息。
![image](https://github.com/user-attachments/assets/3a0d8493-3d8e-4fad-b2c3-a2cb6793af7b)


配置环境变量
     这是因为Windows会根据一个Path的环境变量设定的路径去查找python.exe，如果没找到，就会报错。如果在安装时漏掉了勾选Add Python 3.9 to PATH，那就要手动把python.exe所在的路径添加到Path中。
     如果发现忘记勾选或者是不会设置PATH路径那么，你重新安装一遍记得勾选上Add Python 3.9 to PATH就ok了。(第2步：出现错误的信息一般都是没有配置环境变量导致的)

步骤：右键我的电脑–>选择属性–>选择高级系统设置–>选择右下角的环境变量
![image](https://github.com/user-attachments/assets/ab1cfe73-478e-4f9c-9406-80ca637d76ac)


环境变量主要有用户变量和系统变量，需要设置的环境变量就在这两个变量中
用户变量是将自己的下载的程序可以在cmd命令中使用，把程序的绝对路径写到用户变量中即可使用
![image](https://github.com/user-attachments/assets/6119d395-452c-4ade-bb46-bc667ab6bec6)
![image](https://github.com/user-attachments/assets/697d2cc3-8e80-4dfb-a9c5-5d597d0ebcfb)



5. 测试输出
win+R ，输入cmd 回车
![image](https://github.com/user-attachments/assets/48f22ec2-533c-4f37-ae21-bdb8aba6fe69)

输入python回车，进入python开发环境
![image](https://github.com/user-attachments/assets/d51659c2-5dbe-4405-95f5-b80725705769)

需要注意的是调用函数（打印 等）需要括号，不然会提示
![image](https://github.com/user-attachments/assets/acd8782f-60cd-4ebd-a7bd-3172f7642fb4)
直接在print后面加一段文字来输出的话，需要给文字加上双引号或者单引号。大家发现，print除了打印文字之外，还能输出各种数字、运算结果、比较结果等。你们试着自己print一些别的东西，看看哪些能成功，哪些会失败，有兴趣的话再猜一猜失败的原因。

其实在python命令行下，print是可以省略的，默认就会输出每一次命令的结果。就像这样：![image](https://github.com/user-attachments/assets/232e0904-1e34-49c7-80a9-916f5b28529c)

<br>
<br>

---  

<br>
<br>
**安装开发工具**  
安装PyCharm工具，网上可以下载，很多资源，也有免安装的版本，解压就可以用，我现在演示的是需要进行安装的Pycharm开发工具。
访问PyCharm官方网址http://www.jetbrains.com/pycharm/download/，进入PyCharm的下载页面。
![image](https://github.com/user-attachments/assets/c996289c-005b-4c88-8f2e-0e5aaa7fd628)
![image](https://github.com/user-attachments/assets/20ec346a-284f-4fde-afbf-11d2fa1e38b3)
![image](https://github.com/user-attachments/assets/abf9adef-9db0-4a1d-9c74-ff64a38f5e46)
![image](https://github.com/user-attachments/assets/931b4bd1-8b90-438d-855b-aa0210491954)
![image](https://github.com/user-attachments/assets/14c48b6d-70cd-4feb-b742-a461520387bf)

第一次打开pycharm会显示这个
![image](https://github.com/user-attachments/assets/9d3979f3-6d37-48ef-870f-7fea49c87f7a)
![image](https://github.com/user-attachments/assets/5ec1fe19-277a-4fae-8797-9cf0afcba651)
![image](https://github.com/user-attachments/assets/2ae12717-b94e-4ae2-8892-e1171d6e8dc5)
![image](https://github.com/user-attachments/assets/a86dc016-cb24-4b65-a461-b29215b62475)
![image](https://github.com/user-attachments/assets/0a98e380-b88b-4ed2-88a1-ae6a1d4c0969)
![image](https://github.com/user-attachments/assets/e4b8c730-00ef-4777-a88a-bcb6faa2fe7c)


这样选着会有一个venv文件夹，新建项目时默认是新建一个虚拟环境
![image](https://github.com/user-attachments/assets/86a8647c-5253-4d3b-9f2c-f34626863f78)
![image](https://github.com/user-attachments/assets/3c26b36d-fd9a-4ec8-810a-d0427b201737)


不需要venv的虚拟环境文件夹，选着第二个选项并且设置python的环境，默认是没有的哦
![image](https://github.com/user-attachments/assets/13129c9d-a505-469e-9b5b-d71178719c4a)

点击下一步完成空项目的创建
![image](https://github.com/user-attachments/assets/5458520d-a20d-4a14-9aad-5e0e0ae67bca)

创建一个文件夹用于分类管理
![image](https://github.com/user-attachments/assets/51a1d311-2e4f-4a33-aa7f-671b9fc3b356)

创建一个python文件里面可以写python语句
![image](https://github.com/user-attachments/assets/6b401a25-c01c-46b7-91b6-4235b5dab104)
![image](https://github.com/user-attachments/assets/789a727a-f7a6-473b-9220-95ea2026e40c)


来运行一下python代码，打印第一句python代码，Hello World ！
![image](https://github.com/user-attachments/assets/8c44f8c5-9af8-4f4b-a529-a5486f59c166)

 
 


 
 
————————————————

                            版权声明：本文为博主原创文章，遵循 CC 4.0 BY-SA 版权协议，转载请附上原文出处链接和本声明。
                        
原文链接：https://blog.csdn.net/qq_45502336/article/details/109531599
