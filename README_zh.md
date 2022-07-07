# 配置表格工具

用于Godot引擎的插件，可将Excel表格文件转换成GDScript文件，以便在Godot中使用。此版本为Godot4的版本。

原作者Raiix蘩，[原仓库](https://github.com/rayxuln/Config-Table-Plugin)，作者写的使用方法文档：[使用方法](https://www.bilibili.com/read/cv1429700)

不过遇到了个问题，就是启用插件时，会拷贝template文件，但这时会遇到报错：

```
  Directory must be opened before use.
  Can't copy template file from /Users/qianzhihao/Godot/Godot_Nameless/addons/config_table_plugin/templates/ConfigTable.gd.template to: /Users/qianzhihao/Godot/Godot_Nameless/config_table/templates/ConfigTable.gd.template
  Execute the gdscript config table tool failed: /Users/qianzhihao/Godot/Godot_Nameless/addons/config_table_plugin/tools/gdscript_config_table_tool/GDScriptConfigTableTool.exe
  Code: 126
```

不管mac还是windows都是同样的报错，我暂时还没解决这个问题，现在想使用的话需要自己手动 把`addons/config_table_plugin/templates/ConfigTable.gd.template` 拷贝到 `config_table/templates/ConfigTable.gd.template` 。拷贝完之后才可以正常使用。

我也刚学不久，工具有什么问题可以只管提。