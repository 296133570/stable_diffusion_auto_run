前言：
本人非科班，纯个人B站大学学习得来，第一次制作超小型GUI，深知欠缺美感和技术力，如有不妥之处，多多包涵。

启动需求：

1、需要结合秋葉大佬的启动器[整合包]。（其他启动器可以联系我，做变版）

2、需要在A绘世启动器.exe的原目录下存放两个文件，一个是web driver，另一个是表格。

①地址为X:\sd-webui-aki\sd-webui-aki-v4.8 下

如下图所示
![image](https://github.com/user-attachments/assets/8eec0c14-2bc3-47fe-89a3-4ba1f75a523d)

②该文件夹还需要放 chromedriver.exe。本软件暂时只支持谷歌游览器，请下载相对应的版本。

（1）检查谷歌浏览器的版本：浏览器地址栏输入: chrome://version
（2）下载ChromeDriver时一定要对应好自己的浏览器版本，下载链接：https://registry.npmmirror.com/binary.html?path=chromedriver/ 
（3）将下载好的chromedriver保存至上述目录中：

③ 文件夹还需要放入mo.xls。示例表格也已经上传，请不要修改文件名字
3、软件有许多鸡肋按钮，今后的会进行优化
4、在正式启动前请确保，个人电脑能正常运行秋葉大佬的启动器，先正常跑一次图。
5、配置不高的情况容易死机，在另一台i7-9750H+1660ti的电脑测试中，运行中切换SDXL大模型三次均失败，原因在于加载模型时间超过程序等待时间。建议配置配置不高的用户不要使用在任务列表里面添加大模型任务。
6、软件中使用的部分图片来自网上，部分图片来自本人AI绘画，若有侵权，务必联系删除。

使用方法，请看视频：

https://www.bilibili.com/video/BV17vYkedEwu/




其中任务列表上限是100个
注意：
1、删除任务，再进行删除，需要按照新的数量 从上到下进行删除
2、预设库里的删除预设，暂时无用（对应其他版本设计），直接在mo.xls 里修改即可。
如果出现了BUG 或者其他问题可以留言给我
