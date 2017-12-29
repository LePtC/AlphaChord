AlphaChord
======

AlphaChord 是一个根据无理数序列生成和弦乐曲的程序，用途大概就是帮助萌狸君学习下乐理，以及从随机乐曲中找编曲灵感吧…

AlphaChord is a Mathematica program that generate chord music from irrational number sequence, for helping me learn music theory, and provide possible inspirations for composition.



更新日志
======

### 2017.12.13 v0.1

- 伴奏取[万能和弦 1645](https://www.bilibili.com/video/av17160192/) ，种子应用于主旋律，音符限定在 5 个和弦音上

<details>

<summary>【点击查看 v0.1－v.0.14 开发记录】</summary>

### 2017.12.14 v0.11

- 伴奏加入节奏一分为二和手动设置转位
- 主旋律在一个小节内用相同序列

### 2017.12.14 v0.12

- 主旋律数量翻倍，加入节奏提取表
- 主旋律每换一小节使用不同的节奏表，奇偶小节疏密交错，同样根据种子生成
- 主旋律乐器改成 Flute
- 主旋律每小节的第三段铺满

### 2017.12.14 v0.13

- 主旋律交替使用 Flute 和 Piano
- 伴奏音量小于主旋律音量

### 2017.12.14 v0.14

- 每两小节伴奏用不同节奏，同样根据种子生成
- 伴奏前面铺一节再进主旋律
- 中间和末尾加多音阶连弹点缀

### 2017.12.17 v0.14.1

- 修少量 bug

</details>


0.1X 系列到此完结

- [观看演示视频](http://www.bilibili.com/video/av17271600/)
- [下载 e12.mp3](https://github.com/LePtC/AlphaChord/raw/master/v0.14.1/e12.mp3)




### 2017.12.18

通过哔站认识了 UP 主 [@yxlllc](http://space.bilibili.com/75304607) ，他开发过各种 Mathematica 编曲的工具，他提出的 SMSP（Standard Musical String Protocol）我非常喜欢，这是一种接近于简谱的纯文本编曲方式。我愿意基于 [@yxlllc](https://github.com/yxlllc) 的编译器 重构 AlphaChord 的代码，这将大大方便程序以后开发更复杂的功能。

此后版本的 AlphaChord 依赖于 [@yxlllc](https://github.com/yxlllc) 的编译器

### 2017.12.29 v0.2.0 beta

- 功能和之前一样，只不过改成了基于 SMSP 编译器编程
- 增加了常见和弦进行库



### TODO：

- 更丰富的节奏型
- 伴奏根据主旋律智能转位
- 种子交替应用于伴奏和主旋律
- 主旋律带有一定套路，不完全按随机序列
- 音符扩充到和弦以外的音
