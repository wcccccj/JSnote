# npm卸载并更换指定版本插件



```
//查看版本
npm ls -g --depth=0

//卸载
npm uninstall -g 插件名称

//安装特定版本
npm install -g 插件名称@指定版本

// 删除node_modules
rm -rf node_modules

// 删除版本锁定文件
rm package-lock.json

// 清楚npm缓存
npm cache clear --force
```

