This is my vim dot file.

vundle相关配置在vundle_vimrc中，用vundle管理插件，插件列表`:PluginList`查看
python相关配置在python_vimrc中

Windows下，在vim目录下

```
git init
git remote add origin https://github.com/einverne/dotfile.git
git fetch
git checkout -t origin/master
```

然后再vim目录下安装Vundle

	git clone https://github.com/gmarik/Vundle.vim.git vimfiles/bundle/Vundle.vim

进入vim，运行 `:PluginInstall` 安装剩余插件

将 https://github.com/tomasr/molokai 工程中的配色下载到 ~/vimfile/colors/ 目录下

将 ctags58.zip 压缩包中的 ctags.exe 解压到 vim74/ 目录下
