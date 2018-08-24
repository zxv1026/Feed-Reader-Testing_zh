## 如何运行

克隆到本地，直接打开index.html即可。

## 测试功能

* RSS Feeds
    * allFeeds 变量被定义了而且不是空的。
    * allFeeds 对象里面的所有的源有链接字段而且链接不是空的
    * allFeeds 对象里面的所有的源有名字字段而且不是空的
* The menu
    * 菜单元素默认是隐藏的
    * 菜单图标被点击的时候菜单会切换可见状态
* Initial Entries
    * loadFeed 函数被调用而且工作正常
* New Feed Selection
    * loadFeed 函数加载一个新源的时候内容会真的改变