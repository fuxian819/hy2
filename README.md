# Hy2协议 个人魔改，慎用！！！


```shell
wget -N --no-check-certificate https://raw.githubusercontent.com/byilrq/hy2-install/main/hy2/hysteria.sh && bash hysteria.sh
```

#一键安装或升级到最新版本。

bash <(curl -fsSL https://get.hy2.sh/)

#移除相关服务。

bash <(curl -fsSL https://get.hy2.sh/) --remove

#启动Hy

systemctl start hysteria-server.service

#重启Hy

systemctl restart hysteria-server.service

#查看Hy

systemctl status hysteria-server.service

#停止Hy

systemctl stop hysteria-server.service

#设置开机自启

systemctl enable hysteria-server.service

#查看日志

journalctl -u hysteria-server.service
