# 创软俱乐部项目训练

[[后端] 3/21 猜数字](./03-21/backend)

猜数字是已一个古老的游戏，由一个出题者随机出一个数字，由猜题者猜，若所猜数字大于所出数字，则出题者回答『大了』；若小于，则回答『小了』；直到猜题者猜中。现在请编写程序模拟出题者，随机数字在0~1000之间。当使用者猜中时，同时打印出猜测次数。

[[爬虫] 3/21 获取IP](./03-21/crawler)

访问网站：ip.sxisa.com 可以得到本机的外网IP。现在，请编写程序，打印出本机的外网IP。

[[前端] 3/21 网站设计](./03-21/frontend)

按照设计图制作出对应的网页：

![](https://dn-coding-net-production-file.qbox.me/979a7d78-0bb3-4341-a0f4-7694e166e119.png?download/%E8%AE%BE%E8%AE%A1%E5%9B%BE01.png&e=1522749860&token=goE9CtaiT5YaIP6ZQ1nAafd_C1Z_H2gVP8AwuC-5:X6dVov783YiMZknEG75UwYLLDzg=)


---

[后端] 4/11 保存猜数字成绩

修改上一个程序，添加如下功能：  
1. 当用户猜到数字之后，提示其输入一个昵称作为游戏名称，然后保存成绩，包含昵称，开始时间，耗时，所猜数字，猜测次数；  
2. 游戏开启时，若用户已有设置了昵称，则输出提示语：你好！昵称~；  
3. 然后提示选择 1. 玩猜数字；2. 查看历史成绩；3. 更改设置昵称；  
4. 实现2，3功能。  

[爬虫] 3/29 获取IP与IP相关信息

爬取 www.myip.cn 得到本机的外网IP，IP 地域，运营商。

[前端] 3/29 表单验证

修改上一个网页，添加如下功能：  
当用户输入的电话号码非数字与长度不等于11位时，提示无效的手机号，同时禁用按钮，当输入符合要求时，则按钮恢复可用。