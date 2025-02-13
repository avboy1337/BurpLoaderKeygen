# BurpLoaderKeygen <img src="https://img.shields.io/static/v1?label=JAVA&message=v8%2B&color=blue"> <img src="https://img.shields.io/static/v1?label=BurpSuitePro&message=1.7%2b&color=blue"> <img src="https://img.shields.io/static/v1?label=System&message=Windows | Linux | macOS&color=blue"> <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/h3110w0r1d-y/BurpLoaderKeygen?style=social">
Burp Suite Pro Loader &amp; Keygen ( v1.7-v2022.8 )
## ‼️ Only v2022.8 and below is supported, for v2022.9 and above, please use ja-netfilter. https://github.com/h3110w0r1d-y/BurpLoaderKeygen/issues/22
## ‼️ 只支持 v2022.8 及以下版本, v2022.9 及以上版本请使用ja-netfilter激活. https://github.com/h3110w0r1d-y/BurpLoaderKeygen/issues/22
## **项目仅供学习和交流使用，商业使用请购买正版软件！链接:https://portswigger.net/burp**
## **This project is only for learning and communication. For commercial use, please buy genuine software! Link:https://portswigger.net/burp**
### 本项目由以下项目整合而成 / This project is integrated by the following projects 
- https://github.com/x-Ai/BurpSuiteLoader
- BurpSuitePro Loader&Keygen By surferxyz

### 特性 / Features
- 检测Burp更新，如果不需要检测请勾选`Ignore Update`
- 不用编写脚本，自动启动burp，只需要勾选`Auto Run`
- 支持指定Java版本，只需要把指定版本的Java放到同目录下，注册机会自动调用
- 支持Java8及以上所有版本
- 支持BurpSuite v1.7-v2022.8

- Detect burp updates. If you don't need, please check `Ignore Update` 
- Auto start burp without write command manually, just check `Auto Run`
- Support for specifying java versions, just put java files in same path
- Support Java 8+
- Support BurpSuite v1.7-v2022.8

### **Jar包未混淆，欢迎dalao们改进！**

## BUG

如果发现BUG，欢迎提交Issues

## Mac版食用方法

安装Mac版Burp

将注册机放置到`/Applications/Burp Suite Professional.app/Contents/Resources/app`目录下

执行以下命令启动注册机

```
cd "/Applications/Burp Suite Professional.app/Contents/Resources/app"
"/Applications/Burp Suite Professional.app/Contents/Resources/jre.bundle/Contents/Home/bin/java" -jar BurpLoaderKeygen.jar
```

点击run启动Burp, 激活后关闭注册机

修改`/Applications/Burp Suite Professional.app/Contents/vmoptions.txt`, 增加两行

```
-javaagent:BurpLoaderKeygen.jar
-noverify
```

之后便可以正常启动了

## 其他系统食用方法

0. 将BurpLoaderKeygen.jar、burpsuite_pro_v20**.*.jar 放到同一目录下(也可将指定版本的Java放到目录中，注册机会自动调用)
![image](https://user-images.githubusercontent.com/52311174/136488232-bae027a6-8f9a-45eb-9d6c-e0b150084170.png)

1. 直接双击 BurpLoaderKeygen.jar 或者 `java -jar BurpLoaderKeygen.jar`

2. 点击`Run`，输入许可证然后选择**手动激活**即可

3. 激活后勾选`Auto Run`，打开BurpLoaderKeygen.jar即可自动启动BurpSuite，不显示注册机窗口，但会在后台自动检测Burp更新，当检测到更新时将显示注册机，你可以勾选`Ignore Update` 来禁止检测更新，启动Burp后注册机直接退出。
