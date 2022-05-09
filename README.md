# <center> EndlessWorld_DarkGemLand</center>

<center><img src="https://github.com/UkokuGemini/UkokuGemini.github.io/blob/MainBranches/img/EndlessWorld_DarkGemLand/ReadMeLogo.png?raw=true" width="400"></center>

## **项目**
![branches](https://badgen.net/github/branches/UkokuGemini/EndlessWorld_DarkGemLand-Release)
![commits](https://badgen.net/github/commits/UkokuGemini/EndlessWorld_DarkGemLand-Release/MainBranches)
![releases](https://badgen.net/github/releases/UkokuGemini/EndlessWorld_DarkGemLand-Release)
![tags](https://badgen.net/github/tags/UkokuGemini/EndlessWorld_DarkGemLand-Release)
![issues](https://badgen.net/github/issues/UkokuGemini/EndlessWorld_DarkGemLand-Release)

![watchers](https://badgen.net/github/watchers/UkokuGemini/EndlessWorld_DarkGemLand-Release)
![stars](https://badgen.net/github/stars/UkokuGemini/EndlessWorld_DarkGemLand-Release)
![assets-dl(Download)](https://badgen.net/github/assets-dl/UkokuGemini/EndlessWorld_DarkGemLand-Release)
![forks](https://badgen.net/github/forks/UkokuGemini/EndlessWorld_DarkGemLand-Release)

## **游戏**

### `描述`

异世界讨伐魔物的游戏.

世界是无尽边际的,充斥着不确定性的.

需要你的智慧和策略.不断成长才有更独特的风景. 


### `世界观`
这是一个建立在异世界的故事。

城镇冈托斯多的周围近期出现了越来越多的魔物，国王颁布讨伐令很久，勇士们争相出城，而你无论战胜还是战败，总能安全归城，成为这座城市不死的神话，城市的人奉你为英雄。
而只有你知道，魔物变异的形势愈发严峻，你不断变强的渴望也越发强烈...

***

## **使用手册**

### `平台&运行库`

- 你至少需要Windows系统下`FrameWork4.7.2`.

  [官方页面](https://dotnet.microsoft.com/zh-cn/download/dotnet-framework/net472) &
  [下载链接](https://dotnet.microsoft.com/zh-cn/download/dotnet-framework/thank-you/net472-web-installer).

 - 游戏使用SQLite数据库.

    需要 `SQLite.Interop.dll ` & `System.Data.SQLite.dll `两个运行库(32位).

    - [官方页面](http://system.data.sqlite.org/index.html/doc/trunk/www/downloads.wiki) (因新版本链接库不支持PassWord关键字,请使用`Ver1.0.112.0`版本链接库.)

    - [我的GitHub拷贝](https://github.com/UkokuGemini/EndlessWorld_DarkGemLand-Release/tree/MainBranches/Dll):([SQLite.Interop.dll](https://github.com/UkokuGemini/EndlessWorld_DarkGemLand-Release/blob/MainBranches/Dll/SQLite.Interop.dll)  & [System.Data.SQLite.dll](https://github.com/UkokuGemini/EndlessWorld_DarkGemLand-Release/blob/MainBranches/Dll/System.Data.SQLite.dll)). - `Ver1.0.112.0`

##### Windows7系统部分文字缺失问题解决方案
 - [更新Windows补丁包Windows6.1-KB2729094-v2-x64](https://support.microsoft.com/zh-cn/topic/%E7%8E%B0%E6%8F%90%E4%BE%9B%E5%AF%B9-windows-7-%E5%92%8C-windows-server-2008-r2-%E4%B8%AD-segoe-ui-%E7%AC%A6%E5%8F%B7%E5%AD%97%E4%BD%93%E7%9A%84%E6%9B%B4%E6%96%B0-0743a473-3afe-e8b2-7c20-54aa430463d6)

***

## **帮助&支持**

### `社区`
欢迎和我交流,访问我的 [Website & Blog](https://ukokugemini.github.io)

### `Fork`
考虑到游戏性和机制，不提倡通过修改源码达到获取游戏资源，加速游戏进程的目的。

源码暂未提供Fork。

如果有好的意见建议，欢迎联系我进行学术交流。

也期待大家可以参与进来，成为开发团队中的一员。

### `License`
[![license](https://badgen.net/github/license/UkokuGemini/EndlessWorld_DarkGemLand-Release)](https://github.com/UkokuGemini/EndlessWorld_DarkGemLand-Release/blob/MainBranches/LICENSE)

***

## **Release**
#### 🔰`稳定发布版本` 
[![stable-release](https://badgen.net/github/release/UkokuGemini/EndlessWorld_DarkGemLand-Release/stable/)](https://github.com/UkokuGemini/EndlessWorld_DarkGemLand-Release/releases/tag/Version4.1.6(%E5%B0%8F%E9%A6%84%E9%A5%A8))
#### 🔰`最新开发版本`
![last-release](https://badgen.net/badge/release/Version4.3.6[2022-5-8])
![last-mommit](https://badgen.net/github/last-commit/UkokuGemini/EndlessWorld_DarkGemLand-Release/MainBranches)
```
Ver4.2.5简要更新日志: 
-   新增叠加技能显示.(显示技能叠加了多少次数)
-   实装技能(战斗技巧/多重箭矢/瞄准/穿透/专注)
-   完成某些Buff技能,暂存,在一定条件触发并消耗的机制
-   消耗性技能战斗日志显示
-   暂停战斗功能
-   更快回城(步数增加距离百分比)
-   冒险途中改变自动冒险选项
-   修改怪物评分系统
```

文件一览

>Application（EndlessWorld_DarkGemLand.exe）
>
>DataBase系统数据库(EndlessWorld_DarkGemLand.SysData.db)
>
>DataBase用户数据库存档(EndlessWorld_DarkGemLand.UserData.db)
>
>AutoUpdate版本更新软件(AutoUpdate-EndlessWorld_DarkGemLand.exe)
>
>SQLite.DLL数据库组件(System.Data.SQLite.dll & SQLite.Interop.dll)<sub>`Ver1.0.112`</sub>

***
## **特别感谢**

特别感谢以下贡献者：

- PSY

- [SUNSHINE](https://github.com/sunshineyg)

***
## **捐赠**

- NoNeed

***
***