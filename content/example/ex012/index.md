---
title: 绘制M-T图
date: 2017-07-29
authors:
    - 戴宗辉
    - 王亮
images:
    - mt.png
commands:
    - psxy
---

{{% notice info %}}
数据下载： [mt.dat](/example/ex012/mt.dat)
{{% /notice %}}

M-T图表示地震随时间发展的数量密度和震级大小。M-T图的横轴是时间，纵轴是震级。图中每一条竖线代表一次地震，竖线的位置表示了地震发生的时间，而竖线的长度代表了震级的大小。

绘图效果如下：

{{< figure src="/example/ex012/mt.png" title="M-T图" width="500px">}}

绘图脚本如下：

{{< include-code "plot-mt.sh" bash >}}
