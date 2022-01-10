# travelpolicy_HoshinoBot
一个适用于HoshinoBot的疫情出行政策获取插件

# 安装方法
和一般hoshino插件一样  

1. 在hoshino/modules下clone本仓库`git clone https://github.com/SlightDust/travelpolicy_HoshinoBot.git`  
2. 在hoshino/config/\_\_bot\_\_.py中加入
```
MODULES_ON = {
...
'travelpolicy_HoshinoBot',  # 出行政策
}
```
3. 重启hoshino

# 使用方法
|命令|说明|
|----|---|
|出行政策|获取使用帮助|
|出行政策 A|获取A城市的离开、进入和酒店政策|
|出行政策 A B|获取A城市的离开政策、B城市的进入政策和酒店政策|

如：`出行政策 杭州 北京`

# 日志
2022/01/10 大概能用了。年关将至，大家出行注意安全，做好个人防护。

# 免责声明
数据来源：[https://news.qq.com/hdh5/sftravel.htm#/](https://news.qq.com/hdh5/sftravel.htm#/)