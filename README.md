# fund
爬取天天基金网，辅助对投资基金的选择

2018.9.11
实现爬取天天基金所有的6103个基金的代码和名称

2018.9.27
在爬取得到的基金，基金代码的基础上，爬取他们的前1月、3月、6月、1年、3年、成立来的收益率
下一步，计划加入多进程多线程，数据量一大，线性处理就变得非常慢(已加入多线程）
再下一步，对爬取的数据进行分析，筛选出大致5-20个未来可期的基金

加上多线程之后，问题就来了，爬得太快，服务器就不应答了
明天再看看怎么降速度，或者用代理ip啥的