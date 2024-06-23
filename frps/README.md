Frp-Server 安装平台：CentOS、Debian、Ubuntu

Server
------

### 安装

```Bash
wget --no-check-certificate https://raw.githubusercontent.com/junfuchang/onekey-install-frps/master/frps/install-frps.sh -O ./install-frps.sh

chmod 700 ./install-frps.sh

./install-frps.sh install
```

### 卸载
```Bash
./install-frps.sh uninstall
```

### Update
```Bash
./install-frps.sh update
```

### 服务器管理
```Bash
Usage: /etc/init.d/frps {start|stop|restart|status|config|version}
```

