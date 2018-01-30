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
nslookup store.steampowered.com
``` 
```
添加 社区community hosts
C:\Windows\System32\drivers\etc\   hosts

104.78.74.220 steamcommunity.com

这里的IP最好使用上一步解析出来的IP
```
```
修改程序启动参数
"D:\Program Files (x86)\Steam\Steam.exe" -community="https://steamcommunity.com"
```

商店 http://store.steampowered.com/

社区 https://steamcommunity.com/

搜索好友 https://steamcommunity.com/search/users/
