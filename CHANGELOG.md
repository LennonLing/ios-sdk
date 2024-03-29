**v2.2.0** (2019/10/18)
- 支持重置用户属性
- 事件预置属性新增时间偏移，适配多时区需求
- 新增接口，支持按照指定时区上传事件数据

**v2.1.1** (2019/10/11)
- 优化上报逻辑，解决缓存数据库异常导致的重复上报

**v2.1.0** (2019/08/30)
- 支持轻量级实例, 便于上报被动事件等需求
- 新增 enableTracking 接口, 可以打开或关闭实例上报功能
- 新增 optOutTracking/optInTracking 接口
- 其他代码优化

**v2.0.1** (2019/07/15)
- 优化自动采集事件的时间序列

**v2.0.0** (2019/07/10)
- 支持重复事件监测功能
- 自动采集事件新增 APP 安装事件
- 自动采集事件新增后台自启事件，默认不采集
- 自动采集新增 UIControl 类的点击事件

**v1.2.0** (2019/06/15)
- 支持动态公共属性
- 支持 APP 崩溃信息自动采集
- 支持多项目采集 （多 APP ID）
- 新增获取公共属性接口
- 新增 flush 接口，支持主动上报数据

**v1.1.3** (2019/06/10)
- APP 版本数据跟随每个事件发送


**v1.1.2** (2019/06/04)
- 修复 iOS 10 嵌入H5 通过原生SDK 发送的异常
- 修复 distinct_id 不兼容老版本的问题

**v1.1.1** (2019/05/03)
- 支持 bitcode
- 支持 H5 与原生 SDK 打通

**v1.0.12** (2018/12/07)
- 修复时间格式问题: 不使用公历的国家的时间格式不符合要求

**v1.0.11** (2018/11/22)
- 新增 setNetworkType接口，可设置允许上报数据的网络环境
- 删除废弃的 isWifiForcedPush 接口
