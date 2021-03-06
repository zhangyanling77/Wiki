---
title: 计算机早期历史 | 书香讲 CS 之一
date: 2019-08-05
authors:
  - demongodYY
categories:
  - Article
tags:
  - computer
  - science
  - history

original: https://chinese.freecodecamp.org/news/computer-science-history-by-shu-xiang-part-one-early-history/
thumbnail: https://chinese.freecodecamp.org/news/content/images/size/w2000/2019/08/rdn_552b25bca3bda.jpg
toc: true
---

## 手动计算设备

有记载中，人们最早使用的的计算设备是——算盘。

最早的算盘大约在公元前 2500 年，发明于美索不达米亚。由于当时的社会规模已经远远超出了人们的心算能力（比手指脚趾加一起还多），因此需要帮助计算加减，并且能存储计算状态的手动计算器。

<figure>
{% asset_img 27hfx8krdlb.png %}
    <figcaption>算盘计数：6302715408</figcaption>
</figure>

<!-- more -->

随着社会的发展，人们还发明了各种计算工具：

<figure>
{% asset_img 1bcc51hlx0n.png %}
    <figcaption>星盘，用于在海上计算维度</figcaption>
</figure>

<figure>
{% asset_img 22vqi0zev05.png %}
    <figcaption>计算尺，用于帮助计算乘除法</figcaption>
</figure>

<figure>
{% asset_img 1fx3hhli7f2.png %}
    <figcaption>日晷，用于计算潮汐，天体运动或计时</figcaption>
</figure>

## Computer

最早的 Computer 出现于 1613 年，是一种**职业**，专指负责计算的人。**“Computer”**们会借助一些工具来帮助计算，但主要还是靠人力。

<figure>
{% asset_img 53o0pskr4d.png %}
    <figcaption>“computer”们在工作</figcaption>
</figure>

直到某一天，戈特弗里德·莱布尼茨说：“让优秀的人浪费时间算数简直侮辱尊严，文盲用机器能算得一样准”，于是他发明了**步进计算器。**
步进计算器有一串齿轮，每个齿轮 10 个齿，代表 0-9，每次超过 9 就让前面的进一位，减法时反向运动。经过巧妙的设计，可以方便地进行多次加减法，来完成乘法和除法。

<figure>
{% asset_img 8as1px5pjn.png %}
    <figcaption>莱布尼茨步进计算器</figcaption>
</figure>

通过机械化的计算器，大大简化了计算器的操作方式，降低了计算人员的学习成本。但是这种计算器计算较大的数字时，依然很费时间，往往一次计算要耗时几个小时到几天不等。另外因为造价高昂，因此并没有得到足够的重视。

## 计算表

为了快速进行更为复杂的计算（例如指数，对数，三角函数等），人们将计算好的结果提前算好，并制成计算表方便查询。

在军事中，因为经常需要更为快速，精准的机选，计算表的方式得到了广泛的运用。例如在炮兵中，炮手发射的炮弹会因为风力，温度，大气压等等环境因素的变化而影响射程，而很难打中目标。根据使用射程表，通过当前的环境因素和射程，来快速计算出当前应当设置的炮的仰角，大大提高了命中率。

<figure>
{% asset_img 1wirisxlm5n.png %}
    <figcaption>拿破仑军队中的炮兵计算表</figcaption>
</figure>

**但是**，如果更换了新的火炮或者炮弹，对应的计算表都需要重新计算，依然会非常耗费人力和时间。

## 分析机

“随着知识的增长和新工具的诞生，人工劳力会越来越少。”

Charles Babbage 认为通过机器应该可以自己完成通用的计算过程，并于 1837 年设计出了**分析机**，可以自动运算一系列运算操作。

Ada Lovelace 为分析机写了假象的程序，并预言：“未来会诞生一门全新的，强大的，专为分析所用的语言“（计算机程序雏形）。

因为设计理念过于超前，分析机的制作成本过高，导致这个设备并没有真正制造出来。但是人们通常认为 Charles Babbage 是通用计算机之父，而 Ada Lovelace 是第一个程序员。

<figure>
{% asset_img blgq60nefm8.png %}
    <figcaption>伦敦科学馆的分析机复制品</figcaption>
</figure>

## 电动计算器

19 世纪末，计算设备往往用于科学或者工程等特定领域。但是随着大量移民导致地人口增长，美国政府在 1890 年的人口普查中却遇到了问题。

美国宪法规定每 10 年进行一次人口普查，统计各项数据，用于分配联邦资金等等。然而在 1890 年需要进行普查的时候，发现根据当时人口数量，统计计算各项数据需要 13 年之久！还没统计计算完就需要进行下一次普查了！

美国政府找到了 Herman Hollerith，发明了电动机械计算器。这个计算器采用传统步进计算器的方式进行计数，却将其他用于操作的结构用电动设备连接了起来。通过插入打孔的卡片，来控制电路系统，从而代替人力操作来完成统计和计算。

<figure>
{% asset_img 14ahpxemqh0.png %}
    <figcaption>打孔计算器</figcaption>
</figure>

<figure>
{% asset_img 2ie5bez0f1c.png %}
    <figcaption>打孔卡</figcaption>
</figure>

这种计算器的运行速度大概是手动速度的 10 倍，并在人口普查中为美国政府节省了大约 500 万美金的开支。

这个成绩，使得越来越多的公司意识到打卡计算器的优势。于是，Hollerith 干脆成立了打卡机器公司，并在 1924 年与其他机械制造商合并，改名成为了 **IBM（**国际商用机器公司**）**。

## 之后

1900 年代中叶，随着人口爆炸式增长以及贸易的兴起，对数据的计算量大大增加。但是机械计算器在长期运作中造成的磨损，而产生的的计算错误以及成本提高问题越来越严重。人们迫切需求更快更灵活的工具处理大量的数据，这为电子计算机的发展奠定了基础，让咱们下期讨论~
