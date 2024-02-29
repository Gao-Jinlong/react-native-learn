## 运行 android 

```bash
npm run start
```

启动 android studio, 打开 android 目录, 点击运行按钮即可运行 android 项目，如果没有 virtual device 需要先创建一个 virtual device

需要注意的是, 如果是第一次运行, 会下载 gradle, 默认访问 google 服务器，即使挂梯子也会非常慢，可以在 android 目录下的 `gradle/wrapper/gradle-wrapper.properties` 文件中修改 `distributionUrl` 为国内镜像地址

```bash
# 腾讯镜像地址
https://mirrors.cloud.tencent.com/gradle/
```