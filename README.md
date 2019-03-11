## 收集整理的一些脚本
> 脚本来源@[逗比](https://doub.io)@[秋水逸冰](https://teddysun.com)@[老鬼](https://www.oldking.net)

* [***代理***](#代理)
  * [ssr.sh](#ssrsh)
  * [brook.sh](#brooksh)
  * [mtproxy.sh](#mtproxysh)
  * [bbr.sh](#bbrsh)
  * [shadowsocks-all.sh](#shadowsocks-allsh)
* [***中转***](#中转)
  * [iptables-pf.sh](#iptables-pfsh)
  * [brook-pf.sh](#brook-pfsh)
  * [haproxy.sh](#haproxysh)
  * [socat.sh](#socatsh)
  * [tinymapper.sh](#tinymappersh)
* [***其他***](#其他)
  * [backup.sh](#backupsh)
  * [sshport.sh](#sshportsh)
  * [caddy_install.sh](#caddy_installsh)
  * [gfw_push.sh](#gfw_pushsh)
  * [ssrstatus.sh](#ssrstatussh)
  * [kms.sh](#kmssh)
  * [superbench.sh](#superbenchsh)
  * [superspeed.sh](#superspeedsh)

---
## 代理
## ssr.sh

- 脚本说明: ShadowsocksR 一键安装管理脚本，支持单端口/多端口切换和管理
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/ss-jc42/

#### 脚本特点:
- 支持 限制 用户速度
- 支持 限制 端口设备数
- 支持 显示 当前连接IP
- 支持 显示 SS/SSR连接+二维码
- 支持 切换管理 单/多端口
- 支持 一键安装 锐速
- 支持 一键安装 BBR
- 支持 一键封禁 垃圾邮件(SMAP)/BT/PT


#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubi/doubi/master/ssr.sh && chmod +x ssr.sh && bash ssr.sh
## 备用安装
wget -N --no-check-certificate https://github.com/lyrbet/shell/raw/master/proxy/ssr.sh && chmod +x ssr.sh && bash ssr.sh
```
---
## brook.sh

- 脚本说明: Brook 一键安装管理脚本
- 系统支持: CentOS6+ / Debian7+ / Ubuntu14+
- 使用方法: https://doub.io/brook-jc3/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubi/doubi/master/brook.sh && chmod +x brook.sh && bash brook.sh
## 备用安装
wget -N --no-check-certificate https://github.com/lyrbet/shell/raw/master/proxy/brook.sh && chmod +x brook.sh && bash brook.sh
```
---
## mtproxy.sh

- 脚本说明: Mtproto Proxy 一键安装管理脚本
- 系统支持: CentOS7 / Debian7+ / Ubuntu14+
- 使用方法: https://doub.io/shell-jc7/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubi/doubi/master/mtproxy.sh && chmod +x mtproxy.sh && bash mtproxy.sh
## 备用安装
wget -N --no-check-certificate https://github.com/lyrbet/shell/raw/master/proxy/mtproxy.sh && chmod +x mtproxy.sh && bash mtproxy.sh
```
## bbr.sh

- 脚本说明: BBR 一键安装管理脚本
- 系统支持: Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/wlzy-16/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubi/doubi/master/bbr.sh && chmod +x bbr.sh && bash bbr.sh
## 备用安装
wget -N --no-check-certificate https://github.com/lyrbet/shell/raw/master/proxy/bbr.sh && chmod +x bbr.sh && bash bbr.sh
```
## shadowsocks-all.sh

- 脚本说明: shadowsocks一键脚本四合一
- 系统支持: CentOS 6+，Debian 7+，Ubuntu 12+
- 使用方法: https://teddysun.com/486.html

#### 下载安装:
``` bash
wget --no-check-certificate -O shadowsocks-all.sh https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks-all.sh
chmod +x shadowsocks-all.sh
./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log
## 备用安装
wget --no-check-certificate -O shadowsocks-all.sh https://github.com/lyrbet/shell/raw/master/proxy/shadowsocks-all.sh
chmod +x shadowsocks-all.sh
./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log
```
## 中转
## iptables-pf.sh

- 脚本说明: iptables 端口转发 一键安装管理脚本
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/wlzy-20/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubi/doubi/master/iptables-pf.sh && chmod +x iptables-pf.sh && bash iptables-pf.sh
## 备用安装
wget -N --no-check-certificate https://github.com/lyrbet/shell/raw/master/transfer/iptables-pf.sh && chmod +x iptables-pf.sh && bash iptables-pf.sh
```

---
## brook-pf.sh

- 脚本说明: Brook 端口转发 一键安装管理脚本
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/wlzy-37/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubi/doubi/master/brook-pf.sh && chmod +x brook-pf.sh && bash brook-pf.sh
## 备用安装
wget -N --no-check-certificate https://github.com/lyrbet/shell/raw/master/transfer/brook-pf.sh && chmod +x brook-pf.sh && bash brook-pf.sh
```

---
## haproxy.sh

- 脚本说明: HaProxy 一键安装管理脚本
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/wlzy-19/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubi/doubi/master/haproxy.sh && chmod +x haproxy.sh && bash haproxy.sh
## 备用安装
wget -N --no-check-certificate https://github.com/lyrbet/shell/raw/master/transfer/haproxy.sh && chmod +x haproxy.sh && bash haproxy.sh
```

---
## socat.sh

- 脚本说明: Socat 一键安装管理脚本
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/wlzy-18/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubi/doubi/master/socat.sh && chmod +x socat.sh && bash socat.sh
## 备用安装
wget -N --no-check-certificate https://github.com/lyrbet/shell/raw/master/transfer/socat.sh && chmod +x socat.sh && bash socat.sh
```

---
## tinymapper.sh

- 脚本说明: tinyPortMapper 一键安装管理脚本
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/wlzy-36/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubi/doubi/master/tinymapper.sh && chmod +x tinymapper.sh && bash tinymapper.sh
## 备用安装
wget -N --no-check-certificate https://github.com/lyrbet/shell/raw/master/transfer/tinymapper.sh && chmod +x tinymapper.sh && bash tinymapper.sh
```
##其他
---
### backup.sh

- 脚本说明: 网站一键备份脚本backup.sh
- 使用方法: https://teddysun.com/469.html

#### 下载安装:
``` bash
wget --no-check-certificate https://github.com/teddysun/across/raw/master/backup.sh
chmod +x backup.sh
```
*脚本需要配置后使用*

---
## sshport.sh

- 脚本说明: SSH 一键修改端口脚本
- 系统支持: Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/linux-jc11/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubi/doubi/master/ssh_port.sh && chmod +x ssh_port.sh && bash ssh_port.sh
## 备用安装:
wget -N --no-check-certificate https://github.com/lyrbet/shell/raw/master/others/sshport.sh && chmod +x sshport.sh && bash sshport.sh
```

## caddy_install.sh

- 脚本说明: Caddy 一键安装脚本
- 系统支持: CentOS6+ / Debian7+ / Ubuntu14+
- 使用方法: https://doub.io/shell-jc1

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubi/doubi/master/caddy_install.sh && chmod +x caddy_install.sh && bash caddy_install.sh
# 安装插件：
bash caddy_install.sh xxx,xxx
# 例如同时安装 http.filemanager 和 http.webdav插件：
bash caddy_install.sh http.filemanager,http.webdav
# 插件和Caddy是集成在一起的(单个二进制文件)，多个插件必须同时安装。
# 卸载命令：
caddy_install.sh uninstall
## 备用下载：
wget -N --no-check-certificate https://github.com/lyrbet/shell/raw/master/others/caddy_install.sh && chmod +x caddy_install.sh && bash caddy_install.sh

```

## gfw_push.sh

- 脚本说明: 监测服务器IP是否被墙并推送至 Telegram 一键脚本
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/shell-jc8/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubi/doubi/master/gfw_push.sh && chmod +x gfw_push.sh && bash gfw_push.sh
##备用下载
wget -N --no-check-certificate https://github.com/lyrbet/shell/raw/master/others/gfw_push.sh && chmod +x gfw_push.sh && bash gfw_push.sh

```
---
## ssrstatus.sh

- 脚本说明: ShadowsocksR 账号在线监控网站
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/shell-jc5/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubi/doubi/master/ssrstatus.sh && chmod +x ssrstatus.sh && bash ssrstatus
##备用下载
wget -N --no-check-certificate https://github.com/lyrbet/shell/raw/master/others/ssrstatus.sh && chmod +x ssrstatus.sh && bash ssrstatus
```
## kms.sh

- 脚本说明: 一键安装KMS服务脚本
- 系统支持: CentOS 6+，Debian 7+，Ubuntu 12+
- 使用方法: https://teddysun.com/530.html

#### 下载安装:
``` bash
wget --no-check-certificate https://github.com/teddysun/across/raw/master/kms.sh && chmod +x kms.sh && ./kms.sh
#安装完成后，输入以下命令查看端口号 1688 的监听情况
netstat -nxtlp | grep 1688
##备用地址
wget --no-check-certificate https://github.com/lyrbet/shell/raw/master/others/kms.sh && chmod +x kms.sh && ./kms.sh
```
## superspeed.sh

- 脚本说明: 一键测试服务器到国内的速度
- 使用方法: https://www.oldking.net/305.html

#### 下载安装:
``` bash
wget https://raw.githubusercontent.com/oooldking/script/master/superspeed.sh && chmod +x superspeed.sh && ./superspeed.sh
##备用下载
wget https://github.com/lyrbet/shell/raw/master/others/superspeed.sh && chmod +x superspeed.sh && ./superspeed.sh
```
## superspeed.sh

- 脚本说明: 一键测试服务器的基本参数
- 使用方法: https://www.oldking.net/350.html

#### 下载安装:
``` bash
wget -qO- --no-check-certificate https://raw.githubusercontent.com/oooldking/script/master/superbench.sh | bash
##备用地址
wget -qO- --no-check-certificate https://github.com/lyrbet/shell/raw/master/others/superbench.sh | bash
```