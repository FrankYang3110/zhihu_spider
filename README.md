# Zhihu_spider
Practice project

Scrapy抓取知乎全部问题和答案，存入mysql数据库。

开始用selenium模拟登陆知乎，然后将cookies保存，交给后面的Request

用twisted提供的异步接口将数据存入mysql

知乎问题入库：

![Image1](https://github.com/FrankYang3110/img-folder/blob/master/zhihu_question.png)

知乎回答入库：

![Image2](https://github.com/FrankYang3110/img-folder/blob/master/zhihu_answer.png)
