# Centos7 搭建gollumn wiki

## 软件安装

- 安装ruby

		yum install -y ruby ruby-devel

- 安装依赖库

		yum install -y libxml2-devel libxslt-devel git libicu-devel

- 安装编译工具

		yum install -y gcc-c++

- 安装gollum

	gem install gollum

## 本地创建wiki

一下为Ant本人使用方法

- 创建wiki用户

		adduser wiki
		cd ~wiki
		su wiki

- 创建wiki目录

		cd ~wiki
		mkdir wiki
		cd wiki

- 初始化git仓库

		git init

- 启动wiki

		gollumn

