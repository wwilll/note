<!--
 * @Author: leo
 * @Description: nrm introduction
 * @Date: 2020-07-08 20:32:16
--> 
### 介绍
使用nrm帮你快速切换npm源,[npm包地址](https://www.npmjs.com/package/nrm)
nrm can help you easy and fast switch between different npm registries, now include: npm, cnpm, taobao, nj(nodejitsu).

```js
npm install -g nrm // 安装
nrm ls
-----------------------------------------
  npm -------- https://registry.npmjs.org/
  yarn ------- https://registry.yarnpkg.com/
  cnpm ------- http://r.cnpmjs.org/
* taobao ----- https://registry.npm.taobao.org/
  nj --------- https://registry.nodejitsu.com/
  npmMirror -- https://skimdb.npmjs.com/registry/
  edunpm ----- http://registry.enpmjs.org/
-----------------------------------------
nrm use cnpm // 使用
```