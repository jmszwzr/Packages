#Sublime Text3 Packages的优质插件


##Sublime Text 3中关闭记住上次打开的文件

打开Sublime的配置文件，针对这个功能定位到了两个参数：

“hot_exit”：默认值为true，它便是决定是否出现保存提示的关键，开启这个参数未保存的文件便会单独存储。
“remember_open_files”：打开上一次打开的文件了，这个参数依赖于hot_exit，只在开启hot_exit时生效。
关闭hot_exit：进入 Preferences  => Settings-User 我的修改如下：
```
{
"color_scheme": "Packages/Color Scheme - Default/Monokai Bright.tmTheme",
"font_size": 10.5,
"hot_exit": false,
"ignored_packages":
[
"Vintage"
],
"remember_open_files": false,
}
```
