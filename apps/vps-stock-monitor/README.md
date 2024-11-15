# VPS Stock Monitor

VPS Stock Monitor 是一个简单的库存监控工具，支持通过配置监控多个商品，并在库存状态变化时，通过 Telegram、微信或自定义 URL 通知用户。该工具提供了一个基于 Flask 的 Web 界面，用户可以通过浏览器轻松管理配置和监控项。

## 功能

- **库存监控**：支持监控多个商品的库存状态，支持判断商品是否有货。
- **通知方式选择**：可以选择通过 Telegram、微信或自定义 URL 发送库存变更通知。
- **Web 控制台**：基于 Flask 提供一个简单的 Web 控制台，用于添加、删除、暂停监控项和配置通知。
- **定时监控**：支持定时检查商品的库存状态，并在状态变化时发送通知。