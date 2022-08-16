## 安装
```
npm install tdvite -g
```

## 启动
- cd 到项目的根目录下
- 执行tdvite

## 自定义配置
- 在根目录下创建vite.config.js文件, 配置如下，其他配置参考vite官方文档
```
module.exports = {
    htmlPath: './src/index.html', // html的地址
    entriesPath: '/src/app.js' // 入口js文件
};
```
## 修改proxy
- 默认会取build/config.js的proxyTable ｜ port