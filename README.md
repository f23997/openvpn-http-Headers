
-

# -d          : Run hoproxy in the background (detached/daemon mode)
# -l 80    : Listen on local port 80
# -r 127.0.0.1:1194 : Forward all incoming connections to localhost:1194 (local OpenVPN port)
apt install gcc socat -y



gcc hoproxy.c -o hoproxy



./hoproxy -d -l 80 -r 127.0.0.1:1194

在国内可用

hoproxy会接受自定伪装域名端口，转发到指定的ip地址tcp端口

客户端伪装host域名请求


搭建教程
https://github.com/f23997/openvpn-Free-internet/blob/main/%E6%90%AD%E5%BB%BA%E6%95%99%E7%A8%8B.txt















%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%         %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


