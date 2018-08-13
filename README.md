# WeRateDogs Data Wrangle and Analysis  
# WeRateDogs数据整理和分析项目

## 项目介绍  
WeRateDogs 是一个推特主，他以诙谐幽默的方式对人们的宠物狗评分。这些评分通常以 10 作为分母，但是分子则一般大于 10：11/10、12/10、13/10 等等。  
该项目采用python对数据进行整理和分析。
根据项目要求，只需要含有图片的原始评级 (不包括转发)，对数据进行清洗并对结果进行分析和可视化。  
完整项目包括两个部分：Data wrangling和data analyses and visualizations report。其中Data wrangling有几个部分：数据收集，数据评估，数据清洗等。
## 数据整理过程：
### 1.数据收集
(1)手动下载包含该账号推特档案文件的 twitter-archive-enhanced.csv 文件，读取并获得 tweet_id.
(2)通过 tweepy 获取相对应 tweet_id 的推特数据，将 json 格式的数据写入 txt 文件并读取。  
(3)通 过 python4以 编 程 的 方 式 变 成 下 载 包 含 对 图 片 狗 狗 品 种 预 测 的image-predictions.tsv 并读取其中数据。  
### 2.数据评估和清理  
以目测和编程两个方式对数据进行评估，发现数据在质量和整洁度方面存在的问题，并对数据集进行清理，同时将以上三个文件整合。
数据整理的代码保存在wrangle-act.ipynb中，数据整理过程的报告为wrangle_report.pdf。
## 数据分析
对整理后数据的分析则记录为act_report.pdf
