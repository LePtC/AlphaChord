AlphaChord
======

AlphaChord 是一个根据无理数序列生成和弦乐曲的程序，用途大概就是帮助萌狸君学习下乐理，以及从随机乐曲中找编曲灵感吧…

AlphaChord is a Mathematica program that generate chord music from irrational number sequence, for helping me learn music theory, and provide possible inspirations for composition.



更新日志
======

##2017.12.13 v0.1

- 伴奏取[万能和弦 1645](https://www.bilibili.com/video/av17160192/) ，种子应用于主旋律，音符限定在 5 个和弦音上

##2017.12.14 v0.11

- 伴奏加入节奏一分为二和手动设置转位
- 主旋律在一个小节内用相同序列

##2017.12.14 v0.12

- 主旋律数量翻倍，加入节奏提取表
- 主旋律每换一小节使用不同的节奏表，奇偶小节疏密交错，同样根据种子生成
- 主旋律乐器改成 Flute
- 主旋律每小节的第三段铺满

##2017.12.14 v0.13

- 主旋律交替使用 Flute 和 Piano
- 伴奏音量小于主旋律音量

##TODO：

- 更丰富的节奏型
- 伴奏根据主旋律智能转位
- 种子交替应用于伴奏和主旋律
- 主旋律带有一定套路，不完全按随机序列
- 音符扩充到和弦以外的音
