# AndroidVesyncCN-GlobalBuild
Android Vesync中国区全局编译配置环境
## 文件说明
### 1. component-base-config.gradle
组件的build.gradle公共配置，主要配置 `compileSdkVersion,buildToolsVersion,minSdkVersion,targetSdkVersion`等属性，保证每个组件的环境一致。
同时配置了其他的公共配置和公共依赖
### 2. component-base-publish.gradle
组件打包aar的gradle task配置文件
### 2. component-dev-config.gradle
读取根目录下的local.properties文件里的配置，控制组件是否进行源码以来，防止配置代码误传到git上
