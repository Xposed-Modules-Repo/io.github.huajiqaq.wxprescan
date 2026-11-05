# WeChatPreScan

**微信 / 企业微信相册、长按扫码结果按相机来源处理。**

- 作用域：`com.tencent.mm`、`com.tencent.wework`
- 框架：LibXposed API 102
- 无界面，日志 TAG `WxPreScan`
- 源码：[huajiqaq/WeChatPreScan](https://github.com/huajiqaq/WeChatPreScan)

## 1.1

- 新增企业微信支持（适配基于 5.0.13.84802）。
- 企业微信来源 1013 / 1012 → 1011，小程序来源 2 / 3 / 4 → 1。
- 微信保持原 QBar 来源改写。
- 修复热重载状态交接。
