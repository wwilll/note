<!--
 * @Author: leo
 * @Description: npm introduction
 * @Date: 2020-07-07 22:30:36
--> 
## 来源
- nodejs自带

## 如何使用
#### 一般命令行工具都会有帮助命令
```js
npm --help // 一般是这个，可以尝试，如果错误一般也会给提示
npm -h // 结果如下
--------------------------------------
Usage: npm <command>
where <command> is one of:
    access, adduser, audit, bin, bugs, c, cache, ci, cit,
    clean-install, clean-install-test, completion, config,
    create, ddp, dedupe, deprecate, dist-tag, docs, doctor,
    edit, explore, fund, get, help, help-search, hook, i, init,
    install, install-ci-test, install-test, it, link, list, ln,
    login, logout, ls, org, outdated, owner, pack, ping, prefix,
    profile, prune, publish, rb, rebuild, repo, restart, root,
    run, run-script, s, se, search, set, shrinkwrap, star,
    stars, start, stop, t, team, test, token, tst, un,
    uninstall, unpublish, unstar, up, update, v, version, view,
    whoami
npm <command> -h  quick help on <command>
npm -l            display full usage info
npm help <term>   search for help on <term>
npm help npm      involved overview
--------------------------------------
npm -l // 根据提示，列出详细使用信息
```

#### 常用设置命令
```js
npm config get registry  // 查看npm当前镜像
npm config set registry https://registry.npm.taobao.org/  // 设置淘宝镜像
npm info [react] // 查看包具体信息如react版本等
npm ls -g --depth=0 // 查看已经安装在全局的模块
npm config // 从如下报错信息中查看其他信息
----------------------------------
npm ERR! Usage:
npm ERR! npm config set <key> <value>
npm ERR! npm config get [<key>]
npm ERR! npm config delete <key>
npm ERR! npm config list [--json]
npm ERR! npm config edit
npm ERR! npm set <key> <value>
npm ERR! npm get [<key>]
----------------------------------
```

#### npm connection error
```
info There appears to be trouble with your network connection. Retrying...
info There appears to be trouble with your network connection. Retrying...
info There appears to be trouble with your network connection. Retrying...
```
