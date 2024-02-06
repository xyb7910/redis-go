# 使用 Go 手写redis

## 开发步骤
- 功能函数的实现
- 建立 tcp 连接
- redis 网络协议解析
  - 实现 replay const
  - 实现 replay error
  - 实现 自定义 replay
  - 实现 parser 解析器
- 实现 dict 相关逻辑
- 实现 command 相关逻辑
- 实现 databases 相关逻辑
- 实现 PING / DELETE / EXISTS / KEYS / FLUSHDB / TYPE / RENAME / RENAMENX
