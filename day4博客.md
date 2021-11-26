| 这个作业属于哪个课程 | [构建之法-2021秋-福州大学软件工程](https://bbs.csdn.net/forums/fzuSoftwareEngineering2021) |
| -------------------- | ------------------------------------------------------------ |
| 这个作业要求在哪里   | [2021秋软工实践alpha冲刺](https://bbs.csdn.net/topics/603251837) |
| 团队名称             | 测码奔腾                                                     |
| 这个作业的目标       | Alpha冲刺(day4)                                              |

## 今日进度


## 今日进度

| 成员姓名 | 完成的任务                                       | 完成任务时长 | 遇到问题                                                     | 解决方式                                                     |
| :------- | :----------------------------------------------- | ------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 梁育诚   | 选择合适的爬虫模板，初步爬取整个页面             | 3h           | 整个页面包含了各种各样的标签，且不知道如何分离url和文章标题  | 查找博客，学习了使用正则表达式来分离字符串中的url和标题信息  |
| 方奕林   | 历史搜索词汇清除                                 | 3h           | 如何对历史词汇清除，使得再次打开之后没有历史记录             | 通过清理缓存                                                 |
| 江山     | 学习如何与后端进行交互                           | 3h           | 对于后端传过来的文件不能筛选出有效信息                       | 通过与后端人员交流得到文件格式                               |
| 许叶源   | 改进爬虫程序，实现定时爬取和爬取链接中的文章内容 | 3h           | 1.对咨询页面爬取数据无法获取资讯内部详细信息 2.资讯详细页的信息不在标签内部，直接匹配标签无法获得文本内容 3.3.osChine综合咨询页面有时会出现代码页，与爬取时设置的文本标签不符，导致程序终止无法实现定时爬取 | 1.通过再次对链接进行爬取，实现跨页爬取数据 2.通过beautifulsoup内置函数.text实现对标签内部的数据爬取 3.通过对爬取的返回值进行测试 特殊判断解决。 |
| 吾木提   | 学习退出登录如何实现                             | 3h           | 网上的教程是把用户信息存到本地，退出登录只需要把本地缓存清空， | 继续查找资料，学习实现退出登录                               |
| 杨建伟   | 使用wx.request api调用GET请求GitHub数据          | 3h           | GET请求的格式，以及github api调用格式，参数形式等            | 搜索GET、POST请求的相关教程，跟着教程学习                    |
| 翁子龙   | 点击文章旁爱心收藏并向后端通信判断该文章收藏情况 | 3h           | 点击父组件中子组件，想要触发子组件事件并传递父组件参数，总是错误 | 上网学习相关知识后得到解决                                   |
| 吴俊玮   | 服务器搭建                                       | 3h           | 服务器搭建教程杂乱，易出错                                   | 暂时还未搭建成功，根据教程慢慢搭建试错                       |
| 林智垚   | 学习python方面知识，下载pycharm学习使用          | 3h           | 对python语言不是特别了解                                     | 通过博客，b站等资源进行学习                                  |

## 介绍

目前小程序前端工作还在进行中，前端工作经过前端人员的不断努力基本页面已经实现，后端人员的爬取信息在不断进步中，已经能够爬取部分信息。

今日进展不多，燃尽图完成任务数量相对固定。
![请添加图片描述](https://img-blog.csdnimg.cn/3aa87fbc6edd48508df9d315de24fdd2.png?x-oss-process=image/watermark,type_ZHJvaWRzYW5zZmFsbGJhY2s,shadow_50,text_Q1NETiBA5LiJ5Y-3ODg0,size_20,color_FFFFFF,t_70,g_se,x_16)

## 贡献表

| 成员姓名 | 贡献程度(百分比) |
| :------- | :--------------- |
| 梁育诚   | 11.1%            |
| 方奕林   | 11.1%            |
| 江山     | 11.1%            |
| 许叶源   | 11.1%            |
| 吾木提   | 11.1%            |
| 杨建伟   | 11.1%            |
| 翁子龙   | 11.1%            |
| 吴俊玮   | 11.1%            |
| 林智垚   | 11.1%            |

## 图

### UML设计图



![UML设计图](https://img-blog.csdnimg.cn/b86757e33d2a4cf8bf16cd6e1c9a31b8.png?x-oss-process=image/watermark,type_ZHJvaWRzYW5zZmFsbGJhY2s,shadow_50,text_Q1NETiBA5LiJ5Y-3ODg0,size_20,color_FFFFFF,t_70,g_se,x_16)




### 汇报

前端各界面基础内容已经完成，差于前后端交互部分，后端仍旧在努力开发中。

#### 类图                 

![img](https://img-blog.csdnimg.cn/img_convert/21f5533075805c08ee2f5643b176773f.png)        



### 时序图

![\[外链图片转存失败,源站可能有防盗链机制,建议将图片保存下来直接上传(img-HH3kGBtY-1637153375742)(C:\Users\86150\Desktop\软工alpha冲刺\时序图.png)\]](https://img-blog.csdnimg.cn/7d466e2f97674cc6b73e255a41483aea.png?x-oss-process=image/watermark,type_ZHJvaWRzYW5zZmFsbGJhY2s,shadow_50,text_Q1NETiBA5LiJ5Y-3ODg0,size_20,color_FFFFFF,t_70,g_se,x_16)


### 状态图

![\[外链图片转存失败,源站可能有防盗链机制,建议将图片保存下来直接上传(img-VdRUWnp7-1637153375745)(C:\Users\86150\Desktop\软工alpha冲刺\状态图.png)\]](https://img-blog.csdnimg.cn/28294615e346449ebdf7c0e85b9eb94f.png?x-oss-process=image/watermark,type_ZHJvaWRzYW5zZmFsbGJhY2s,shadow_50,text_Q1NETiBA5LiJ5Y-3ODg0,size_20,color_FFFFFF,t_70,g_se,x_16)


### 活动图

![\[外链图片转存失败,源站可能有防盗链机制,建议将图片保存下来直接上传(img-XysOLwIm-1637153375749)(C:\Users\86150\Desktop\软工alpha冲刺\活动图.png)\]](https://img-blog.csdnimg.cn/453e90ba83c84f5ba3fa24bcbcf9779f.png?x-oss-process=image/watermark,type_ZHJvaWRzYW5zZmFsbGJhY2s,shadow_50,text_Q1NETiBA5LiJ5Y-3ODg0,size_20,color_FFFFFF,t_70,g_se,x_16)