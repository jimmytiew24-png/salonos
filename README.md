# SalonOS

美发门店营运系统。此快照对应 2026-11-06 的 v13.6.10.63。

| 文件 | 内容 |
| --- | --- |
| salonos-v13.6.10.63-source.zip | 完整源码快照，包含 v13 网站、数据库迁移与测试 |
| SalonOS_v13.6.10.63_ENGLISH_NAVIGATION_PATCH.zip | 英文导航增量包，适用于 v13.6.10.62 |
| VERSION | 本次源码的版本号 |

解压源码后，在 v13/assets/supabase-config.js 与 PHP 配置中填写自己的 Supabase 项目 URL 和 publishable key。PHP 可使用 SALONOS_SUPABASE_URL 和 SALONOS_SUPABASE_PUBLISHABLE_KEY 环境变量。迁移脚本位于 v13/supabase/migrations。公开快照不含线上数据库备份。