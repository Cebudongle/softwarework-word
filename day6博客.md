| 这个作业属于哪个课程 | [构建之法-2021秋-福州大学软件工程](https://bbs.csdn.net/forums/fzuSoftwareEngineering2021) |
| -------------------- | ------------------------------------------------------------ |
| 这个作业要求在哪里   | [2021秋软工实践alpha冲刺](https://bbs.csdn.net/topics/603251837) |
| 团队名称             | 测码奔腾                                                     |
| 这个作业的目标       | Alpha冲刺(day6)                                              |


## 今日进度

| 成员姓名 | 完成的任务                                                   | 完成任务时长 | 遇到问题                                                     | 解决方式                                                     |
| :------- | :----------------------------------------------------------- | ------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 梁育诚   | 下载、配置了MySQL环境，与小组的数据库进行连接、交互，将爬取出的数据传送到数据库中 | 3h           | 没使用过MySQL，不知道要怎么配置；python的与数据库交互的函数不了解 | 在小组伙伴的帮助下完成了安装配置；查找博客学习了python中与数据库相关的函数，成功与数据库交互，之后完成了对数据库的删除、更新等操作。 |
| 方奕林   | 下拉刷新出行的结果                                           | 3h           | 如何信息下拉刷新                                             | 通过微信小程序中原本包含的函数，书写js脚本添加创建新的数组   |
| 江山     | 与后端进行交互，将数据库中的信息表现在页面中                 | 3h           | 若使用文本信息排版问题无法解决                               | 使用url路径进行转载，不进行自己的排版                        |
| 许叶源   | 与数据库进行交互，将爬取的信息存入数据库                     | 3h           | 定时爬取由于网站文字更新速度问题，可能爬取重复数据，造成数据冗余 | 在每次爬取之前重新初始化数据库再存入数据                     |
| 吾木提   | 修改页面名，删除无关页面，把修改后的版本传到前端仓库分支     | 3h           | 由于一开始就是边学习边写代码，创建了一些无关的页面，代码也忘记注释导致前端整合的时候不是很方便 | 队友提醒，并修改                                             |
| 杨建伟   | 调用云函数，由云函数发送GET请求到GitHub search api           | 3h           | 云开发函数的格式，返回值，加入request-promise的使用          | 借鉴相关开源代码                                             |
| 翁子龙   | 修改并完善存在的一些问题                                     | 3h           | 存在的一些问题难以解决                                       | 上网查询后解决                                               |
| 吴俊玮   | 服务器搭建                                                   | 3h           | 服务器搭建教程杂乱，易出错                                   | 暂时还未搭建成功，根据教程慢慢搭建试错                       |
| 林智垚   | 学习有关数据库数据处理的知识                                 | 3h           | 如何处理程序脚本运行后更新得到的数据库,需要运用到哪些知识    | 通过询问组员了解了如何处理数据库中的信息,并在网上查找资料学习了一些相应的办法 |

## 介绍

今日开始前后端交互测试，并且已经可以通过本地测试进行初步交互，由于服务器暂未搭建完成，故暂时未部署到服务器上
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



#### 类图                 

![img](https://img-blog.csdnimg.cn/img_convert/21f5533075805c08ee2f5643b176773f.png)        



### 时序图

![\[外链图片转存失败,源站可能有防盗链机制,建议将图片保存下来直接上传(img-HH3kGBtY-1637153375742)(C:\Users\86150\Desktop\软工alpha冲刺\时序图.png)\]](https://img-blog.csdnimg.cn/7d466e2f97674cc6b73e255a41483aea.png?x-oss-process=image/watermark,type_ZHJvaWRzYW5zZmFsbGJhY2s,shadow_50,text_Q1NETiBA5LiJ5Y-3ODg0,size_20,color_FFFFFF,t_70,g_se,x_16)


### 状态图

![\[外链图片转存失败,源站可能有防盗链机制,建议将图片保存下来直接上传(img-VdRUWnp7-1637153375745)(C:\Users\86150\Desktop\软工alpha冲刺\状态图.png)\]](https://img-blog.csdnimg.cn/28294615e346449ebdf7c0e85b9eb94f.png?x-oss-process=image/watermark,type_ZHJvaWRzYW5zZmFsbGJhY2s,shadow_50,text_Q1NETiBA5LiJ5Y-3ODg0,size_20,color_FFFFFF,t_70,g_se,x_16)


### 活动图

![\[外链图片转存失败,源站可能有防盗链机制,建议将图片保存下来直接上传(img-XysOLwIm-1637153375749)(C:\Users\86150\Desktop\软工alpha冲刺\活动图.png)\]](https://img-blog.csdnimg.cn/453e90ba83c84f5ba3fa24bcbcf9779f.png?x-oss-process=image/watermark,type_ZHJvaWRzYW5zZmFsbGJhY2s,shadow_50,text_Q1NETiBA5LiJ5Y-3ODg0,size_20,color_FFFFFF,t_70,g_se,x_16)