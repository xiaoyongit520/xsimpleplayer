# XsimplePlayer
[![](https://jitpack.io/v/xiaoyongit520/XsimplePlayer.svg)](https://jitpack.io/#xiaoyongit520/XsimplePlayer)
### 自己封装的一个基于Vitamio播放器lib
#### 1.添加中央库
gradle
```java
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
#### 2.添加引用
```java
	dependencies {
	        compile 'com.github.xiaoyongit520:XsimplePlayer:{version}'
	}
```


#### 3.使用方式见demo  
【注意】manifests里面Actvity的声明方式,视频播放器的根布局一定要设置为 android:fitsSystemWindows="true" 否则视频控制界面会出现错位。
