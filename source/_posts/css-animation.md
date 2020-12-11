---
title: Css 动画
date: 2020-12-11 15:05:25
------
##### 页面带音乐播放按钮，控制按钮旋转播放，代码如下:
```
  @keyframes turn {
    0% {
      -webkit-transform: rotate(0deg);
    }
    25% {
      -webkit-transform: rotate(90deg);
    }
    50% {
      -webkit-transform: rotate(180deg);
    }
    75% {
      -webkit-transform: rotate(270deg);
    }
    100% {
      -webkit-transform: rotate(360deg);
    }
  }

  animation: turn 5s linear infinite;
```
##### 音乐播放暂停属性控制:
```
animationPlayState: musicPlay ? 'running' : 'paused'
```
-----




