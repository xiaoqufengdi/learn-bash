<!--
 * @Author: xiaoqufengdi 1776394122@qq.com
 * @Date: 2026-06-04 21:22:02
 * @LastEditors: xiaoqufengdi 1776394122@qq.com
 * @LastEditTime: 2026-06-04 22:17:46
 * @FilePath: \learn-bash\README.md
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
# learn-bash
> bash 命令学习笔记
+ [bash脚本教程](https://wangdoc.com/bash/)
## 简介
>Bash 是 Unix 系统和 Linux 系统的一种 Shell（命令行环境），是目前绝大多数 Linux 发行版的默认 Shell
+ Shell 是一个程序，提供一个与用户对话的环境
+ Shell 是一个命令解释器
+ Shell 是一个工具箱，提供了各种小工具，供用户方便地使用操作系统的功能。


## wsl
>WSL (Windows Subsystem for Linux)，即适用于 Linux 的 Windows 子系统
>允许用户在 Windows 操作系统上直接运行原生 Linux 命令
+ 安装linux
```shell
# 可安装的版本（可选）
wsl --list --online
#安装最新版 Ubuntu (推荐)
wsl --install -d Ubuntu

```


## 简介
## shell 种类
>Shell 有很多种，只要能给用户提供命令行环境的程序，都可以看作是 Shell
+ Bash 是目前最常用的 Shell
```shell
# 查看当前设备的默认 Shell
$ echo $SHELL
```

## tmux
>终端复用器。它是一个管理会话和窗口的工具，本身不解释命令，而是为 Shell 提供一个稳定、多窗口的运行环境。

## 命令行环境
+ 中断模拟器-一个模拟命令行窗口的程序
+ 命令提示符
>提示符往往是一串前缀，最后以一个美元符号$结尾，用户可以在这个符号后面输入各种命令。
>[user@hostname] $，其中前缀是用户名（user）加上@，再加主机名（hostname）
+ 进入和退出方法
```shell
$ bash
# 推出 或者ctrl+d
$ exit
$ pwd

```