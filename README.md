## 链接
- 博客：https://dhds999.com   

[解决sublime不能安装packages的问题]

## 使用说明
"https://packagecontrol.io/channel_v3.json"该文件造成的

解决：

1.下载 channel_v3.json文件放在本地，比如直接放在D盘根目录下

2.Package Control.sublime-settings]修改方法：
Preferences > Package Settings > Package Control > Settings - User
添加

"channels":
[
"D:/channel_v3.json"
],