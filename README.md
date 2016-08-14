# vimrc-backup
vim配置文件备份

# 使用说明
> 本配置是在mac下的，windows下能否使用并没有测试
需要注意的是配置中的部分插件需要下载power-fonts字体

- clone项目到本地用户的当前目录
- 修改文件为隐藏文件，放到当前目录下
- 启动vim，输入:PluginInstall

# 说明
项目是从[spf13](https://github.com/spf13/spf13-vim) fork下来的。其中做了部分设置主要添加了如下内容：

- 使用F5打开文件预览（mac下默认的文件打开方式）
- [markdown](https://github.com/suan/vim-instant-markdown)预览插件，当打开md文件的时候，游览器会自动打开并显示内容.(本插件只针对mac和linux起作用)
- 设置了gvim的默认字体为power-font
- 设置了[vim-airline](https://github.com/vim-airline/vim-airline)的主题
- 添加了[tern_for_vim](https://github.com/ternjs/tern_for_vim)来实现对js的自动补全功能

