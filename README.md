**网上偶然看到一种更高效的判断质数的方法**

首先看一个关于质数分布的规律：


    大于等于5的质数一定和6的倍数相邻。例如5和7，11和13,17和19等等

证明：

令x≥1，将大于等于5的自然数表示如下：

    ······ 6x-1，6x，6x+1，6x+2，6x+3，6x+4，6x+5，6(x+1），6(x+1)+1 ······

可以看到，不在6的倍数两侧，即6x两侧的数为:


    6x+2，6x+3，6x+4，由于2(3x+1)，3(2x+1)，2(3x+2)

所以它们一定不是素数，再除去6x本身


显然，素数要出现只可能出现在6x的相邻两侧。


根据以上规律，判断质数可以6个为单元快进