# README

## WePY项目的创建与使用

WePY的安装或更新都通过`npm`(没有`npm`请自行安装`cnpm`)进行。

### 全局安装或更新WePY命令行工具
```bash
npm install wepy-cli -g
```

### 在开发目录中生成Demo开发项目, 1.7.0之后版本请移步[wepy-cli文档](https://tencent.github.io/wepy/document.html#/./doc.cli)
```bash
wepy new myproject
# 1.7.0之后的版本使用 wepy init standard myproject 初始化项目，使用 wepy list 查看项目模板
```

### 切换至项目目录
```bash
cd myproject
```

### 安装依赖
```bash
npm install
```

### 开启实时编译
```bash
wepy build --watch
```

## 相关文档

### 微信小程序组件化开发框架WePY官方文档
https://tencent.github.io/wepy/document.html#/

### wepy开发文档地址
https://tencent.github.io/wepy/

### 小程序开发文档
http://mp.weixin.qq.com/debug/wxadoc/dev/

## 开发工具
推荐使用webstrom。

## 开发使用说明(重要)

- 使用微信开发者工具-->添加项目，项目目录请选择dist目录。
- 微信开发者工具-->项目-->关闭ES6转ES5。 <font color=red>重要：漏掉此项会运行报错。</font> 
- 微信开发者工具-->项目-->关闭上传代码时样式自动补全。  <font color=red>重要：某些情况下漏掉此项也会运行报错。</font> 
- 微信开发者工具-->项目-->关闭代码压缩上传。  <font color=red>重要：开启后，会导致真机computed, props.sync 等等属性失效。</font> 




