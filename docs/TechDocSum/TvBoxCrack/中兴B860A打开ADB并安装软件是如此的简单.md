# 中兴B860A打开ADB并安装软件是如此的简单

研究了好多天中兴B860A安装软件提示不能安装的问题，今天偶然看到一片文章写四川电信中兴B860A机顶盒双网看电视的教程，照着他的方法并不能安装软件只是一个双开脚本，正在懊恼的时候，不断翻页看他们的评论，结果眼睛一亮，看到了为什么我们这么多人照着网上教程就是不能随意安装软件的秘密，好吧，废话说了一大堆，现在我就来教教你们，而且本人亲测，绝对有效！
 1.首先你得下载中兴盒子的修改工具STB，这里我用的是7.5.8的汉化版本。
 2.打开中兴盒子的电源，等待启动，进入设置模式（就是按遥控器上边的设置），一般进入设置都要求输入密码，输入1000或6321，我这里地区是四川电信，基本上用的是后边一个密码。
 3.进入后就能看到一些功能菜单，点击左边无线连接（这里连接了有线的，请把有线断开），移到右边打开无线连接，然后选择你的WIFI连接上去（不要告诉我你不会，那我也帮不了你了），连接成功后，点击连接成功的wifi，这里你将看到IP地址，记下（一般就是192.168.1.X或者192.168.0.X这样的，可能还有其他的，这里我就不一一列举了）
 4.回到电脑上，运行STB工具（有的小白同志可能会遇到要输入注册码的问题，自己看STB工具的教程，很简单），输入你记下的IP地址，直接点连接，不出意外很快就连接上了，这个时候好多教程就教我们点击“打开ADB”那个按钮，很多朋友都跟我一样，点了那个按钮后没有变成“关闭ADB”，重要的来了，如果变成了“关闭ADB”的朋友，到此你们就可以用盒子助手安装软件了，以下教程就与你们无关了，没有显示的，请接着看
 5.选择“基本配置信息”这个标签，然后点击“读取配置”，读出来后，点击“导出配置”（为什么要做这步，就是怕接下来我们做的这些，如果出问题后还可以恢复），导出配置后，请往下看
 6.选择“特征配置信息”这个标签，点开后就会显示你这个机器的很多配置（这里千万不要乱改，照我说的做），慢慢看，右边有一栏是“国家-省份-运营商”，把中间那个选择框点开（这里因该是显示你们所在地的省份），往上拉，选择“通用市场”，OK，选择好后，点第5步那个标签，选择“写入配置”
 7.选择“连接和自检”标签，下边有一个按钮叫“重启”，点他，等待盒子重启，然后STB选择“断开”再"连接"，连接上后点“打开ADB”，如果这里显示“关闭ADB”，那么恭喜你，成功了，可以随意安装软件，而且你在盒子里安装的市场APP都可以下载安装任意一款软件了
 好了，教程到这里结束了，如果你成功了，希望你回复一下帖子，你是那个地区的，简短分享下经验，这样大家都可以成功，独乐乐不如众乐乐。
