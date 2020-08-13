# 我的个人博客css
这是博主博客**自用的**css代码，虽然水平不行，但还是作为自己第一次写css的纪念，分享出来，也为了我教程的读者，方便引用*福利css*
## 效果展示
![](https://gitee.com/jackyfzh/imgs_bed/raw/master/小书匠/2020/8/12/1597234999764.png)

![](https://gitee.com/jackyfzh/imgs_bed/raw/master/小书匠/2020/8/12/1597235031706.png)

![](https://gitee.com/jackyfzh/imgs_bed/raw/master/小书匠/2020/8/12/1597235044632.png)

## 特色
1. 五种颜色的note
2. 有阴影效果的按钮
3. 移动端适配较佳
4. 快捷键特别效果
5. 小代码块效果
6. 常用标题效果

## 引用
建议使用jsdelivr的加速cdn或者直接下载或者复制，这里只说cdn的引用方式，在HTML文件的head中写入：
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jackyfzh/css@master/blog/main.css">
```

## 使用
使用方法很多，大家可以参考HTML文件示例。
1. 所有内容都需要包含在article里面，像这样：
```html
<div id='article'>

</div>
```
2. 图片：图片最简单，直接用img标签就可以，不需要指定类
3. note：note有很多种，建议去看HTML示例，这里列举：
```html
<div class="note-info">info<br>信息</div>
<div class="note-warn">warn<br>警告</div>
<div class="note-primary">primary<br>主要</div>
<div class="note-success">success<br>成功</div>
<div class="note-danger">danger<br>危险</div>
```
4. 引用可以使用markdown，会自动解析：
```markdown
> 应用部分
```
也可以是HTML：
```html
<blockquote><p>赞<br>测试<br>真完美</p></blockquote>
```
5. 最后就是按钮了，看示例：
```html
<button class="btn btn-shadow">button 蓝色阴影按钮</button>
<a href="https://jackypy.xyz" class="btn btn-shadow btn-yellow">button 黄色阴影按钮</a>
<button class="btn btn-green">button 绿色按钮</button>
```

> 有基础的博主建议看示例或者css源码
> 有问题欢迎加群：**Python学习交流 1140464262**