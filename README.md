# CAJ Samples

These are collected from the issue tracker. Refer to the specific issue for their details.

As a convenience, it is possible to get at their specific type by setting
`MAGIC=magic` (the file `magic` in this directory) before running the GNU `file`
command. For example, this shows which is which in the entire collection:

```
$ MAGIC=magic find issue* -type f -name '*.caj' -exec file {} \; | sort
issue-20/文件名未知.caj: CAJ file (canonical)
issue-21/实时网络流量异常检测算法研究和系统实现_林尚朕.caj: CAJ file (HN variant)
issue-21/时间序列模型在卫星异常检测中的应用研究_余文艳.caj: CAJ file (KDH variant)
...
issue-33/test1.caj: CAJ file (C8 variant)
issue-33/test2.caj: PDF document
...
```
