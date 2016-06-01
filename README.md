# didi-rank
## 滴滴算法大赛中，获取自己的排名以及记录自己的排名的历史信息

### 每次查询成绩都需要从头翻页，所以花了点时间写了个获取排名的脚本，因为后期滴滴可能会有此方面的功能，所以代码没有refactor，现在功能有：
- 支持查看最新排名
- 支持查看最佳排名
- 支持查看最佳排名提交日期
- 支持记录历史数据（需要你每天run一次，记录在ranks.json文件中），方便查看的成绩趋势
- 支持一次查询多个账号，因为有人用多个小号提交


## 用法：
- 运行环境： python3
- 依赖包：   requests
- 下载或者clone该repo
- 修改你的账号列表
``` python
team_names = ['XMZH', 'yiersan']
```
-  然后运行就行了，运行结果如图
![image](https://github.com/176coding/didi-rank/blob/master/imgs/didi-rk.png)
