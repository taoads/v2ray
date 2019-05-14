备份
为了避免由于不可抗拒的原因所造成本人主动删除脚本，所以建议请将本脚本 Fork 一份
备份地址： https://github.com/233boy/v2ray/fork 
安装方法，确保你已经 Fork 了脚本，将 233boy 修改成你的 Github 用户名

git clone https://github.com/233boy/v2ray
cd v2ray
chmod +x install.sh
./install.sh local
如果提示 git 命令不可用，那就自己安装咯，不会安装啊？我也不知道啊。哈哈

快速管理
v2ray info 查看 V2Ray 配置信息
v2ray config 修改 V2Ray 配置
v2ray link 生成 V2Ray 配置文件链接
v2ray infolink 生成 V2Ray 配置信息链接
v2ray qr 生成 V2Ray 配置二维码链接
v2ray ss 修改 Shadowsocks 配置
v2ray ssinfo 查看 Shadowsocks 配置信息
v2ray ssqr 生成 Shadowsocks 配置二维码链接
v2ray status 查看 V2Ray 运行状态
v2ray start 启动 V2Ray
v2ray stop 停止 V2Ray
v2ray restart 重启 V2Ray
v2ray log 查看 V2Ray 运行日志
v2ray update 更新 V2Ray
v2ray update.sh 更新 V2Ray 管理脚本
v2ray uninstall 卸载 V2Ray

安装或卸载
温馨提醒，此脚本默认屏蔽一些不友好的网站！(仅限轮子相关)

要求：Ubuntu 16+ / Debian 8+ / CentOS 7+ 系统
推荐使用 Debian 9 系统，脚本会自动启用 BBR 优化。
备注：不推荐使用 Debian 8 系统，因为 Caddy 申请证书可能会出现一些莫名其妙的问题
强烈推荐使用 搬瓦工VPS，稳定，快速，针对中国线路专门优化，完全无须担心跑路，服务好，30天退款保证。
在这里可以找到 搬瓦工 VPS 套餐大全 ，优惠码在这里： 搬瓦工 VPS 优惠码 
使用 root 用户输入下面命令安装或卸载

bash <(curl -s -L https://git.io/v2ray.sh)
如果提示 curl: command not found ，那是因为你的 VPS 没装 Curl
ubuntu/debian 系统安装 Curl 方法: apt-get update -y && apt-get install curl -y
centos 系统安装 Curl 方法: yum update -y && yum install curl -y
安装好 curl 之后就能安装脚本了

备注：安装完成后，输入 v2ray 即可管理 V2Ray
如果提示你的系统不支持此脚本，那么请尝试更换系统
