本配置由本人综合各位大佬所得（所提及配置文件于致谢）
若有问题请联系https://t.me/iOSgifts

surge 4 远程配置 分组较全
使用方式：raw出url粘贴至订阅转换的远程配置处回车即可

致谢：
ACL4SSR
lhie1
DivineEngine


########snell
snell Debian安装
amd版
wget —no-check-certificate -O snell.sh https://raw.githubusercontent.com/primovist/snell.sh/master/snell.sh
chmod +x snell.sh
./snell.sh

arm版
wget —no-check-certificate -O snell.sh https://raw.githubusercontent.com/primovist/snell.sh/master/snell-arm.sh
chmod +x snell.sh
./snell.sh

修改端口号

vi /etc/snell/snell-server.conf
systemctl restart snell
 

查看Snell运行状态：

systemctl status snell
##########