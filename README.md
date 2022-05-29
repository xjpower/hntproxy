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






阿里云CENTOS专用

sudo -i

wget --no-check-certificate https://raw.githubusercontent.com/zlqzh/hntproxy/master/aliyun-centos.sh

chmod +x aliyun-centos.sh

./aliyun-centost.sh


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
