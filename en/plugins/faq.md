---
description: 'Author: Allen'
---

# FAQ

## How to handle plugin upload failure during installation?

**Error Details**: The error message shows `PluginDaemonBadRequestError: plugin_unique_identifier is not valid`.

**Solution**: Modify the `author` field in both the `manifest.yaml` file in the plugin project and the `.yaml` file under the `/provider` path to your GitHub ID.

Retype the plugin packaging command and install the new plugin package.
