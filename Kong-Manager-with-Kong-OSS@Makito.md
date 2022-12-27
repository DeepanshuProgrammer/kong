Note: Kong Manager with Kong OSS PoC
======

### 1. EE:kong/enterprise_edition/invoke_plugin.lua -> CE:kong/invoke_plugin.lua

This is to invoke the `cors` plugin in the `before_filter` for Admin API requests.

### 2. EE:kong/enterprise_edition/init.lua (Partial)-> CE:kong/admin_gui/init.lua

This is to prepare filesystem for Admin GUI (e.g., `kconfig.js`)

### 3. EE:kong/enterprise_edition/conf_loader.lua (Partial)-> CE:kong/admin_gui/conf_loader.lua

This is to provide definitions and validations for Admin GUI specific configurations.
