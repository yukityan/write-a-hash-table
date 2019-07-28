[<img src="/.translations/flags/gb.png">](/README.md) [<img src="/.translations/flags/fr.png">](/.translations/fr/README.md)

# 用C实现一个哈希表

[哈希表](https://en.wikipedia.org/wiki/Hash_table) 是最有用的数据结构之一。哈希表快速且易拓展
插入查找和删除,从而使得他们与大量计算机科学问题相关。

在这个教程中, 我们用C实现了基于 [开放寻址法](https://en.wikipedia.org/wiki/Open_addressing), 
[双重哈希法](https://en.wikipedia.org/wiki/Double_hashing) 的哈希表。
通过学习这个教程, 你将会得到:

- 理解哈希这个数据结构的底层原理。
- 能够了解什么时候使用哈希表,什么时候不使用哈希表,同时为什么哈希在有些情况哈希表性能不好。
- 接触新的C代码。

之所以用C语言实现哈希表:

- C语言没有内置的哈希表数据结构。
- C语言是低级语言,你可以从机器角度更加了解工作原理。

这个教程假设你对编程和C语法有一定程度的了解。代码本身是相对直观的, 而且大部分的问题都可以通过
搜索引擎来解决。如果你遇到其他问题, 可以在Github上提交
[Issue](https://github.com/jamesroutley/write-a-hash-table/issues)。

完整的实现大概在200行代码,可以在1到2个小时内完成。

## Contents

1。[简介](/01-introduction)
2。[哈希表 structure](/02-hash-table)
3。[哈希函数](/03-hashing)
4。[处理冲突](/04-collisions)
5。[相关方法](/05-methods)
6。[容量调整](/06-resizing)
6。[附录: 其他处理冲突的办法](/07-appendix)

## Credits

这个教程由 [James Routley](https://twitter.com/james_routley)编写,
博客地址 [routley.io](https://routley.io).
