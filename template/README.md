# Hippy-react

> hippy react 版本脚手架

## 启动项目

### web版本

```shell
npm run serve
```

在浏览器中输入 `http://localhost:8080/{{YourProjectName}}.html#/`

### hippy 版本

#### 启动项目

```shell
npm run serve:hippy // npm run hippy:dev & npm run hippy:debug & npm run hippy:ios
```

#### 启动模拟器/真机

* 启动ios模拟器

```shell
npm run hippy:ios
```

或者直接打开ios项目，本地编译

1. 打开`./ios`下的功能
2. xcode中构建，拉起模拟器

*注：ios目前不支持热加载，需要手动reload更新, `cmd+R`*


* 连接android虚拟机

```shell
npm run hippy:and
```
启动本地打包，webpack watch模式
