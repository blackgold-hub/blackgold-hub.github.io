---
title: 零基础建立自己的博客
date: 2023-03-10 10:03:53
tags:
hidden: true
---

> 本文使用的是由[云游君](https://www.yunyoujun.cn/)开发的静态博客框架[valaxy](https://valaxy.site/?lang=zh-CN)
> 过程有些复杂，但只要有耐心，按照步骤来并没有难度

## 环境配置 ##
下载安装[node.js](https://nodejs.org/zh-cn/download/)，版本>14.18
下载安装[git](https://git-scm.com/)最新版
下载安装[TortoiseGit](https://tortoisegit.org/)最新版

## 注册Github ##
注：如果已经拥有Github账号可以跳过这一步。
注册账号完成后，进入[Github](https://github.com/)，创建新的Repo，命名为`` [你自己的ID].github.io ``
完成后，打开本地文件夹，将项目克隆进来。

## 创建Valaxy ##
进入clone下来的文件夹，右键--打开Gitbash
安装 pnpm：`` npm i -g pnpm ``
创建：`` pnpm create valaxy ``

按照步骤完成创建后，会自动启动
输入地址可以查看demo
``` http://localhost:4859/ ```

## 部署 ##
进入项目文件夹，提交代码，右键--git commit
完成后点击push
