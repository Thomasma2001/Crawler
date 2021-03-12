本地运行豆瓣电影爬取程序的步骤

1.安装beatifulSoup4

 !beatifulSoup4是一个著名的爬虫框架

 pip install bs4

2.在windows10下安装openpyxl

 !xlwt,xlrd是Python写Excel文件用的package. 

从https://pypi.python.org/pypi/openpyxl 下载zip 文件然后在本地解压，进入openpyxl目录，setup.py文件应该在这个目录下。

运行命令python setup.py install

3.运行crawler.py后 豆瓣电影Top250.xlsx文件将出现在本地电脑的指定目录中。
