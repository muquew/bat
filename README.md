# bat
快捷bat


[README_EN.md](./README_EN.md)



记录一下bat脚本的快捷打开
![image](./Pic/show.png)
原理是通过把bat脚本放入一个文件夹中并配置环境变量  
然后cmd窗口输入ls展示所有的脚本名以及相关的注释  
![image](./Pic/list.png)
主要是ls.bat脚本  
为了使得ls显示的尽可能整齐  
设置脚本文件的名称长度filenameLength  
以及需要把注释放置第三行并且前缀必须为REM和一个空格（这里是4个字符）  
还需要更改目标文件夹的路径  
