#云知声口语评测 SDK 文档工程
清晰、统一、方便查找的SDK文档，是提升客户服务质量的关键点之一。

借助git专业的版本管理能力和github的高可用性，特建此文档工程，将一应SDK的文档归总此处。

* [版本号](#版本号)
* [接口文档](#接口文档)
* [demo](#demo)

###版本号
* 版本号为三段整数，前两段为需求，最后一段为debug
* SDK需要提供接口获取当前版本号
* 每个版本对应有New Feature和Bugfix
* 每个版本有beta/release稳定状态标示
* 每一个代码提交必须对应一个版本号上升
* 每一个提交必须包含一个修改说明

### 接口文档
* 每个平台和编程语言的SDK API文档独立
* 不针对SDK版本单独维护文档，而是在每个接口中添加版本支持说明
* 修改API接口，应视为功能变化，对应的需上升版本号第一或第二段

### demo
* 每个平台和编程语言应提供demo源代码
* 商务原因，此文档工程中，不提供整个可编译运行demo的工程下载
* demo源码中应穿插有SDK的使用说明注释
