# hntprox
HNT 代理工具 自用 不适合其他人 谢谢！


HNT适用L2TP 代理一键搭建同时开通端口44158转发 

VPS 服务器系统版本为 UBUNTU16.04

一键安装有可选项版本（推荐）：

wget --no-check-certificate https://raw.githubusercontent.com/zlqzh/hntproxy/master/l2tp-hnt.sh

chmod +x l2tp-hnt.sh

./l2tp-hnt.sh


阿里云专用

sudo -i

apt update

apt-get install gawk

wget --no-check-certificate https://raw.githubusercontent.com/zlqzh/hntproxy/master/aliyun-l2tp-hnt.sh

chmod +x aliyun-l2tp-hnt.sh

./aliyun-l2tp-hnt.sh

阿里云测试

sudo -i

apt update

apt-get install gawk

wget --no-check-certificate https://raw.githubusercontent.com/zlqzh/hntproxy/master/aliyun-hnt-auto.sh

chmod +x aliyun-hnt-auto.sh

./aliyun-hnt-auto.sh



阿里云CENTOS专用

sudo -i

wget --no-check-certificate https://raw.githubusercontent.com/zlqzh/hntproxy/master/aliyuncentos.sh

chmod +x aliyuncentos.sh

./aliyuncentos.sh

阿里云一键

sudo -i

apt update

apt-get install gawk

wget --no-check-certificate https://raw.githubusercontent.com/zlqzh/hntproxy/master/aliyun-hnt-auto.sh

chmod +x aliyun-hnt-auto.sh

./aliyun-hnt-auto.sh


ubuntu 多网卡设置

auto eth0:0
iface eth0:0 inet static
address 111.111.111.112
netmask 255.255.255.192
gateway 111.111.111.110

auto eth0:1
iface eth0:1 inet static
address 111.111.111.113
netmask 255.255.255.192
gateway 111.111.111.110


PI转发

sudo -i

apt update

apt-get install gawk

wget --no-check-certificate https://raw.githubusercontent.com/zlqzh/hntproxy/master/l2tp-pi.sh

chmod +x l2tp-pi.sh

./l2tp-pi.sh


Socks5转l2tp

sudo -i

apt update

apt-get install -y gawk dos2unix

wget --no-check-certificate https://raw.githubusercontent.com/zlqzh/hntproxy/master/l2tp-ip.sh

dos2unix l2tp-ip.sh

chmod +x l2tp-ip.sh

./l2tp-ip.sh
