# LightHouse

LightHouse 是一个微信小程序项目，在测试 mini-program skills 过程中衍生而来。

## 项目简介

这是一个每日饮食摄入记录小程序（Daily Intake），帮助用户追踪和管理日常饮食记录。

### 主要功能

- **今日** — 查看当天的饮食摄入记录
- **记录** — 浏览历史饮食记录列表
- **添加记录** — 新增饮食摄入条目
- **我的** — 个人中心与设置

## 技术栈

- 微信小程序原生开发
- 微信云开发（云函数 + 云数据库）
- 自定义 TabBar 组件

## 项目结构

```
├── app.js / app.json / app.wxss   # 小程序入口与全局配置
├── pages/
│   ├── index/                     # 今日页面
│   ├── list/                      # 记录列表页面
│   ├── add-record/                # 添加记录页面
│   └── profile/                   # 个人中心页面
├── components/                    # 公共组件
├── custom-tab-bar/                # 自定义底部导航栏
├── cloudfunctions/                # 云函数
└── utils/                         # 工具函数
```

## 开发环境

1. 安装 [微信开发者工具](https://developers.weixin.qq.com/miniprogram/dev/devtools/download.html)
2. 导入本项目
3. 在微信开发者工具中开通云开发环境
4. 编译运行
