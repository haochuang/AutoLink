# AutoLink 详细介绍

## 介绍

AutoLink 开源自动化测试集成解决方案。

AutoLink 是 RobotFramework 的 web 集成开发环境。

AutoLink 支持 RobotFramework 语法高亮，自动提示等功能。

AutoLink 可以帮助你轻易的构建 web 自动化测试脚本、HTTP 接口自动化测试脚本以及移动自动化测试脚本。

AutoLink 完美的支持 RobotFramework 所有的关键字。

AutoLink 可以直接应用到你的企业实践中，节省框架开发成本。

AutoLink 是很简单的，但也很容易使用。

## 安装与启动

安装 Python3 版本，确保加入环境变量，pip 命令可用

从 AutoLink Github 项目下载源码

执行以下命令安装 AutoLink 依赖

pip install -r requirements.txt

4.1 执行以下命令启动 AutoLink 服务

python AutoLink.py runserver

4.1.1 访问以下网址，即可

http://127.0.0.1:5000

4.2 执行以下命令可外网访问

python AutoLink.py runserver -h 0.0.0.0 -p 8000 通过

4.2.1 即可通过你的IP地址来访问

http://ip:8000

注：

-h选项指定为0.0.0.0即为绑定本机ip启动，网络其他用户通过你的ip和-p指定的端口即可访问 AutoLink

-p指定AutoLink服务启动时的端口

默认账号: AutoLink
默认密码: 123456

下载 selenium webdriver 对应的浏览器驱动放在 driver 目录即可

截图
AutoLink Web IDE 编辑模式截图欣赏

