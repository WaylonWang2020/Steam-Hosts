# Steam-Hosts
In order to use the steam platform normally, we need to modify something


```
DNS显示与刷新
ipconfig /displaydns
ipconfig /flushdns
```
```
两个关键URL
store.steampowered.com
steamcommunity.com
```
```
解析 商店Store 的IP
nslookup steamcommunity.com 8.8.8.8
nslookup store.steampowered.com 8.8.8.8
``` 
```
添加 社区community hosts
C:\Windows\System32\drivers\etc\
                               └hosts

31.13.70.20 steamcommunity.com
23.192.59.22 store.steampowered.com
这里的IP使用上一步解析出来的IP
```
```
修改程序启动参数
"D:\Program Files (x86)\Steam\Steam.exe" -community="https://steamcommunity.com"
```

商店 http://store.steampowered.com/

社区 https://steamcommunity.com/

搜索好友 https://steamcommunity.com/search/users/
