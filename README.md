# JetBrainsRuntime-for-Linux-x64  
使用 Github Actions 每月 2 日定时把社区大佬 “每月 1 日定时编译社区大佬改进的 JetBrainsRuntime 的 Linux x64 版本” 自动更新到 AUR 上。  

## 说明  
解决在 Linux x64 操作系统环境下，使用 JetBrains 系 IDE 存在的两个问题： 
  - fcitx 输入法候选框不跟随光标  
  - Markdown 文件无法正常预览  

使用方法（激进）：  
  - 直接替换 IDE 安装目录下的 jbr 目录  

## 参考  
[idea 中文输入法定位不准问题修复(fcitx框架输入法)](https://blog.csdn.net/u011166277/article/details/106287587)  
[BUG解决之路-1 Linux下fcitx输入法候选框在IDEA等JetBrains系列IDE中不跟随光标（JetBrains Runtime版本：11.0.7）](https://blog.csdn.net/qq_41859728/article/details/109187748)  

