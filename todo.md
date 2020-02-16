自己动手试试hexo主题编写，同时也是学习一下ejs(最后换用短小一点的pug)

hexo开发文档:https://hexo.io/zh-cn/docs
变量:https://hexo.io/zh-cn/docs/variables

pug文档：https://pugjs.bootcss.com/
ejs文档：
### 将要进行魔改的地方

1. 增加几个页面：分类和~~标签~~。
2. ~~layout改写成pug~~
3. title的设置
4. 分页器按照不同的页面进行分页(初步需要根据title),目前分页控制参数(config)并没有用上233。


### 更新记录：
| 时间 | 内容 |
| - | - |
| 2020年2月15日 | 把ejs改成pug（剩余page页面（包括tag和categories) |
| 2020年2月15日 | 修正：前后文章链接点击后不变色,保持清爽 |  
| 2020年2月16日 | 增加网页图标 |
| 2020年2月17日 | 增加标签页面　|
| 2020年2月17日 | 修正缺失分页器样式的bug |
| 2020年2月17日 | 修正归档时使用page.post,应该使用site.post |
