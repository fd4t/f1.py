律饭：fanfou web proxy

define:
ff=fanfou

function:
- call ff.api
- 检查是否有更新，避免重复send request
- 用缓存减少刷新频率
- 设置每日发送配额
- 自定义过滤器
- 二次OAuth
- 访客mode / topic/专题 mode
- 数据备份/数据导出
- standalone 本地host

todo:
- write in Rust / 生成exe
- write in asp.net core / production use / 环保
