# 创建项目
使用Scrapy 命令创建、初始化项目<br>
`scrapy startproject spidername`

创建完成后，会初始化爬虫目录，并创建项目文件模板

![scrapyproject](images/2018/07/scrapyproject.png)

```
finspider/
    scrapy.cfg   # 部署配置文件
    finspider/   # 项目主目录
       item.py   # 定义需要获取的字段
       middlewares.py    # 项目中间件文件
       pipelines.py      # 定义存储方式
       settings.py       # 项目设置文件
       spiders/          # 放置爬虫文件
```
