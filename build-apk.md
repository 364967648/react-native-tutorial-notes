# ReactNative项目打包发布操作流程

## 第一步
* 在项目根目录下运行打包
```
react-native ram-bundle --entry-file index.js --platform android --dev false --bundle-output ./android/app/src/main/assets/index.android.bundle --assets-dest ./android/app/src/main/res/
```
## 第二步
* 借助于Android Studio生成 keystore签名文件 或者通过命令行

## 第三步
* 打包生成app
