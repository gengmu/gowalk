#简介
gowalk是借鉴goagent，使用go开发的高性能稳定的代理服务器。

#快速体验
[下载二进制包](http://pan.baidu.com/s/1hq69vAO)
第一次运行后，将自动生成的certs目录下的ca.crt添加到浏览器信任CA(chrome:授权中心/firefox:证书机构)中

#服务器端部署
1. 运行upload.py直接部署，具体参考goagent的部署方式(感谢goagent提供的部署代码)

#客户端安装
1. [下载](https://golang.org/dl/)并解压go的安装包，已知在go1.1上无法编译通过，建议使用go1.3
2. 配置环境变量GOPATH指向go的解压目录
3. windows执行build.bat，其他操作系统执行build.sh
4. ./gowalk
5. 第一次运行后，将自动生成的certs目录下的ca.crt添加到浏览器信任CA(chrome:授权中心/firefox:证书机构)中

[二进制包下载](http://pan.baidu.com/s/1hq69vAO)

6. 建议采用[gogotester](https://github.com/azzvx/gogotester)扫描IP后填入配置文件
