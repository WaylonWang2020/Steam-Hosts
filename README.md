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
解析Store的IP
nslookup store.steampowered.com
``` 
```
添加hosts
C:\Windows\System32\drivers\etc\   hosts
#104.78.74.220 store.steampowered.com
104.78.74.220 steamcommunity.com
```
```
修改程序启动参数
"D:\Program Files (x86)\Steam\Steam.exe" -community="https://steamcommunity.com"
```

商店 http://store.steampowered.com/

社区 https://steamcommunity.com/

搜索好友 https://steamcommunity.com/search/users/
