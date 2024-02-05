# 更好的简体中文字体

此模组将替换游戏内的简体中文字体，字体为[思源黑体](https://github.com/adobe-fonts/source-han-sans)。

## 使用方法

使用[Reloaded-II](https://github.com/Reloaded-Project/Reloaded-II)来注入游戏，模组的前置还需要[Persona 3 Reload Essentials](https://gamebanana.com/mods/494020)。

## 效果图

| 替换前                                         | 替换后                                         |
| ---------------------------------------------- | ---------------------------------------------- |
| ![1707154597357](image/README/1707154597357.png) | ![1707154604313](image/README/1707154604313.png) |
| ![1707154680144](image/README/1707154680144.png) | ![1707154685301](image/README/1707154685301.png) |
| ![1707154896679](image/README/1707154896679.png) | ![1707154900629](image/README/1707154900629.png) |

## 替换原理

将想要替换的字体重命名为 `DFGBJH8.ufont`来替换文件。

```
UnrealEssentials\P3R\Content\Xrd777\Font\DFGBJH8.ufont
```

字体配置路径，不同的语言目录也不一样，例如简体中文的是 `zh-Hans`文件夹。

```
UnrealEssentials\P3R\Content\L10N\zh-Hans\Xrd777\Font\FSA_FontStyle.uasset
```
