# 智能养鸡平台 — 项目配置

## 快速信息
- 本地路径: `c:/Users/Faith/Desktop/chicken-farm-platform/`
- 在线地址: `http://zhushishunsui.cloud` (HTTPS 等待中)
- GitHub: `github.com/sfhgwg4ggh-droid/chicken-farm-platform`
- Cloudflare Zone: `7ec45c0c0658cf5e7feedbebffcdf25d`

## 本地启动
```bash
# 直接浏览器打开
start index.html

# 或 HTTP 服务器
npx serve .
```

## Git
```bash
cd "c:/Users/Faith/Desktop/chicken-farm-platform/"
# Remote: git@github.com:sfhgwg4ggh-droid/chicken-farm-platform.git
# Branch: main
# SSH: ~/.ssh/id_ed25519
```

## 域名/DNS
- 注册商: 腾讯云 (dnspod)
- NS: autumn.ns.cloudflare.com, kyrie.ns.cloudflare.com
- DNS 管理: Cloudflare (免费计划)
- 记录: @ 和 www → CNAME → sfhgwg4ggh-droid.github.io (橙色代理)

## 外部 API
- 天气: Open-Meteo (免费, 无需 Key), 默认城市商洛(33.53,109.88)
- 备用: 和风天气 (devapi.qweather.com)
- 行情: 聚合数据 (juhe.cn) 或自定义 API

## 设计 Token
- primary: #4A7C59, accent: #D4A853
- bg: #f5f1eb, radius: 8px, shadow: 0 1px 4px rgba(0,0,0,.06)
