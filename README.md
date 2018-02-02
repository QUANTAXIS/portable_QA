# portable_QA
便捷版quantaxis（QA）

采用的软件是：
WinPython-64bit-3.6.3.0Zero.exe
mongodb-win32-x86_64-2008plus-ssl-3.6.2.zip
quantaxis 采用1.0.4 （下载后可以自行gitpull更新）

下载路径：
http://winpython.github.io/
http://dl.mongodb.org/dl/win32/x86_64

测试系统为：
win7 64位，
该版本主要为了方便部署，已包含mongodb（未包含数据），包含quantaxis及相关依赖性，如需安装其他库、git更新quantaxis、下载数据请使用WinPython Command Prompt.exe进行。
默认安装位置为d盘根目录下，如需更改，请自行配置mongodb服务。


使用步骤：
第一步：
解压在d盘根目录下
第一步：
运行开始运行.bat（删除旧MongoDB服务并创建新服务）
第三步：
打开WinPython Command Prompt.exe   进入quantaxis去下载数据，见github
第4步：
打开JupyterNotebook.exe 使用。。
备注每次使用前请查看MongoDB服务是否已打开。请勿在quantaxis内使用jupyternotebook，请勿修改quantaxis内相关文件 否则将无法更新quantaxis。


压缩包不好上传自己去下载吧，微云链接：http://url.cn/5HKBjX3    密码：lQ9yUV
