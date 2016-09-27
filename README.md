# LaTeX 团队协作写作
本项目将演示如何使用Git+Vim ([vim-fugitive](https://github.com/tpope/vim-fugitive) in fact) 来实现LaTeX团队协作.

##环境的搭建

###Vim配置

1. 需要安装VIM并配置`_vimrc`
2. 安装包管理器`vim-Plug`
3. 安装`vim-tex`, `vim-fugitive`

###项目配置

###协作流程

由于本模板仓库包含有LaTeX写作模板以及文件结构. 你可以以此为模板进行协作.

1. 新建一个团队协作目录(例如`TEAM`), 并在`cygwin-shell`下切换到该目录

	```
	$ cd /path/to/TEAM
	```

2. 克隆本模板仓库到本地

	```git
	$git clone git@github.com:vanabel/LaTeX-TEAM.git
	```

3. 编辑文件

	```sh
	gvim main.tex subs/test.tex
	```

4. 提交编辑

	```vim
	:Gwrite
	```

5. 同步编辑

###参考链接

1. [vim插件介绍－Fugitive](http://www.d0u9.xyz/vimcha-jian-jie-shao-fugitive/)
