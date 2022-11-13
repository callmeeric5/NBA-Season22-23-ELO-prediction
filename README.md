# NBA-Season22-23-ELO-prediction

简介
项目目标:
通过网络爬虫的方式获取2021-2022赛季NBA的比赛数据,并以XLS的格式保存
进行数据清洗后将其转化为一个可以进行数据分析的数据集并可视化分析具体的问题
根据ELO算法训练模型,并以此预测22-23赛季的比赛结果
调用包: requests(URL请求);etree(解析网页);pandas(构建dataframe);sklearn(建模)
数据源: BBR 个人认为可能是最好的篮球数据网站: https://www.basketball-reference.com/leagues/NBA_2022.html
