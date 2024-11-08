---
title: 【教程】MacOS压制Ass字幕
date: 2024-11-07 20:38:00 +0100
description: 尝试压制组在MacOS上工作的可能

categories: [字幕组, 教程]
tags: [字幕组, 教程, 压制]
---

## 软件安装
1. 在Mac上执行压制需要用到两个软件：
    - MKVToolNix
    - HandBrake
    
2. MKVToolNix用于将视频与Ass字幕打包为一个mkv文件，可以在官网 [https://mkvtoolnix.download/macos/](https://mkvtoolnix.download/macos/) 进行下载。截止撰稿日，最新的版本号为88.0。
   
   <center><img src="/assets/img/post/2024-11-07-how-to-compress-final-video-in-mac/mkvtoolnix_download.png" alt= "mkvtoolnix.download"></center>
    <br/>
   <center><img src="/assets/img/post/2024-11-07-how-to-compress-final-video-in-mac/mkvtoolnix_download2.png" alt= "mkvtoolnix.download2"></center>
    <br/>
3. 下载后打开dmg文件，将 `MKVToolNix-88.0` 图标拖动到Applications文件夹中，即完成安装。
   
   <center><img src="/assets/img/post/2024-11-07-how-to-compress-final-video-in-mac/mkvtoolnix_install.png" alt= "mkvtoolnix.install"></center>
   <br/>
4. 同理我们从官网 [https://handbrake.fr/](https://handbrake.fr/) 下载HandBrake的dmg安装包并打开。区别在于这次我们要自己开启 `访达/Finder` 将程序拖动到应用程序文件夹中。
   
   <center><img src="/assets/img/post/2024-11-07-how-to-compress-final-video-in-mac/handbrake_install.png" alt= "handbrake.install"></center>
   <br/>
   
5. 之后便可以在系统启动台中找到新安装的两个软件。
   
   <center><img src="/assets/img/post/2024-11-07-how-to-compress-final-video-in-mac/mkvtoolnix_open.png" alt= "mkvtoolnix.open"></center>
   <br/>

## 生成外挂字幕.mkv档案

1. 开启MKVToolNix，点击 `Add source files` ，将片源和已经制作好的Ass字幕一起添加进去。
   
   <center><img src="/assets/img/post/2024-11-07-how-to-compress-final-video-in-mac/mkvtoolnix_add_files.png" alt= "mkvtoolnix.add.files"></center>
   <br/>
2. 然后点击 `Start multiplexing` ，将视频与字幕合并。由于不涉及编码，通常瞬间就会完成，并存放在下方的 `Destination file` 路径中。
   
   <center><img src="/assets/img/post/2024-11-07-how-to-compress-final-video-in-mac/mkvtoolnix_start.png" alt= "mkvtoolnix.strat"></center>
   <br/>
3. 打开生成的文件，检查字幕是否有顺利添加。推荐使用开源播放器 `VLC` 或 `IINA` ，因为系统自带的 `QuickTime Player` 无法打开.mkv文件。
   
   <center><img src="/assets/img/post/2024-11-07-how-to-compress-final-video-in-mac/mkvtoolnix_result.png" alt= "mkvtoolnix.result"></center>
   <br/>

## 压制硬字幕版本

1. 打开 `HandBrake` ，选择刚才生成的.mkv文件。
   
    <center><img src="/assets/img/post/2024-11-07-how-to-compress-final-video-in-mac/handbrake_open.png" alt= "handbrake.open"></center>
   <br/>
2. 此处提供一个预设文件，可以直接导入以减少配置负担。参考了[V2EX网友的帖子](https://fast.v2ex.com/t/1060444)，根据我们组的习惯进行了调整。
   
   
3.  

