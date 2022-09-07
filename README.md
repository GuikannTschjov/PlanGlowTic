# 遍荧黑体 — PlanGlowTic

[遍黑体](https://github.com/Fitzgerald-Porthmouth-Koenigsegg/Plangothic)与[未来荧黑](https://github.com/welai/glow-sans)的缝合。就是把遍黑体机械压缩到80%再用[字体缝合器](https://github.com/nowar-fonts/Warcraft-Font-Merger)和未来荧黑最窄体缝合起来而已。

和遍黑体（截至2022/09/06）一样，可以显示扩展FGH区所有汉字、BCD区部分汉字。

![亮点：𫙉𰃙𱙂](https://raw.githubusercontent.com/GuikannTschjov/PlanGlowTic/main/PlanGlowTic.png)

自用。

## 版本

有两个版本：

1. 一个缝了[明喃黑体](https://www.hannom-rcv.org/font.html#e)的版本。明喃黑体来自不可商用的方正兰亭黑（a.k.a 微软雅黑），因此整个字体都不可商用。
2. 一个缝了一点[Noto Unicode](https://www.bilibili.com/read/cv8805564)的版本，的版本。无法显示常见喃字（罕见的倒是能显示）。所有字体都源自思源黑体，也使用SIL Open Font License 1.1发布。

## 问题

* 由于字体的65536字形限制，无法显示谚文音节。但却能用OpenType特效显示古谚文和真动态组字谚文。
* 因为是机械压缩，有些字竖画比较细。本来还可以用FontCreator的加粗功能横向加粗的。可是遍黑体的笔画是拆开的，无论直接加粗还是合并字形都会出BUG。

## 备考

有个基于未来荧黑的[寒蝉高黑体](https://github.com/Warren2060/Chill-G-Sans)，对未来荧黑进行了手动调整。要不是结合了旧字形，和遍黑体风格不兼容，我就缝进来了。
