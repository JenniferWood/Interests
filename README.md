简单的搜索引擎

网页排名方法包括：
1、PAGERANK * TF-IDF
2、单词出现位置越靠前得分越高
3、搜索词包含多个词时，网页中这些词语距离越短者优先
4、根据链接提示词包含关键词的网页的pagerank值
5、根据用户点击行为训练MLP，根据BP修改权值

同时支持OR分隔的布尔搜索

不足（后续修改）：
数据库查询效率低
只支持英文（还没做中文分词）
不支持AND，和精确搜索
