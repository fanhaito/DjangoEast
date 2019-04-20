# DjangoEast
# 更新日志
## 2019.3.7
- 文章目录去掉无序列表的圆点
- 修改相关文章的文章标题的显示效果
- 修改文章列表页文章标题显示长度，30→50
- 修复mdeditor编辑器上传图片无法显示的问题
- 取消git对项目下的upload与media文件夹的跟踪
- 去除文章摘要中的">"字符，在结尾添加"......"
- 删除templates/blog/base.html文件（还未同步）
- 修改tag_list页面下文章显示顺序，刚发表的排在前面
- 修改了STATIC_ROOT的参数，使collectstatic操作正常

## 2019.3.8
- 修改文章页底部相关文章的个数：8→4
- 修复分类归档页面使用regroup产生的分组重复的问题

## 2019.3.10
- 修改分类目录页文章显示顺序
- 首页添加按分类展示的文章块:blockposts(移动端不显示)

## 2019.3.12
- 增加我的书单功能

## 2019.3.14
- 添加标签大全功能
- 改进文章目录功能
- 修改文章列表页文章显示

## 2019.3.15
- 书单页中有读书笔记的跳转至读书笔记页面，否则不跳转
- 添加book_list.html页面用于呈现每个图书标签下的图书

## 2019.3.17
- 添加我的影单功能

## 2019.3.20
- 修改文章列表块的样式
- 新增文章列表前的label功能
- PC端网站颜色改版，由极简黑到活力彩

## 2019.3.23
- 更改路由配置方式，由正则改为路径

## 2019.4.03
- 添加文章评论功能
- 评论二级回复功能
- 评论区支持富文本编辑器ckeditor

## 2019.4.06
- 添加评论统计功能
- 为评论者添加默认头像
- 修改博主评论显示样式
- 将获取评论列表功能写入自定义标签
- 将提交新的评论功能写入自定义标签

## 2019.4.07
- 为首页添加我的留言功能
- 后台评论功能添加按照评论对象进行筛选功能

## 2019.4.16
- 全站添加CNZZ网站统计
- 网站升级HTTPS
- 重新部署至腾讯云