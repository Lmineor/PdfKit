# PdfKit

鉴于网上不少影印的PDF没有目录，自己暂时还没找到一个小工具自动生成目录的，就做了这个PdfKit 

## 功能

1. 合并PDF
2. 为PDF生成目录

## 使用说明

1. 如果是生成书签，则至少说明目录所在页数和内容第一页所在页数，输出原pdf的副本文件（*_copy.pdf）
2. 如果合并pdf，则按顺序说明被合成的pdf所在路径，输出merge.pdf

## 运行注意事项：

1. 必要的依赖[requirements.txt](./requirements.txt)
2. 进入pdf目录后，运行pk.py文件即可看到基本的命令, pk -h 进一步查看命令
