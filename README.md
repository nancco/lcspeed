# Lcspeed 极客纯净测速
浏览器端纯前端测速工具箱，**不需要后端，打开HTML直接本地运行**，无广告。

>[![Live Demo](https://img.shields.io/badge/Live--Demo-Online-22c55e?style=flat-square&logo=firefox)](https://nancco.github.io/lcspeed/)
[![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)](LICENSE)
> > ⚠️ 注意：GitHub Pages在线演示受浏览器跨域限制，**公网IP获取、部分网络接口会大概率失败**；完整体验建议：下载 `index.html` 在本地浏览器打开。

浏览器端纯前端测速工具箱，**不需要后端，打开HTML直接本地运行**，无广告。

> ⚠️ 说明：网页JS**无法读取局域网内网IP**；公网IP依赖第三方公网API接口，网络环境差的时候可能获取失败。

## 功能列表
- 网络测速：下载、上传、HTTP‑延迟抖动、DNS耗时，测速历史本地 localStorage 保存
- 工具箱：IPv4 CIDR子网计算器、Unix时间戳转换、Base64(修复中文)、IP归属地查询
- PC端：键盘无冲测试、鼠标DPI测算、鼠标微动连点检测、鼠标回报率测试(pointer‑lock)
- 移动端：屏幕刷新率测试、多点触控+触控采样测试

## 使用
1. 下载 index.html
2. 浏览器直接打开本地文件即可，**不需要服务器**
3. 网络类功能（获取公网IP、测速、IP归属查询）需要联网；计算类全部纯本地运行

## 注意事项
1. 获取公网IP依赖海外API，国内网络环境有可能超时失败
2. HTTP延迟 ≠ 系统ICMP ping，是HTTP请求耗时，会包含DNS/TCP握手开销
3. 鼠标回报率使用浏览器 PointerLock API，部分浏览器/iframe会被限制
4. 触控采样率为浏览器上报事件，不等于硬件真实采样率
