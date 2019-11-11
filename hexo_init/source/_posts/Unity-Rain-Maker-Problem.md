---
title: '[Unity] Rain Maker Problem'
date: 2019-11-11 18:04:53
tags: Unity
---

使用插件Rain Maker时，发现雨滴无法落下。

经过两天的各种查找，发现是在使用cinemachine时，用了polygon collider 2d，导致雨滴无法落下。

在修改雨滴层数和Confiner层数后，发现雨滴依旧无法落下。

再次查看rain maker的Inspector界面后，发现它本身也有Collision Mask的选项。根据需要调整发生collision的对象。

可下雨了。

![rain](/images/rain.jpg)
