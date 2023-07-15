| # | Server | Location | Protocol |Websocket+TLS| Type | Remark | Bandwidth/Quota|
|---|----------|----------|----------|-----|----------|----------|-----|
|1.1|[WannaShabuShabuRP](ss://eGNoYWNoYTIwLWlldGYtcG9seTEzMDU6U2xlZXB5X1MwcnJyeQ@jp.chiioi.eu.org:443/?plugin=v2ray-plugin%3btls%3bhost%3djp.chiioi.eu.org%3bpath%3d%2fv2ray)| Tokyo, JP | ss | ✓| Cloudflare CDN|Microsoft Azure|50Mbps/15GB|
|1.2.1*|[WannaShabuShabu](vless://140b968a-155b-4aec-95d6-a487147a4fd9@jpvl.chiioi.eu.org:1443?security=tls&encryption=none&alpn=http/1.1&headerType=none&type=tcp&flow=xtls-rprx-vision#ShabuShabu)| Tokyo, JP | VLESS| | direct|Microsoft Azure|50Mbps/15GB|
|2.1|[SecretGardenRP](ss://eGNoYWNoYTIwLWlldGYtcG9seTEzMDU6U2xlZWd5X1MwcnJyeQ@sg.chiioi.me:443/?plugin=v2ray-plugin%3btls%3bhost%3dsg.chiioi.me%3bpath%3d%2fgarden)| Singapore, SG | ss|✓|Cloudflare CDN/Planning to Rebuild CDN in Shanghai|DigitalOcean/Recommended(Special Days)|INF/1.5TB|
|2.2|[SecretGarden](vmess://eyJhZGQiOiJzZ3JwLmNoaWlvaS5ldS5vcmciLCJhaWQiOiIwIiwiYWxwbiI6IiIsImZwIjoiIiwiaG9zdCI6IiIsImlkIjoiYzgzMTMyMWQtNjMyNC00ZDUzLWFkNGYtOGNkYTQ4YjEyMzQ1IiwibmV0Ijoid3MiLCJwYXRoIjoiL3NncnAiLCJwb3J0IjoiNDQzIiwicHMiOiJTZWNyZXRHYXJkZW4iLCJzY3kiOiJhdXRvIiwic25pIjoiIiwidGxzIjoidGxzIiwidHlwZSI6IiIsInYiOiIyIn0=)| Singapore, SG |  vmess| ✓| direct|Recommended |INF/1.5TB|
|3.1|[SleepyLoMei](ss://eGNoYWNoYTIwLWlldGYtcG9seTEzMDU6U2ZlZXB5X1MwcnJyeQ@us.chiioi.eu.org:443/?plugin=v2ray-plugin%3btls%3bhost%3dus.chiioi.eu.org%3bpath%3d%2flm)| San Francisco, US  | ss| ✓  |direct| DigitalOcean/Share Quota with SecretGarden|INF/1.5TB|
|3.2|[SleepyLoMeiRP](vmess://eyJhZGQiOiJ1c3JwLmNoaWlvaS5tZSIsImFpZCI6IjAiLCJhbHBuIjoiIiwiZnAiOiIiLCJob3N0IjoiIiwiaWQiOiJjODMxMzIxZC02MzI0LTRkNTMtYWQ0Zi04Y2RhNDhiNjEwMTkiLCJuZXQiOiJ3cyIsInBhdGgiOiIvbG1ycCIsInBvcnQiOiI0NDMiLCJwcyI6IkxvTWVpUlAiLCJzY3kiOiJhdXRvIiwic25pIjoiIiwidGxzIjoidGxzIiwidHlwZSI6IiIsInYiOiIyIn0=)| San Francisco, US  | vmess |✓| Cloudflare CDN||INF/1.5TB|
|4.3|[MickeyMouse](trojan://Sleepy_S0rrry@mk.chiioi.me:443#mk.chiioi.me%3A443)| Sydney, AU  | trojan  ||  direct|Backup/DigitalOcean/Share Quota with SecretGarden/***使用trojan協議請注意自身數據安全***|INF/1.5TB|
|0.0|DryMincedBeef| Macau, CN  | ||Cloudflare|Mtel/Only For Test/ss/v2/trojan||

Clash格式的配置文件（二選一即可）：

主文件:  [https://config.chiioi.me/magicbox.yaml](https://config.chiioi.me/magicbox.yaml) (Github/Cloudflare CDN)

鏡像(鏡粉唔好打禾qq): <strike>[https://conf2.chiioi.me](https://conf2.chiioi.me)</strike> (JPEast/Cloudflare CDN)

廢置: <strike>https://jp.chiioi.eu.org/magicbox.yaml</strike>  (JPEast/direct)

---

Windows:
你可以選擇以下任一客戶端進行連接
- 使用Shadowsocks配合v2ray-plugin連接上表中的Server x.1
- 使用V2Ray core配合V2RayN或Qv2ray介面連接上表中的Server x.2
	*Qv2ray配合各QvPlugin可以連接上表的任一Server*
- <strike>使用Trojan-Qt5連接上表中的Server x.3</strike>
- 使用Clash連接上表的不帶*號的任一Server（這個很麻煩我也不會用）

---

Mac OS:
你可以選擇以下任一客戶端進行連接
- 使用V2Ray core配合Qv2ray介面連接上表中的Server x.2
	*Qv2ray配合各QvPlugin可以連接上表的任一Server*
- 使用ClashX連接上表的任一Server

---

Android:
你可以選擇以下任一客戶端進行連接
- 使用Shadowsocks配合v2ray-plugin連接上表中的Server x.1
- 使用V2rayNG連接上表中的Server x.2/x.3
- 使用Clash for Android連接上表不帶*號的的任一Server（強推Android端貓貓client）

---

iOS:
你可以選擇以下任一客戶端進行連接
- 使用Shadowrocket連接上表不帶*號的的任一Server

---
