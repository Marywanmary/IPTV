
<h1 align="center"> 经常维护的IPv6直播源收集、分流、Shorten计划</h1>
  <h3 align="center"> 本计划只是收集，随缘更新。</h1>
  
## 源收集介绍

### 源介绍
    ***M3U源/TXT源/Televizo/TiviMate/TVBox电视源的一些理解***</p>
    M3U/TXT源都可以分组，但是无法自动换源，换源是在客户端配置；</p>
    Televizo/TiviMate均无法设置换源，多少条重复源就显示多少条，只有TVBox能合并自动换源。</p>
    Televizo/TiviMate/TVBox都接受M3U源跟TXT源</p>

    M3U源分组格式</p>
    #EXTM3U x-tvg-url="https://live.fanmingming.com/e.xml"</p>
    #EXTINF:-1 tvg-id="CCTV1" tvg-name="CCTV1" tvg-logo="https://live.fanmingming.com/tv/CCTV1.png" group-title="央视",CCTV-1 综合</p>
    可用的CCTV1节目源</p>
    此处省略...</p>

    TXT源分组格式</p>
    分组1,#genre#</p>
    可用的节目源</p>
    分组2,#genre#</p>
    可用的节目源</p>
    
### 源收集
 - IPTV-org，全球IPTV直播源，每日更新，缺点国内源不一定高效，作为收集备选。</p>
    - https://iptv-org.github.io/iptv/countries/cn.m3u</p>
    https://iptv-org.github.io/iptv/countries/hk.m3u</p>
    https://iptv-org.github.io/iptv/countries/tw.m3u</p>
    https://iptv-org.github.io/iptv/countries/sg.m3u</p>
    https://iptv-org.github.io/iptv/countries/jp.m3u</p>
 - fanmingming，范明明，近期很火的直播源，不用FQ，更新及时，主要为IPv6，主力推荐。</p>
    https://live.fanmingming.com/tv/m3u/ipv6.m3u</p>
    短网址：https://gg.gg/zby001</p>
    https://raw.githubusercontent.com/fanmingming/live/main/tv/m3u/ipv6.m3u 需要FQ

 - lqtv，乐青影音，不用FQ，更新及时，有IPv6，各地卫视，缺点台太多，适合TVBox</p>
    https://lqtv.github.io/m3u/tv.m3u</p>
    短网址：https://gg.gg/zby002</p>
 - Gavin12340，
    https://raw.githubusercontent.com/Gavin12340/iptv_ipv6_main/main/iptv_ipv6_main.m3u
 - Kimentanm
    https://raw.githubusercontent.com/Kimentanm/aptv/master/m3u/iptv.m3u
 - Meroser
    https://raw.githubusercontent.com/Meroser/IPTV/main/IPTV.m3u
 - whpsky
    https://raw.githubusercontent.com/whpsky/iptv/main/chinatv.m3u
 - wuyun999
    https://raw.githubusercontent.com/wuyun999/wuyun/main/zb/ix3.m3u
 - YanG-1989
    https://raw.githubusercontent.com/YanG-1989/m3u/main/Gather.m3u
    https://raw.githubusercontent.com/YanG-1989/m3u/main/Adult.m3u
 - YueChan
    https://raw.githubusercontent.com/YueChan/Live/main/IPTV.m3u
 - hussobaba
    https://raw.githubusercontent.com/hussobaba/AILE-Tv/main/TBRT5_AL.m3u

</p>
</p>

# 反代
    反代简单理解为主动将服务器的内容反馈给客户端，达到FQ或者提速的目的。
    GitHub目前收集到的反代有2类，替换跟前置。
    hub.fgit.cf/hub.yzuu.cf/hub.nuaa.cf/kkgithub.com，替换github.com和raw.githubusercontent.com，可以自动反代raw，不过建议引用url的时候使用raw.fgit.cf/raw.yzuu.cf/raw.nuaa.cf/raw.kkgithub.com
    https://ghproxy.net/https://ghproxy.org/https://mirror.ghproxy.com/https://gh.api.99988866.xyz/，直接加在github.com和raw.githubusercontent.com前面。

# 分流
    基于保存目的分流，不至于因为删库无法使用，佛系更新，介意者请自行建源。
    

## 分流更新日期：
<table>
  <thead>
    <tr>
      <th>原链接</th>
      <th>原短链接</th>
      <th>原作更新日期</th>
      <th>分流链接</th>
      <th>分流短链接</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="范明明">https://live.fanmingming.com/tv/m3u/ipv6.m3u</a></td>
      <td><a href="https://gg.gg/zby001">https://gg.gg/zby001</a></td>
      <td>20-Dec-2023</td>
      <td><a href="分流"></a></td>
      <td><a href="分流短"></a></td>
    </tr>
    <tr>
      <td><a href="范明明Github">https://raw.githubusercontent.com/fanmingming/live/main/tv/m3u/ipv6.m3u</a></td>
      <td><a href="https://gg.gg/zby003">https://gg.gg/zby003</a></td>
      <td>20-Dec-2023</td>
      <td><a href="分流"></a></td>
      <td><a href="分流短"></a></td>
    </tr>    
    <tr>
      <td><a href="Gavin12340">https://raw.githubusercontent.com/Gavin12340/iptv_ipv6_main/main/iptv_ipv6_main.m3u</a></td>
      <td><a href="https://gg.gg/zby004">https://gg.gg/zby004</a></td>
      <td>09-Sep-2023</td>
      <td><a href="分流"></a></td>
      <td><a href="分流短"></a></td>
    </tr>
    <tr>
      <td><a href="Kimentanm">https://raw.githubusercontent.com/Kimentanm/aptv/master/m3u/iptv.m3u</a></td>
      <td><a href="https://gg.gg/zby005">https://gg.gg/zby005</a></td>
      <td>18-Dec-2023</td>
      <td><a href="分流"></a></td>
      <td><a href="分流短"></a></td>
    </tr>
    <tr>
      <td><a href="Meroser">https://raw.githubusercontent.com/Meroser/IPTV/main/IPTV.m3u</a></td>
      <td><a href="https://gg.gg/zby006">https://gg.gg/zby006</a></td>
      <td>23-Dec-2023</td>
      <td><a href="分流"></a></td>
      <td><a href="分流短"></a></td>
    </tr>
    <tr>
      <td><a href="whpsky">https://raw.githubusercontent.com/whpsky/iptv/main/chinatv.m3u</a></td>
      <td><a href="https://gg.gg/zby007">https://gg.gg/zby007</a></td>
      <td>15-Dec-2023</td>
      <td><a href="分流"></a></td>
      <td><a href="分流短"></a></td>
    </tr>            
    <tr>
      <td><a href="wuyun999">https://raw.githubusercontent.com/wuyun999/wuyun/main/zb/ix3.m3u</a></td>
      <td><a href="https://gg.gg/zby008">https://gg.gg/zby008</a></td>
      <td>01-Jun-2023</td>
      <td><a href="分流"></a></td>
      <td><a href="分流短"></a></td>
    </tr>            
    <tr>
      <td><a href="YanG-1989">https://raw.githubusercontent.com/YanG-1989/m3u/main/Gather.m3u</a></td>
      <td><a href="https://gg.gg/zby009">https://gg.gg/zby009</a></td>
      <td>15-Dec-2023</td>
      <td><a href="分流"></a></td>
      <td><a href="分流短"></a></td>
    </tr>
    <tr>
      <td><a href="YanG-1989-18+">https://raw.githubusercontent.com/YanG-1989/m3u/main/Adult.m3u</a></td>
      <td><a href="https://gg.gg/zby1801">https://gg.gg/zby1801</a></td>
      <td>15-Dec-2023</td>
      <td><a href="分流"></a></td>
      <td><a href="分流短"></a></td>
    </tr>            
    <tr>
      <td><a href="YueChan">https://raw.githubusercontent.com/YueChan/Live/main/IPTV.m3u</a></td>
      <td><a href="https://gg.gg/zby010">https://gg.gg/zby010</a></td>
      <td>26-Dec-2023</td>
      <td><a href="分流"></a></td>
      <td><a href="分流短"></a></td>
    </tr>
    <tr>
      <td><a href="YueChan">https://raw.githubusercontent.com/YueChan/Live/main/IPTV.txt</a></td>
      <td><a href="https://gg.gg/zby011">https://gg.gg/zby011</a></td>
      <td>26-Dec-2023</td>
      <td><a href="分流"></a></td>
      <td><a href="分流短"></a></td>
    </tr>                    
  </tbody>
</table>

