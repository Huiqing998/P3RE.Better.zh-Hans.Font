# P3RE | 更好的简体中文字体

~~此模组将替换游戏内的简体中文字体，字体为[思源黑体](https://github.com/adobe-fonts/source-han-sans)。~~

将简体中文版游戏所使用的字体修改为[HarmonyOS Sans](https://developer.harmonyos.com/cn/design/resource)，使其阅读起来更清晰易读。

## 使用方法

使用[Reloaded-II](https://github.com/Reloaded-Project/Reloaded-II)来注入游戏，模组还需要前置[Persona 3 Reload Essentials](https://gamebanana.com/mods/494020)。

## 效果图

| 替换前                                         | 替换后                                         |
| ---------------------------------------------- | ---------------------------------------------- |
| ![1707154597357](image/README/1707154597357.png) | ![1707187150312](image/README/1707187150312.png) |
| ![1707154680144](image/README/1707154680144.png) | ![1707188228083](image/README/1707188228083.png) |
| ![1707154896679](image/README/1707154896679.png) | ![1707187159829](image/README/1707187159829.png) |

此模组的替换也不是十全十美的，有些字体还是替换不了，例如右上角的“夜晚”、游戏开头的两个免责声明等等。

我不清楚是硬编码还是其它什么原因，我甚至替换了所有的字体文件但还是那样，所以就算了吧。

| ![1707186559378](image/README/1707186559378.png) | ![1707186567267](image/README/1707186567267.png) | ![1707186573615](image/README/1707186573615.png) |
| ---------------------------------------------- | ---------------------------------------------- | ---------------------------------------------- |

## 替换原理

将想要替换的`.ttf`字体文件重命名为 `DFGBJH8.ufont`来替换文件。

```
UnrealEssentials\P3R\Content\Xrd777\Font\DFGBJH8.ufont
```

字体配置路径，不同的语言目录也不一样，例如简体中文的是 `zh-Hans`文件夹。

```
UnrealEssentials\P3R\Content\L10N\zh-Hans\Xrd777\Font\FSA_FontStyle.uasset
```

## 繁体中文

我不清楚是否和简体中文共用一个字体文件，但我留了一份 `zh-Hant`的配置，要是有人愿意的可以自行测试。

```
UnrealEssentials\P3R\Content\L10N\zh-Hant\Xrd777\Font\FSA_FontStyle.uasset
```
