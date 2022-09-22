# from-data-to-dissertation

看到南京大学池彪老师的《教育人力资本的代际传递研究》结构和思路都非常清晰，萌生一个想法，从结构上复现这篇硕士论文，目的在于让大家感觉 R 语言的强大，有几点需要说明：

1. 因为[CFPS](https://opendata.pku.edu.cn/)数据集更新了，所以我们使用的数据与原文有点差别
2. 本文使用 R & Tidyverse 完成统计计算
3. 因为数据不同，所以我们的统计结果与原文不一致，但仍然照搬了原文文字描述，主要是给同学们展示论文的框架结构
4. 运行本文档需要安装 `install.packages(c("tidyverse", "gt", "readxl", "psych", "broom", "erer", "bookdown"), dependencies = TRUE)`
