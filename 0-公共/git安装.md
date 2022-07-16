

# Git检查

首先看看系统有没有安装Git。

##window检查

Win+R然后在输入框输入cmd,打开cmd命令行工具，然后执行命令：

```
git --version
```

未安装



已安装：

![1657929640274](E:\gitApp\vuepress-devkit\image\1657929640274.png)

git安装在哪

执行命令：

```
where git
```

![1657931598978](E:\gitApp\vuepress-devkit\image\1657931598978.png)

## linux检查

输入`git`，看看系统有没有安装Git。

```
$ git
The program 'git' is currently not installed. You can install it by typing:
sudo apt-get install git
```

上面的命令告诉你Git没有安装，同时也告诉你如何安装Git.



# Git安装

## window安装
从 http://git-scm.com/download 上下载window版的客户端，以管理员身份运行后，一直选择下一步安装即可，请注意，一般情况保持默认的选项即可。

## Debian或Ubuntu安装

打开终端，然后执行命令：
```
apt-get install git
```

## Centos或Redhat安装
打开终端，然后执行命令：
```
yum install git
```

##SUSE或OPENSUSE安装

打开终端，然后执行命令：

```
sudo zypper install git
```

## Mac安装

### 通过homebrew

先安装homebrew，然后通过homebrew安装Git，具体方法参考：<http://brew.sh/>。

### Xcode

Xcode是Apple官方IDE，功能非常强大，是开发Mac和iOS App的必选装备，而且是免费的！

安装步骤：

1. 从AppStore安装Xcode
2. 运行Xcode，选择菜单“Xcode”->“Preferences”.
3. 在弹出窗口中找到“Downloads”，选择“Command Line Tools”，点“Install”。



# Git 验证

可参考Git检查。