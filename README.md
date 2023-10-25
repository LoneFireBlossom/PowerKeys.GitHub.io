更改了原Power Keys中的「快捷键简化 Mac」为：
- Tab改成左shift+左ctrl+左option+左cmd
- ~改成左shift+左ctrl+左command
- esc改成左shift+左option+左command 
 - capslock改成左shift+左ctrl+左option（因为shift+ctrl+opt+cmd+W/.在Catalina中都是系统级别不可调整的快捷键，所以我把常用的capslock改成shift+ctrl+opt，tab改成shift+ctrl+opt+cmd。我感觉现在capslock这个组合应该不会有任何软件去用）

对于没有Touch Bar的Mac来说，比起「光速启动」，我更想要这些F键自带的功能，所以我把光速启动相关的代码全部删掉了，这样F1-F12的功能（例如F1、F2是调节亮度）就可以由karabiner-elements中的`Function Keys`来调节了。
对于有Touch Bar的Mac来说，这几个功能都可以不用F键来完成，所以这些代码仍然保留。两个版本唯一的区别就是有没有删掉相关代码。

安装链接为

有Touch Bar的Mac：
```
karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/LoneFireBlossom/PowerKeys.GitHub.io/master/powerkeys%20for%20TouchBar%20Mac.json
```
没有Touch Bar的Mac：
```
karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/LoneFireBlossom/PowerKeys.GitHub.io/master/powerkeys%20for%20no-TouchBar%20Mac.json
```
好像用这个链接会闪退？那就下载下来直接放到karabiner的设置文件夹里吧
```
/Users/lonefireblossom/.config/karabiner/assets/complex_modifications/
```
