# 五笔86极点/小鹤音形 Rime鼠须管挂接说明 macOS系统  
                
#### Rime平台鼠须管下载  
请到 [此地址下载](https://rime.im/download/) 鼠须管目前MacOS最新版 0.15.2 (2019-06-23)，并安装
```
brew install --cask squirrel
```

注意`squirrel.yaml`文件中的`config_version`要与当前软件版本的配置版本号一致。

``` squirrel.yaml
config_version: "0.37"  # 会影响主题和其他配置
```

``` squirrel.custom.yaml
customization:
  distribution_version: 0.15.2  # 软件的版本，保持最新
  rime_version: 1.7.3
```

#### 挂接五笔86极点/小鹤音形  
1、在菜单栏中的输入法中选择“鼠须管(Squirrel)”，然后选择“用户设定(Settings)”打开Rime文件夹`~/Library/Rime/`  
2、将本项目rime文件夹中的文件及文件夹全部复制到上面打开的文件夹内，**覆盖**同名文件  
3、回到鼠须管菜单，点击“重新部署(Deploy)”即完成  

#### 修改配置文件
- squirrel.yaml 定义可用主题
- squirrel.custom.yaml 设置选定主题
- default.yaml 定义半全角标点和快捷键等
- default.custom.yaml 配置可用输入法以及常用设置
- wubi86_jidian.schema.yaml 五笔极点输入法基础配置
- wubi86_jidian.dict.yaml 极点五笔基础词库
- wubi86_jidian_user.dict.yaml 用户自定义五笔词库

#### 常用组合键：
```
Ctrl+Shift+~    切换不同的输入方案  
Ctrl+Option+`   部署Deploy配置
```

#### 可用主题
![Simple Dark](./pics/SimpleDark.png)

- 浮尘／Dust
- 沙漠夜／Mojave Dark
- 简约黑／Simple Dark
- 简约蓝／Simple Blue
- 简约白／Simple White

#### 注意事项  
+ 修改文件后，均需重新部署方能生效  
+ 五笔86极点码表基于极点十周年版本生成  
+ 五笔86极点wubi86_jidian.dict.yaml极点词库、wubi86_jidian_user.dict.yaml用户词库，需自行备份保存  
+ 小鹤音形bin码表基于 librime 1.3.2 生成，其他系统rime如需使用，需匹配此版本  
+ 小鹤音形flypy_top.txt置顶词库、flypy_user.txt用户词库，需自行备份保存  

#### 参考资料  
+ [86五笔极点码表Rime鼠须管输入法](https://github.com/KyleBing/rime-wubi86-jidan)  
+ [鼠须管输入法五笔定制](https://networm.me/2019/01/20/squirrel-wubi/)  
+ [极点五笔官网](http://www.freewb.org/)  
+ [小鹤双拼官网](http://flypy.com)  
+ [鹤形入门教程](https://flypy.com/xing.html)  
+ [小鹤双拼官方网盘](http://flypy.ys168.com)  
+ [小鹤音形二简词RIME码表](http://noodlefighter.com/post/note_xhup_jianma/)  
