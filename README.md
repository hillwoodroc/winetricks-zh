winetricks-zh
===

这是一个 winetricks 的修改版，添加了一些国内常用的 windows 应用支持，以弥补官方版 winetricks 对国内应用支持不足的情况。但最终目的仍然是希望上游能将这些应用添加进去。

##目的

为所有发行版提供无差异化的 windows 安装向导支持。
由于本人精力有限，希望能有更多贡献者能加入到这个小项目，为大家提供更多的国内应用支持。

##目前支持的应用

QQ国际版2.11 
对应的 verb 文件：qqintl.verb

QQ 6.3（高版本 QQ 由于 wine 的 bug 导致无法创建起动器）
对应的 verb 文件：qq.verb

同花顺股票软件
对应的 verb 文件：THS.verb

QQ游戏2013
对应的 verb 文件：QQGame.verb

TM2013 Preview1
对应的 verb 文件：TM2013P1.verb

TM2013 Preview2
对应的 verb 文件：TM2013P2.verb

## 使用方法

###已安装有旧版 winetricks

打开终端进入 verb 文件，运行命令： winetricks <文件名> 

###未安装 winetricks 

将 winetricks-zh 复制到 /usr/bin/ 下，然后在终端中直接运行 winetricks-zh。当然安装有 winetricks 的情况也可以使用这种方法。

## 注意

winetricks 本身不像 crossover 一样带有一个 wine ，所以由于各个发行版自带的 wine 版本的差异，可能会导致使用该工具安装 windows 应用失败或者程序无法正常起动。所以请先想办法把系统自带的 wine 升级到最新版本。
