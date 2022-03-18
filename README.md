# Shadow
使用java8打包

# 修改版本号
> common.gradle  ext.VERSION_NAME

## 打包执行
```shell
./gradlew publish
```
#更新日志
1.0.1 2022/2/18, 2:54 下午
1.0.4 2022/3/9, 2:40 下午  API 26保留odex过程
1.0.6 2022/3/9, 2:40 下午  增加支付白名单
1.0.7 2022/3/9, 增加日志输出
1.0.8 2022/3/9, 插件里的 so 库路径名称太长加载不成功  pluginConfig.UUID 改为 pluginConfig.UUID.substring(5)