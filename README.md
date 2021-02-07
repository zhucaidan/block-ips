# block-ips
Linux VPS一键屏蔽指定国家所有的IP访问

使用
本脚本适用于CentOS、Debian、Ubuntu等常用系统。

使用root运行以下命令：

wget -N --no-check-certificate https://raw.githubusercontent.com/zhucaidan/block-ips/main/block-ips.sh

chmod +x block-ips.sh

./block-ips.sh

封禁ip时会要求你输入国家代码，代码查看：http://www.ipdeny.com/ipblocks 记住所填参数均为小写字母。比如JAPAN (JP)，我们就输入jp这个参数。
