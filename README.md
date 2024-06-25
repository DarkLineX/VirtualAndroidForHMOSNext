# VirtualAndroidForHMOSNext
Running Android .apk file on harmonyos Next . 

在您的鸿蒙Next系统上流畅的运行 .apk 安卓应用

如果你需要用安卓运行鸿蒙应用请前往这个项目>>[VirtualHMOSNextForAndroid](https://github.com/Eeeextend/VirtualHMOSNextForAndroid)

### 提示

因为本人还没拿到正式版本的鸿蒙Next设备，所以该项目还存在于PPT阶段。


#### 虚拟机方案选择

#### 方案1:全量代理 植入aosp framwork层

通过对apk的代理，将四大组件注册到植入的framework层完全代理，让apk感觉自己运行在安卓系统中。

#### 方案2:重打包

通过资源重组的方式，将apk文件转化成等效的hap文件。

#### 方案3:直接qemu运行虚拟系统

使用qemu载入一个裁剪版本的Android OS系统来运行apk文件。


综合考虑下来方案3是最合适的方案。
