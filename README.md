# ike

艾森豪威尔矩阵, 按重要和紧急把任务分进四个象限

- 紧急且重要: 立即处理
- 重要但不紧急: 安排时间
- 紧急但不重要: 委派他人
- 既不紧急也不重要: 直接舍弃

在线使用: https://rainzee.github.io/ike/

## 同步

点「同步」, 粘贴一个只带 `gist` 权限的 GitHub 令牌 ([生成](https://github.com/settings/tokens/new?scopes=gist&description=ike)), 任务会存进你账号下的私密 Gist `ike.json`, 每台设备粘贴一次即可

- 打开页面, 回到前台, 网络恢复, 以及每次修改后 1 秒自动同步
- 按任务合并, 同一任务两边都改过时保留较新的一份
- 不同步时数据只在浏览器 localStorage 里, 可通过导出和导入备份

单个 `index.html`, 无构建步骤
