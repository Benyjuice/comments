---
title: KDE Neo解决kdialog崩溃问题
date: 2017-06-17
comment: true
articleId: KDE-Neo解决kdialog崩溃问题-md
---
# 安装kde-baseapps-bin
```bash
sudo apt install kde-baseapps-bin
```
# [可选]更改权限
如果安装了kde-baseapps-bin，kdialog提示配置文件权限问题，可将相应目录的权限改成当前的用户

```bash
sudo chown -R $USER:$USER /home/$USER/.kde/
```
