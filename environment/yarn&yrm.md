<!--
 * @Author: leo
 * @Description: your description
 * @Date: 2020-07-26 18:04:09
--> 
## 来源npm安装（使用原npm镜像安装，taobao镜像没有该库）
[yarn参数介绍](https://classic.yarnpkg.com/en/docs/cli/install)
```
npm i -g yarn 
```

## [yarn命令慢，切换源](https://learnku.com/articles/15976/yarn-accelerate-and-modify-mirror-source-in-china)
```
// 查看源
yarn config get registry
// 修改源
yarn config set registry https://registry.npm.taobao.org/
```


## 使用yrm快速切换源(同nrm)
```
npm i -g yrm
yrm ls
yrm use taobao
yrm test taobao // 测速
```

## 设置包源
如果特定包下载不畅，可以查看包镜像源，在.npmrc或.yarnrc文件中配置如：
```
registry "https://registry.npm.taobao.org/"
electron_mirror "https://npm.taobao.org/mirrors/electron/"
```
或使用[命令操作](https://my.oschina.net/benwen/blog/3073481)
```
yarn config set electron_mirror https://npm.taobao.org/mirrors/electron/
npm config set electron_mirror https://mirrors.huaweicloud.com/electron/
```