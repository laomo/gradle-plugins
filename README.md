## Gradle Plugins

Android Studio以下简称AS。
####  Hugo
Annotation-triggered method call logging for your debug builds.

`JakeWharton` 大神的作品，log 不再是重复的体力劳动

https://github.com/JakeWharton/hugo

####  SDK Manager Plugin
Gradle plugin which downloads and manages your Android SDK.

`JakeWharton` 大神出品

https://github.com/JakeWharton/sdk-manager-plugin
####  android-apt
The android-apt plugin assists in working with annotation processors in combination with Android Studio. It has two purposes:

* Allow to configure a compile time only annotation processor as a dependency, not including the artifact in the final APK or library
* Set up the source paths so that code that is generated from the annotation processor is correctly picked up by Android Studio.

This plugin requires the android or android-library plugin (version 0.9.x or up) to be configured on your project.

后面提到的很多插件依赖次插件以达到AS中开发的完美体验。

https://bitbucket.org/hvisser/android-apt

#### Dexcount Gradle Plugin
A Gradle plugin to report the number of method references in your APK on every build.

This helps you keep tabs on the growth of your app, with an eye to staying under the 65,536 method-reference limit, and avoiding the headache of eliminating methods or enabling multidex.

https://github.com/KeepSafe/dexcount-gradle-plugin

#### Gradle Versions Plugin
In the spirit of the `Maven Versions Plugin`, this plugin provides a task to determine which dependencies have updates.

AS 对gradle的支持并不完美，目前只能提示SDK以及Support相关的版本更新，不支持第三方插件以及类库的版本更新检查，此插件就是解决这个问题的。

PS：吐槽下，AS目前好多gradle配置还不能很好的识别。

https://github.com/ben-manes/gradle-versions-plugin


####  gag (gradle-android-git)
This is a Gradle plugin to manage Android dependency using Git. Usually, libraries are versioned with group, name and version numbers and you can download from Maven Central repository or jcenter.
But sometimes you might want to use not versioned library.
This project enables you to manage those libraries in your Android app build process.

这个插件提供了一种不错的思路，用 git 管理 libraries 。还没体验过，有兴趣的可以尝试下。

PS：相关的关于类库的使用，提供另一种思路：http://www.philosophicalhacker.com/2014/10/03/an-alternative-multiproject-setup-for-android-studio/

https://github.com/ksoichiro/gradle-android-git

####  packer-ng-plugin
下一代Android打包工具，1000个渠道包只需要5秒
https://github.com/mcxiaoke/packer-ng-plugin
#### Gradle Protobuf Plugin
Gradle plugin for Google Protocol Buffers

https://github.com/andrewkroh/gradle-protobuf-plugin

#### Gradle Protobuf Plugin

Protobuf Plugin for Gradle

https://github.com/google/protobuf-gradle-plugin

####  More Plugins
https://plugins.gradle.org/

####  DIY : Create Your Plugin
https://docs.gradle.org/current/userguide/custom_plugins.html
