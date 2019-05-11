# 搜狗输入法挂接小鹤双拼+双形

1. 打开设置，“常用” 选项中，选择 “双拼”，双拼方案设置中选择 “小鹤双拼”；

2. “高级”选项中，打开“自定义短语设置”，选“直接编辑配置文件”项，此时弹出 Phrases.ini 文件，把 “sogou-flypy-xxx.ini” 文件中的内容贴到此文件内即可；高级设置中的“固定首位”的选项不勾选。  
+ `sogou-flypy-word.ini`  小鹤双拼单字版本（作为辅助码推荐选择此方案）  
+ `sogou-flypy-phrase.ini` 小鹤双拼词组版本（另可直接尝试小鹤音形方案）  

> 搜狗输入法 Windows 和 Mac 版均适用。Mac版不能编辑只能导入，且导入的文件编码格式必须为`UTF-16 LF`。

Inspired from https://github.com/fanqi/sogou-flypy.git