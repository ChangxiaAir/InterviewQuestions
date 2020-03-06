# 页面导入样式时，使用 link 和 @import 有什么区别。

1. 从属关系区别。@import 只能导入样式表，link 还可以定义 RSS、rel 连接属性、引入网站图标等；
2. 加载顺序区别；加载页面时，link 标签引入的 CSS 被同时加载；@import 引入的 CSS 将在页面加载完毕后被加载；
3. 兼容性区别；