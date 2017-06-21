# Vue-c
Technique website built by Vue2.3+Axios+CSS3 

[ Vue2.0+Axios+CSS3 构建的技术资讯网站 ]() : 
使用Cnode社区官方提供的API作为资讯内容来源，采用Vue.js进行页面渲染，和NPM的Axios客户端完成Ajax请求。同时页面表现使用CSS3构造，使用scss预编译技术，编译软件使用koala。页面路由方面由Location等原生html对象实现。

## 目前主要使用了cNode社区的以下几个Api
* get /topics 主题首页

> 接收 get 参数

` page Number 页数
tab String 主题分类。目前有 ask share job good
limit Number 每一页的主题数量
mdrender String 当为 false 时，不渲染。默认为 true，渲染出现的所有 markdown 格式文本。`
> 示例：/api/v1/topics

get /topic/:id 主题详情

* 接收 get 参数

`mdrender String 当为 false 时，不渲染。默认为 true，渲染出现的所有 markdown 格式文本。
accesstoken String 当需要知道一个主题是否被特定用户收藏以及对应评论是否被特定用户点赞时，才需要带此参数。会影响返回值中的 is_collect 以及 replies 列表中的 is_uped 值。`
> 示例：/api/v1/topic/5433d5e4e737cbe96dcef312
## How to use
---
Clone this project in direct without any backup environment,
Just enjoy your reading.
---
