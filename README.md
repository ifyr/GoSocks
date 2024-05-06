# GoSocks
GoSocks implements SOCKS4/5 Proxy Protocol and HTTP Tunnel in GO language.

The [cmd/socksd](https://github.com/ifyr/GoSocks/cmd/socksd) build with package SOCKS, supports cipher connection which crypto method is rc4, des, aes-128-cfb, aes-192-cfb and aes-256-cfb, upstream which can be shadowsocks or socsk5.

Original project: [eahydra/socks](https://github.com/eahydra/socks)

Forked from: [ssoor/socks](https://github.com/ssoor/socks)

# Statement
SOCKS 实现了 SOCKS4/5 代理协议以及 HTTP 代理隧道, 你可以通过使用这些来简化你编写代理的难度.
 [cmd/socksd](https://github.com/eahydra/socks/blob/master/cmd/socksd) 这个项目是一个使用 socks 包构建的转换代理, 用于将 shadowsocks 或者 socsk5 转换成 SOCKS4/5 或者 HTTP 代理.
 
 目前 socks 支持的加密方式有 rc4, des, aes-128-cfb, aes-192-cfb , aes-256-cfb, 后端协议支持 shadowsocks 或者 socsk5.

# Install
如果你需要从源码安装, 可以尝试执行如下指令.

If you want to install [cmd/socksd](https://github.com/ifyr/GoSocks/cmd/socksd), please read the [README.md](https://github.com/ifyr/GoSocks/cmd/socksd/README.md)

如果你想获得可运行文件, 请编译 [cmd/socksd](https://github.com/ifyr/GoSocks/cmd/socksd), 编译时可以参考此文档 [README.md](https://github.com/ifyr/GoSocks/cmd/socksd/README.md)
