# ssrstartup
An unoffical ssr install script
集成ss四版本和bbr的一键安装脚本
## 关于
  
Shadowsocks-Python 和 ShadowsocksR 安装后不可同时启动（因为本质上都属 Python 版）
  
## 部署  
1.下载脚本
`wget --no-check-certificate -O ssr-startup.sh  
https://raw.githubusercontent.com/wwc-workspace/ssrstartup/master/ssr-startup.sh`
  
2.添加可执行权限
`chmod +x ssr-startup.sh`
  
3.运行脚本
`./ssr-startup.sh  2>&1 | tee ssr-startup.log`
  

## 安装完成后，脚本提示如下
```
Congratulations, your_shadowsocks_version install completed!  
Your Server IP        :your_server_ip  
Your Server Port      :your_server_port  
Your Password         :your_password  
Your Encryption Method:your_encryption_method

Your QR Code: (For Shadowsocks Windows, OSX, Android and iOS clients)  
 ss://your_encryption_method:[email protected]_server_ip:your_server_port
Your QR Code has been saved as a PNG file path:  
 your_path.png

Welcome to visit:https://www.hathtv.tk  
Enjoy it!
```
  
## 各版本默认配置文件
```
Shadowsocks-Python 版：
/etc/shadowsocks-python/config.json

ShadowsocksR 版：
/etc/shadowsocks-r/config.json

Shadowsocks-Go 版：
/etc/shadowsocks-go/config.json

Shadowsocks-libev 版：
/etc/shadowsocks-libev/config.json
```
  
***

## 详细说明请参阅
[露露慧的小窝](http://www.hathtv.tk/ghost/4/)
  
脚本魔改自[秋水逸冰](https://teddysun.com/)
