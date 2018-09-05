Orange.Decoder
=======

Decode 23andme snp data with snpedia database


桔子生物.解码器
=======
桔子生物.解码器目前是一个用snpedia.com数据解读23andme公司检测的snp数据的工具；

愿景是成为整合更多数据库(比如：pharmgkb)来解读个人全基因组的工具 :)

## 使用方法
1. git clone 代码;
2. 安装django 1.7; sudo pip install django;
3. cd decoder 目录:
	
	python decode.py -t html -i 你的23andme数据 -o 报告生成目录

4. 1-3 分钟后，运行完毕。用浏览器打开报告生成目录中的report.html

## website

http://juzishengwu.github.io

## 报告Demo

http://decoder.juzishengwu.com/

## Snpedia.com 数据下载 

http://bio2016.oss-cn-qingdao.aliyuncs.com/snpedia.tar.gz
