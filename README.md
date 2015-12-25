###简介
本项目是基于AmazeUI根据观麦内部需求定制而来,具体的请参考<a href="https://github.com/allmobilize/amazeui.git" target="_blank">AmazeUI</a>

## 开发及构建

用户可以在 Amaze UI 的基础上进行二次开发。

### 目录结构

```
amazeui
|-- HISTORY.md
|-- LICENSE
|-- README.md
|-- package.json
|-- dist        # 构建目录
|-- docs        # 文档
|-- fonts       # Icon font，目前使用了 http://staticfile.org/
|-- gulpfile.js # 构建配置文件
|-- js          # JS 文件
|-- less        # LESS 文件
|-- tools       # 相关工具
|-- vendor
`-- widget      # Web 组件
```

### 构建工具

Custom UI 使用 [gulp.js](http://gulpjs.com/) 构建项目。

首先全局安装 gulp：

```
npm install -g gulp
```

克隆项目文件:

```
git clone https://github.com/Pines-Cheng/CustomUI
```

然后进入目录安装依赖：

```
npm install
```

接下来，执行 `gulp`：

```
gulp
```

### Developed with Open Source Licensed [WebStorm](http://www.jetbrains.com/webstorm/)

<a href="http://www.jetbrains.com/webstorm/" target="_blank">
<img src="http://ww1.sinaimg.cn/large/005yyi5Jjw1elpp6svs2eg30k004i3ye.gif" width="240" />
</a>
