运行环境：Ubuntu系统下Python2.7，数据库MySQL</br>
利用Scrapy爬虫框架爬取了豆瓣电影top系列以及新浪微博粉丝资料，
新浪微博爬虫初始需要键入用户名密码，验证码的处理方式为下载后手动输入。</br>
考虑到可能的反爬虫方式，可以加上下载器中间件利用cookie池和user-agent池来交替下载。</br>
参考资料:LiuXingMing的github</br>
![image](https://raw.githubusercontent.com/shichangtai/ScrapySpider/master/screenshots/douban.png)</br>
![img](https://raw.githubusercontent.com/shichangtai/ScrapySpider/master/screenshots/sina.png)
