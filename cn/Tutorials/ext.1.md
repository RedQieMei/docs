---
category: 
- 教程
---
# ext.1 BepInEX插件

欢迎，勇者！

当你进入具有ext文档分类的教程时，即意味着你已经精通RF的基础+中级MOD制作，开始使用外围与社区Framework来为RF开发社区模组了！

如果你还未学习前面非ext教程，请先暂时离开此处，ext教程要求需要坚实的开发基础

好的进入正言

由于BepInEX插件的开发基本等同于Unity游戏开发且其应用在整个Unity圈里极为广泛，因此此处本文档不作过多赘述，自有比我们解释得更好的人来指路

下面推几个教程自行研习：

- [从0开始教你使用BepInEx制作游戏插件Mod](https://mod.3dmgame.com/wiki/BepInEx)

主家虽然是流氓3DMGAME，但他们MOD组维护的教程确实不错

- [\[BIE\] 基于BepInEx的Mod/插件开发教程](https://nga.178.com/read.php?tid=25006771)

作者B站:[BiliBili](https://space.bilibili.com/1306433)，中文高质量教程

- [BepInEx Docs](https://docs.bepinex.dev/)

官版英文文档

:::tip
因为RF使用的.Net Framework版本为4，因此对于电脑渣的玩家可以选择下载[VS Express 2010 Visual C#](https://visualstudio.microsoft.com/zh-hans/dev-essentials/)（至少，但这个版本仅英文。建议VSE2013起步）编辑器来代替VS Community，前者仅占磁盘空间大约小于300MB

不建议使用VS Code，基于JavaScript开发的它对.Net Solution的开发极其不友好，甚至不如VS Express 2010这个13年前的IDE
:::

:::tip
如果插件要引入外部Assets资源，记得先给assets构建AssetBundles

具体参考：[Github](https://github.com/BepInEx/Il2CppInterop/blob/master/Documentation/Injected-Components-In-Asset-Bundles.md)
:::
