---
layout: post
title: python更改源
description: >
  Python pip 源设置方法。
image: /assets/img/blog/example-content-ii.jpg
noindex: true
---
## pip国内的一些镜像
- 阿里云 http://mirrors.aliyun.com/pypi/simple/
- 中国科技大学  https://pypi.mirrors.ustc.edu.cn/simple/
- 豆瓣(douban) http://pypi.douban.com/simple/
- 清华大学 https://pypi.tuna.tsinghua.edu.cn/simple/
- 中国科学技术大学 http://pypi.mirrors.ustc.edu.cn/simple/

## 修改源方法

在使用pip的时候在后面加上-i参数，指定pip源
```bat
%一次修改%
pip install scrapy -i https://pypi.tuna.tsinghua.edu.cn/simple

%永久修改%
pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple
```
