# linux
linux learning road

一线运维不得不会的awk妙用汇总（2022）
https://mp.weixin.qq.com/s/SPHeJ_nwu7BsDBHQc2UmNA

docker-compose教程（安装，使用, 快速入门）
https://blog.csdn.net/pushiqiang/article/details/78682323 

如何用 10 行 bash shell 脚本监控 Linux
https://mp.weixin.qq.com/s/lt5RvYZ6fInPa9v4YubCJA

部署centos全过程
服务器配置
测试服务器  192.168.196.72

[X] linux 安装配置zerotier
1、在线安装zerotier
curl -s https://install.zerotier.com/ | sudo bash
2、添加开机自启
$ sudo systemctl enable zerotier-one.service
3、启动zerotier-one.service
$ sudo systemctl start zerotier-one.service
4、加入网络
$ zerotier-cli join 35c192ce9b5dffd5
[X]  yum update
[X] docker-io
https://www.jianshu.com/p/6e5da590aeda
[X] Docker更换国内镜像源
1、修改/etc/docker/daemon.json配置文件
sudo vim /etc/docker/daemon.json

2、修改daemon.json文件的内容
{ "registry-mirrors": ["https://docker.mirrors.ustc.edu.cn"] } systemctl restart docker.service
[]里面的网址可以随便更换为国内镜像源的网址，我这里用的是中国科技大学的镜像源，
大家可以随意选择，保存文件之后重启一下docker就完成配置了
sudo systemctl restart docker
[X] Docker
promethues+Grafana+Exporter+Portainer
[X] Docker portainer-ce 汉化版安装（基于centos）
https://blog.csdn.net/Forgetnot9/article/details/121977409

[X] dnmp
https://github.com/blue002324github/dnmp
[X] btop
https://github.com/blue002324github/btop
[X] python
./ipy3.sh 3.9.12
