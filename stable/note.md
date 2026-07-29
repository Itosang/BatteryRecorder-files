## 变更

### 记录器（Server）

- 适配“公平运行内存”机制
- 适配 Android 10~17
- 新增无障碍服务模式
- 新增实时功耗悬浮窗
- 新增充放电电量报警
- 新增状态栏图标数据显示
- 新增电池状态校准
- 新增点击实时通知点击打开 App
- 新增 Magisk 自启动模块
- 新增“兼容设置”：轮询获取前台 App
- 修复 HyperOS 打开通知崩溃、通知不显示等等问题
- 移除“批量大小” / “写入延迟设置”
- 优化 OneUI / AOSP 系统下通知图标
- 独立通知分组，防止通知同 Metric 通知折叠
- 不记录小窗 App

### 查看器（App）

- 适配“公平运行内存”机制
- 新增续航预测分数
- 新增记录详情长截图设备信息
- 新增 Alpha 版本更新检测
- 新增更新检测时大陆加速
- 新增 App 内置离线手册
- 新增独立“兼容设置”页，包含：

    - 轮询获取息屏状态 (HyperOS / MagicOS / OriginOS 默认开启)
    - 轮询获取前台 App (HyperOS 默认开启)
    - 通知兼容模式 (OriginOS 默认开启)

- 新增独立“关于”页，支持手动检查更新，加入开源许可声明
- 新增独立“主题”设置页，预测性返回手势开关、多种主题、HDR 实时曲线
- 新增充电时也可查看续航预测
- 新增历史列表标记最近查看的记录
- 新增历史记录备注
- 新增手动重启服务按钮
- 修复温度曲线 0 度以下被截断的问题
- 优化首页统计、续航预测与息屏功耗统计算法

### 通用

- 一些架构重构
- 优化一些异常捕获、崩溃处理

## Changes

### Recorder (Server)

- Added support for the Fair Memory mechanism
- Added support for Android 10–17
- Added Accessibility Service mode
- Added a real-time power overlay
- Added battery level alerts for charging and discharging
- Added data display in the status bar icon
- Added battery status calibration
- Tapping the real-time notification now opens the app
- Added a Magisk auto-start module
- Added a compatibility setting for polling the foreground app
- Fixed crashes and missing notifications on HyperOS, among other issues
- Removed the Batch Size and Write Delay settings
- Improved notification icons on One UI and AOSP-based systems
- Separated notification groups to prevent notifications from collapsing with Metric notifications
- Apps running in floating windows are no longer recorded

### Viewer (App)

- Added support for the Fair Memory mechanism
- Added battery life prediction scores
- Added device information to long screenshots of record details
- Added update checks for Alpha releases
- Added mainland China acceleration for update checks
- Added a built-in offline user guide
- Added a dedicated Compatibility Settings page with:

    - Screen-off status polling (enabled by default on HyperOS, MagicOS, and OriginOS)
    - Foreground app polling (enabled by default on HyperOS)
    - Notification compatibility mode (enabled by default on OriginOS)

- Added a dedicated About page with manual update checks and open-source license notices
- Added a dedicated Theme Settings page with a predictive back gesture toggle, multiple themes, and HDR real-time charts
- Added battery life predictions while charging
- Added an indicator for the most recently viewed record in the history list
- Added history record remarks
- Added a button to restart the service manually
- Fixed temperature curves being clipped below 0°C
- Improved the algorithms for home statistics, battery life predictions, and screen-off power consumption statistics

### General

- Refactored parts of the architecture
- Improved exception handling and crash handling
