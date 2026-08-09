## 变更

- 新增澎湃超级岛
- 新增状态栏电压、电流显示
- 新增状态栏图标显示使用系统默认字体（非主题字体）
- 支持 [OPlus-MMS-Unlock-via-OPBATT](https://github.com/yangFenTuoZi/OPlus-MMS-Unlock-via-OPBATT) 采样解限
- 解决国内 CDN 缓存导致收不到更新的问题
- 修复原本开关控件在非 TonalSpot 配色下对比度过低问题
- 修复某个极特殊系统实现中注册电量报警通知导致的崩溃
- 修复 OriginOS5 系统上通知崩溃
- 修复息屏掉电百分比统计异常
- 修复 ImGUI 悬浮窗大小更新延迟的问题
- 优化一些文本
- 服务架构重构

## Changes

- Added HyperOS Super Island support
- Added status-bar voltage and current display
- Added an option for status-bar icons to use the system default font instead of the theme font
- Added support for sampling-limit unlocking via [OPlus-MMS-Unlock-via-OPBATT](https://github.com/yangFenTuoZi/OPlus-MMS-Unlock-via-OPBATT)
- Fixed update checks being blocked by domestic CDN caching
- Fixed insufficient contrast of the original switch component under non-TonalSpot color schemes
- Fixed a crash when registering battery-level alert notifications on a very specific system implementation
- Fixed notification crashes on OriginOS 5
- Fixed incorrect screen-off battery-drain percentage statistics
- Fixed delayed ImGui overlay window size updates
- Improved some text
- Refactored the service architecture