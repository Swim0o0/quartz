# 一、部署好Quartz以后怎么上传新笔记？

1. 把要发布到网页的笔记放入quartz库中的content文件夹中
2. cmd打开控制台，一条一条输入以下命令：

```shell
#进入D盘
D:
#进入D盘中的quartz文件夹下
cd quartz
#同步新笔记到网页
npx quartz sync
```

3. 约40s，进入网页端即可看到更新后的内容