# 贴切NPM源



## WHAT

淘宝源是npmjs.org的镜像，可以替代我们在安装包时使用的数据源是国内的服务器资源，保证下载速度

## WHY

防止npm安装依赖时的安装失败，安装速度慢的问题

## HOW

使用`cnpm`代替`npm`

```
$ npm install -g cnpm --registry=https://registry.npm.taobao.org
```

替换npm源

```
alias cnpm="npm --registry=https://registry.npm.taobao.org \
--cache=$HOME/.npm/.cache/cnpm \
--disturl=https://npm.taobao.org/dist \
--userconfig=$HOME/.cnpmrc"

# Or alias it in .bashrc or .zshrc
$ echo '\n#alias for cnpm\nalias cnpm="npm --registry=https://registry.npm.taobao.org \
  --cache=$HOME/.npm/.cache/cnpm \
  --disturl=https://npm.taobao.org/dist \
  --userconfig=$HOME/.cnpmrc"' >> ~/.zshrc && source ~/.zshrc

```



### source

https://developer.aliyun.com/mirror/NPM?from=tnpm