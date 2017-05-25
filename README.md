# Android 集成 fabric 遇到的问题

由于fabric国内被屏蔽，在Android Studio 中集成 fabric，gradle报错

  Gradle sync failed: Operation timed out. If you are behind an HTTP proxy, please configure the proxy settings either in IDE or Gradle.

或者
  
  Failed to resolve: com.crashlytics.sdk.android:crashlytics:2.6.8

# 解决方案

下载本仓库的第三方库，拷贝到下面的目录

  {YourProjectPath}/app/build/intermediates/exploded-aar
  
其他集成步骤按照fabric官网上的来。
