########snell
snell Debian安装
amd版
wget —no-check-certificate -O snell.sh https://raw.githubusercontent.com/DecoAri/Surge/master/snell.sh
chmod +x snell.sh
./snell.sh

arm版
wget —no-check-certificate -O snell.sh https://raw.githubusercontent.com/DecoAri/Surge/master/snell-arm.sh
chmod +x snell.sh
./snell.sh

修改端口号

nano /etc/snell/snell-server.conf
systemctl restart snell

开机自启
systemctl enable snell

查看Snell运行状态：

systemctl status snell

卸载

wget —no-check-certificate -O uninstall-snell.sh https://raw.githubusercontent.com/primovist/snell.sh/master/uninstall-snell.sh
chmod +x uninstall-snell.sh
./uninstall-snell.sh

TIPS：
sysctl -w net.core.rmem_max=26214400
sysctl -w net.core.rmem_default=26214400
##########