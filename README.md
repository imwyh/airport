# airport

### docker环境下vmess+ws+tls+web一键傻瓜脚本

前置条件：

- 已购买域名
- 已购买VPS
- 已做好解析
- 本机和服务器提供商防火墙已设置放行22、443、54321端口
- 服务器已安装wget和curl命令

本脚本在甲骨文ubuntu系统上测试通过

使用方式：

cd 到你要安装到的目录

sudo mkdir ariport && cd airport

sudo curl -L "https://raw.githubusercontent.com/fan23333/airport/main/install.sh" -o ./install.sh && sudo bash ./install.sh

根据指引进行安装

根据不良林 https://www.youtube.com/watch?v=s90feRmdr9A 教程总结
