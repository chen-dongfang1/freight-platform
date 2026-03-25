# 货运+代驾双平台系统

基于 Telegram Bot 的货运与代驾平台，支持用户下单、司机接单、管理后台。

## 🚀 功能特点

### 用户端（Telegram Bot）
- 货运下单：输入取货/送货地址，自动计算价格
- 代驾下单：输入当前位置/目的地，自动计算价格
- 订单状态查询
- 确认完成订单

### 司机端（Telegram Bot）
- 司机注册（姓名、电话、车型/驾龄）
- 查看待接订单
- 抢单/接单
- 查看已接订单
- 提现申请

### 管理后台（Web）
- 订单列表展示（支持货运/代驾分类）
- 统计卡片（总订单、待接单、已完成）
- 订单详情查看
- CSV 数据导出
- 订单状态修改

## 🛠️ 技术栈

- **后端**：Python / Flask
- **Bot**：python-telegram-bot
- **地图**：Google Maps API
- **前端**：Bootstrap 5
- **部署**：阿里云轻量服务器

## 📸 功能截图

### 管理后台
![管理后台](https://via.placeholder.com/800x400?text=Admin+Panel)

### Telegram Bot
![Telegram Bot](https://via.placeholder.com/400x600?text=Telegram+Bot)

## 🔧 本地运行

1. 克隆仓库
```bash
git clone https://github.com/chen-dongfang1/freight-platform.git
cd freight-platform
