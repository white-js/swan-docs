---
title: 云开发用户集成介绍
header: develop
nav: cloud
sidebar: cloud_essentials_user
---

# 云开发用户集成介绍

云开发整合了小程序使用者的用户体系，无论用户是否已经登陆宿主应用，都会对应一个唯一ID。开发者可以利用这个用户ID在云函数中扩展自己的用户相关业务逻辑，也可以将它应用在云存储和数据库资源中。通过云开发中托管资源的安全规则，在使用小程序端 SDK 访问这些资源时，云开发可以识别用户身份，进而实现访问权限控制。在未来的版本中，开发中还可以自己定义不同资源的访问安全规则，实现更灵活的权限控制。