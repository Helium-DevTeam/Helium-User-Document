# 指令

对于所有来自控制台的输入和服务器中的玩家信息,Helium首先将其视为指令进行解析和匹配,若失败则会将输入其发送至活动的Minecraft服务器.

执行Helium指令需要执行者拥有对应的[权限](/zh-cn/permission.md),在Helium控制台中输入的指令总是以HELIUM_OWNER级权限(即最高权限)执行,在服务器中的玩家输入会根据配置文件中给出的权限等级执行.若执行者权限达不到相应指令的要求,则指令不会执行.

Helium中指令可以由Helium本身及[扩展]()注册,的本页面将会介绍Helium中内建的一系列指令,关于插件中的指令相关操作,请看[此处]().

## `#helium`指令

### 指令树管理:`command`指令

#### `attribute`

#### `bind`

#### `detail`

#### `list`

### 服务器管理:`server`指令

### 事件管理:`event`指令

### 扩展管理:`extension`指令

### 状态显示:`status`指令

### 热重载:`reload`指令

### 杂项:`exit`,`update`,`show`和`version`指令

## `#help`指令

### 查看Helium在线文档:`documentation`指令

### 查看指令相关用法:`manual`指令