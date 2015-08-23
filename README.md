shadowsocks-nodejs
==================
**Backup of shadowsocks**
Create your own config.json file. Change "TODO FIXME" item.
Run on server:
cd shadowsocks2
bin/sserver -c config.json 

Run on client:
cd shadowsocks2
bin/sslocal

Then open browser. Firefox use autoproxy plugin(Chrome use switchsharp) and set socks5 proxy, proxy server is 127.0.0.1 ,port  is 1080.

Then use proxy to browse the web site what you want to surf.

