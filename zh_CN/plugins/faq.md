---
description: 'Author: Allen'
---

# 常见问题

## 安装插件时提示上传失败如何处理？

**错误详情**：出现 `PluginDaemonBadRequestError: plugin_unique_identifier is not valid` 报错提示。

**解决办法**：将插件项目下的 `manifest.yaml` 文件和 `/provider` 路径下的 `.yaml` 文件中的 `author` 字段修改为 GitHub ID。

重新运行插件打包命令并安装新的插件包。

