# Config Table Plugin

A plugin for Godot Engine that can convert Excel files to GDScripts. Origin plugin has some errors in Godot4, here is the fixed plugin for Godot4.

It may have some error on activating the plugin:

```
  Directory must be opened before use.
  Can't copy template file from /Users/qianzhihao/Godot/Godot_Nameless/addons/config_table_plugin/templates/ConfigTable.gd.template to: /Users/qianzhihao/Godot/Godot_Nameless/config_table/templates/ConfigTable.gd.template
  Execute the gdscript config table tool failed: /Users/qianzhihao/Godot/Godot_Nameless/addons/config_table_plugin/tools/gdscript_config_table_tool/GDScriptConfigTableTool.exe
  Code: 126
```

I haven't solved the problem yet. But you can copy `addons/config_table_plugin/templates/ConfigTable.gd.template` to `config_table/templates/ConfigTable.gd.template` manually. After this, it will work properly.

[The source of the tool]()

[简体中文](./README_zh.md)

## License

MIT
