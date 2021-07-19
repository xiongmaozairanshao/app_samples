# 轻量级偏好数据库<a name="ZH-CN_TOPIC_0000001080279654"></a>

### 简介<a name="section103mcpsimp"></a>

轻量级偏好数据库主要提供轻量级Key-Value操作，支持本地应用存储少量数据。本示例通过 Preferences 创建、删除、更新和查询应用程序偏好数据，主要实现了登录页面偏好数据存取及主页面背景色偏好数据存取。

### 使用说明<a name="section105mcpsimp"></a>

1.  启动页面勾选不再显示，保存该偏好数据，下次启动应用不再显示该页面，直接进入模拟登录页面。
2.  模拟登录页面输入用户名和密码，点击登录跳转到主页面，自动保存登录状态，下次不再显示模拟登录页面。
3.  主页面点击应用背景色后，再点击对应颜色可保存背景色，点击清除偏好设置，清除已保存的背景色。

### 约束与限制<a name="section110mcpsimp"></a>

本示例支持在大型系统上运行。
