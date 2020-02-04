### Adoc

> Just **A**nother markdown **doc** editor

PHP 7.2 + Laravel 5.8 + React-Bootstrap

### Features

1. UI使用直角主题，以及不会腻的黑白色
2. 编辑快捷键添加 ctrl/cmd + shift + s 保存并返回
3. 添加了文档活动记录，暂无其他用途，只是个历史查看谁改动了哪些文档
4. github 风格文档历史对比(react-diff-viewer)
5. 添加文档附件功能
6. 编辑、展示和导出都使用 editor.md，(showdoc编辑和展示是两个不同的程序)
7. 文档菜单无限极分类(编辑父级同样)
8. 文档菜单滑动到顶部固定
9. 文档搜索
10. 编辑器/显示 使用等宽字体，避免空格排版、数字/符号显示不明显问题
11. JSON工具生成MD表格为字段增加了 padEnd 空格填充，使之尽量都在一列
12. 文档左侧列表拖动排序(react-beautiful-dnd)，湿滑纵享，强迫症福利
13. 文档点赞，文档评论

#### 💚github
[github](https://github.com/yybawang/Adoc)

#### 安装

```bash
git clone https://github.com/yybawang/Adoc.git
cd Adoc
composer install
php artisan app:install

// 访问 APP_URL 测试
```


#### 升级

- 更新代码和数据库迁移

```bash
git pull
composer install
```

* [x] 项目功能
    * [x] 项目新增
    * [x] 项目配置
    * [x] 项目权限分配，使用 gate
    * [x] 项目删除
    * [x] 项目所有权转移
    * [x] 项目置顶，列表排前显示，替代排序功能(只会影响当前用户，非全局排序)
    * [ ] 项目tag标签
    * [ ] 列表可选使用 tag 分组展示
* [x] 文档功能
    * [x] 文档增删改查
    * [x] 文档自定义模版
    * [x] 文档修改历史，对比、还原
    * [x] 文档模版
    * [x] markdown 编辑器图片上传，上传到 laravel 配置的 filesystem 配置中，默认 public
    * [x] 文档编辑时可能已被修改过，提示先备份再编辑
    * [x] 文档搜索，头部右上角，暂只支持搜索当前展示项目下文档
    * [x] 文档列表拖动排序
    * [x] 文档附件
    * [x] JSON工具，json 转MD表格，json 美化
    * [x] 文档 github 风格选择 emoji 反应
    * [x] 文档评论，三天内可删除
    * [x] 新建文档如果未填写标题，默认为 Y-m-d，用于在线记事本使用
* [x] 编辑器快捷键优化
    * [x] Ctrl/Cmd + s 保存(停留当前页)， Ctrl/Cmd + Shift + s 保存并返回到列表
    * [x] Ctrl + d 插入当前时间
    * [x] Cmd + d 复制当前行到下一行
    


![示例](https://raw.githubusercontent.com/yybawang/images/master/adoc/Xnip2019-05-25_12-28-38.png)
![示例](https://raw.githubusercontent.com/yybawang/images/master/adoc/Xnip2019-07-04_18-07-30.png)
![示例](https://raw.githubusercontent.com/yybawang/images/master/adoc/Xnip2019-07-04_18-07-44.png)
![示例](https://raw.githubusercontent.com/yybawang/images/master/adoc/Xnip2019-07-04_18-07-58.png)
![示例](https://raw.githubusercontent.com/yybawang/images/master/picgo/20190715003350.png)
