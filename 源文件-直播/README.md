
<h1 align="center"> 经常维护的IPv6直播源收集、分流、反代、短网址计划</h1>
  <h3 align="center"> 本计划只是收集，随缘更新。</h1>
  
## 源收集

|#|源地址|反代免翻短网址|更新时间|分流网址|分流反代短网址|备注|
|---|----|-----|-----|-----|-----|-----|
|1|[范明明][FMM]|https://gg.gg/zby001|20/Dec/23|待完善|待完善|更新及时，主要为v6，主力推荐|
|2|[乐青影音][LQ]|https://gg.gg/zby002|26/Dec/23|待完善|待完善|4000台，建议TVBox换源|
|3|[范明明Github][FMMG]|https://gg.gg/zby003|20/Dec/23|待完善|待完善|同范明明|
|4|[Gavin12340][Gavin]|https://gg.gg/zby004|9/Sep/23|待完善|待完善|v6卫视港台国际|
|5|[Kimentanm][KIM]|https://gg.gg/zby005|18/Dec/23|待完善|待完善|v4v6卫视香港|
|6|[Meroser][MER]|https://gg.gg/zby006|23/Dec/23|待完善|待完善|v6卫视港台国际|
|7|[whpsky][WHP]|https://gg.gg/zby007|15/Dec/23|待完善|待完善|v6上海苏州卫视港台国际|
|8|[wuyun999][WY]|https://gg.gg/zby008|1/Jun/23|待完善|待完善|1000台，杂，有广播|
|9|[YanG-1989][YGG]|https://gg.gg/zby009|15/Dec/23|待完善|待完善|2000台，杂，有广播|
|10|[YanG-1989-Adult][YGA]|https://gg.gg/zby1801|15/Dec/23|待完善|待完善|懂的都懂|
|11|[YueChan][YC]|https://gg.gg/zby010|26/Dec/23|待完善|待完善|v6，卫视港台国际|

- IPTV-org，全球IPTV直播源，每日更新，国内源不一定高效，作为收集备选。
  - [中国][IPTV-org-CN]  [香港][IPTV-org-HK]  [台湾][IPTV-org-TW]  [新加坡][IPTV-org-SG]  [日本][IPTV-org-JP] 
- 其余源请在目录内自行翻阅，目录名为Github作者名，可自行查询更新。

### 源介绍
  **M3U源/TXT源/Televizo/TiviMate/TVBox电视源的一些理解:**
 -    M3U/TXT源都可以分组，播放器Televizo/TiviMate/TVBox都接受M3U源跟TXT源，但是无法自动换源，换源是在客户端配置；
 -   播放器Televizo/TiviMate均无法设置换源，多少条重复源就显示多少条，只有TVBox能合并自动换源；

    `M3U源`分组格式
    #EXTM3U x-tvg-url="https://live.fanmingming.com/e.xml"
    #EXTINF:-1 tvg-id="CCTV1" tvg-name="CCTV1" tvg-logo="https://live.fanmingming.com/tv/CCTV1.png" group-title="央视",CCTV-1 综合
    可用的CCTV1节目源
    此处省略...

    `TXT源`分组格式
    分组1,#genre#
    可用的节目源
    分组2,#genre#
    可用的节目源
    

### 反代
反代简单理解为主动将服务器的内容反馈给客户端，达到FQ或者提速的目的，GitHub目前收集到的反代有2类，替换跟前置：
  1. hub.fgit.cf/hub.yzuu.cf/hub.nuaa.cf/kkgithub.com，替换github.com和raw.githubusercontent.com，可以自动反代raw，不过建议引用文件的时候使用raw.fgit.cf/raw.yzuu.cf/raw.nuaa.cf/raw.kkgithub.com。
  2. ghproxy.net/ghproxy.org/mirror.ghproxy.com/gh.api.99988866.xyz/，直接加在github.com和raw.githubusercontent.com前面。

    
--------------------------------
[IPTV-org-CN]:https://iptv-org.github.io/iptv/countries/cn.m3u
[IPTV-org-HK]:https://iptv-org.github.io/iptv/countries/hk.m3u
[IPTV-org-TW]:https://iptv-org.github.io/iptv/countries/tw.m3u
[IPTV-org-SG]:https://iptv-org.github.io/iptv/countries/sg.m3u
[IPTV-org-JP]:https://iptv-org.github.io/iptv/countries/jp.m3u
[FMM]:https://live.fanmingming.com/tv/m3u/ipv6.m3u
[LQ]:https://lqtv.github.io/m3u/tv.m3u
[FMMG]:https://raw.githubusercontent.com/fanmingming/live/main/tv/m3u/ipv6.m3u
[Gavin]:https://raw.githubusercontent.com/Gavin12340/iptv_ipv6_main/main/iptv_ipv6_main.m3u
[KIM]:https://raw.githubusercontent.com/Kimentanm/aptv/master/m3u/iptv.m3u
[MER]:https://raw.githubusercontent.com/Meroser/IPTV/main/IPTV.m3u
[WHP]:https://raw.githubusercontent.com/whpsky/iptv/main/chinatv.m3u
[WY]:https://raw.githubusercontent.com/wuyun999/wuyun/main/zb/ix3.m3u
[YGG]:https://raw.githubusercontent.com/YanG-1989/m3u/main/Gather.m3u
[YGA]:https://raw.githubusercontent.com/YanG-1989/m3u/main/Adult.m3u
[YC]:https://raw.githubusercontent.com/YueChan/Live/main/IPTV.m3u
