# ConL-Fonts

旨在提供风格统一、美观的泛 Unicode 字体。

## 项目由来

在开发 ConL-IME 项目时，时常苦恼没有一款支持语言
(人造语言) 多的、风格统一的、体积还不大的字体。

+ Noto fonts
    + 优点
        + 开源
        + 涵盖 Unicode 所有区段
        + 字体种类 (Serif, Sans-Serif, Light, Bold...) 齐全
    + 缺点
        + 不支持 (U)CSUR
        + 各语言的字体是分开的，加在一起体积又很大
+ unifont
    + 优点
        + 开源
        + 涵盖 Unicode 所有区段
        + 支持部分 (U)CSUR
        + 单个字体，文件大小在可接受范围
    + 缺点
        + 太丑了，真的丑得不忍直视
        + 某些语言的文字有错误
+ CODE2000
    + 优点
        + 涵盖了 Unicode5.2 绝大多数区段
        + 支持部分 (U)CSUR
        + 单个字体，文件大小在可接受范围
    + 缺点
        + 早已停止开发，得不到后续支持
        + 授权方式不明，可能会侵权
+ ......
+ ......

终于求而不得，决定自己制作一款字体。

## 使用

本项目共分发四款字体，可从 [Github Releases] 中下载。

+ csur
    + 只包含由我个人维护 [CSUR] PUA 符号
+ emoji
    + 只包含 Emoji 表情符号
+ ime-font
    + 只包含 ConL-IME 输入法项目会用到的符号 (是 unifont 的子集)
+ unifont
    + 所有的 Unicode 符号 (含 emoji、csur)

[Github Releases]: https://github.com/aj-ash/ConL-Fonts/releases

## 进度

| 字体名称 | 进度 (%)  |
|:---------|:----------|
| csur     | 00.00%    |
| emoji    | 00.00%    |
| ime-font | 00.00%    |
| unifont  | 00.00%    |

## 相关项目

+ [CSUR]

一个全新的由个人维护的分配 PUA 码位的志愿项目 (不兼容现有的 CSUR、UCSUR... 项目)。

+ [ConL-IME]

ConL-IME 是一款旨在为各种 **人造语言** 提供开箱即用、
简便和各平台输入体验统一的输入法。

[CSUR]: https://github.com/aj-ash/CSUR
[ConL-IME]: https://github.com/aj-ash/ConL-IME
