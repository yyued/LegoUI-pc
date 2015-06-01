# 开始使用

---

LegoUI for pc 是一套轻量级的前端UI库，从欢聚时代的实际业务产品需求中精选提取而来的CSS解决方案，旨在像组装LEGO积木一样方便、快捷、灵活的组装成一个web应用。LegoUI使用SASS来组织和书写样式，遵循YY UED前端规范。

---

## 获取源码

### git

直接clone到本地使用：

<pre>git clone https://github.com/duowan/legoui-pc.git</pre>

### 前端构建工具

如果你正在使用我们的gulp构建工具 [Generator Lego](https://github.com/duowan/generator-lego)，那可以在初始化时使用`yo lego:more`命令，然后选择*LegoUI for pc模板*即可以将LegoUI for pc初始化到你的开发目录了。


## 包含内容

我们提供了编译好的 CSS 文件，还有经过压缩的 CSS 文件，可以直接使用到任何 web 项目中。同时还包含了来自阿里字体库的图标字体。


```

LegoUI-for-pc
│
├── dist/                           
│   ├── lego.css                    # 预编译的 CSS 文件
│   └── lego.min.css                # 压缩版 CSS 文件
│   
├── sass/                           # LegoUI SASS 文件
│   ├── lego.scss
│   ├── base.scss
│   ├── ...
│
├── font/                           # web 字体
│   └── lego/                       # LegoUI 图标字体
│       ├── iconfont.eot
│       ├── iconfont.svg
│       ├── iconfont.ttf
│       └── iconfont.woff
│
└── README.md                       # LegoUI 说明文档
```


## 创建一个简单的页面

这是一个简单的页面模板，直接拷贝然后愉快的使用LegoUI for pc吧：

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="renderer" content="webkit">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="Keywords" content="">
    <meta name="description" content="">
    <title>LegoUI</title>
    <link rel="stylesheet" href="../css/lego.min.css">
    <link rel="stylesheet" href="../css/app.css">
</head>
<body>
    <p>
        Hello Lego UI.
    </p>

    <!-- 在这里编写你的代码 -->
    
</body>
</html>
```

## 参考使用的项目

* [Sea.js](https://github.com/seajs/seajs) ([ MIT License ](https://github.com/seajs/seajs/blob/master/LICENSE.md))
* [Arale](https://github.com/aralejs/aralejs.org/) ([ MIT License ](https://github.com/aralejs/aralejs.org/blob/master/LICENSE))
* [Normalize.css](https://github.com/necolas/normalize.css) ([ MIT License ](https://github.com/necolas/normalize.css/blob/master/LICENSE.md))
* [Bootstrap](https://github.com/twbs/bootstrap) ([ MIT License ](https://github.com/twbs/bootstrap/blob/master/LICENSE))
* [Alice](https://github.com/aliceui/aliceui.org/) ([ MIT License ](https://github.com/aliceui/aliceui.org/blob/master/LICENSE))
* [Pure](https://github.com/yui/pure) ([ BSD License ](https://github.com/yui/pure/blob/master/LICENSE.md))
* [Neat.css](https://github.com/thx/cube) ([ MIT License ](https://github.com/thx/cube/blob/gh-pages/LICENSE))

