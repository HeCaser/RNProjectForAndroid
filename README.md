# 这是一个 RN 项目， 按照官方文档创建

- 目的是为了生成一个运行在 Android 设备上的 App

- 这是一个纯粹的 RN 项目，默认支持 Android 与 iOS 构建， 这里仅使用 Android

官方文档：
https://reactnative.dev/docs/environment-setup

---

2023-03-10 初次构建

## 步骤
- 命令行创建项目： npx react-native@latest init RNProjectForAndroid

- 启动 Metro， 在项目所在目录下，执行命令： npx react-native start. 启动成功,控制台输出如图所示信息

    <img src='01runmetro.png'>

- 编译构建 App。
  - 保留 Metro 所在的终端， 新启一个终端
  - 执行命令 npx react-native run-android
  - 过程若报错，依次解决