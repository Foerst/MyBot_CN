# MyBot_CN

# 使用说明：

1.安装一个模拟器，哪个在你电脑上流畅安装哪个。然后启动模拟器，安装对应版本的coc, 下载链接： http://update.coc.kunlun.com/?channel=XXX, 
下载时请将xxx替换为对应的版本，比如 baidu、xiaomi、oppo。

2.安装vc和.net环境：分别安装vcredist_X86.exe NDP451-KB2859818-Web.exe。
3.解压Mybot_XXX.zip,点击运行Mybot.run.exe。正常情况下会在bot/Android/安装的coc中出现，然后选择版本，设置一下，点击“开始”即可运行。



技术参考：

1. 无法识别时如何使用Mybot启动coc?

修改方法为 开启编辑Profiles\MyVillage\config.ini
找到game.package和game.class修改為国服版本的包名or类名

2. 如何查看apk包名和启动Activity名？

Cmd中使用aapt命令， ./aapt d badging apk路径


如果改变，要去修改 COCBot/function/android/Distributors.au3文件,并重新编译可执行文件。

3. 如何编译源码得到可执行文件？

https://www.jb51.net/article/14864.htm

4. 多开教程？

https://mybot.run/forums/index.php?/topic/15860-how-to-run-multiple-botshow-to-bot-on-droid4x-nox-and-memu-w-updated-tool/&
