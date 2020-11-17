# OIPMS

一个基于Vue开发的权限管理系统，后续会增加更多实用的功能。

## 项目下载后,首先安装依赖包

``` bash
npm install
```

或

``` bash
npm install --registry=https://registry.npm.taobao.org
```

### 安装成功后，运行即可

``` bash
npm run serve
```

## Tips

如果你想换端口，可以直接修改根目录下的 vue.config.js 文件

``` json
  devServer: {
    port: 9999, // 当前 admin 项目的端口号

    proxy: {
      // 配置代理
      "/api": {
        target: "http://localhost:8888",//改成后端api地址

```

### 开发过程中检查错误，可执行lint

``` bash
npm run lint
```

### 想要发布，执行bulid打包成dist

``` bash
npm run build
```
