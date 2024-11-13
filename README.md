# Hy2 协议一键部署脚本-个人魔改，慎用！！！


```shell
wget -N --no-check-certificate https://raw.githubusercontent.com/byilrq/hy2-install/main/hy2/hysteria.sh && bash hysteria.sh
```

#一键安装或升级到最新版本。
bash <(curl -fsSL https://get.hy2.sh/)

#移除相关服务。
bash <(curl -fsSL https://get.hy2.sh/) --remove

#启动Hysteria2
systemctl start hysteria-server.service

#重启Hysteria2
systemctl restart hysteria-server.service

#查看Hysteria2状态
systemctl status hysteria-server.service

#停止Hysteria2
systemctl stop hysteria-server.service

#设置开机自启
systemctl enable hysteria-server.service

#查看日志
journalctl -u hysteria-server.service
