# scrapy_doubai
Scrapy爬取豆瓣全部热门电影，提取封面、评分、简介。将数据分别存为json文件、下载图片、存到MongoDB、MYSQL(自行创建mysql数据库和表)。
豆瓣有一定的反爬机制，如果希望减少被封的几率，可以自行采用登录后再爬取、或者设置代理池、USER_AGENT池等
