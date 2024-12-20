---
title: 【教程】MacOS使用Shutter Encoder压制视频小版本
date: 2024-11-06 20:00:00 +0100
description: 简单介绍Mac系统压制小版本的方法

categories: [字幕组, 教程]
tags: [字幕组, 教程, 小版本, Shutter Encoder]
---

## 软件安装

1. 打开Shutter Encoder的官网：[https://www.shutterencoder.com](https://www.shutterencoder.com)
   
   <center><img src= "/assets/img/post/2024-11-06-how-to-compress-video-by-shutter-encoder/website.webp" alt = "Offical Website"></center>
   <br/>

2. 点击Downloads，跳转到下方的下载区域。
   
   <center><img src= "/assets/img/post/2024-11-06-how-to-compress-video-by-shutter-encoder/downloads.webp" alt= "Downloads"></center>
   <br/>

3. 将中间的捐赠滑动条拖到最左边，即捐赠0美元。然后根据自己的系统及CPU型号选择对应的版本。早期苹果电脑请选择Intel版本，M1芯片及之后的产品请点击Apple Silicon。
   <br/>

4. 之后会跳出下载界面，不同浏览器的显示方式不同，保存后双击打开或直接打开均可。
   
   <center><img src="/assets/img/post/2024-11-06-how-to-compress-video-by-shutter-encoder/versions.webp" alt="Firefox浏览器下载界面"><figcaption>firefox浏览器</figcaption></center>

    <center><img src="/assets/img/post/2024-11-06-how-to-compress-video-by-shutter-encoder/versions2.webp" alt="Edge浏览器下载界面"><figcaption>Edge浏览器</figcaption></center>
    <br/>

5. 打开安装界面后，一路点击继续，期间会需要同意协议，以及输入Apple ID的密码或用指纹替代。
   
   <center><img src="/assets/img/post/2024-11-06-how-to-compress-video-by-shutter-encoder/install1.webp" alt="Shutter Encoder安装界面"></center>

    <center><img src="/assets/img/post/2024-11-06-how-to-compress-video-by-shutter-encoder/install2.webp" alt="Shutter Encoder安装界面"></center>

    <center><img src="/assets/img/post/2024-11-06-how-to-compress-video-by-shutter-encoder/install3.webp" alt="Shutter Encoder安装界面"></center>
    <br/>
6. 安装结束后可将安装文件移到废纸篓，或自行删除。
   
    <center><img src="/assets/img/post/2024-11-06-how-to-compress-video-by-shutter-encoder/install4.webp" alt="Shutter Encoder安装界面"></center>
    <br/>

7. 以上步骤完成后软件会自动打开。

   <center><img src="/assets/img/post/2024-11-06-how-to-compress-video-by-shutter-encoder/se1.webp" alt="Shutter Encoder主界面"></center>
    <br/>

8.  点击左上角的齿轮按钮打开设置，在 `Set language to` 中可以将语言切换为简体中文。下面的教程将标注中英双语。

   <center><img src="/assets/img/post/2024-11-06-how-to-compress-video-by-shutter-encoder/language.webp" alt="选择语言"></center>
   
## 参数调节

1. 点击顶部的 `Browse/浏览` ，选择你需要压缩小版本的视频片源。

   <center><img src="/assets/img/post/2024-11-06-how-to-compress-video-by-shutter-encoder/choose_video.webp" alt="选择视频"></center>
   <br/>

2. 在下方的 `Choose function/选择功能` 中选择希望使用的视频编码格式，通常使用 `H264` 。 `H265` 的压缩比例会更高一些，对解码性能的要求也比较高，电脑配置一般的志愿者播放H256视频可能会卡顿，所以不建议小版本使用。

   <center><img src="/assets/img/post/2024-11-06-how-to-compress-video-by-shutter-encoder/choose_function.webp" alt="选择编码"></center>
   <br/>

3. 栏位下方的蓝色字 `Same as source/与来源相同` 指压制的文件将会保存在片源相同的文件夹中，如果希望自定义，请点击旁边的 `Change/更改` 。
   <br/>
   

4. 点击编码格式后，界面会扩张成三栏，在右上方的 `Scale/比例` 中选择合适的分辨率。
   
   <center><img src="/assets/img/post/2024-11-06-how-to-compress-video-by-shutter-encoder/scale.webp" alt="scale"></center>
   <br/>

5. 需要注意的是，系统给出的分辨率选项们长宽比并不统一，需要寻找与片源相同的类型进行缩放。如果选择了不同的长宽比，则可以明显看到中间的画面出现了黑边宽度变化。保险一些的方式是可以直接选择最下方的 `50%` ，这代表影片在长宽比例不变的情况下分辨率减半。
   
   <center><img src="/assets/img/post/2024-11-06-how-to-compress-video-by-shutter-encoder/scale2.webp" alt="scale2"></center>
   <br/>

6. 右侧中央的 `File size/文件大小` 栏可以根据你的设置提前预估压制后的文件大小。通常小版本视频长片控制在500MB左右即可，最大不要超过700MB，否则会增加其他志愿者的下载负担。
   

## 小版本压制

1. 当通过调整设置将文件体积压缩到合适的大小后，就可以点击左侧 `Choose function/选择功能` 中的 `Start function/启动功能` 按钮，程序将开始压制小版本。此时按钮变为 `Pause/暂停`。如果觉得设置有误，可以点击右侧的 `Cancel/取消` 提前结束本次压制。
   
   <center><img src="/assets/img/post/2024-11-06-how-to-compress-video-by-shutter-encoder/start.webp" alt= "start"></center>
   <br/>

2. 压制完成后请检查视频大小是否成功减少，以及能否正常播放，简单拖动进度条确保没有因为压制异常产生的黑屏或色块。
   
   <center><img src="/assets/img/post/2024-11-06-how-to-compress-video-by-shutter-encoder/file.webp" alt="file"></center>
   <br/>
   
   

