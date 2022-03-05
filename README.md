# 单独使用AdGuardHome
**以下都是上游DNS服务器**
⬇

**谷歌DNS**

8.8.8.8

8.8.4.4

https://dns.google/dns-query

tls://dns.google

**阿里DNS**

223.5.5.5

223.6.6.6

https://dns.alidns.com/dns-query

tls://dns.alidns.com

**CloudFlare DNS**

1.1.1.1

1.0.0.1

https://dns.cloudflare.com/dns-query

tls://1dot1dot1dot1.cloudflare-dns.com

**腾讯DNS**

119.29.29.29

https://doh.pub/dns-query

**百度DNS**

180.76.76.76

**114DNS**

114.114.114.114

# Bootstrap DNS服务器（网友建议是本地运营商DNS）

223.5.5.5

8.8.8.8

119.29.29.29

180.76.76.76

114.114.114.114

# DNS封锁清单 网上很多
**AdGuard DNS filter**:https://adguardteam.github.io/AdGuardSDNSFilter/Filters/filter.txt 

**AdAway Default Blocklist**:https://adaway.org/hosts.txt 

**CHN: anti-AD**:https://anti-ad.net/easylist.txt

**AD1**:https://cats-team.coding.net/p/adguard/d/AdRules/git/raw/main/dns.txt 

**AD2**:https://cats-team.coding.net/p/adguard/d/AdRules/git/raw/main/allow.txt

**隐私1**:https://easylist-downloads.adblockplus.org/easyprivacy.txt

**隐私2**:https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjx-annoyance.txt

**合体1**:https://halflife.coding.net/p/list/d/list/git/raw/master/ad-pc.txt

**合体2**:https://halflife.coding.net/p/list/d/list/git/raw/master/ad.txt

**EasyList China**:https://raw.githubusercontent.com/easylist/easylistchina/master/easylistchina.txt

**效果**
![image](https://user-images.githubusercontent.com/33445700/155882746-7768d612-e2bd-4128-8c3f-14827d7fa4d1.png)


# 搭配SmartDNS
参考骷髅头大佬的文章:https://www.bilibili.com/read/cv12437146?spm_id_from=333.999.0.0

要将二者搭配使用，需要将SmartDNS的重定向取消，然后在AdGuardHome的上有服务器里写上SmartDNS服务器地址和端口，如192.168.2.1:6053

**可能有一些细节没写到或是错误的，我也是小白。教程进仅供记录自己，不供参考，网络不通不怪我。**
