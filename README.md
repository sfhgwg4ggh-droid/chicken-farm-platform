# 全自动化养鸡监测平台 v2.0

智慧养殖管理平台 — 覆盖环境监测、鸡群健康、饲料管理、数据分析的全栈 Web 应用。

## 功能清单

| 模块 | 功能 |
|------|------|
| 🐔 **鸡群管理** | 品种数据库(8品种)、生长曲线模拟、产蛋跟踪、免疫管理、批量操作 |
| 📊 **行情交易** | 多品种实时行情、价格趋势、预警系统、批量买卖 |
| 📈 **统计报表** | 产蛋趋势图、品种分布饼图、死亡统计、鸡蛋销售记录 |
| 🌤️ **天气预报** | Open-Meteo 免费 API + 和风天气 API + 模拟兜底、养殖气象建议 |
| 🌡️ **大棚监测** | 多温室温湿度监控、阈值告警、历史曲线 |
| 📡 **监控通道** | API 连接检测、网络延迟测速、室外气温传感器 |
| 📹 **视频监控** | IP 摄像头 (MJPEG/RTSP/Snapshot)、USB 摄像头、截图回看 |
| ⚙️ **自动化** | 自动喂食/喂水、自动产蛋收集、行情天气自动刷新、传感器模拟 |

## 设计规范

- **配色**: 自然系暖色调 — 大地绿 `#4A7C59`、麦穗金 `#D4A853`、泥土棕 `#8B6914`、天空蓝 `#87CEEB`
- **字体**: 中文优先苹方/思源黑体，数字/英文用系统 UI 字体
- **间距**: 8px 网格系统，内容区最大宽度 1400px
- **圆角**: 8px（卡片）、4px（按钮）、全圆（标签/徽章）
- **数据来源**: Open-Meteo 免费天气 API，默认坐标商洛市山阳县 (lat=33.53, lon=109.88)

## 技术栈

- 纯前端 HTML/CSS/JS 单文件应用
- Chart.js 4.x 数据可视化
- localStorage 数据持久化
- Open-Meteo 免费天气 API（无需 API Key）
- 预留：和风天气 API、聚合数据 API

## 快速开始

```bash
# 直接用浏览器打开
start index.html

# 或用任意 HTTP 服务器
npx serve .
# Python: python -m http.server 3000
```

## 部署到 GitHub Pages

1. 在 GitHub 创建仓库 `chicken-farm-platform`
2. 推送代码：
```bash
git remote add origin https://github.com/sfhgwg4ggh-droid/chicken-farm-platform.git
git branch -M main
git push -u origin main
```
3. 在仓库 Settings → Pages → Source 选择 `main` 分支，根目录
4. 访问 `https://sfhgwg4ggh-droid.github.io/chicken-farm-platform/`

## License

MIT
