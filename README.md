# Animation Sample
**近期停更 由于进入期末周，代码是半成品，编译出来的APK闪退，先用Release**

使用Kotlin Multiplatform和Compose Multiplatform创建的一个转场动画过渡示例，用于测试自用，然后封装

## 平台
Wasm(JS)、Desktop(JVM)、iOS、Android

## 命令
```bash
./gradlew wasmJsBrowserDevelopmentRun -t # Wasm Run In Development
./gradlew wasmJsBrowserProductRun -t # Wasm Run In Product
./gradlew packageDistributionForCurrentOS # 打包
./gradlew run # Desktop Run
```

## 计划
多层界面嵌套的支持、预测式返回手势适配、打开动画因Navigation而差异的优化、简易化的封装、仿IOS的顶栏转场...

### 演示
![截图](/src/shot.jpg)