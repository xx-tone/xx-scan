# 记录平台安全的相关中间件

- 1, 解决用户权限问题 `oauth`
- 2, 待创建总体自定义文本规则,
  - 1, 将自定义的规则单个单个汇总打包成 zip 存到
  - 2, 存到一个大文本直接传输 【目前采用】

## 过程和目录结构
- `views` 目录记录的是所有的视图函数
  - `recover.py` 记录的是重写 `wafmanage\views.py` 函数的内容

## `plat` 中记录到 `config.ini` 是平台 `views.py` 需要用到的部分
