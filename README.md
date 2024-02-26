# amy
port: 7890
socks-port: 7891
redir-port: 7892
mixed-port: 7893
allow-lan: false
mode: Rule
log-level: info
ipv6: false
hosts:
dns:
  enable: true
  ipv6: false
  listen: 0.0.0.0:1053
  use-hosts: true
  default-nameserver:
    - 119.29.29.29
    - 8.8.8.8
    - 1.1.1.1
  nameserver:
    - 223.5.5.5
    - 119.29.29.29
  fake-ip-range: 198.18.0.1/16
  fake-ip-filter:
    - '*.lan'
    - '*.localdomain'
    - '*.example'
    - '*.invalid'
    - '*.localhost'
    - '*.test'
    - '*.local'
    - '*.home.arpa'
    - time.*.com
    - time.*.gov
    - time.*.edu.cn
    - time.*.apple.com
    - time1.*.com
    - time2.*.com
    - time3.*.com
    - time4.*.com
    - time5.*.com
    - time6.*.com
    - time7.*.com
    - ntp.*.com
    - ntp1.*.com
    - ntp2.*.com
    - ntp3.*.com
    - ntp4.*.com
    - ntp5.*.com
    - ntp6.*.com
    - ntp7.*.com
    - '*.time.edu.cn'
    - '*.ntp.org.cn'
    - +.pool.ntp.org
    - time1.cloud.tencent.com
    - stun.*.*
    - stun.*.*.*
    - swscan.apple.com
    - mesu.apple.com
    - music.163.com
    - '*.music.163.com'
    - '*.126.net'
    - musicapi.taihe.com
    - music.taihe.com
    - songsearch.kugou.com
    - trackercdn.kugou.com
    - '*.kuwo.cn'
    - api-jooxtt.sanook.com
    - api.joox.com
    - y.qq.com
    - '*.y.qq.com'
    - streamoc.music.tc.qq.com
    - mobileoc.music.tc.qq.com
    - isure.stream.qqmusic.qq.com
    - dl.stream.qqmusic.qq.com
    - aqqmusic.tc.qq.com
    - amobile.music.tc.qq.com
    - localhost.ptlogin2.qq.com
    - '*.msftconnecttest.com'
    - '*.msftncsi.com'
    - '*.xiami.com'
    - '*.music.migu.cn'
    - music.migu.cn
    - +.wotgame.cn
    - +.wggames.cn
    - +.wowsgame.cn
    - +.wargaming.net
    - '*.*.*.srv.nintendo.net'
    - '*.*.stun.playstation.net'
    - xbox.*.*.microsoft.com
    - '*.*.xboxlive.com'
    - '*.ipv6.microsoft.com'
    - teredo.*.*.*
    - teredo.*.*
    - speedtest.cros.wr.pvp.net
    - +.jjvip8.com
    - www.douyu.com
    - activityapi.huya.com
    - activityapi.huya.com.w.cdngslb.com
    - www.bilibili.com
    - api.bilibili.com
    - a.w.bilicdn1.com
external-controller: 127.0.0.1:9090
clash-for-android:
  append-system-dns: false
profile:
  tracing: true
proxies:
  - name: 🇭🇰 香港 01
    type: ss
    server: a6d3e87.wndtkn.xyz
    port: "18300"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇭🇰 香港 02
    type: ss
    server: a6d3e87.wndtkn.xyz
    port: "18305"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇭🇰 香港 03
    type: ss
    server: a6d3e87.wndtkn.xyz
    port: "18310"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇭🇰 香港 04
    type: ss
    server: a6d3e87.wndtkn.xyz
    port: "18315"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇭🇰 香港 05
    type: ss
    server: a0c82f0.qbewux.xyz
    port: "18320"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇭🇰 香港 06
    type: ss
    server: a0c82f0.qbewux.xyz
    port: "18325"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇭🇰 香港 07
    type: ss
    server: a0c82f0.qbewux.xyz
    port: "18330"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇭🇰 香港 08
    type: ss
    server: a0c82f0.qbewux.xyz
    port: "18335"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇭🇰 香港 09
    type: ss
    server: a0c82f0.qbewux.xyz
    port: "18340"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇭🇰 香港 10
    type: ss
    server: a6d3e87.wndtkn.xyz
    port: "18345"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇭🇰 香港 11
    type: ss
    server: a6d3e87.wndtkn.xyz
    port: "18350"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇭🇰 香港 12
    type: ss
    server: a6d3e87.wndtkn.xyz
    port: "18400"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇭🇰 香港 13
    type: ss
    server: a6d3e87.wndtkn.xyz
    port: "18405"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇭🇰 香港 14
    type: ss
    server: a6d3e87.wndtkn.xyz
    port: "18410"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇭🇰 香港 15
    type: ss
    server: a6d3e87.wndtkn.xyz
    port: "18415"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇭🇰 香港 16
    type: ss
    server: a6d3e87.wndtkn.xyz
    port: "18420"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇭🇰 香港 17
    type: ss
    server: a0c82f0.qbewux.xyz
    port: "18425"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇭🇰 香港 18
    type: ss
    server: a0c82f0.qbewux.xyz
    port: "18430"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇭🇰 香港 19
    type: ss
    server: a0c82f0.qbewux.xyz
    port: "18435"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇭🇰 香港 20
    type: ss
    server: a0c82f0.qbewux.xyz
    port: "18440"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇭🇰 香港 21
    type: ss
    server: a0c82f0.qbewux.xyz
    port: "18445"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇺🇸 美国 01
    type: ss
    server: 34b6870.qfbwcd.xyz
    port: "18100"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇺🇸 美国 02
    type: ss
    server: 34b6870.qfbwcd.xyz
    port: "18105"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇺🇸 美国 03
    type: ss
    server: 34b6870.qfbwcd.xyz
    port: "18110"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇺🇸 美国 04
    type: ss
    server: 34b6870.qfbwcd.xyz
    port: "18115"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇺🇸 美国 05
    type: ss
    server: 34b6870.qfbwcd.xyz
    port: "18120"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇺🇸 美国 06
    type: ss
    server: ca43a43.flmsgo.xyz
    port: "18125"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇺🇸 美国 07
    type: ss
    server: ca43a43.flmsgo.xyz
    port: "18130"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇺🇸 美国 08
    type: ss
    server: ca43a43.flmsgo.xyz
    port: "18135"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇺🇸 美国 09
    type: ss
    server: ca43a43.flmsgo.xyz
    port: "18140"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇺🇸 美国 10
    type: ss
    server: ca43a43.flmsgo.xyz
    port: "18145"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇺🇸 美国 11
    type: ss
    server: ca43a43.flmsgo.xyz
    port: "18150"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇺🇸 美国 12
    type: ss
    server: 34b6870.qfbwcd.xyz
    port: "18155"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇺🇸 美国 13
    type: ss
    server: 34b6870.qfbwcd.xyz
    port: "18160"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇯🇵 日本 01
    type: ss
    server: 34b6870.qfbwcd.xyz
    port: "18002"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇯🇵 日本 02
    type: ss
    server: 34b6870.qfbwcd.xyz
    port: "18005"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇯🇵 日本 03
    type: ss
    server: 34b6870.qfbwcd.xyz
    port: "18010"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇯🇵 日本 04
    type: ss
    server: 34b6870.qfbwcd.xyz
    port: "18015"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇯🇵 日本 05
    type: ss
    server: ca43a43.flmsgo.xyz
    port: "18020"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇯🇵 日本 06
    type: ss
    server: ca43a43.flmsgo.xyz
    port: "18025"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇯🇵 日本 07
    type: ss
    server: ca43a43.flmsgo.xyz
    port: "18030"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇯🇵 日本 08
    type: ss
    server: ca43a43.flmsgo.xyz
    port: "18035"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇨🇳 台湾 01
    type: ss
    server: a6d3e87.wndtkn.xyz
    port: "18355"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇨🇳 台湾 02
    type: ss
    server: a6d3e87.wndtkn.xyz
    port: "18360"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇨🇳 台湾 03
    type: ss
    server: a0c82f0.qbewux.xyz
    port: "18365"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇨🇳 台湾 04
    type: ss
    server: a0c82f0.qbewux.xyz
    port: "18370"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇨🇳 台湾 05
    type: ss
    server: a6d3e87.wndtkn.xyz
    port: "18375"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇨🇳 台湾 06
    type: ss
    server: a6d3e87.wndtkn.xyz
    port: "18356"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇨🇳 台湾 07
    type: ss
    server: a6d3e87.wndtkn.xyz
    port: "18361"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇨🇳 台湾 08
    type: ss
    server: a0c82f0.qbewux.xyz
    port: "18366"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇨🇳 台湾 09
    type: ss
    server: a0c82f0.qbewux.xyz
    port: "18371"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇨🇳 台湾 10
    type: ss
    server: a0c82f0.qbewux.xyz
    port: "18376"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇸🇬 新加坡 01
    type: ss
    server: a6d3e87.wndtkn.xyz
    port: "18380"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇸🇬 新加坡 02
    type: ss
    server: a6d3e87.wndtkn.xyz
    port: "18385"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇸🇬 新加坡 03
    type: ss
    server: a0c82f0.qbewux.xyz
    port: "18390"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
  - name: 🇸🇬 新加坡 04
    type: ss
    server: a0c82f0.qbewux.xyz
    port: "18395"
    cipher: aes-128-gcm
    password: 4ab0eefc37d96661
    udp: true
    plugin: obfs
    plugin-opts:
      mode: http
      host: 2Aof7d8u6K.microsoft.com
proxy-groups:
  - name: AmyTelecom
    type: select
    proxies:
      - ♻️ Auto
      - 🇭🇰 香港 01
      - 🇭🇰 香港 02
      - 🇭🇰 香港 03
      - 🇭🇰 香港 04
      - 🇭🇰 香港 05
      - 🇭🇰 香港 06
      - 🇭🇰 香港 07
      - 🇭🇰 香港 08
      - 🇭🇰 香港 09
      - 🇭🇰 香港 10
      - 🇭🇰 香港 11
      - 🇭🇰 香港 12
      - 🇭🇰 香港 13
      - 🇭🇰 香港 14
      - 🇭🇰 香港 15
      - 🇭🇰 香港 16
      - 🇭🇰 香港 17
      - 🇭🇰 香港 18
      - 🇭🇰 香港 19
      - 🇭🇰 香港 20
      - 🇭🇰 香港 21
      - 🇺🇸 美国 01
      - 🇺🇸 美国 02
      - 🇺🇸 美国 03
      - 🇺🇸 美国 04
      - 🇺🇸 美国 05
      - 🇺🇸 美国 06
      - 🇺🇸 美国 07
      - 🇺🇸 美国 08
      - 🇺🇸 美国 09
      - 🇺🇸 美国 10
      - 🇺🇸 美国 11
      - 🇺🇸 美国 12
      - 🇺🇸 美国 13
      - 🇯🇵 日本 01
      - 🇯🇵 日本 02
      - 🇯🇵 日本 03
      - 🇯🇵 日本 04
      - 🇯🇵 日本 05
      - 🇯🇵 日本 06
      - 🇯🇵 日本 07
      - 🇯🇵 日本 08
      - 🇨🇳 台湾 01
      - 🇨🇳 台湾 02
      - 🇨🇳 台湾 03
      - 🇨🇳 台湾 04
      - 🇨🇳 台湾 05
      - 🇨🇳 台湾 06
      - 🇨🇳 台湾 07
      - 🇨🇳 台湾 08
      - 🇨🇳 台湾 09
      - 🇨🇳 台湾 10
      - 🇸🇬 新加坡 01
      - 🇸🇬 新加坡 02
      - 🇸🇬 新加坡 03
      - 🇸🇬 新加坡 04
  - name: ♻️ Auto
    type: url-test
    url: http://www.google.com/generate_204
    interval: 300
    tolerance: 50
    proxies:
      - 🇭🇰 香港 01
      - 🇭🇰 香港 02
      - 🇭🇰 香港 03
      - 🇭🇰 香港 04
      - 🇭🇰 香港 05
      - 🇭🇰 香港 06
      - 🇭🇰 香港 07
      - 🇭🇰 香港 08
      - 🇭🇰 香港 09
      - 🇭🇰 香港 10
      - 🇭🇰 香港 11
      - 🇭🇰 香港 12
      - 🇭🇰 香港 13
      - 🇭🇰 香港 14
      - 🇭🇰 香港 15
      - 🇭🇰 香港 16
      - 🇭🇰 香港 17
      - 🇭🇰 香港 18
      - 🇭🇰 香港 19
      - 🇭🇰 香港 20
      - 🇭🇰 香港 21
      - 🇺🇸 美国 01
      - 🇺🇸 美国 02
      - 🇺🇸 美国 03
      - 🇺🇸 美国 04
      - 🇺🇸 美国 05
      - 🇺🇸 美国 06
      - 🇺🇸 美国 07
      - 🇺🇸 美国 08
      - 🇺🇸 美国 09
      - 🇺🇸 美国 10
      - 🇺🇸 美国 11
      - 🇺🇸 美国 12
      - 🇺🇸 美国 13
      - 🇯🇵 日本 01
      - 🇯🇵 日本 02
      - 🇯🇵 日本 03
      - 🇯🇵 日本 04
      - 🇯🇵 日本 05
      - 🇯🇵 日本 06
      - 🇯🇵 日本 07
      - 🇯🇵 日本 08
      - 🇨🇳 台湾 01
      - 🇨🇳 台湾 02
      - 🇨🇳 台湾 03
      - 🇨🇳 台湾 04
      - 🇨🇳 台湾 05
      - 🇨🇳 台湾 06
      - 🇨🇳 台湾 07
      - 🇨🇳 台湾 08
      - 🇨🇳 台湾 09
      - 🇨🇳 台湾 10
      - 🇸🇬 新加坡 01
      - 🇸🇬 新加坡 02
      - 🇸🇬 新加坡 03
      - 🇸🇬 新加坡 04
  - name: 🍎 Apple
    type: select
    proxies:
      - DIRECT
      - AmyTelecom
  - name: 🎬 Emby
    type: select
    proxies:
      - AmyTelecom
      - DIRECT
      - 🇭🇰 香港 01
      - 🇭🇰 香港 02
      - 🇭🇰 香港 03
      - 🇭🇰 香港 04
      - 🇭🇰 香港 05
      - 🇭🇰 香港 06
      - 🇭🇰 香港 07
      - 🇭🇰 香港 08
      - 🇭🇰 香港 09
      - 🇭🇰 香港 10
      - 🇭🇰 香港 11
      - 🇭🇰 香港 12
      - 🇭🇰 香港 13
      - 🇭🇰 香港 14
      - 🇭🇰 香港 15
      - 🇭🇰 香港 16
      - 🇭🇰 香港 17
      - 🇭🇰 香港 18
      - 🇭🇰 香港 19
      - 🇭🇰 香港 20
      - 🇭🇰 香港 21
      - 🇺🇸 美国 01
      - 🇺🇸 美国 02
      - 🇺🇸 美国 03
      - 🇺🇸 美国 04
      - 🇺🇸 美国 05
      - 🇺🇸 美国 06
      - 🇺🇸 美国 07
      - 🇺🇸 美国 08
      - 🇺🇸 美国 09
      - 🇺🇸 美国 10
      - 🇺🇸 美国 11
      - 🇺🇸 美国 12
      - 🇺🇸 美国 13
      - 🇯🇵 日本 01
      - 🇯🇵 日本 02
      - 🇯🇵 日本 03
      - 🇯🇵 日本 04
      - 🇯🇵 日本 05
      - 🇯🇵 日本 06
      - 🇯🇵 日本 07
      - 🇯🇵 日本 08
      - 🇨🇳 台湾 01
      - 🇨🇳 台湾 02
      - 🇨🇳 台湾 03
      - 🇨🇳 台湾 04
      - 🇨🇳 台湾 05
      - 🇨🇳 台湾 06
      - 🇨🇳 台湾 07
      - 🇨🇳 台湾 08
      - 🇨🇳 台湾 09
      - 🇨🇳 台湾 10
      - 🇸🇬 新加坡 01
      - 🇸🇬 新加坡 02
      - 🇸🇬 新加坡 03
      - 🇸🇬 新加坡 04
  - name: 📲 Telegram
    type: select
    proxies:
      - AmyTelecom
      - DIRECT
      - 🇭🇰 香港 01
      - 🇭🇰 香港 02
      - 🇭🇰 香港 03
      - 🇭🇰 香港 04
      - 🇭🇰 香港 05
      - 🇭🇰 香港 06
      - 🇭🇰 香港 07
      - 🇭🇰 香港 08
      - 🇭🇰 香港 09
      - 🇭🇰 香港 10
      - 🇭🇰 香港 11
      - 🇭🇰 香港 12
      - 🇭🇰 香港 13
      - 🇭🇰 香港 14
      - 🇭🇰 香港 15
      - 🇭🇰 香港 16
      - 🇭🇰 香港 17
      - 🇭🇰 香港 18
      - 🇭🇰 香港 19
      - 🇭🇰 香港 20
      - 🇭🇰 香港 21
      - 🇺🇸 美国 01
      - 🇺🇸 美国 02
      - 🇺🇸 美国 03
      - 🇺🇸 美国 04
      - 🇺🇸 美国 05
      - 🇺🇸 美国 06
      - 🇺🇸 美国 07
      - 🇺🇸 美国 08
      - 🇺🇸 美国 09
      - 🇺🇸 美国 10
      - 🇺🇸 美国 11
      - 🇺🇸 美国 12
      - 🇺🇸 美国 13
      - 🇯🇵 日本 01
      - 🇯🇵 日本 02
      - 🇯🇵 日本 03
      - 🇯🇵 日本 04
      - 🇯🇵 日本 05
      - 🇯🇵 日本 06
      - 🇯🇵 日本 07
      - 🇯🇵 日本 08
      - 🇨🇳 台湾 01
      - 🇨🇳 台湾 02
      - 🇨🇳 台湾 03
      - 🇨🇳 台湾 04
      - 🇨🇳 台湾 05
      - 🇨🇳 台湾 06
      - 🇨🇳 台湾 07
      - 🇨🇳 台湾 08
      - 🇨🇳 台湾 09
      - 🇨🇳 台湾 10
      - 🇸🇬 新加坡 01
      - 🇸🇬 新加坡 02
      - 🇸🇬 新加坡 03
      - 🇸🇬 新加坡 04
  - name: 🎬 YouTube
    type: select
    proxies:
      - AmyTelecom
      - DIRECT
      - 🇭🇰 香港 01
      - 🇭🇰 香港 02
      - 🇭🇰 香港 03
      - 🇭🇰 香港 04
      - 🇭🇰 香港 05
      - 🇭🇰 香港 06
      - 🇭🇰 香港 07
      - 🇭🇰 香港 08
      - 🇭🇰 香港 09
      - 🇭🇰 香港 10
      - 🇭🇰 香港 11
      - 🇭🇰 香港 12
      - 🇭🇰 香港 13
      - 🇭🇰 香港 14
      - 🇭🇰 香港 15
      - 🇭🇰 香港 16
      - 🇭🇰 香港 17
      - 🇭🇰 香港 18
      - 🇭🇰 香港 19
      - 🇭🇰 香港 20
      - 🇭🇰 香港 21
      - 🇺🇸 美国 01
      - 🇺🇸 美国 02
      - 🇺🇸 美国 03
      - 🇺🇸 美国 04
      - 🇺🇸 美国 05
      - 🇺🇸 美国 06
      - 🇺🇸 美国 07
      - 🇺🇸 美国 08
      - 🇺🇸 美国 09
      - 🇺🇸 美国 10
      - 🇺🇸 美国 11
      - 🇺🇸 美国 12
      - 🇺🇸 美国 13
      - 🇯🇵 日本 01
      - 🇯🇵 日本 02
      - 🇯🇵 日本 03
      - 🇯🇵 日本 04
      - 🇯🇵 日本 05
      - 🇯🇵 日本 06
      - 🇯🇵 日本 07
      - 🇯🇵 日本 08
      - 🇨🇳 台湾 01
      - 🇨🇳 台湾 02
      - 🇨🇳 台湾 03
      - 🇨🇳 台湾 04
      - 🇨🇳 台湾 05
      - 🇨🇳 台湾 06
      - 🇨🇳 台湾 07
      - 🇨🇳 台湾 08
      - 🇨🇳 台湾 09
      - 🇨🇳 台湾 10
      - 🇸🇬 新加坡 01
      - 🇸🇬 新加坡 02
      - 🇸🇬 新加坡 03
      - 🇸🇬 新加坡 04
  - name: 🎬 Bilibili
    type: select
    proxies:
      - DIRECT
      - AmyTelecom
      - 🇭🇰 香港 01
      - 🇭🇰 香港 02
      - 🇭🇰 香港 03
      - 🇭🇰 香港 04
      - 🇭🇰 香港 05
      - 🇭🇰 香港 06
      - 🇭🇰 香港 07
      - 🇭🇰 香港 08
      - 🇭🇰 香港 09
      - 🇭🇰 香港 10
      - 🇭🇰 香港 11
      - 🇭🇰 香港 12
      - 🇭🇰 香港 13
      - 🇭🇰 香港 14
      - 🇭🇰 香港 15
      - 🇭🇰 香港 16
      - 🇭🇰 香港 17
      - 🇭🇰 香港 18
      - 🇭🇰 香港 19
      - 🇭🇰 香港 20
      - 🇭🇰 香港 21
      - 🇺🇸 美国 01
      - 🇺🇸 美国 02
      - 🇺🇸 美国 03
      - 🇺🇸 美国 04
      - 🇺🇸 美国 05
      - 🇺🇸 美国 06
      - 🇺🇸 美国 07
      - 🇺🇸 美国 08
      - 🇺🇸 美国 09
      - 🇺🇸 美国 10
      - 🇺🇸 美国 11
      - 🇺🇸 美国 12
      - 🇺🇸 美国 13
      - 🇯🇵 日本 01
      - 🇯🇵 日本 02
      - 🇯🇵 日本 03
      - 🇯🇵 日本 04
      - 🇯🇵 日本 05
      - 🇯🇵 日本 06
      - 🇯🇵 日本 07
      - 🇯🇵 日本 08
      - 🇨🇳 台湾 01
      - 🇨🇳 台湾 02
      - 🇨🇳 台湾 03
      - 🇨🇳 台湾 04
      - 🇨🇳 台湾 05
      - 🇨🇳 台湾 06
      - 🇨🇳 台湾 07
      - 🇨🇳 台湾 08
      - 🇨🇳 台湾 09
      - 🇨🇳 台湾 10
      - 🇸🇬 新加坡 01
      - 🇸🇬 新加坡 02
      - 🇸🇬 新加坡 03
      - 🇸🇬 新加坡 04
  - name: 🎬 myTVSUPER
    type: select
    proxies:
      - AmyTelecom
      - DIRECT
      - 🇭🇰 香港 01
      - 🇭🇰 香港 02
      - 🇭🇰 香港 03
      - 🇭🇰 香港 04
      - 🇭🇰 香港 05
      - 🇭🇰 香港 06
      - 🇭🇰 香港 07
      - 🇭🇰 香港 08
      - 🇭🇰 香港 09
      - 🇭🇰 香港 10
      - 🇭🇰 香港 11
      - 🇭🇰 香港 12
      - 🇭🇰 香港 13
      - 🇭🇰 香港 14
      - 🇭🇰 香港 15
      - 🇭🇰 香港 16
      - 🇭🇰 香港 17
      - 🇭🇰 香港 18
      - 🇭🇰 香港 19
      - 🇭🇰 香港 20
      - 🇭🇰 香港 21
      - 🇺🇸 美国 01
      - 🇺🇸 美国 02
      - 🇺🇸 美国 03
      - 🇺🇸 美国 04
      - 🇺🇸 美国 05
      - 🇺🇸 美国 06
      - 🇺🇸 美国 07
      - 🇺🇸 美国 08
      - 🇺🇸 美国 09
      - 🇺🇸 美国 10
      - 🇺🇸 美国 11
      - 🇺🇸 美国 12
      - 🇺🇸 美国 13
      - 🇯🇵 日本 01
      - 🇯🇵 日本 02
      - 🇯🇵 日本 03
      - 🇯🇵 日本 04
      - 🇯🇵 日本 05
      - 🇯🇵 日本 06
      - 🇯🇵 日本 07
      - 🇯🇵 日本 08
      - 🇨🇳 台湾 01
      - 🇨🇳 台湾 02
      - 🇨🇳 台湾 03
      - 🇨🇳 台湾 04
      - 🇨🇳 台湾 05
      - 🇨🇳 台湾 06
      - 🇨🇳 台湾 07
      - 🇨🇳 台湾 08
      - 🇨🇳 台湾 09
      - 🇨🇳 台湾 10
      - 🇸🇬 新加坡 01
      - 🇸🇬 新加坡 02
      - 🇸🇬 新加坡 03
      - 🇸🇬 新加坡 04
  - name: 📲 LineTV
    type: select
    proxies:
      - AmyTelecom
      - DIRECT
      - 🇭🇰 香港 01
      - 🇭🇰 香港 02
      - 🇭🇰 香港 03
      - 🇭🇰 香港 04
      - 🇭🇰 香港 05
      - 🇭🇰 香港 06
      - 🇭🇰 香港 07
      - 🇭🇰 香港 08
      - 🇭🇰 香港 09
      - 🇭🇰 香港 10
      - 🇭🇰 香港 11
      - 🇭🇰 香港 12
      - 🇭🇰 香港 13
      - 🇭🇰 香港 14
      - 🇭🇰 香港 15
      - 🇭🇰 香港 16
      - 🇭🇰 香港 17
      - 🇭🇰 香港 18
      - 🇭🇰 香港 19
      - 🇭🇰 香港 20
      - 🇭🇰 香港 21
      - 🇺🇸 美国 01
      - 🇺🇸 美国 02
      - 🇺🇸 美国 03
      - 🇺🇸 美国 04
      - 🇺🇸 美国 05
      - 🇺🇸 美国 06
      - 🇺🇸 美国 07
      - 🇺🇸 美国 08
      - 🇺🇸 美国 09
      - 🇺🇸 美国 10
      - 🇺🇸 美国 11
      - 🇺🇸 美国 12
      - 🇺🇸 美国 13
      - 🇯🇵 日本 01
      - 🇯🇵 日本 02
      - 🇯🇵 日本 03
      - 🇯🇵 日本 04
      - 🇯🇵 日本 05
      - 🇯🇵 日本 06
      - 🇯🇵 日本 07
      - 🇯🇵 日本 08
      - 🇨🇳 台湾 01
      - 🇨🇳 台湾 02
      - 🇨🇳 台湾 03
      - 🇨🇳 台湾 04
      - 🇨🇳 台湾 05
      - 🇨🇳 台湾 06
      - 🇨🇳 台湾 07
      - 🇨🇳 台湾 08
      - 🇨🇳 台湾 09
      - 🇨🇳 台湾 10
      - 🇸🇬 新加坡 01
      - 🇸🇬 新加坡 02
      - 🇸🇬 新加坡 03
      - 🇸🇬 新加坡 04
  - name: 🎬 iQiyi
    type: select
    proxies:
      - DIRECT
      - AmyTelecom
      - 🇭🇰 香港 01
      - 🇭🇰 香港 02
      - 🇭🇰 香港 03
      - 🇭🇰 香港 04
      - 🇭🇰 香港 05
      - 🇭🇰 香港 06
      - 🇭🇰 香港 07
      - 🇭🇰 香港 08
      - 🇭🇰 香港 09
      - 🇭🇰 香港 10
      - 🇭🇰 香港 11
      - 🇭🇰 香港 12
      - 🇭🇰 香港 13
      - 🇭🇰 香港 14
      - 🇭🇰 香港 15
      - 🇭🇰 香港 16
      - 🇭🇰 香港 17
      - 🇭🇰 香港 18
      - 🇭🇰 香港 19
      - 🇭🇰 香港 20
      - 🇭🇰 香港 21
      - 🇺🇸 美国 01
      - 🇺🇸 美国 02
      - 🇺🇸 美国 03
      - 🇺🇸 美国 04
      - 🇺🇸 美国 05
      - 🇺🇸 美国 06
      - 🇺🇸 美国 07
      - 🇺🇸 美国 08
      - 🇺🇸 美国 09
      - 🇺🇸 美国 10
      - 🇺🇸 美国 11
      - 🇺🇸 美国 12
      - 🇺🇸 美国 13
      - 🇯🇵 日本 01
      - 🇯🇵 日本 02
      - 🇯🇵 日本 03
      - 🇯🇵 日本 04
      - 🇯🇵 日本 05
      - 🇯🇵 日本 06
      - 🇯🇵 日本 07
      - 🇯🇵 日本 08
      - 🇨🇳 台湾 01
      - 🇨🇳 台湾 02
      - 🇨🇳 台湾 03
      - 🇨🇳 台湾 04
      - 🇨🇳 台湾 05
      - 🇨🇳 台湾 06
      - 🇨🇳 台湾 07
      - 🇨🇳 台湾 08
      - 🇨🇳 台湾 09
      - 🇨🇳 台湾 10
      - 🇸🇬 新加坡 01
      - 🇸🇬 新加坡 02
      - 🇸🇬 新加坡 03
      - 🇸🇬 新加坡 04
  - name: 🎵 Tiktok
    type: select
    proxies:
      - AmyTelecom
      - DIRECT
      - 🇭🇰 香港 01
      - 🇭🇰 香港 02
      - 🇭🇰 香港 03
      - 🇭🇰 香港 04
      - 🇭🇰 香港 05
      - 🇭🇰 香港 06
      - 🇭🇰 香港 07
      - 🇭🇰 香港 08
      - 🇭🇰 香港 09
      - 🇭🇰 香港 10
      - 🇭🇰 香港 11
      - 🇭🇰 香港 12
      - 🇭🇰 香港 13
      - 🇭🇰 香港 14
      - 🇭🇰 香港 15
      - 🇭🇰 香港 16
      - 🇭🇰 香港 17
      - 🇭🇰 香港 18
      - 🇭🇰 香港 19
      - 🇭🇰 香港 20
      - 🇭🇰 香港 21
      - 🇺🇸 美国 01
      - 🇺🇸 美国 02
      - 🇺🇸 美国 03
      - 🇺🇸 美国 04
      - 🇺🇸 美国 05
      - 🇺🇸 美国 06
      - 🇺🇸 美国 07
      - 🇺🇸 美国 08
      - 🇺🇸 美国 09
      - 🇺🇸 美国 10
      - 🇺🇸 美国 11
      - 🇺🇸 美国 12
      - 🇺🇸 美国 13
      - 🇯🇵 日本 01
      - 🇯🇵 日本 02
      - 🇯🇵 日本 03
      - 🇯🇵 日本 04
      - 🇯🇵 日本 05
      - 🇯🇵 日本 06
      - 🇯🇵 日本 07
      - 🇯🇵 日本 08
      - 🇨🇳 台湾 01
      - 🇨🇳 台湾 02
      - 🇨🇳 台湾 03
      - 🇨🇳 台湾 04
      - 🇨🇳 台湾 05
      - 🇨🇳 台湾 06
      - 🇨🇳 台湾 07
      - 🇨🇳 台湾 08
      - 🇨🇳 台湾 09
      - 🇨🇳 台湾 10
      - 🇸🇬 新加坡 01
      - 🇸🇬 新加坡 02
      - 🇸🇬 新加坡 03
      - 🇸🇬 新加坡 04
  - name: 📺 Disney
    type: select
    proxies:
      - AmyTelecom
      - DIRECT
      - 🇭🇰 香港 01
      - 🇭🇰 香港 02
      - 🇭🇰 香港 03
      - 🇭🇰 香港 04
      - 🇭🇰 香港 05
      - 🇭🇰 香港 06
      - 🇭🇰 香港 07
      - 🇭🇰 香港 08
      - 🇭🇰 香港 09
      - 🇭🇰 香港 10
      - 🇭🇰 香港 11
      - 🇭🇰 香港 12
      - 🇭🇰 香港 13
      - 🇭🇰 香港 14
      - 🇭🇰 香港 15
      - 🇭🇰 香港 16
      - 🇭🇰 香港 17
      - 🇭🇰 香港 18
      - 🇭🇰 香港 19
      - 🇭🇰 香港 20
      - 🇭🇰 香港 21
      - 🇺🇸 美国 01
      - 🇺🇸 美国 02
      - 🇺🇸 美国 03
      - 🇺🇸 美国 04
      - 🇺🇸 美国 05
      - 🇺🇸 美国 06
      - 🇺🇸 美国 07
      - 🇺🇸 美国 08
      - 🇺🇸 美国 09
      - 🇺🇸 美国 10
      - 🇺🇸 美国 11
      - 🇺🇸 美国 12
      - 🇺🇸 美国 13
      - 🇯🇵 日本 01
      - 🇯🇵 日本 02
      - 🇯🇵 日本 03
      - 🇯🇵 日本 04
      - 🇯🇵 日本 05
      - 🇯🇵 日本 06
      - 🇯🇵 日本 07
      - 🇯🇵 日本 08
      - 🇨🇳 台湾 01
      - 🇨🇳 台湾 02
      - 🇨🇳 台湾 03
      - 🇨🇳 台湾 04
      - 🇨🇳 台湾 05
      - 🇨🇳 台湾 06
      - 🇨🇳 台湾 07
      - 🇨🇳 台湾 08
      - 🇨🇳 台湾 09
      - 🇨🇳 台湾 10
      - 🇸🇬 新加坡 01
      - 🇸🇬 新加坡 02
      - 🇸🇬 新加坡 03
      - 🇸🇬 新加坡 04
  - name: 📺 Netflix
    type: select
    proxies:
      - AmyTelecom
      - DIRECT
      - 🇭🇰 香港 01
      - 🇭🇰 香港 02
      - 🇭🇰 香港 03
      - 🇭🇰 香港 04
      - 🇭🇰 香港 05
      - 🇭🇰 香港 06
      - 🇭🇰 香港 07
      - 🇭🇰 香港 08
      - 🇭🇰 香港 09
      - 🇭🇰 香港 10
      - 🇭🇰 香港 11
      - 🇭🇰 香港 12
      - 🇭🇰 香港 13
      - 🇭🇰 香港 14
      - 🇭🇰 香港 15
      - 🇭🇰 香港 16
      - 🇭🇰 香港 17
      - 🇭🇰 香港 18
      - 🇭🇰 香港 19
      - 🇭🇰 香港 20
      - 🇭🇰 香港 21
      - 🇺🇸 美国 01
      - 🇺🇸 美国 02
      - 🇺🇸 美国 03
      - 🇺🇸 美国 04
      - 🇺🇸 美国 05
      - 🇺🇸 美国 06
      - 🇺🇸 美国 07
      - 🇺🇸 美国 08
      - 🇺🇸 美国 09
      - 🇺🇸 美国 10
      - 🇺🇸 美国 11
      - 🇺🇸 美国 12
      - 🇺🇸 美国 13
      - 🇯🇵 日本 01
      - 🇯🇵 日本 02
      - 🇯🇵 日本 03
      - 🇯🇵 日本 04
      - 🇯🇵 日本 05
      - 🇯🇵 日本 06
      - 🇯🇵 日本 07
      - 🇯🇵 日本 08
      - 🇨🇳 台湾 01
      - 🇨🇳 台湾 02
      - 🇨🇳 台湾 03
      - 🇨🇳 台湾 04
      - 🇨🇳 台湾 05
      - 🇨🇳 台湾 06
      - 🇨🇳 台湾 07
      - 🇨🇳 台湾 08
      - 🇨🇳 台湾 09
      - 🇨🇳 台湾 10
      - 🇸🇬 新加坡 01
      - 🇸🇬 新加坡 02
      - 🇸🇬 新加坡 03
      - 🇸🇬 新加坡 04
  - name: 🌐 Google
    type: select
    proxies:
      - AmyTelecom
      - DIRECT
      - 🇭🇰 香港 01
      - 🇭🇰 香港 02
      - 🇭🇰 香港 03
      - 🇭🇰 香港 04
      - 🇭🇰 香港 05
      - 🇭🇰 香港 06
      - 🇭🇰 香港 07
      - 🇭🇰 香港 08
      - 🇭🇰 香港 09
      - 🇭🇰 香港 10
      - 🇭🇰 香港 11
      - 🇭🇰 香港 12
      - 🇭🇰 香港 13
      - 🇭🇰 香港 14
      - 🇭🇰 香港 15
      - 🇭🇰 香港 16
      - 🇭🇰 香港 17
      - 🇭🇰 香港 18
      - 🇭🇰 香港 19
      - 🇭🇰 香港 20
      - 🇭🇰 香港 21
      - 🇺🇸 美国 01
      - 🇺🇸 美国 02
      - 🇺🇸 美国 03
      - 🇺🇸 美国 04
      - 🇺🇸 美国 05
      - 🇺🇸 美国 06
      - 🇺🇸 美国 07
      - 🇺🇸 美国 08
      - 🇺🇸 美国 09
      - 🇺🇸 美国 10
      - 🇺🇸 美国 11
      - 🇺🇸 美国 12
      - 🇺🇸 美国 13
      - 🇯🇵 日本 01
      - 🇯🇵 日本 02
      - 🇯🇵 日本 03
      - 🇯🇵 日本 04
      - 🇯🇵 日本 05
      - 🇯🇵 日本 06
      - 🇯🇵 日本 07
      - 🇯🇵 日本 08
      - 🇨🇳 台湾 01
      - 🇨🇳 台湾 02
      - 🇨🇳 台湾 03
      - 🇨🇳 台湾 04
      - 🇨🇳 台湾 05
      - 🇨🇳 台湾 06
      - 🇨🇳 台湾 07
      - 🇨🇳 台湾 08
      - 🇨🇳 台湾 09
      - 🇨🇳 台湾 10
      - 🇸🇬 新加坡 01
      - 🇸🇬 新加坡 02
      - 🇸🇬 新加坡 03
      - 🇸🇬 新加坡 04
  - name: 🐹 OpenAI
    type: select
    proxies:
      - AmyTelecom
      - DIRECT
      - 🇭🇰 香港 01
      - 🇭🇰 香港 02
      - 🇭🇰 香港 03
      - 🇭🇰 香港 04
      - 🇭🇰 香港 05
      - 🇭🇰 香港 06
      - 🇭🇰 香港 07
      - 🇭🇰 香港 08
      - 🇭🇰 香港 09
      - 🇭🇰 香港 10
      - 🇭🇰 香港 11
      - 🇭🇰 香港 12
      - 🇭🇰 香港 13
      - 🇭🇰 香港 14
      - 🇭🇰 香港 15
      - 🇭🇰 香港 16
      - 🇭🇰 香港 17
      - 🇭🇰 香港 18
      - 🇭🇰 香港 19
      - 🇭🇰 香港 20
      - 🇭🇰 香港 21
      - 🇺🇸 美国 01
      - 🇺🇸 美国 02
      - 🇺🇸 美国 03
      - 🇺🇸 美国 04
      - 🇺🇸 美国 05
      - 🇺🇸 美国 06
      - 🇺🇸 美国 07
      - 🇺🇸 美国 08
      - 🇺🇸 美国 09
      - 🇺🇸 美国 10
      - 🇺🇸 美国 11
      - 🇺🇸 美国 12
      - 🇺🇸 美国 13
      - 🇯🇵 日本 01
      - 🇯🇵 日本 02
      - 🇯🇵 日本 03
      - 🇯🇵 日本 04
      - 🇯🇵 日本 05
      - 🇯🇵 日本 06
      - 🇯🇵 日本 07
      - 🇯🇵 日本 08
      - 🇨🇳 台湾 01
      - 🇨🇳 台湾 02
      - 🇨🇳 台湾 03
      - 🇨🇳 台湾 04
      - 🇨🇳 台湾 05
      - 🇨🇳 台湾 06
      - 🇨🇳 台湾 07
      - 🇨🇳 台湾 08
      - 🇨🇳 台湾 09
      - 🇨🇳 台湾 10
      - 🇸🇬 新加坡 01
      - 🇸🇬 新加坡 02
      - 🇸🇬 新加坡 03
      - 🇸🇬 新加坡 04
  - name: 🖥 Microsoft
    type: select
    proxies:
      - DIRECT
      - AmyTelecom
      - 🇭🇰 香港 01
      - 🇭🇰 香港 02
      - 🇭🇰 香港 03
      - 🇭🇰 香港 04
      - 🇭🇰 香港 05
      - 🇭🇰 香港 06
      - 🇭🇰 香港 07
      - 🇭🇰 香港 08
      - 🇭🇰 香港 09
      - 🇭🇰 香港 10
      - 🇭🇰 香港 11
      - 🇭🇰 香港 12
      - 🇭🇰 香港 13
      - 🇭🇰 香港 14
      - 🇭🇰 香港 15
      - 🇭🇰 香港 16
      - 🇭🇰 香港 17
      - 🇭🇰 香港 18
      - 🇭🇰 香港 19
      - 🇭🇰 香港 20
      - 🇭🇰 香港 21
      - 🇺🇸 美国 01
      - 🇺🇸 美国 02
      - 🇺🇸 美国 03
      - 🇺🇸 美国 04
      - 🇺🇸 美国 05
      - 🇺🇸 美国 06
      - 🇺🇸 美国 07
      - 🇺🇸 美国 08
      - 🇺🇸 美国 09
      - 🇺🇸 美国 10
      - 🇺🇸 美国 11
      - 🇺🇸 美国 12
      - 🇺🇸 美国 13
      - 🇯🇵 日本 01
      - 🇯🇵 日本 02
      - 🇯🇵 日本 03
      - 🇯🇵 日本 04
      - 🇯🇵 日本 05
      - 🇯🇵 日本 06
      - 🇯🇵 日本 07
      - 🇯🇵 日本 08
      - 🇨🇳 台湾 01
      - 🇨🇳 台湾 02
      - 🇨🇳 台湾 03
      - 🇨🇳 台湾 04
      - 🇨🇳 台湾 05
      - 🇨🇳 台湾 06
      - 🇨🇳 台湾 07
      - 🇨🇳 台湾 08
      - 🇨🇳 台湾 09
      - 🇨🇳 台湾 10
      - 🇸🇬 新加坡 01
      - 🇸🇬 新加坡 02
      - 🇸🇬 新加坡 03
      - 🇸🇬 新加坡 04
  - name: 🖥 Learning
    type: select
    proxies:
      - AmyTelecom
      - DIRECT
      - 🇭🇰 香港 01
      - 🇭🇰 香港 02
      - 🇭🇰 香港 03
      - 🇭🇰 香港 04
      - 🇭🇰 香港 05
      - 🇭🇰 香港 06
      - 🇭🇰 香港 07
      - 🇭🇰 香港 08
      - 🇭🇰 香港 09
      - 🇭🇰 香港 10
      - 🇭🇰 香港 11
      - 🇭🇰 香港 12
      - 🇭🇰 香港 13
      - 🇭🇰 香港 14
      - 🇭🇰 香港 15
      - 🇭🇰 香港 16
      - 🇭🇰 香港 17
      - 🇭🇰 香港 18
      - 🇭🇰 香港 19
      - 🇭🇰 香港 20
      - 🇭🇰 香港 21
      - 🇺🇸 美国 01
      - 🇺🇸 美国 02
      - 🇺🇸 美国 03
      - 🇺🇸 美国 04
      - 🇺🇸 美国 05
      - 🇺🇸 美国 06
      - 🇺🇸 美国 07
      - 🇺🇸 美国 08
      - 🇺🇸 美国 09
      - 🇺🇸 美国 10
      - 🇺🇸 美国 11
      - 🇺🇸 美国 12
      - 🇺🇸 美国 13
      - 🇯🇵 日本 01
      - 🇯🇵 日本 02
      - 🇯🇵 日本 03
      - 🇯🇵 日本 04
      - 🇯🇵 日本 05
      - 🇯🇵 日本 06
      - 🇯🇵 日本 07
      - 🇯🇵 日本 08
      - 🇨🇳 台湾 01
      - 🇨🇳 台湾 02
      - 🇨🇳 台湾 03
      - 🇨🇳 台湾 04
      - 🇨🇳 台湾 05
      - 🇨🇳 台湾 06
      - 🇨🇳 台湾 07
      - 🇨🇳 台湾 08
      - 🇨🇳 台湾 09
      - 🇨🇳 台湾 10
      - 🇸🇬 新加坡 01
      - 🇸🇬 新加坡 02
      - 🇸🇬 新加坡 03
      - 🇸🇬 新加坡 04
  - name: 📟 Twitter
    type: select
    proxies:
      - AmyTelecom
      - DIRECT
      - 🇭🇰 香港 01
      - 🇭🇰 香港 02
      - 🇭🇰 香港 03
      - 🇭🇰 香港 04
      - 🇭🇰 香港 05
      - 🇭🇰 香港 06
      - 🇭🇰 香港 07
      - 🇭🇰 香港 08
      - 🇭🇰 香港 09
      - 🇭🇰 香港 10
      - 🇭🇰 香港 11
      - 🇭🇰 香港 12
      - 🇭🇰 香港 13
      - 🇭🇰 香港 14
      - 🇭🇰 香港 15
      - 🇭🇰 香港 16
      - 🇭🇰 香港 17
      - 🇭🇰 香港 18
      - 🇭🇰 香港 19
      - 🇭🇰 香港 20
      - 🇭🇰 香港 21
      - 🇺🇸 美国 01
      - 🇺🇸 美国 02
      - 🇺🇸 美国 03
      - 🇺🇸 美国 04
      - 🇺🇸 美国 05
      - 🇺🇸 美国 06
      - 🇺🇸 美国 07
      - 🇺🇸 美国 08
      - 🇺🇸 美国 09
      - 🇺🇸 美国 10
      - 🇺🇸 美国 11
      - 🇺🇸 美国 12
      - 🇺🇸 美国 13
      - 🇯🇵 日本 01
      - 🇯🇵 日本 02
      - 🇯🇵 日本 03
      - 🇯🇵 日本 04
      - 🇯🇵 日本 05
      - 🇯🇵 日本 06
      - 🇯🇵 日本 07
      - 🇯🇵 日本 08
      - 🇨🇳 台湾 01
      - 🇨🇳 台湾 02
      - 🇨🇳 台湾 03
      - 🇨🇳 台湾 04
      - 🇨🇳 台湾 05
      - 🇨🇳 台湾 06
      - 🇨🇳 台湾 07
      - 🇨🇳 台湾 08
      - 🇨🇳 台湾 09
      - 🇨🇳 台湾 10
      - 🇸🇬 新加坡 01
      - 🇸🇬 新加坡 02
      - 🇸🇬 新加坡 03
      - 🇸🇬 新加坡 04
  - name: 📺 International-Media
    type: select
    proxies:
      - AmyTelecom
      - DIRECT
      - 🇭🇰 香港 01
      - 🇭🇰 香港 02
      - 🇭🇰 香港 03
      - 🇭🇰 香港 04
      - 🇭🇰 香港 05
      - 🇭🇰 香港 06
      - 🇭🇰 香港 07
      - 🇭🇰 香港 08
      - 🇭🇰 香港 09
      - 🇭🇰 香港 10
      - 🇭🇰 香港 11
      - 🇭🇰 香港 12
      - 🇭🇰 香港 13
      - 🇭🇰 香港 14
      - 🇭🇰 香港 15
      - 🇭🇰 香港 16
      - 🇭🇰 香港 17
      - 🇭🇰 香港 18
      - 🇭🇰 香港 19
      - 🇭🇰 香港 20
      - 🇭🇰 香港 21
      - 🇺🇸 美国 01
      - 🇺🇸 美国 02
      - 🇺🇸 美国 03
      - 🇺🇸 美国 04
      - 🇺🇸 美国 05
      - 🇺🇸 美国 06
      - 🇺🇸 美国 07
      - 🇺🇸 美国 08
      - 🇺🇸 美国 09
      - 🇺🇸 美国 10
      - 🇺🇸 美国 11
      - 🇺🇸 美国 12
      - 🇺🇸 美国 13
      - 🇯🇵 日本 01
      - 🇯🇵 日本 02
      - 🇯🇵 日本 03
      - 🇯🇵 日本 04
      - 🇯🇵 日本 05
      - 🇯🇵 日本 06
      - 🇯🇵 日本 07
      - 🇯🇵 日本 08
      - 🇨🇳 台湾 01
      - 🇨🇳 台湾 02
      - 🇨🇳 台湾 03
      - 🇨🇳 台湾 04
      - 🇨🇳 台湾 05
      - 🇨🇳 台湾 06
      - 🇨🇳 台湾 07
      - 🇨🇳 台湾 08
      - 🇨🇳 台湾 09
      - 🇨🇳 台湾 10
      - 🇸🇬 新加坡 01
      - 🇸🇬 新加坡 02
      - 🇸🇬 新加坡 03
      - 🇸🇬 新加坡 04
  - name: China-Media
    type: select
    proxies:
      - DIRECT
      - AmyTelecom
  - name: Hijacking
    type: select
    proxies:
      - REJECT
      - DIRECT
  - name: China-Websites
    type: select
    proxies:
      - DIRECT
      - AmyTelecom
  - name: Final
    type: select
    proxies:
      - AmyTelecom
      - DIRECT
rules:
  - DOMAIN-SUFFIX,emby.nexitally.com,🎬 Emby
  - DOMAIN-SUFFIX,qfbwcd.xyz,DIRECT
  - DOMAIN-SUFFIX,ap.spotify.com,DIRECT
  - DOMAIN-KEYWORD,epochtimes,REJECT
  - DOMAIN-SUFFIX,881903.com,REJECT
  - DOMAIN-SUFFIX,aboluowang.com,REJECT
  - DOMAIN-SUFFIX,bannedbook.org,REJECT
  - DOMAIN-SUFFIX,bldaily.com,REJECT
  - DOMAIN-SUFFIX,china21.org,REJECT
  - DOMAIN-SUFFIX,chinaaffairs.org,REJECT
  - DOMAIN-SUFFIX,dajiyuan.com,REJECT
  - DOMAIN-SUFFIX,dalianmeng.org,REJECT
  - DOMAIN-SUFFIX,dkn.tv,REJECT
  - DOMAIN-SUFFIX,dongtaiwang.com,REJECT
  - DOMAIN-SUFFIX,edoors.com,REJECT
  - DOMAIN-SUFFIX,epochweekly.com,REJECT
  - DOMAIN-SUFFIX,falundafa.org,REJECT
  - DOMAIN-SUFFIX,fgmtv.org,REJECT
  - DOMAIN-SUFFIX,gardennetworks.com,REJECT
  - DOMAIN-SUFFIX,gongyiluntan.org,REJECT
  - DOMAIN-SUFFIX,gpass1.com,REJECT
  - DOMAIN-SUFFIX,hrichina.org,REJECT
  - DOMAIN-SUFFIX,huanghuagang.org,REJECT
  - DOMAIN-SUFFIX,internetfreedom.org,REJECT
  - DOMAIN-SUFFIX,kanzhongguo.com,REJECT
  - DOMAIN-SUFFIX,lagranepoca.com,REJECT
  - DOMAIN-SUFFIX,mh4u.org,REJECT
  - DOMAIN-SUFFIX,mhradio.org,REJECT
  - DOMAIN-SUFFIX,minghui.org,REJECT
  - DOMAIN-SUFFIX,newrealmstudios.ca,REJECT
  - DOMAIN-SUFFIX,ntdtv.com,REJECT
  - DOMAIN-SUFFIX,ogate.org,REJECT
  - DOMAIN-SUFFIX,open.com.hk,REJECT
  - DOMAIN-SUFFIX,organcare.org.tw,REJECT
  - DOMAIN-SUFFIX,qxbbs.org,REJECT
  - DOMAIN-SUFFIX,renminbao.com,REJECT
  - DOMAIN-SUFFIX,secretchina.com,REJECT
  - DOMAIN-SUFFIX,shenyun.com,REJECT
  - DOMAIN-SUFFIX,shenyunperformingarts.org,REJECT
  - DOMAIN-SUFFIX,shenzhoufilm.com,REJECT
  - DOMAIN-SUFFIX,soundofhope.org,REJECT
  - DOMAIN-SUFFIX,theepochtimes.com,REJECT
  - DOMAIN-SUFFIX,tiandixing.org,REJECT
  - DOMAIN-SUFFIX,tuidang.org,REJECT
  - DOMAIN-SUFFIX,velkaepocha.sk,REJECT
  - DOMAIN-SUFFIX,watchinese.com,REJECT
  - DOMAIN-SUFFIX,wixsite.com,REJECT
  - DOMAIN-SUFFIX,wujie.net,REJECT
  - DOMAIN-SUFFIX,wujieliulan.com,REJECT
  - DOMAIN-SUFFIX,xinsheng.net,REJECT
  - DOMAIN-SUFFIX,zhengjian.org,REJECT
  - DOMAIN-SUFFIX,zhuichaguoji.org,REJECT
  - DOMAIN-SUFFIX,aaplimg.com,🍎 Apple
  - DOMAIN-SUFFIX,Apple.co,🍎 Apple
  - DOMAIN-SUFFIX,Apple.com,🍎 Apple
  - DOMAIN-SUFFIX,appstore.com,🍎 Apple
  - DOMAIN-SUFFIX,cdn-Apple.com,🍎 Apple
  - DOMAIN-SUFFIX,crashlytics.com,🍎 Apple
  - DOMAIN-SUFFIX,icloud.com,🍎 Apple
  - DOMAIN-SUFFIX,icloud-content.com,🍎 Apple
  - DOMAIN-SUFFIX,me.com,🍎 Apple
  - DOMAIN-SUFFIX,mzstatic.com,🍎 Apple
  - DOMAIN,www-cdn.icloud.com.akadns.net,🍎 Apple
  - IP-CIDR,17.0.0.0/8,🍎 Apple
  - DOMAIN-SUFFIX,t.me,📲 Telegram
  - DOMAIN-SUFFIX,tdesktop.com,📲 Telegram
  - DOMAIN-SUFFIX,telegra.ph,📲 Telegram
  - DOMAIN-SUFFIX,telegram.me,📲 Telegram
  - DOMAIN-SUFFIX,telegram.org,📲 Telegram
  - DOMAIN-SUFFIX,telesco.pe,📲 Telegram
  - IP-CIDR,91.108.4.0/22,📲 Telegram
  - IP-CIDR,91.108.8.0/22,📲 Telegram
  - IP-CIDR,91.108.12.0/22,📲 Telegram
  - IP-CIDR,91.108.16.0/22,📲 Telegram
  - IP-CIDR,91.108.20.0/22,📲 Telegram
  - IP-CIDR,91.108.56.0/22,📲 Telegram
  - IP-CIDR,149.154.160.0/20,📲 Telegram
  - DOMAIN-SUFFIX,flightpacific.net,Final
  - DOMAIN-SUFFIX,nexitallysecure.com,Final
  - DOMAIN-SUFFIX,nexitally.com,Final
  - DOMAIN-SUFFIX,amysecure.com,Final
  - DOMAIN-SUFFIX,amytele.com,Final
  - DOMAIN,0gr4uqmtt8y41hcjsgrzdrc31.ourdvsss.com,🎬 Bilibili
  - DOMAIN,0gr4uqmtt8y41hcjsgrzdrc3s.ourdvsss.com,🎬 Bilibili
  - DOMAIN,0gr4uqmtt8y41hcjsgrzdrc3z.ourdvsss.com,🎬 Bilibili
  - DOMAIN,0gr4uqmtt8y41hcjsgrzdrctt.ourdvsss.com,🎬 Bilibili
  - DOMAIN,0gr4uqmtt8y41hcjsgrzdrctu.ourdvsss.com,🎬 Bilibili
  - DOMAIN,0gr4uqmtt8y41hcjz8yzdnc31.ourdvsss.com,🎬 Bilibili
  - DOMAIN,0gr4uqmtt8y41hcjz8yzdnc3t.ourdvsss.com,🎬 Bilibili
  - DOMAIN,0gr4uqmtt8y41hcjzgazdrpba.ourdvsss.com,🎬 Bilibili
  - DOMAIN,0gr4uqmtt8y41hcjzgazdrpbz.ourdvsss.com,🎬 Bilibili
  - DOMAIN,0gr4uqmtt8y41hcjzgazdrpjt.ourdvsss.com,🎬 Bilibili
  - DOMAIN,0gr5dgmttgha1hcj38yzdncb3.ourdvsss.com,🎬 Bilibili
  - DOMAIN,112-81-125-43.dhost.00cdn.com,🎬 Bilibili
  - DOMAIN,113-219-145-1.ksyungslb.com,🎬 Bilibili
  - DOMAIN,114-236-92-129.ksyungslb.com,🎬 Bilibili
  - DOMAIN,180-101-74-1.ksyungslb.com,🎬 Bilibili
  - DOMAIN,1geadrmttge3nhcjwgazdope.ourdvsss.com,🎬 Bilibili
  - DOMAIN,1geadrmttge3nhcjwgwzdqqe.ourdvsss.com,🎬 Bilibili
  - DOMAIN,1gr3uomttgr31hcjo8yzdnco.ourdvsss.com,🎬 Bilibili
  - DOMAIN,1gr3uomttgr31hcjo8yzdnpy.ourdvsss.com,🎬 Bilibili
  - DOMAIN,1gr3uomttgr31hcjtgezdkcy.ourdvsss.com,🎬 Bilibili
  - DOMAIN,1gr4uqmtt8y41hcjigazdqca.ourdvsss.com,🎬 Bilibili
  - DOMAIN,1gr4uqmtt8y41hcjigazdqce.ourdvsss.com,🎬 Bilibili
  - DOMAIN,1gr4uqmtt8y41hcjigazdqco.ourdvsss.com,🎬 Bilibili
  - DOMAIN,1gr4uqmtt8y41hcjigazdqpo.ourdvsss.com,🎬 Bilibili
  - DOMAIN,1gr4uqmtt8y41hcjzgwzdkqe.ourdvsss.com,🎬 Bilibili
  - DOMAIN,1gr5dgmttgha1hcj38yzdcca.ourdvsss.com,🎬 Bilibili
  - DOMAIN,1gr5dgmttgha1hcj38yzdcco.ourdvsss.com,🎬 Bilibili
  - DOMAIN,1gr5dgmttgha1hcj38yzdkca.ourdvsss.com,🎬 Bilibili
  - DOMAIN,1gr5dgmttgha1hcj38yzdkco.ourdvsss.com,🎬 Bilibili
  - DOMAIN,1gr5dgmttgha1hcj38yzdkpe.ourdvsss.com,🎬 Bilibili
  - DOMAIN,1gr5dgmttgha1hcj38yzdkpy.ourdvsss.com,🎬 Bilibili
  - DOMAIN,1gr5dgmttgha1hcj38yzdkqy.ourdvsss.com,🎬 Bilibili
  - DOMAIN,1gr5dgmttgha1hcj3gczdcpa.ourdvsss.com,🎬 Bilibili
  - DOMAIN,1gr5dgmttgha1hcj3gczdcpe.ourdvsss.com,🎬 Bilibili
  - DOMAIN,1gr5dgmttgha1hcj3gczdcpo.ourdvsss.com,🎬 Bilibili
  - DOMAIN,1gr5dgmttgha1hcj3gczdcqy.ourdvsss.com,🎬 Bilibili
  - DOMAIN,1gr5dgmttgha1hcttgrzdnpo.ourdvsss.com,🎬 Bilibili
  - DOMAIN,1graukmttga4nhcjtgozdgce.ourdvsss.com,🎬 Bilibili
  - DOMAIN,218-91-225-1.ksyungslb.com,🎬 Bilibili
  - DOMAIN,219-155-150-1.ksyungslb.com,🎬 Bilibili
  - DOMAIN,222-188-6-1.ksyungslb.com,🎬 Bilibili
  - DOMAIN,36-104-134-1.ksyungslb.com,🎬 Bilibili
  - DOMAIN,36-25-252-1.ksyungslb.com,🎬 Bilibili
  - DOMAIN,3ge3drmttga5nhcbqge3ur.ourdvsss.com,🎬 Bilibili
  - DOMAIN,3geauymtsgrzdnqbofa5do.ourdvsss.com,🎬 Bilibili
  - DOMAIN,3geauymtsgrzdnqbofa5dy.ourdvsss.com,🎬 Bilibili
  - DOMAIN,3geauymtsgrzdrcbzfahue.ourdvsss.com,🎬 Bilibili
  - DOMAIN,3geauymtsgrzdrcbzfahuk.ourdvsss.com,🎬 Bilibili
  - DOMAIN,4go41hcjtgazdoctqge4o.ourdvsss.com,🎬 Bilibili
  - DOMAIN,p-bstarstatic.akamaized.net,🎬 Bilibili
  - DOMAIN,p.bstarstatic.com,🎬 Bilibili
  - DOMAIN,upos-bstar-mirrorakam.akamaized.net,🎬 Bilibili
  - DOMAIN,upos-bstar1-mirrorakam.akamaized.net,🎬 Bilibili
  - DOMAIN-SUFFIX,acg.tv,🎬 Bilibili
  - DOMAIN-SUFFIX,acgvideo.com,🎬 Bilibili
  - DOMAIN-SUFFIX,animetamashi.cn,🎬 Bilibili
  - DOMAIN-SUFFIX,animetamashi.com,🎬 Bilibili
  - DOMAIN-SUFFIX,anitama.cn,🎬 Bilibili
  - DOMAIN-SUFFIX,anitama.net,🎬 Bilibili
  - DOMAIN-SUFFIX,b23.tv,🎬 Bilibili
  - DOMAIN-SUFFIX,baka.im,🎬 Bilibili
  - DOMAIN-SUFFIX,bigfun.cn,🎬 Bilibili
  - DOMAIN-SUFFIX,bigfunapp.cn,🎬 Bilibili
  - DOMAIN-SUFFIX,bili22.cn,🎬 Bilibili
  - DOMAIN-SUFFIX,bili2233.cn,🎬 Bilibili
  - DOMAIN-SUFFIX,bili23.cn,🎬 Bilibili
  - DOMAIN-SUFFIX,bili33.cn,🎬 Bilibili
  - DOMAIN-SUFFIX,biliapi.com,🎬 Bilibili
  - DOMAIN-SUFFIX,biliapi.net,🎬 Bilibili
  - DOMAIN-SUFFIX,bilibili.cc,🎬 Bilibili
  - DOMAIN-SUFFIX,bilibili.cn,🎬 Bilibili
  - DOMAIN-SUFFIX,bilibili.co,🎬 Bilibili
  - DOMAIN-SUFFIX,bilibili.com,🎬 Bilibili
  - DOMAIN-SUFFIX,bilibili.net,🎬 Bilibili
  - DOMAIN-SUFFIX,bilibili.tv,🎬 Bilibili
  - DOMAIN-SUFFIX,bilibiligame.cn,🎬 Bilibili
  - DOMAIN-SUFFIX,bilibiligame.co,🎬 Bilibili
  - DOMAIN-SUFFIX,bilibiligame.net,🎬 Bilibili
  - DOMAIN-SUFFIX,bilibilipay.cn,🎬 Bilibili
  - DOMAIN-SUFFIX,bilibilipay.com,🎬 Bilibili
  - DOMAIN-SUFFIX,bilicdn1.com,🎬 Bilibili
  - DOMAIN-SUFFIX,bilicdn2.com,🎬 Bilibili
  - DOMAIN-SUFFIX,bilicdn3.com,🎬 Bilibili
  - DOMAIN-SUFFIX,bilicdn4.com,🎬 Bilibili
  - DOMAIN-SUFFIX,bilicdn5.com,🎬 Bilibili
  - DOMAIN-SUFFIX,bilicomics.com,🎬 Bilibili
  - DOMAIN-SUFFIX,biligame.cn,🎬 Bilibili
  - DOMAIN-SUFFIX,biligame.co,🎬 Bilibili
  - DOMAIN-SUFFIX,biligame.com,🎬 Bilibili
  - DOMAIN-SUFFIX,biligame.net,🎬 Bilibili
  - DOMAIN-SUFFIX,biligo.com,🎬 Bilibili
  - DOMAIN-SUFFIX,biliimg.com,🎬 Bilibili
  - DOMAIN-SUFFIX,biliintl.com,🎬 Bilibili
  - DOMAIN-SUFFIX,biliplus.com,🎬 Bilibili
  - DOMAIN-SUFFIX,bilivideo.cn,🎬 Bilibili
  - DOMAIN-SUFFIX,bilivideo.com,🎬 Bilibili
  - DOMAIN-SUFFIX,bilivideo.net,🎬 Bilibili
  - DOMAIN-SUFFIX,corari.com,🎬 Bilibili
  - DOMAIN-SUFFIX,dreamcast.hk,🎬 Bilibili
  - DOMAIN-SUFFIX,dyhgames.com,🎬 Bilibili
  - DOMAIN-SUFFIX,hdslb.com,🎬 Bilibili
  - DOMAIN-SUFFIX,hdslb.com.w.kunlunhuf.com,🎬 Bilibili
  - DOMAIN-SUFFIX,hdslb.com.w.kunlunpi.com,🎬 Bilibili
  - DOMAIN-SUFFIX,hdslb.net,🎬 Bilibili
  - DOMAIN-SUFFIX,hdslb.org,🎬 Bilibili
  - DOMAIN-SUFFIX,im9.com,🎬 Bilibili
  - DOMAIN-SUFFIX,maoercdn.com,🎬 Bilibili
  - DOMAIN-SUFFIX,mcbbs.net,🎬 Bilibili
  - DOMAIN-SUFFIX,mincdn.com,🎬 Bilibili
  - DOMAIN-SUFFIX,sharejoytech.com,🎬 Bilibili
  - DOMAIN-SUFFIX,smtcdns.net,🎬 Bilibili
  - DOMAIN-SUFFIX,upos-hz-mirrorakam.akamaized.net,🎬 Bilibili
  - DOMAIN-SUFFIX,uposdash-302-bilivideo.yfcdn.net,🎬 Bilibili
  - DOMAIN-SUFFIX,yo9.com,🎬 Bilibili
  - IP-CIDR,106.75.74.76/32,🎬 Bilibili
  - IP-CIDR,111.206.25.147/32,🎬 Bilibili
  - IP-CIDR,119.3.238.64/32,🎬 Bilibili
  - IP-CIDR,120.92.108.182/32,🎬 Bilibili
  - IP-CIDR,120.92.113.99/32,🎬 Bilibili
  - IP-CIDR,120.92.153.217/32,🎬 Bilibili
  - IP-CIDR,134.175.207.130/32,🎬 Bilibili
  - IP-CIDR,203.107.1.0/24,🎬 Bilibili
  - DOMAIN-SUFFIX,mytvsuper.com,🎬 myTVSUPER
  - DOMAIN-SUFFIX,tvb.com,🎬 myTVSUPER
  - DOMAIN-SUFFIX,d3c7rimkq79yfu.cloudfront.net,📲 LineTV
  - DOMAIN-SUFFIX,linetv.tw,📲 LineTV
  - DOMAIN-SUFFIX,profile.line-scdn.net,📲 LineTV
  - DOMAIN,intel-cache.m.iqiyi.com,🎬 iQiyi
  - DOMAIN,intel-cache.video.iqiyi.com,🎬 iQiyi
  - DOMAIN,intl-rcd.iqiyi.com,🎬 iQiyi
  - DOMAIN,intl-subscription.iqiyi.com,🎬 iQiyi
  - DOMAIN-SUFFIX,inter.iqiyi.com,🎬 iQiyi
  - DOMAIN-SUFFIX,inter.ptqy.gitv.tv,🎬 iQiyi
  - DOMAIN-SUFFIX,intl.iqiyi.com,🎬 iQiyi
  - DOMAIN-SUFFIX,iq.com,🎬 iQiyi
  - IP-CIDR,103.44.56.0/22,🎬 iQiyi
  - IP-CIDR,118.26.120.0/24,🎬 iQiyi
  - IP-CIDR,118.26.32.0/23,🎬 iQiyi
  - IP-CIDR,223.119.62.225/28,🎬 iQiyi
  - IP-CIDR,23.40.241.251/32,🎬 iQiyi
  - IP-CIDR,23.40.242.10/32,🎬 iQiyi
  - DOMAIN-SUFFIX,byteoversea.com,🎵 Tiktok
  - DOMAIN-SUFFIX,ibytedtos.com,🎵 Tiktok
  - DOMAIN-SUFFIX,ipstatp.com,🎵 Tiktok
  - DOMAIN-SUFFIX,muscdn.com,🎵 Tiktok
  - DOMAIN-SUFFIX,musical.ly,🎵 Tiktok
  - DOMAIN-SUFFIX,tiktok.com,🎵 Tiktok
  - DOMAIN-SUFFIX,tik-tokapi.com,🎵 Tiktok
  - DOMAIN-SUFFIX,tiktokcdn.com,🎵 Tiktok
  - DOMAIN-SUFFIX,tiktokv.com,🎵 Tiktok
  - DOMAIN-KEYWORD,-tiktokcdn-com,🎵 Tiktok
  - DOMAIN-SUFFIX,googlevideo.com,🎬 YouTube
  - DOMAIN-SUFFIX,youtube.com,🎬 YouTube
  - DOMAIN-SUFFIX,ytimg.com,🎬 YouTube
  - DOMAIN,youtubei.googleapis.com,🎬 YouTube
  - DOMAIN,yt3.ggpht.com,🎬 YouTube
  - DOMAIN-SUFFIX,20thcenturystudios.com.au,📺 Disney
  - DOMAIN-SUFFIX,20thcenturystudios.com.br,📺 Disney
  - DOMAIN-SUFFIX,20thcenturystudios.jp,📺 Disney
  - DOMAIN-SUFFIX,abc-studios.com,📺 Disney
  - DOMAIN-SUFFIX,abc.com,📺 Disney
  - DOMAIN-SUFFIX,abcnews.com,📺 Disney
  - DOMAIN-SUFFIX,abcnews.edgesuite.net,📺 Disney
  - DOMAIN-SUFFIX,adobedtm.com,📺 Disney
  - DOMAIN-SUFFIX,adventuresbydisney.com,📺 Disney
  - DOMAIN-SUFFIX,babble.com,📺 Disney
  - DOMAIN-SUFFIX,babyzone.com,📺 Disney
  - DOMAIN-SUFFIX,bam.nr-data.net,📺 Disney
  - DOMAIN-SUFFIX,bamgrid.com,📺 Disney
  - DOMAIN-SUFFIX,beautyandthebeastmusical.co.uk,📺 Disney
  - DOMAIN-SUFFIX,braze.com,📺 Disney
  - DOMAIN-SUFFIX,cdn.optimizely.com,📺 Disney
  - DOMAIN-SUFFIX,conviva.com,📺 Disney
  - DOMAIN-SUFFIX,d9.flashtalking.com,📺 Disney
  - DOMAIN-SUFFIX,dilcdn.com,📺 Disney
  - DOMAIN-SUFFIX,disney-asia.com,📺 Disney
  - DOMAIN-SUFFIX,disney-discount.com,📺 Disney
  - DOMAIN-SUFFIX,disney-plus.net,📺 Disney
  - DOMAIN-SUFFIX,disney-portal.my.onetrust.com,📺 Disney
  - DOMAIN-SUFFIX,disney-studio.com,📺 Disney
  - DOMAIN-SUFFIX,disney-studio.net,📺 Disney
  - DOMAIN-SUFFIX,disney.asia,📺 Disney
  - DOMAIN-SUFFIX,disney.be,📺 Disney
  - DOMAIN-SUFFIX,disney.bg,📺 Disney
  - DOMAIN-SUFFIX,disney.ca,📺 Disney
  - DOMAIN-SUFFIX,disney.ch,📺 Disney
  - DOMAIN-SUFFIX,disney.co.il,📺 Disney
  - DOMAIN-SUFFIX,disney.co.jp,📺 Disney
  - DOMAIN-SUFFIX,disney.co.kr,📺 Disney
  - DOMAIN-SUFFIX,disney.co.th,📺 Disney
  - DOMAIN-SUFFIX,disney.co.uk,📺 Disney
  - DOMAIN-SUFFIX,disney.co.za,📺 Disney
  - DOMAIN-SUFFIX,disney.com,📺 Disney
  - DOMAIN-SUFFIX,disney.com.au,📺 Disney
  - DOMAIN-SUFFIX,disney.com.br,📺 Disney
  - DOMAIN-SUFFIX,disney.com.hk,📺 Disney
  - DOMAIN-SUFFIX,disney.com.tw,📺 Disney
  - DOMAIN-SUFFIX,disney.cz,📺 Disney
  - DOMAIN-SUFFIX,disney.de,📺 Disney
  - DOMAIN-SUFFIX,disney.demdex.net,📺 Disney
  - DOMAIN-SUFFIX,disney.dk,📺 Disney
  - DOMAIN-SUFFIX,disney.es,📺 Disney
  - DOMAIN-SUFFIX,disney.fi,📺 Disney
  - DOMAIN-SUFFIX,disney.fr,📺 Disney
  - DOMAIN-SUFFIX,disney.gr,📺 Disney
  - DOMAIN-SUFFIX,disney.hu,📺 Disney
  - DOMAIN-SUFFIX,disney.id,📺 Disney
  - DOMAIN-SUFFIX,disney.in,📺 Disney
  - DOMAIN-SUFFIX,disney.io,📺 Disney
  - DOMAIN-SUFFIX,disney.it,📺 Disney
  - DOMAIN-SUFFIX,disney.my,📺 Disney
  - DOMAIN-SUFFIX,disney.my.sentry.io,📺 Disney
  - DOMAIN-SUFFIX,disney.nl,📺 Disney
  - DOMAIN-SUFFIX,disney.no,📺 Disney
  - DOMAIN-SUFFIX,disney.ph,📺 Disney
  - DOMAIN-SUFFIX,disney.pl,📺 Disney
  - DOMAIN-SUFFIX,disney.pt,📺 Disney
  - DOMAIN-SUFFIX,disney.ro,📺 Disney
  - DOMAIN-SUFFIX,disney.ru,📺 Disney
  - DOMAIN-SUFFIX,disney.se,📺 Disney
  - DOMAIN-SUFFIX,disney.sg,📺 Disney
  - DOMAIN-SUFFIX,disneyadsales.com,📺 Disney
  - DOMAIN-SUFFIX,disneyarena.com,📺 Disney
  - DOMAIN-SUFFIX,disneyaulani.com,📺 Disney
  - DOMAIN-SUFFIX,disneybaby.com,📺 Disney
  - DOMAIN-SUFFIX,disneycareers.com,📺 Disney
  - DOMAIN-SUFFIX,disneychannelonstage.com,📺 Disney
  - DOMAIN-SUFFIX,disneychannelroadtrip.com,📺 Disney
  - DOMAIN-SUFFIX,disneycruisebrasil.com,📺 Disney
  - DOMAIN-SUFFIX,disneyenconcert.com,📺 Disney
  - DOMAIN-SUFFIX,disneyiejobs.com,📺 Disney
  - DOMAIN-SUFFIX,disneyinflight.com,📺 Disney
  - DOMAIN-SUFFIX,disneyinternational.com,📺 Disney
  - DOMAIN-SUFFIX,disneyinternationalhd.com,📺 Disney
  - DOMAIN-SUFFIX,disneyjunior.com,📺 Disney
  - DOMAIN-SUFFIX,disneyjuniortreataday.com,📺 Disney
  - DOMAIN-SUFFIX,disneylatino.com,📺 Disney
  - DOMAIN-SUFFIX,disneymagicmoments.co.il,📺 Disney
  - DOMAIN-SUFFIX,disneymagicmoments.co.uk,📺 Disney
  - DOMAIN-SUFFIX,disneymagicmoments.co.za,📺 Disney
  - DOMAIN-SUFFIX,disneymagicmoments.de,📺 Disney
  - DOMAIN-SUFFIX,disneymagicmoments.es,📺 Disney
  - DOMAIN-SUFFIX,disneymagicmoments.fr,📺 Disney
  - DOMAIN-SUFFIX,disneymagicmoments.gen.tr,📺 Disney
  - DOMAIN-SUFFIX,disneymagicmoments.gr,📺 Disney
  - DOMAIN-SUFFIX,disneymagicmoments.it,📺 Disney
  - DOMAIN-SUFFIX,disneymagicmoments.pl,📺 Disney
  - DOMAIN-SUFFIX,disneymagicmomentsme.com,📺 Disney
  - DOMAIN-SUFFIX,disneyme.com,📺 Disney
  - DOMAIN-SUFFIX,disneymeetingsandevents.com,📺 Disney
  - DOMAIN-SUFFIX,disneymovieinsiders.com,📺 Disney
  - DOMAIN-SUFFIX,disneymusicpromotion.com,📺 Disney
  - DOMAIN-SUFFIX,disneynewseries.com,📺 Disney
  - DOMAIN-SUFFIX,disneynow.com,📺 Disney
  - DOMAIN-SUFFIX,disneypeoplesurveys.com,📺 Disney
  - DOMAIN-SUFFIX,disneyplus.bn5x.net,📺 Disney
  - DOMAIN-SUFFIX,disneyplus.com,📺 Disney
  - DOMAIN-SUFFIX,disneyplus.com.ssl.sc.omtrdc.net,📺 Disney
  - DOMAIN-SUFFIX,disneyredirects.com,📺 Disney
  - DOMAIN-SUFFIX,disneysrivieraresort.com,📺 Disney
  - DOMAIN-SUFFIX,disneystore.com,📺 Disney
  - DOMAIN-SUFFIX,disneystreaming.com,📺 Disney
  - DOMAIN-SUFFIX,disneysubscription.com,📺 Disney
  - DOMAIN-SUFFIX,disneytickets.co.uk,📺 Disney
  - DOMAIN-SUFFIX,disneyturkiye.com.tr,📺 Disney
  - DOMAIN-SUFFIX,disneytvajobs.com,📺 Disney
  - DOMAIN-SUFFIX,disneyworld-go.com,📺 Disney
  - DOMAIN-SUFFIX,dmed.technology,📺 Disney
  - DOMAIN-SUFFIX,dssott.com,📺 Disney
  - DOMAIN-SUFFIX,dtci.co,📺 Disney
  - DOMAIN-SUFFIX,dtci.technology,📺 Disney
  - DOMAIN-SUFFIX,edgedatg.com,📺 Disney
  - DOMAIN-SUFFIX,espn.co.uk,📺 Disney
  - DOMAIN-SUFFIX,espn.com,📺 Disney
  - DOMAIN-SUFFIX,espn.hb.omtrdc.net,📺 Disney
  - DOMAIN-SUFFIX,espn.net,📺 Disney
  - DOMAIN-SUFFIX,espncdn.com,📺 Disney
  - DOMAIN-SUFFIX,espndotcom.tt.omtrdc.net,📺 Disney
  - DOMAIN-SUFFIX,espnqa.com,📺 Disney
  - DOMAIN-SUFFIX,execute-api.us-east-1.amazonaws.com,📺 Disney
  - DOMAIN-SUFFIX,go-disneyworldgo.com,📺 Disney
  - DOMAIN-SUFFIX,go.com,📺 Disney
  - DOMAIN-SUFFIX,js-agent.newrelic.com,📺 Disney
  - DOMAIN-SUFFIX,marvel.com,📺 Disney
  - DOMAIN-SUFFIX,marvel10thanniversary.com,📺 Disney
  - DOMAIN-SUFFIX,marveldimensionofheroes.com,📺 Disney
  - DOMAIN-SUFFIX,marvelparty.net,📺 Disney
  - DOMAIN-SUFFIX,marvelpinball.com,📺 Disney
  - DOMAIN-SUFFIX,marvelsdoubleagent.com,📺 Disney
  - DOMAIN-SUFFIX,marvelspotlightplays.com,📺 Disney
  - DOMAIN-SUFFIX,marvelsuperheroseptember.com,📺 Disney
  - DOMAIN-SUFFIX,marvelsuperwar.com,📺 Disney
  - DOMAIN-SUFFIX,mickey.tv,📺 Disney
  - DOMAIN-SUFFIX,moviesanywhere.com,📺 Disney
  - DOMAIN-SUFFIX,natgeomaps.com,📺 Disney
  - DOMAIN-SUFFIX,nationalgeographic.com,📺 Disney
  - DOMAIN-SUFFIX,nationalgeographicpartners.com,📺 Disney
  - DOMAIN-SUFFIX,ngeo.com,📺 Disney
  - DOMAIN-SUFFIX,nomadlandmovie.ch,📺 Disney
  - DOMAIN-SUFFIX,playmation.com,📺 Disney
  - DOMAIN-SUFFIX,shopdisney.com,📺 Disney
  - DOMAIN-SUFFIX,shops-disney.com,📺 Disney
  - DOMAIN-SUFFIX,sorcerersarena.com,📺 Disney
  - DOMAIN-SUFFIX,spaindisney.com,📺 Disney
  - DOMAIN-SUFFIX,star-brasil.com,📺 Disney
  - DOMAIN-SUFFIX,star-latam.com,📺 Disney
  - DOMAIN-SUFFIX,starwars.com,📺 Disney
  - DOMAIN-SUFFIX,starwarsgalacticstarcruiser.com,📺 Disney
  - DOMAIN-SUFFIX,starwarskids.com,📺 Disney
  - DOMAIN-SUFFIX,streamingdisney.net,📺 Disney
  - DOMAIN-SUFFIX,themarvelexperiencetour.com,📺 Disney
  - DOMAIN-SUFFIX,thestationbymaker.com,📺 Disney
  - DOMAIN-SUFFIX,thisispolaris.com,📺 Disney
  - DOMAIN-SUFFIX,watchdisneyfe.com,📺 Disney
  - DOMAIN-SUFFIX,watchespn.com,📺 Disney
  - PROCESS-NAME,com.disney.datg.videoplatforms.android.abc,📺 Disney
  - PROCESS-NAME,com.disney.disneyplus,📺 Disney
  - DOMAIN,e13252.dscg.akamaiedge.net,📺 Netflix
  - DOMAIN,h-netflix.online-metrix.net,📺 Netflix
  - DOMAIN,netflix.com.edgesuite.net,📺 Netflix
  - DOMAIN-SUFFIX,fast.com,📺 Netflix
  - DOMAIN-SUFFIX,flxvpn.net,📺 Netflix
  - DOMAIN-SUFFIX,netflix.ca,📺 Netflix
  - DOMAIN-SUFFIX,netflix.com,📺 Netflix
  - DOMAIN-SUFFIX,netflix.com.au,📺 Netflix
  - DOMAIN-SUFFIX,netflix.com.edgesuite.net,📺 Netflix
  - DOMAIN-SUFFIX,netflix.net,📺 Netflix
  - DOMAIN-SUFFIX,netflixdnstest0.com,📺 Netflix
  - DOMAIN-SUFFIX,netflixdnstest1.com,📺 Netflix
  - DOMAIN-SUFFIX,netflixdnstest10.com,📺 Netflix
  - DOMAIN-SUFFIX,netflixdnstest2.com,📺 Netflix
  - DOMAIN-SUFFIX,netflixdnstest3.com,📺 Netflix
  - DOMAIN-SUFFIX,netflixdnstest4.com,📺 Netflix
  - DOMAIN-SUFFIX,netflixdnstest5.com,📺 Netflix
  - DOMAIN-SUFFIX,netflixdnstest6.com,📺 Netflix
  - DOMAIN-SUFFIX,netflixdnstest7.com,📺 Netflix
  - DOMAIN-SUFFIX,netflixdnstest8.com,📺 Netflix
  - DOMAIN-SUFFIX,netflixdnstest9.com,📺 Netflix
  - DOMAIN-SUFFIX,netflixinvestor.com,📺 Netflix
  - DOMAIN-SUFFIX,netflixstudios.com,📺 Netflix
  - DOMAIN-SUFFIX,netflixtechblog.com,📺 Netflix
  - DOMAIN-SUFFIX,nflxext.com,📺 Netflix
  - DOMAIN-SUFFIX,nflximg.com,📺 Netflix
  - DOMAIN-SUFFIX,nflximg.net,📺 Netflix
  - DOMAIN-SUFFIX,nflxsearch.net,📺 Netflix
  - DOMAIN-SUFFIX,nflxso.net,📺 Netflix
  - DOMAIN-SUFFIX,nflxvideo.net,📺 Netflix
  - DOMAIN-KEYWORD,apiproxy-device-prod-nlb-,📺 Netflix
  - DOMAIN-KEYWORD,dualstack.apiproxy-,📺 Netflix
  - DOMAIN-KEYWORD,dualstack.ichnaea-web-,📺 Netflix
  - DOMAIN-KEYWORD,netflixdnstest,📺 Netflix
  - DOMAIN,mtalk.google.com,🌐 Google
  - DOMAIN,mobile-gtalk.l.google.com,🌐 Google
  - DOMAIN,alt1-mtalk.google.com,🌐 Google
  - DOMAIN,alt2-mtalk.google.com,🌐 Google
  - DOMAIN,alt3-mtalk.google.com,🌐 Google
  - DOMAIN,alt4-mtalk.google.com,🌐 Google
  - DOMAIN,alt5-mtalk.google.com,🌐 Google
  - DOMAIN,alt6-mtalk.google.com,🌐 Google
  - DOMAIN,alt7-mtalk.google.com,🌐 Google
  - DOMAIN,alt8-mtalk.google.com,🌐 Google
  - DOMAIN,alt9-mtalk.google.com,🌐 Google
  - DOMAIN-SUFFIX,mobile-gtalk.l.google.com,🌐 Google
  - DOMAIN-SUFFIX,265.com,🌐 Google
  - DOMAIN-SUFFIX,2mdn.net,🌐 Google
  - DOMAIN-SUFFIX,abc.xyz,🌐 Google
  - DOMAIN-SUFFIX,adservice.google.com,🌐 Google
  - DOMAIN-SUFFIX,ampproject.org,🌐 Google
  - DOMAIN-SUFFIX,android.com,🌐 Google
  - DOMAIN-SUFFIX,androidify.com,🌐 Google
  - DOMAIN-SUFFIX,app-measurement.com,🌐 Google
  - DOMAIN-SUFFIX,appspot.com,🌐 Google
  - DOMAIN-SUFFIX,autodraw.com,🌐 Google
  - DOMAIN-SUFFIX,beacons.gcp.gvt2.com,🌐 Google
  - DOMAIN-SUFFIX,beacons.gvt2.com,🌐 Google
  - DOMAIN-SUFFIX,beacons3.gvt2.com,🌐 Google
  - DOMAIN-SUFFIX,blogger.com,🌐 Google
  - DOMAIN-SUFFIX,c.admob.com,🌐 Google
  - DOMAIN-SUFFIX,c.android.clients.google.com,🌐 Google
  - DOMAIN-SUFFIX,cache.pack.google.com,🌐 Google
  - DOMAIN-SUFFIX,capitalg.com,🌐 Google
  - DOMAIN-SUFFIX,certificate-transparency.org,🌐 Google
  - DOMAIN-SUFFIX,chrome.com,🌐 Google
  - DOMAIN-SUFFIX,chromeexperiments.com,🌐 Google
  - DOMAIN-SUFFIX,chromestatus.com,🌐 Google
  - DOMAIN-SUFFIX,chromium.org,🌐 Google
  - DOMAIN-SUFFIX,clickserve.dartsearch.net,🌐 Google
  - DOMAIN-SUFFIX,corp.google.com,🌐 Google
  - DOMAIN-SUFFIX,creativelab5.com,🌐 Google
  - DOMAIN-SUFFIX,crl.pki.goog,🌐 Google
  - DOMAIN-SUFFIX,debug.com,🌐 Google
  - DOMAIN-SUFFIX,deepmind.com,🌐 Google
  - DOMAIN-SUFFIX,dialogflow.com,🌐 Google
  - DOMAIN-SUFFIX,dl.google.com,🌐 Google
  - DOMAIN-SUFFIX,dl.l.google.com,🌐 Google
  - DOMAIN-SUFFIX,docs.google.com,🌐 Google
  - DOMAIN-SUFFIX,doubleclick.net,🌐 Google
  - DOMAIN-SUFFIX,drive.google.com,🌐 Google
  - DOMAIN-SUFFIX,firebase-settings.crashlytics.com,🌐 Google
  - DOMAIN-SUFFIX,firebaseio.com,🌐 Google
  - DOMAIN-SUFFIX,getmdl.io,🌐 Google
  - DOMAIN-SUFFIX,getoutline.org,🌐 Google
  - DOMAIN-SUFFIX,ggpht.com,🌐 Google
  - DOMAIN-SUFFIX,gmail.com,🌐 Google
  - DOMAIN-SUFFIX,gmodules.com,🌐 Google
  - DOMAIN-SUFFIX,godoc.org,🌐 Google
  - DOMAIN-SUFFIX,golang.org,🌐 Google
  - DOMAIN-SUFFIX,google-analytics.com,🌐 Google
  - DOMAIN-SUFFIX,google.cn,🌐 Google
  - DOMAIN-SUFFIX,googleadservices.com,🌐 Google
  - DOMAIN-SUFFIX,googleanalytics.com,🌐 Google
  - DOMAIN-SUFFIX,googleapis.com,🌐 Google
  - DOMAIN-SUFFIX,googledrive.com,🌐 Google
  - DOMAIN-SUFFIX,googlesyndication.com,🌐 Google
  - DOMAIN-SUFFIX,googletagmanager.com,🌐 Google
  - DOMAIN-SUFFIX,googletagservices.com,🌐 Google
  - DOMAIN-SUFFIX,googleusercontent.com,🌐 Google
  - DOMAIN-SUFFIX,gstatic.com,🌐 Google
  - DOMAIN-SUFFIX,gtm.oasisfeng.com,🌐 Google
  - DOMAIN-SUFFIX,gv.com,🌐 Google
  - DOMAIN-SUFFIX,gvt0.com,🌐 Google
  - DOMAIN-SUFFIX,gvt1.com,🌐 Google
  - DOMAIN-SUFFIX,gvt3.com,🌐 Google
  - DOMAIN-SUFFIX,gwtproject.org,🌐 Google
  - DOMAIN-SUFFIX,itasoftware.com,🌐 Google
  - DOMAIN-SUFFIX,madewithcode.com,🌐 Google
  - DOMAIN-SUFFIX,material.io,🌐 Google
  - DOMAIN-SUFFIX,mtalk.google.com,🌐 Google
  - DOMAIN-SUFFIX,ocsp.pki.goog,🌐 Google
  - DOMAIN-SUFFIX,pagead-googlehosted.l.google.com,🌐 Google
  - DOMAIN-SUFFIX,pki-goog.l.google.com,🌐 Google
  - DOMAIN-SUFFIX,polymer-project.org,🌐 Google
  - DOMAIN-SUFFIX,recaptcha.net,🌐 Google
  - DOMAIN-SUFFIX,safebrowsing-cache.google.com,🌐 Google
  - DOMAIN-SUFFIX,settings.crashlytics.com,🌐 Google
  - DOMAIN-SUFFIX,shattered.io,🌐 Google
  - DOMAIN-SUFFIX,ssl-google-analytics.l.google.com,🌐 Google
  - DOMAIN-SUFFIX,synergyse.com,🌐 Google
  - DOMAIN-SUFFIX,telephony.goog,🌐 Google
  - DOMAIN-SUFFIX,tensorflow.org,🌐 Google
  - DOMAIN-SUFFIX,tfhub.dev,🌐 Google
  - DOMAIN-SUFFIX,tiltbrush.com,🌐 Google
  - DOMAIN-SUFFIX,toolbarqueries.google.com,🌐 Google
  - DOMAIN-SUFFIX,tools.google.com,🌐 Google
  - DOMAIN-SUFFIX,tools.l.google.com,🌐 Google
  - DOMAIN-SUFFIX,waveprotocol.org,🌐 Google
  - DOMAIN-SUFFIX,waymo.com,🌐 Google
  - DOMAIN-SUFFIX,webmproject.org,🌐 Google
  - DOMAIN-SUFFIX,webrtc.org,🌐 Google
  - DOMAIN-SUFFIX,whatbrowser.org,🌐 Google
  - DOMAIN-SUFFIX,widevine.com,🌐 Google
  - DOMAIN-SUFFIX,www-googletagmanager.l.google.com,🌐 Google
  - DOMAIN-SUFFIX,x.company,🌐 Google
  - DOMAIN-SUFFIX,xn--ngstr-lra8j.com,🌐 Google
  - DOMAIN-SUFFIX,youtu.be,🌐 Google
  - DOMAIN-SUFFIX,yt.be,🌐 Google
  - DOMAIN-SUFFIX,ytimg.com,🌐 Google
  - DOMAIN-KEYWORD,blogspot,🌐 Google
  - DOMAIN-KEYWORD,gmail,🌐 Google
  - DOMAIN-KEYWORD,google,🌐 Google
  - DOMAIN-KEYWORD,gstatic,🌐 Google
  - DOMAIN-KEYWORD,www.google,🌐 Google
  - IP-CIDR,173.194.0.0/16,🌐 Google
  - IP-CIDR,74.125.0.0/16,🌐 Google
  - DOMAIN-SUFFIX,openai.com,🐹 OpenAI
  - DOMAIN-SUFFIX,ai.com,🐹 OpenAI
  - DOMAIN-SUFFIX,openaiapi-site.azureedge.net,🐹 OpenAI
  - DOMAIN-SUFFIX,openaicom.imgix.net,🐹 OpenAI
  - DOMAIN-SUFFIX,openaicomproductionae4b.blob.core.windows.net,🐹 OpenAI
  - DOMAIN-SUFFIX,openaicom-api-bdcpf8c6d2e9atf6.z01.azurefd.net,🐹 OpenAI
  - DOMAIN-SUFFIX,openaicomproductionae4b.blob.core.windows.net,🐹 OpenAI
  - DOMAIN-SUFFIX,oaistatic.com,🐹 OpenAI
  - DOMAIN-SUFFIX,oaiusercontent.com,🐹 OpenAI
  - DOMAIN-SUFFIX,1drv.com,🖥 Microsoft
  - DOMAIN-SUFFIX,aadrm.com,🖥 Microsoft
  - DOMAIN-SUFFIX,acompli.com,🖥 Microsoft
  - DOMAIN-SUFFIX,acompli.net,🖥 Microsoft
  - DOMAIN-SUFFIX,aka.ms,🖥 Microsoft
  - DOMAIN-SUFFIX,akadns.net,🖥 Microsoft
  - DOMAIN-SUFFIX,aspnetcdn.com,🖥 Microsoft
  - DOMAIN-SUFFIX,assets-yammer.com,🖥 Microsoft
  - DOMAIN-SUFFIX,azure.cn,🖥 Microsoft
  - DOMAIN-SUFFIX,azure.com,🖥 Microsoft
  - DOMAIN-SUFFIX,azure.net,🖥 Microsoft
  - DOMAIN-SUFFIX,azureedge.net,🖥 Microsoft
  - DOMAIN-SUFFIX,azurerms.com,🖥 Microsoft
  - DOMAIN-SUFFIX,bing.com,🖥 Microsoft
  - DOMAIN-SUFFIX,bing.com.cn,🖥 Microsoft
  - DOMAIN-SUFFIX,bingads.com,🖥 Microsoft
  - DOMAIN-SUFFIX,bingagencyawards.com,🖥 Microsoft
  - DOMAIN-SUFFIX,bingapistatistics.com,🖥 Microsoft
  - DOMAIN-SUFFIX,bingsandbox.com,🖥 Microsoft
  - DOMAIN-SUFFIX,bingvisualsearch.com,🖥 Microsoft
  - DOMAIN-SUFFIX,bingworld.com,🖥 Microsoft
  - DOMAIN-SUFFIX,bluehatnights.com,🖥 Microsoft
  - DOMAIN-SUFFIX,dictate.ms,🖥 Microsoft
  - DOMAIN-SUFFIX,flipwithsurface.com,🖥 Microsoft
  - DOMAIN-SUFFIX,masalladeloslimites.com,🖥 Microsoft
  - DOMAIN-SUFFIX,microsoft-give.com,🖥 Microsoft
  - DOMAIN-SUFFIX,microsoftcloudsummit.com,🖥 Microsoft
  - DOMAIN-SUFFIX,microsoftdiplomados.com,🖥 Microsoft
  - DOMAIN-SUFFIX,microsoftlatamholiday.com,🖥 Microsoft
  - DOMAIN-SUFFIX,microsoftmxfilantropia.com,🖥 Microsoft
  - DOMAIN-SUFFIX,microsoftpartnersolutions.com,🖥 Microsoft
  - DOMAIN-SUFFIX,msunlimitedcloudsummit.com,🖥 Microsoft
  - DOMAIN-SUFFIX,office365love.com,🖥 Microsoft
  - DOMAIN-SUFFIX,office365tw.com,🖥 Microsoft
  - DOMAIN-SUFFIX,renovacionoffice.com,🖥 Microsoft
  - DOMAIN-SUFFIX,sprinklesapp.com,🖥 Microsoft
  - DOMAIN-SUFFIX,cn.bing.com,🖥 Microsoft
  - DOMAIN-SUFFIX,cn.bing.net,🖥 Microsoft
  - DOMAIN-SUFFIX,ditu.live.com,🖥 Microsoft
  - DOMAIN-SUFFIX,full:bj1.api.bing.com,🖥 Microsoft
  - DOMAIN-SUFFIX,full:emoi-cncdn.bing.com,🖥 Microsoft
  - DOMAIN-SUFFIX,bing.net,🖥 Microsoft
  - DOMAIN-SUFFIX,cloudapp.net,🖥 Microsoft
  - DOMAIN-SUFFIX,cloudappsecurity.com,🖥 Microsoft
  - DOMAIN-SUFFIX,docs.com,🖥 Microsoft
  - DOMAIN-SUFFIX,edgesuite.net,🖥 Microsoft
  - DOMAIN-SUFFIX,fabric.io,🖥 Microsoft
  - DOMAIN-SUFFIX,gfx.ms,🖥 Microsoft
  - DOMAIN-SUFFIX,hotmail.com,🖥 Microsoft
  - DOMAIN-SUFFIX,live.com,🖥 Microsoft
  - DOMAIN-SUFFIX,live.net,🖥 Microsoft
  - DOMAIN-SUFFIX,livefilestore.com,🖥 Microsoft
  - DOMAIN-SUFFIX,lync.com,🖥 Microsoft
  - DOMAIN-SUFFIX,mesh.com,🖥 Microsoft
  - DOMAIN-SUFFIX,microsoft-tst.com,🖥 Microsoft
  - DOMAIN-SUFFIX,microsoft.com,🖥 Microsoft
  - DOMAIN-SUFFIX,microsoftonline.com,🖥 Microsoft
  - DOMAIN-SUFFIX,msappproxy.net,🖥 Microsoft
  - DOMAIN-SUFFIX,msauth.net,🖥 Microsoft
  - DOMAIN-SUFFIX,msauthimages.net,🖥 Microsoft
  - DOMAIN-SUFFIX,msecnd.net,🖥 Microsoft
  - DOMAIN-SUFFIX,msedge.net,🖥 Microsoft
  - DOMAIN-SUFFIX,msft.net,🖥 Microsoft
  - DOMAIN-SUFFIX,msftauth.net,🖥 Microsoft
  - DOMAIN-SUFFIX,msftauthimages.net,🖥 Microsoft
  - DOMAIN-SUFFIX,msftconnecttest.com,🖥 Microsoft
  - DOMAIN-SUFFIX,msftidentity.com,🖥 Microsoft
  - DOMAIN-SUFFIX,msidentity.com,🖥 Microsoft
  - DOMAIN-SUFFIX,msn.com,🖥 Microsoft
  - DOMAIN-SUFFIX,msocdn.com,🖥 Microsoft
  - DOMAIN-SUFFIX,msocsp.com,🖥 Microsoft
  - DOMAIN-SUFFIX,mstea.ms,🖥 Microsoft
  - DOMAIN-SUFFIX,o365weve.com,🖥 Microsoft
  - DOMAIN-SUFFIX,oaspapps.com,🖥 Microsoft
  - DOMAIN-SUFFIX,office.com,🖥 Microsoft
  - DOMAIN-SUFFIX,office.net,🖥 Microsoft
  - DOMAIN-SUFFIX,office365.com,🖥 Microsoft
  - DOMAIN-SUFFIX,officeppe.net,🖥 Microsoft
  - DOMAIN-SUFFIX,omniroot.com,🖥 Microsoft
  - DOMAIN-SUFFIX,onedrive.com,🖥 Microsoft
  - DOMAIN-SUFFIX,onenote.com,🖥 Microsoft
  - DOMAIN-SUFFIX,onenote.net,🖥 Microsoft
  - DOMAIN-SUFFIX,onestore.ms,🖥 Microsoft
  - DOMAIN-SUFFIX,onmicrosoft.com,🖥 Microsoft
  - DOMAIN-SUFFIX,outlook.com,🖥 Microsoft
  - DOMAIN-SUFFIX,outlookgroups.ms,🖥 Microsoft
  - DOMAIN-SUFFIX,outlookmobile.com,🖥 Microsoft
  - DOMAIN-SUFFIX,phonefactor.net,🖥 Microsoft
  - DOMAIN-SUFFIX,public-trust.com,🖥 Microsoft
  - DOMAIN-SUFFIX,s-microsoft.com,🖥 Microsoft
  - DOMAIN-SUFFIX,sfbassets.com,🖥 Microsoft
  - DOMAIN-SUFFIX,sfx.ms,🖥 Microsoft
  - DOMAIN-SUFFIX,sharepoint.com,🖥 Microsoft
  - DOMAIN-SUFFIX,sharepointonline.com,🖥 Microsoft
  - DOMAIN-SUFFIX,skype.com,🖥 Microsoft
  - DOMAIN-SUFFIX,skypeassets.com,🖥 Microsoft
  - DOMAIN-SUFFIX,skypeforbusiness.com,🖥 Microsoft
  - DOMAIN-SUFFIX,spoprod-a.akamaihd.net,🖥 Microsoft
  - DOMAIN-SUFFIX,staffhub.ms,🖥 Microsoft
  - DOMAIN-SUFFIX,svc.ms,🖥 Microsoft
  - DOMAIN-SUFFIX,sway-cdn.com,🖥 Microsoft
  - DOMAIN-SUFFIX,sway-extensions.com,🖥 Microsoft
  - DOMAIN-SUFFIX,sway.com,🖥 Microsoft
  - DOMAIN-SUFFIX,trafficmanager.net,🖥 Microsoft
  - DOMAIN-SUFFIX,uservoice.com,🖥 Microsoft
  - DOMAIN-SUFFIX,virtualearth.net,🖥 Microsoft
  - DOMAIN-SUFFIX,visualstudio.com,🖥 Microsoft
  - DOMAIN-SUFFIX,windows-ppe.net,🖥 Microsoft
  - DOMAIN-SUFFIX,windows.com,🖥 Microsoft
  - DOMAIN-SUFFIX,windows.net,🖥 Microsoft
  - DOMAIN-SUFFIX,windowsazure.com,🖥 Microsoft
  - DOMAIN-SUFFIX,windowsupdate.com,🖥 Microsoft
  - DOMAIN-SUFFIX,wunderlist.com,🖥 Microsoft
  - DOMAIN-SUFFIX,xbox.cn,🖥 Microsoft
  - DOMAIN-SUFFIX,xbox.com,🖥 Microsoft
  - DOMAIN-SUFFIX,xboxlive.cn,🖥 Microsoft
  - DOMAIN-SUFFIX,xboxlive.com,🖥 Microsoft
  - DOMAIN-SUFFIX,yammer.com,🖥 Microsoft
  - DOMAIN-SUFFIX,yammerusercontent.com,🖥 Microsoft
  - DOMAIN-KEYWORD,1drv,🖥 Microsoft
  - DOMAIN-KEYWORD,microsoft,🖥 Microsoft
  - DOMAIN-KEYWORD,onedrive,🖥 Microsoft
  - DOMAIN-KEYWORD,skydrive,🖥 Microsoft
  - DOMAIN-SUFFIX,acm.org,🖥 Learning
  - DOMAIN-SUFFIX,acs.org,🖥 Learning
  - DOMAIN-SUFFIX,aip.org,🖥 Learning
  - DOMAIN-SUFFIX,ams.org,🖥 Learning
  - DOMAIN-SUFFIX,annualreviews.org,🖥 Learning
  - DOMAIN-SUFFIX,aps.org,🖥 Learning
  - DOMAIN-SUFFIX,ascelibrary.org,🖥 Learning
  - DOMAIN-SUFFIX,asm.org,🖥 Learning
  - DOMAIN-SUFFIX,asme.org,🖥 Learning
  - DOMAIN-SUFFIX,astm.org,🖥 Learning
  - DOMAIN-SUFFIX,blackwell-synergy.com,🖥 Learning
  - DOMAIN-SUFFIX,bmj.com,🖥 Learning
  - DOMAIN-SUFFIX,cabdirect.org,🖥 Learning
  - DOMAIN-SUFFIX,cambridge.org,🖥 Learning
  - DOMAIN-SUFFIX,cas.org,🖥 Learning
  - DOMAIN-SUFFIX,cell.com,🖥 Learning
  - DOMAIN-SUFFIX,clarivate.com,🖥 Learning
  - DOMAIN-SUFFIX,cnki.net,🖥 Learning
  - DOMAIN-SUFFIX,cqvip.com,🖥 Learning
  - DOMAIN-SUFFIX,csiro.au,🖥 Learning
  - DOMAIN-SUFFIX,deepdyve.com,🖥 Learning
  - DOMAIN-SUFFIX,ebscohost.com,🖥 Learning
  - DOMAIN-SUFFIX,els-cdn.com,🖥 Learning
  - DOMAIN-SUFFIX,elsevier.com,🖥 Learning
  - DOMAIN-SUFFIX,emerald.com,🖥 Learning
  - DOMAIN-SUFFIX,endnote.com,🖥 Learning
  - DOMAIN-SUFFIX,engineeringvillage.com,🖥 Learning
  - DOMAIN-SUFFIX,icevirtuallibrary.com,🖥 Learning
  - DOMAIN-SUFFIX,ieee.org,🖥 Learning
  - DOMAIN-SUFFIX,imf.org,🖥 Learning
  - DOMAIN-SUFFIX,iop.org,🖥 Learning
  - DOMAIN-SUFFIX,jamanetwork.com,🖥 Learning
  - DOMAIN-SUFFIX,jbc.org,🖥 Learning
  - DOMAIN-SUFFIX,jhu.edu,🖥 Learning
  - DOMAIN-SUFFIX,jstor.org,🖥 Learning
  - DOMAIN-SUFFIX,karger.com,🖥 Learning
  - DOMAIN-SUFFIX,libguides.com,🖥 Learning
  - DOMAIN-SUFFIX,madsrevolution.net,🖥 Learning
  - DOMAIN-SUFFIX,mdpi.com,🖥 Learning
  - DOMAIN-SUFFIX,mpg.de,🖥 Learning
  - DOMAIN-SUFFIX,myilibrary.com,🖥 Learning
  - DOMAIN-SUFFIX,nature.com,🖥 Learning
  - DOMAIN-SUFFIX,ncbi.nlm.nih.gov,🖥 Learning
  - DOMAIN-SUFFIX,oecd-ilibrary.org,🖥 Learning
  - DOMAIN-SUFFIX,osapublishing.org,🖥 Learning
  - DOMAIN-SUFFIX,oup.com,🖥 Learning
  - DOMAIN-SUFFIX,ovid.com,🖥 Learning
  - DOMAIN-SUFFIX,oxfordartonline.com,🖥 Learning
  - DOMAIN-SUFFIX,oxfordbibliographies.com,🖥 Learning
  - DOMAIN-SUFFIX,oxfordmusiconline.com,🖥 Learning
  - DOMAIN-SUFFIX,pkulaw.com,🖥 Learning
  - DOMAIN-SUFFIX,pnas.org,🖥 Learning
  - DOMAIN-SUFFIX,proquest.com,🖥 Learning
  - DOMAIN-SUFFIX,readcube.com,🖥 Learning
  - DOMAIN-SUFFIX,researchgate.net,🖥 Learning
  - DOMAIN-SUFFIX,rsc.org,🖥 Learning
  - DOMAIN-SUFFIX,sagepub.com,🖥 Learning
  - DOMAIN-SUFFIX,sci-hub.tw,🖥 Learning
  - DOMAIN-SUFFIX,sciencedirect.com,🖥 Learning
  - DOMAIN-SUFFIX,sciencemag.org,🖥 Learning
  - DOMAIN-SUFFIX,scitation.org,🖥 Learning
  - DOMAIN-SUFFIX,scopus.com,🖥 Learning
  - DOMAIN-SUFFIX,siam.org,🖥 Learning
  - DOMAIN-SUFFIX,spiedigitallibrary.org,🖥 Learning
  - DOMAIN-SUFFIX,springer.com,🖥 Learning
  - DOMAIN-SUFFIX,springerlink.com,🖥 Learning
  - DOMAIN-SUFFIX,tandfonline.com,🖥 Learning
  - DOMAIN-SUFFIX,un.org,🖥 Learning
  - DOMAIN-SUFFIX,uni-bielefeld.de,🖥 Learning
  - DOMAIN-SUFFIX,wanfangdata.com,🖥 Learning
  - DOMAIN-SUFFIX,webofknowledge.com,🖥 Learning
  - DOMAIN-SUFFIX,westlaw.com,🖥 Learning
  - DOMAIN-SUFFIX,westlawchina.com,🖥 Learning
  - DOMAIN-SUFFIX,wiley.com,🖥 Learning
  - DOMAIN-SUFFIX,worldbank.org,🖥 Learning
  - DOMAIN-SUFFIX,worldscientific.com,🖥 Learning
  - DOMAIN-SUFFIX,pscp.tv,📟 Twitter
  - DOMAIN-SUFFIX,periscope.tv,📟 Twitter
  - DOMAIN-SUFFIX,t.co,📟 Twitter
  - DOMAIN-SUFFIX,twimg.co,📟 Twitter
  - DOMAIN-SUFFIX,twimg.com,📟 Twitter
  - DOMAIN-SUFFIX,twitpic.com,📟 Twitter
  - DOMAIN-SUFFIX,twitter.com,📟 Twitter
  - DOMAIN-SUFFIX,twitter.jp,📟 Twitter
  - DOMAIN-SUFFIX,vine.co,📟 Twitter
  - DOMAIN-SUFFIX,c4assets.com,📺 International-Media
  - DOMAIN-SUFFIX,channel4.com,📺 International-Media
  - DOMAIN-SUFFIX,abema.io,📺 International-Media
  - DOMAIN-SUFFIX,ameba.jp,📺 International-Media
  - DOMAIN-SUFFIX,hayabusa.io,📺 International-Media
  - DOMAIN,abematv.akamaized.net,📺 International-Media
  - DOMAIN,ds-linear-abematv.akamaized.net,📺 International-Media
  - DOMAIN,ds-vod-abematv.akamaized.net,📺 International-Media
  - DOMAIN,linear-abematv.akamaized.net,📺 International-Media
  - DOMAIN-SUFFIX,primevideo.com,📺 International-Media
  - DOMAIN-SUFFIX,bahamut.com.tw,📺 International-Media
  - DOMAIN-SUFFIX,gamer.com.tw,📺 International-Media
  - DOMAIN,gamer-cds.cdn.hinet.net,📺 International-Media
  - DOMAIN,gamer2-cds.cdn.hinet.net,📺 International-Media
  - DOMAIN-SUFFIX,bbc.co.uk,📺 International-Media
  - DOMAIN-SUFFIX,bbci.co.uk,📺 International-Media
  - DOMAIN-KEYWORD,bbcfmt,📺 International-Media
  - DOMAIN-KEYWORD,uk-live,📺 International-Media
  - DOMAIN-SUFFIX,dazn.com,📺 International-Media
  - DOMAIN-SUFFIX,encoretvb.com,📺 International-Media
  - DOMAIN,content.jwplatform.com,📺 International-Media
  - DOMAIN,videos-f.jwpsrv.com,📺 International-Media
  - DOMAIN-SUFFIX,dashasiafox.akamaized.net,📺 International-Media
  - DOMAIN-SUFFIX,fox.com,📺 International-Media
  - DOMAIN-SUFFIX,foxdcg.com,📺 International-Media
  - DOMAIN-SUFFIX,foxplus.com,📺 International-Media
  - DOMAIN-SUFFIX,staticasiafox.akamaized.net,📺 International-Media
  - DOMAIN-SUFFIX,theplatform.com,📺 International-Media
  - DOMAIN-SUFFIX,uplynk.com,📺 International-Media
  - DOMAIN-SUFFIX,hbo.com,📺 International-Media
  - DOMAIN-SUFFIX,hbogo.com,📺 International-Media
  - DOMAIN-SUFFIX,hboasia.com,📺 International-Media
  - DOMAIN-SUFFIX,hbogo.com,📺 International-Media
  - DOMAIN-SUFFIX,hbogoasia.hk,📺 International-Media
  - DOMAIN,44wilhpljf.execute-api.ap-southeast-1.amazonaws.com,📺 International-Media
  - DOMAIN,bcbolthboa-a.akamaihd.net,📺 International-Media
  - DOMAIN,cf-images.ap-southeast-1.prod.boltdns.net,📺 International-Media
  - DOMAIN,manifest.prod.boltdns.net,📺 International-Media
  - DOMAIN,s3-ap-southeast-1.amazonaws.com,📺 International-Media
  - DOMAIN-SUFFIX,hulu.com,📺 International-Media
  - DOMAIN-SUFFIX,huluim.com,📺 International-Media
  - DOMAIN-SUFFIX,hulustream.com,📺 International-Media
  - DOMAIN-SUFFIX,kktv.com.tw,📺 International-Media
  - DOMAIN-SUFFIX,kktv.me,📺 International-Media
  - DOMAIN,kktv-theater.kk.stream,📺 International-Media
  - DOMAIN-SUFFIX,linetv.tw,📺 International-Media
  - DOMAIN,d3c7rimkq79yfu.cloudfront.net,📺 International-Media
  - DOMAIN-SUFFIX,happyon.jp,📺 International-Media
  - DOMAIN-SUFFIX,hulu.jp,📺 International-Media
  - DOMAIN-SUFFIX,litv.tv,📺 International-Media
  - DOMAIN,litvfreemobile-hichannel.cdn.hinet.net,📺 International-Media
  - DOMAIN-SUFFIX,mytvsuper.com,📺 International-Media
  - DOMAIN-SUFFIX,tvb.com,📺 International-Media
  - DOMAIN-SUFFIX,netflix.com,📺 International-Media
  - DOMAIN-SUFFIX,netflix.net,📺 International-Media
  - DOMAIN-SUFFIX,nflxext.com,📺 International-Media
  - DOMAIN-SUFFIX,nflximg.com,📺 International-Media
  - DOMAIN-SUFFIX,nflximg.net,📺 International-Media
  - DOMAIN-SUFFIX,nflxso.net,📺 International-Media
  - DOMAIN-SUFFIX,nflxvideo.net,📺 International-Media
  - IP-CIDR,23.246.0.0/18,📺 International-Media
  - IP-CIDR,37.77.184.0/21,📺 International-Media
  - IP-CIDR,45.57.0.0/17,📺 International-Media
  - IP-CIDR,64.120.128.0/17,📺 International-Media
  - IP-CIDR,66.197.128.0/17,📺 International-Media
  - IP-CIDR,108.175.32.0/20,📺 International-Media
  - IP-CIDR,192.173.64.0/18,📺 International-Media
  - IP-CIDR,198.38.96.0/19,📺 International-Media
  - IP-CIDR,198.45.48.0/20,📺 International-Media
  - DOMAIN-SUFFIX,pbs.org,📺 International-Media
  - DOMAIN-SUFFIX,phncdn.com,📺 International-Media
  - DOMAIN-SUFFIX,pornhub.com,📺 International-Media
  - DOMAIN-SUFFIX,pornhubpremium.com,📺 International-Media
  - DOMAIN-SUFFIX,twitch.tv,📺 International-Media
  - DOMAIN-SUFFIX,twitchcdn.net,📺 International-Media
  - DOMAIN-SUFFIX,ttvnw.net,📺 International-Media
  - DOMAIN-SUFFIX,viu.com,📺 International-Media
  - DOMAIN-SUFFIX,viu.tv,📺 International-Media
  - DOMAIN,api.viu.now.com,📺 International-Media
  - DOMAIN,d1k2us671qcoau.cloudfront.net,📺 International-Media
  - DOMAIN,d2anahhhmp1ffz.cloudfront.net,📺 International-Media
  - DOMAIN,dfp6rglgjqszk.cloudfront.net,📺 International-Media
  - DOMAIN-SUFFIX,googlevideo.com,📺 International-Media
  - DOMAIN-SUFFIX,youtube.com,📺 International-Media
  - DOMAIN,youtubei.googleapis.com,📺 International-Media
  - DOMAIN-SUFFIX,deezer.com,📺 International-Media
  - DOMAIN-SUFFIX,dzcdn.net,📺 International-Media
  - DOMAIN-SUFFIX,kkbox.com,📺 International-Media
  - DOMAIN-SUFFIX,kkbox.com.tw,📺 International-Media
  - DOMAIN-SUFFIX,kfs.io,📺 International-Media
  - DOMAIN-SUFFIX,joox.com,📺 International-Media
  - DOMAIN-SUFFIX,pandora.com,📺 International-Media
  - DOMAIN-SUFFIX,pscdn.co,📺 International-Media
  - DOMAIN-SUFFIX,scdn.co,📺 International-Media
  - DOMAIN-SUFFIX,spotify.com,📺 International-Media
  - DOMAIN-SUFFIX,spoti.fi,📺 International-Media
  - IP-CIDR,35.186.224.47/32,📺 International-Media
  - DOMAIN-SUFFIX,tidal.com,📺 International-Media
  - DOMAIN-SUFFIX,iqiyi.com,China-Media
  - DOMAIN-SUFFIX,71.am,China-Media
  - DOMAIN-SUFFIX,bilibili.com,China-Media
  - DOMAIN,upos-hz-mirrorakam.akamaized.net,China-Media
  - DOMAIN-SUFFIX,17gouwuba.com,Hijacking
  - DOMAIN-SUFFIX,186078.com,Hijacking
  - DOMAIN-SUFFIX,189zj.cn,Hijacking
  - DOMAIN-SUFFIX,285680.com,Hijacking
  - DOMAIN-SUFFIX,3721zh.com,Hijacking
  - DOMAIN-SUFFIX,4336wang.cn,Hijacking
  - DOMAIN-SUFFIX,51chumoping.com,Hijacking
  - DOMAIN-SUFFIX,51mld.cn,Hijacking
  - DOMAIN-SUFFIX,58mingri.cn,Hijacking
  - DOMAIN-SUFFIX,58mingtian.cn,Hijacking
  - DOMAIN-SUFFIX,6d63d3.com,Hijacking
  - DOMAIN-SUFFIX,7gg.cc,Hijacking
  - DOMAIN-SUFFIX,91veg.com,Hijacking
  - DOMAIN-SUFFIX,9s6q.cn,Hijacking
  - DOMAIN-SUFFIX,adsame.com,Hijacking
  - DOMAIN-SUFFIX,aiclk.com,Hijacking
  - DOMAIN-SUFFIX,akuai.top,Hijacking
  - DOMAIN-SUFFIX,atplay.cn,Hijacking
  - DOMAIN-SUFFIX,baiwanchuangyi.com,Hijacking
  - DOMAIN-SUFFIX,bayimob.com,Hijacking
  - DOMAIN-SUFFIX,beerto.cn,Hijacking
  - DOMAIN-SUFFIX,beilamusi.com,Hijacking
  - DOMAIN-SUFFIX,benshiw.net,Hijacking
  - DOMAIN-SUFFIX,bianxianmao.com,Hijacking
  - DOMAIN-SUFFIX,bryonypie.com,Hijacking
  - DOMAIN-SUFFIX,cishantao.com,Hijacking
  - DOMAIN-SUFFIX,cszlks.com,Hijacking
  - DOMAIN-SUFFIX,cudaojia.com,Hijacking
  - DOMAIN-SUFFIX,dafapromo.com,Hijacking
  - DOMAIN-SUFFIX,daitdai.com,Hijacking
  - DOMAIN-SUFFIX,dsaeerf.com,Hijacking
  - DOMAIN-SUFFIX,dugesheying.com,Hijacking
  - DOMAIN-SUFFIX,dv8c1t.cn,Hijacking
  - DOMAIN-SUFFIX,erdoscs.com,Hijacking
  - DOMAIN-SUFFIX,fan-yong.com,Hijacking
  - DOMAIN-SUFFIX,feih.com.cn,Hijacking
  - DOMAIN-SUFFIX,fjlqqc.com,Hijacking
  - DOMAIN-SUFFIX,fkku194.com,Hijacking
  - DOMAIN-SUFFIX,freedrive.cn,Hijacking
  - DOMAIN-SUFFIX,gclick.cn,Hijacking
  - DOMAIN-SUFFIX,goufanli100.com,Hijacking
  - DOMAIN-SUFFIX,gouwubang.com,Hijacking
  - DOMAIN-SUFFIX,haoshengtoys.com,Hijacking
  - DOMAIN-SUFFIX,ichaosheng.com,Hijacking
  - DOMAIN-SUFFIX,ishop789.com,Hijacking
  - DOMAIN-SUFFIX,jdkic.com,Hijacking
  - DOMAIN-SUFFIX,jiubuhua.com,Hijacking
  - DOMAIN-SUFFIX,jwg365.cn,Hijacking
  - DOMAIN-SUFFIX,kawo77.com,Hijacking
  - DOMAIN-SUFFIX,kualianyingxiao.cn,Hijacking
  - DOMAIN-SUFFIX,kumihua.com,Hijacking
  - DOMAIN-SUFFIX,ltheanine.cn,Hijacking
  - DOMAIN-SUFFIX,maipinshangmao.com,Hijacking
  - DOMAIN-SUFFIX,minisplat.cn,Hijacking
  - DOMAIN-SUFFIX,mkitgfs.com,Hijacking
  - DOMAIN-SUFFIX,mlnbike.com,Hijacking
  - DOMAIN-SUFFIX,mobjump.com,Hijacking
  - DOMAIN-SUFFIX,nbkbgd.cn,Hijacking
  - DOMAIN-SUFFIX,newapi.com,Hijacking
  - DOMAIN-SUFFIX,pinzhitmall.com,Hijacking
  - DOMAIN-SUFFIX,poppyta.com,Hijacking
  - DOMAIN-SUFFIX,qichexin.com,Hijacking
  - DOMAIN-SUFFIX,qinchugudao.com,Hijacking
  - DOMAIN-SUFFIX,quanliyouxi.cn,Hijacking
  - DOMAIN-SUFFIX,qutaobi.com,Hijacking
  - DOMAIN-SUFFIX,ry51w.cn,Hijacking
  - DOMAIN-SUFFIX,sg536.cn,Hijacking
  - DOMAIN-SUFFIX,sifubo.cn,Hijacking
  - DOMAIN-SUFFIX,sifuce.cn,Hijacking
  - DOMAIN-SUFFIX,sifuda.cn,Hijacking
  - DOMAIN-SUFFIX,sifufu.cn,Hijacking
  - DOMAIN-SUFFIX,sifuge.cn,Hijacking
  - DOMAIN-SUFFIX,sifugu.cn,Hijacking
  - DOMAIN-SUFFIX,sifuhe.cn,Hijacking
  - DOMAIN-SUFFIX,sifuhu.cn,Hijacking
  - DOMAIN-SUFFIX,sifuji.cn,Hijacking
  - DOMAIN-SUFFIX,sifuka.cn,Hijacking
  - DOMAIN-SUFFIX,smgru.net,Hijacking
  - DOMAIN-SUFFIX,taoggou.com,Hijacking
  - DOMAIN-SUFFIX,tcxshop.com,Hijacking
  - DOMAIN-SUFFIX,tjqonline.cn,Hijacking
  - DOMAIN-SUFFIX,topitme.com,Hijacking
  - DOMAIN-SUFFIX,tuia.cn,Hijacking
  - DOMAIN-SUFFIX,tuipenguin.com,Hijacking
  - DOMAIN-SUFFIX,tuitiger.com,Hijacking
  - DOMAIN-SUFFIX,wx16999.com,Hijacking
  - DOMAIN-SUFFIX,xiaohuau.xyz,Hijacking
  - DOMAIN-SUFFIX,yinmong.com,Hijacking
  - DOMAIN-SUFFIX,yiqifa.com,Hijacking
  - DOMAIN-SUFFIX,yitaopt.com,Hijacking
  - DOMAIN-SUFFIX,yjqiqi.com,Hijacking
  - DOMAIN-SUFFIX,yukhj.com,Hijacking
  - DOMAIN-SUFFIX,zhaozecheng.cn,Hijacking
  - DOMAIN-SUFFIX,zhenxinet.com,Hijacking
  - DOMAIN-SUFFIX,zunmi.cn,Hijacking
  - DOMAIN-SUFFIX,zzd6.com,Hijacking
  - IP-CIDR,39.107.15.115/32,Hijacking
  - IP-CIDR,47.89.59.182/32,Hijacking
  - IP-CIDR,103.49.209.27/32,Hijacking
  - IP-CIDR,123.56.152.96/32,Hijacking
  - IP-CIDR,61.160.200.223/32,Hijacking
  - IP-CIDR,61.160.200.242/32,Hijacking
  - IP-CIDR,61.160.200.252/32,Hijacking
  - IP-CIDR,61.174.50.214/32,Hijacking
  - IP-CIDR,111.175.220.163/32,Hijacking
  - IP-CIDR,111.175.220.164/32,Hijacking
  - IP-CIDR,124.232.160.178/32,Hijacking
  - IP-CIDR,175.6.223.15/32,Hijacking
  - IP-CIDR,183.59.53.237/32,Hijacking
  - IP-CIDR,218.93.127.37/32,Hijacking
  - IP-CIDR,221.228.17.152/32,Hijacking
  - IP-CIDR,221.231.6.79/32,Hijacking
  - IP-CIDR,222.186.61.91/32,Hijacking
  - IP-CIDR,222.186.61.95/32,Hijacking
  - IP-CIDR,222.186.61.96/32,Hijacking
  - IP-CIDR,222.186.61.97/32,Hijacking
  - IP-CIDR,106.75.231.48/32,Hijacking
  - IP-CIDR,119.4.249.166/32,Hijacking
  - IP-CIDR,220.196.52.141/32,Hijacking
  - IP-CIDR,221.6.4.148/32,Hijacking
  - IP-CIDR,114.247.28.96/32,Hijacking
  - IP-CIDR,221.179.131.72/32,Hijacking
  - IP-CIDR,221.179.140.145/32,Hijacking
  - IP-CIDR,10.72.25.0/24,Hijacking
  - IP-CIDR,115.182.16.79/32,Hijacking
  - IP-CIDR,118.144.88.126/32,Hijacking
  - IP-CIDR,118.144.88.215/32,Hijacking
  - IP-CIDR,118.144.88.216/32,Hijacking
  - IP-CIDR,120.76.189.132/32,Hijacking
  - IP-CIDR,124.14.21.147/32,Hijacking
  - IP-CIDR,124.14.21.151/32,Hijacking
  - IP-CIDR,180.166.52.24/32,Hijacking
  - IP-CIDR,211.161.101.106/32,Hijacking
  - IP-CIDR,220.115.251.25/32,Hijacking
  - IP-CIDR,222.73.156.235/32,Hijacking
  - DOMAIN-SUFFIX,kuaizip.com,Hijacking
  - DOMAIN-SUFFIX,mackeeper.com,Hijacking
  - DOMAIN-SUFFIX,flash.cn,Hijacking
  - DOMAIN,geo2.adobe.com,Hijacking
  - DOMAIN-SUFFIX,4009997658.com,Hijacking
  - DOMAIN-SUFFIX,abbyychina.com,Hijacking
  - DOMAIN-SUFFIX,bartender.cc,Hijacking
  - DOMAIN-SUFFIX,betterzip.net,Hijacking
  - DOMAIN-SUFFIX,beyondcompare.cc,Hijacking
  - DOMAIN-SUFFIX,bingdianhuanyuan.cn,Hijacking
  - DOMAIN-SUFFIX,chemdraw.com.cn,Hijacking
  - DOMAIN-SUFFIX,cjmakeding.com,Hijacking
  - DOMAIN-SUFFIX,cjmkt.com,Hijacking
  - DOMAIN-SUFFIX,codesoftchina.com,Hijacking
  - DOMAIN-SUFFIX,coreldrawchina.com,Hijacking
  - DOMAIN-SUFFIX,crossoverchina.com,Hijacking
  - DOMAIN-SUFFIX,easyrecoverychina.com,Hijacking
  - DOMAIN-SUFFIX,ediuschina.com,Hijacking
  - DOMAIN-SUFFIX,flstudiochina.com,Hijacking
  - DOMAIN-SUFFIX,formysql.com,Hijacking
  - DOMAIN-SUFFIX,guitarpro.cc,Hijacking
  - DOMAIN-SUFFIX,huishenghuiying.com.cn,Hijacking
  - DOMAIN-SUFFIX,hypersnap.net,Hijacking
  - DOMAIN-SUFFIX,iconworkshop.cn,Hijacking
  - DOMAIN-SUFFIX,imindmap.cc,Hijacking
  - DOMAIN-SUFFIX,jihehuaban.com.cn,Hijacking
  - DOMAIN-SUFFIX,keyshot.cc,Hijacking
  - DOMAIN-SUFFIX,kingdeecn.cn,Hijacking
  - DOMAIN-SUFFIX,logoshejishi.com,Hijacking
  - DOMAIN-SUFFIX,mairuan.cn,Hijacking
  - DOMAIN-SUFFIX,mairuan.com,Hijacking
  - DOMAIN-SUFFIX,mairuan.com.cn,Hijacking
  - DOMAIN-SUFFIX,mairuan.net,Hijacking
  - DOMAIN-SUFFIX,mairuanwang.com,Hijacking
  - DOMAIN-SUFFIX,makeding.com,Hijacking
  - DOMAIN-SUFFIX,mathtype.cn,Hijacking
  - DOMAIN-SUFFIX,mindmanager.cc,Hijacking
  - DOMAIN-SUFFIX,mindmapper.cc,Hijacking
  - DOMAIN-SUFFIX,mycleanmymac.com,Hijacking
  - DOMAIN-SUFFIX,nicelabel.cc,Hijacking
  - DOMAIN-SUFFIX,ntfsformac.cc,Hijacking
  - DOMAIN-SUFFIX,ntfsformac.cn,Hijacking
  - DOMAIN-SUFFIX,overturechina.com,Hijacking
  - DOMAIN-SUFFIX,passwordrecovery.cn,Hijacking
  - DOMAIN-SUFFIX,pdfexpert.cc,Hijacking
  - DOMAIN-SUFFIX,shankejingling.com,Hijacking
  - DOMAIN-SUFFIX,ultraiso.net,Hijacking
  - DOMAIN-SUFFIX,vegaschina.cn,Hijacking
  - DOMAIN-SUFFIX,xmindchina.net,Hijacking
  - DOMAIN-SUFFIX,xshellcn.com,Hijacking
  - DOMAIN-SUFFIX,yihuifu.cn,Hijacking
  - DOMAIN-SUFFIX,yuanchengxiezuo.com,Hijacking
  - DOMAIN-SUFFIX,zbrushcn.com,Hijacking
  - DOMAIN-SUFFIX,zhzzx.com,Hijacking
  - DOMAIN-SUFFIX,taichi-maker.com,China-Websites
  - DOMAIN-SUFFIX,leaguehd.com,China-Websites
  - DOMAIN-SUFFIX,plex.tv,China-Websites
  - DOMAIN-SUFFIX,qhres.com,China-Websites
  - DOMAIN-SUFFIX,qhres.com,China-Websites
  - DOMAIN-SUFFIX,qhimg.com,China-Websites
  - DOMAIN-SUFFIX,akadns.net,China-Websites
  - DOMAIN-SUFFIX,alibaba.com,China-Websites
  - DOMAIN-SUFFIX,alicdn.com,China-Websites
  - DOMAIN-SUFFIX,alikunlun.com,China-Websites
  - DOMAIN-SUFFIX,alipay.com,China-Websites
  - DOMAIN-SUFFIX,amap.com,China-Websites
  - DOMAIN-SUFFIX,dingtalk.com,China-Websites
  - DOMAIN-SUFFIX,taobao.com,China-Websites
  - DOMAIN-SUFFIX,tmall.com,China-Websites
  - DOMAIN-SUFFIX,tmall.hk,China-Websites
  - DOMAIN-SUFFIX,ykimg.com,China-Websites
  - DOMAIN-SUFFIX,youku.com,China-Websites
  - DOMAIN-SUFFIX,xiami.com,China-Websites
  - DOMAIN-SUFFIX,xiami.net,China-Websites
  - DOMAIN-SUFFIX,baidu.com,China-Websites
  - DOMAIN-SUFFIX,baidubcr.com,China-Websites
  - DOMAIN-SUFFIX,bdstatic.com,China-Websites
  - DOMAIN-SUFFIX,acgvideo.com,China-Websites
  - DOMAIN-SUFFIX,biliapi.com,China-Websites
  - DOMAIN-SUFFIX,biliapi.net,China-Websites
  - DOMAIN-SUFFIX,bilibili.com,China-Websites
  - DOMAIN-SUFFIX,hdslb.com,China-Websites
  - DOMAIN-SUFFIX,blizzard.com,China-Websites
  - DOMAIN-SUFFIX,battle.net,China-Websites
  - DOMAIN,blzddist1-a.akamaihd.net,China-Websites
  - DOMAIN-SUFFIX,feiliao.com,China-Websites
  - DOMAIN-SUFFIX,pstatp.com,China-Websites
  - DOMAIN-SUFFIX,snssdk.com,China-Websites
  - DOMAIN-SUFFIX,iesdouyin.com,China-Websites
  - DOMAIN-SUFFIX,toutiao.com,China-Websites
  - DOMAIN-SUFFIX,343480.com,China-Websites
  - DOMAIN-SUFFIX,baduziyuan.com,China-Websites
  - DOMAIN-SUFFIX,com-hs-hkdy.com,China-Websites
  - DOMAIN-SUFFIX,czybjz.com,China-Websites
  - DOMAIN-SUFFIX,dandanzan.com,China-Websites
  - DOMAIN-SUFFIX,fjhps.com,China-Websites
  - DOMAIN-SUFFIX,kuyunbo.club,China-Websites
  - DOMAIN-SUFFIX,21cn.com,China-Websites
  - DOMAIN-SUFFIX,hitv.com,China-Websites
  - DOMAIN-SUFFIX,mgtv.com,China-Websites
  - DOMAIN-SUFFIX,iqiyi.com,China-Websites
  - DOMAIN-SUFFIX,iqiyipic.com,China-Websites
  - DOMAIN-SUFFIX,71.am.com,China-Websites
  - DOMAIN-SUFFIX,jd.com,China-Websites
  - DOMAIN-SUFFIX,jd.hk,China-Websites
  - DOMAIN-SUFFIX,360buyimg.com,China-Websites
  - DOMAIN-SUFFIX,iciba.com,China-Websites
  - DOMAIN-SUFFIX,ksosoft.com,China-Websites
  - DOMAIN-SUFFIX,meitu.com,China-Websites
  - DOMAIN-SUFFIX,meitudata.com,China-Websites
  - DOMAIN-SUFFIX,meitustat.com,China-Websites
  - DOMAIN-SUFFIX,meipai.com,China-Websites
  - DOMAIN-SUFFIX,duokan.com,China-Websites
  - DOMAIN-SUFFIX,mi-img.com,China-Websites
  - DOMAIN-SUFFIX,miui.com,China-Websites
  - DOMAIN-SUFFIX,xiaomi.com,China-Websites
  - DOMAIN-SUFFIX,microsoft.com,China-Websites
  - DOMAIN-SUFFIX,windows.com,China-Websites
  - DOMAIN-SUFFIX,windowsupdate.com,China-Websites
  - DOMAIN-SUFFIX,visualstudio.com,China-Websites
  - DOMAIN-SUFFIX,msecnd.net,China-Websites
  - DOMAIN,officecdn-microsoft-com.akamaized.net,China-Websites
  - DOMAIN-SUFFIX,163.com,China-Websites
  - DOMAIN-SUFFIX,126.net,China-Websites
  - DOMAIN-SUFFIX,127.net,China-Websites
  - DOMAIN-SUFFIX,163yun.com,China-Websites
  - DOMAIN-SUFFIX,lofter.com,China-Websites
  - DOMAIN-SUFFIX,ydstatic.com,China-Websites
  - DOMAIN-SUFFIX,sina.com,China-Websites
  - DOMAIN-SUFFIX,weibo.com,China-Websites
  - DOMAIN-SUFFIX,sohu.com,China-Websites
  - DOMAIN-SUFFIX,sohucs.com,China-Websites
  - DOMAIN-SUFFIX,sohu-inc.com,China-Websites
  - DOMAIN-SUFFIX,v-56.com,China-Websites
  - DOMAIN-SUFFIX,sogo.com,China-Websites
  - DOMAIN-SUFFIX,sogou.com,China-Websites
  - DOMAIN-SUFFIX,sogoucdn.com,China-Websites
  - DOMAIN-SUFFIX,qq.com,China-Websites
  - DOMAIN-SUFFIX,tencent.com,China-Websites
  - DOMAIN-SUFFIX,jstucdn.com,China-Websites
  - DOMAIN-SUFFIX,zimuzu.io,China-Websites
  - DOMAIN-SUFFIX,zimuzu.tv,China-Websites
  - DOMAIN-SUFFIX,zmz2019.com,China-Websites
  - DOMAIN-SUFFIX,zmzapi.com,China-Websites
  - DOMAIN-SUFFIX,zmzapi.net,China-Websites
  - DOMAIN-SUFFIX,zmzfile.com,China-Websites
  - DOMAIN-SUFFIX,chinanetcenter.com,China-Websites
  - DOMAIN-SUFFIX,wangsu.com,China-Websites
  - DOMAIN-SUFFIX,meixincdn.com,China-Websites
  - DOMAIN-SUFFIX,ipip.net,China-Websites
  - DOMAIN-SUFFIX,ip.la,China-Websites
  - DOMAIN-SUFFIX,ip-cdn.com,China-Websites
  - DOMAIN-SUFFIX,ipv6-test.com,China-Websites
  - DOMAIN-SUFFIX,test-ipv6.com,China-Websites
  - DOMAIN-SUFFIX,whatismyip.com,China-Websites
  - DOMAIN,ip.bjango.com,China-Websites
  - DOMAIN-SUFFIX,netspeedtestmaster.com,China-Websites
  - DOMAIN,speedtest.macpaw.com,China-Websites
  - DOMAIN-SUFFIX,awesome-hd.me,China-Websites
  - DOMAIN-SUFFIX,broadcasthe.net,China-Websites
  - DOMAIN-SUFFIX,chdbits.co,China-Websites
  - DOMAIN-SUFFIX,classix-unlimited.co.uk,China-Websites
  - DOMAIN-SUFFIX,empornium.me,China-Websites
  - DOMAIN-SUFFIX,gazellegames.net,China-Websites
  - DOMAIN-SUFFIX,hdchina.org,China-Websites
  - DOMAIN-SUFFIX,hdsky.me,China-Websites
  - DOMAIN-SUFFIX,jpopsuki.eu,China-Websites
  - DOMAIN-SUFFIX,keepfrds.com,China-Websites
  - DOMAIN-SUFFIX,m-team.cc,China-Websites
  - DOMAIN-SUFFIX,nanyangpt.com,China-Websites
  - DOMAIN-SUFFIX,ncore.cc,China-Websites
  - DOMAIN-SUFFIX,open.cd,China-Websites
  - DOMAIN-SUFFIX,ourbits.club,China-Websites
  - DOMAIN-SUFFIX,passthepopcorn.me,China-Websites
  - DOMAIN-SUFFIX,privatehd.to,China-Websites
  - DOMAIN-SUFFIX,redacted.ch,China-Websites
  - DOMAIN-SUFFIX,springsunday.net,China-Websites
  - DOMAIN-SUFFIX,tjupt.org,China-Websites
  - DOMAIN-SUFFIX,totheglory.im,China-Websites
  - DOMAIN-SUFFIX,cn,China-Websites
  - DOMAIN-SUFFIX,8686c.com,China-Websites
  - DOMAIN-SUFFIX,aixifan.com,China-Websites
  - DOMAIN-SUFFIX,beitaichufang.com,China-Websites
  - DOMAIN-SUFFIX,booking.com,China-Websites
  - DOMAIN-SUFFIX,bstatic.com,China-Websites
  - DOMAIN-SUFFIX,cailianpress.com,China-Websites
  - DOMAIN-SUFFIX,chunyu.mobi,China-Websites
  - DOMAIN-SUFFIX,chushou.tv,China-Websites
  - DOMAIN-SUFFIX,cmbchina.com,China-Websites
  - DOMAIN-SUFFIX,cmbimg.com,China-Websites
  - DOMAIN-SUFFIX,ctrip.com,China-Websites
  - DOMAIN-SUFFIX,dfcfw.com,China-Websites
  - DOMAIN-SUFFIX,douban.com,China-Websites
  - DOMAIN-SUFFIX,doubanio.com,China-Websites
  - DOMAIN-SUFFIX,douyu.com,China-Websites
  - DOMAIN-SUFFIX,dxycdn.com,China-Websites
  - DOMAIN-SUFFIX,eastmoney.com,China-Websites
  - DOMAIN-SUFFIX,futunn.com,China-Websites
  - DOMAIN-SUFFIX,geilicdn.com,China-Websites
  - DOMAIN-SUFFIX,hicloud.com,China-Websites
  - DOMAIN-SUFFIX,hostbuf.com,China-Websites
  - DOMAIN-SUFFIX,huya.com,China-Websites
  - DOMAIN-SUFFIX,infinitynewtab.com,China-Websites
  - DOMAIN-SUFFIX,ithome.com,China-Websites
  - DOMAIN-SUFFIX,keepcdn.com,China-Websites
  - DOMAIN-SUFFIX,kkmh.com,China-Websites
  - DOMAIN-SUFFIX,luojilab.com,China-Websites
  - DOMAIN-SUFFIX,maoyun.tv,China-Websites
  - DOMAIN-SUFFIX,meituan.net,China-Websites
  - DOMAIN-SUFFIX,mobike.com,China-Websites
  - DOMAIN-SUFFIX,mubu.com,China-Websites
  - DOMAIN-SUFFIX,myzaker.com,China-Websites
  - DOMAIN-SUFFIX,nvidia.com,China-Websites
  - DOMAIN-SUFFIX,paypal.com,China-Websites
  - DOMAIN-SUFFIX,paypalobjects.com,China-Websites
  - DOMAIN-SUFFIX,qyer.com,China-Websites
  - DOMAIN-SUFFIX,qyerstatic.com,China-Websites
  - DOMAIN-SUFFIX,ronghub.com,China-Websites
  - DOMAIN-SUFFIX,ruguoapp.com,China-Websites
  - DOMAIN-SUFFIX,smzdm.com,China-Websites
  - DOMAIN-SUFFIX,snapdrop.net,China-Websites
  - DOMAIN-SUFFIX,sspai.com,China-Websites
  - DOMAIN-SUFFIX,teamviewer.com,China-Websites
  - DOMAIN-SUFFIX,tianyancha.com,China-Websites
  - DOMAIN-SUFFIX,udacity.com,China-Websites
  - DOMAIN-SUFFIX,uning.com,China-Websites
  - DOMAIN-SUFFIX,weather.com,China-Websites
  - DOMAIN-SUFFIX,weidian.com,China-Websites
  - DOMAIN-SUFFIX,xmcdn.com,China-Websites
  - DOMAIN-SUFFIX,yangkeduo.com,China-Websites
  - DOMAIN-SUFFIX,zhangzishi.cc,China-Websites
  - DOMAIN-SUFFIX,zhihu.com,China-Websites
  - DOMAIN-SUFFIX,zhimg.com,China-Websites
  - DOMAIN-SUFFIX,zhuihd.com,China-Websites
  - DOMAIN,download.jetbrains.com,China-Websites
  - DOMAIN-SUFFIX,local,China-Websites
  - DOMAIN,mtalk.google.com,China-Websites
  - IP-CIDR,192.168.0.0/16,China-Websites
  - IP-CIDR,10.0.0.0/8,China-Websites
  - IP-CIDR,172.16.0.0/12,China-Websites
  - IP-CIDR,127.0.0.0/8,China-Websites
  - IP-CIDR,100.64.0.0/10,China-Websites
  - DOMAIN,blizzard.nefficient.co.kr,Final
  - DOMAIN,blzddist1-a.akamaihd.net,Final
  - DOMAIN,blzddistkr1-a.akamaihd.net,Final
  - DOMAIN,bnetproduct-a.akamaihd.net,Final
  - DOMAIN,cdn.blz-contentstack.com,Final
  - DOMAIN-SUFFIX,battle.net,Final
  - DOMAIN-SUFFIX,blizzard.com,Final
  - DOMAIN-SUFFIX,appspot.com,Final
  - DOMAIN-SUFFIX,blogger.com,Final
  - DOMAIN-SUFFIX,getoutline.org,Final
  - DOMAIN-SUFFIX,gvt0.com,Final
  - DOMAIN-SUFFIX,gvt1.com,Final
  - DOMAIN-SUFFIX,gvt3.com,Final
  - DOMAIN-SUFFIX,xn--ngstr-lra8j.com,Final
  - DOMAIN-KEYWORD,google,Final
  - DOMAIN-KEYWORD,blogspot,Final
  - DOMAIN-SUFFIX,onedrive.live.com,Final
  - DOMAIN-SUFFIX,xboxlive.com,Final
  - DOMAIN-SUFFIX,cdninstagram.com,Final
  - DOMAIN-SUFFIX,fb.com,Final
  - DOMAIN-SUFFIX,fb.me,Final
  - DOMAIN-SUFFIX,fbaddins.com,Final
  - DOMAIN-SUFFIX,fbcdn.net,Final
  - DOMAIN-SUFFIX,fbsbx.com,Final
  - DOMAIN-SUFFIX,fbworkmail.com,Final
  - DOMAIN-SUFFIX,instagram.com,Final
  - DOMAIN-SUFFIX,m.me,Final
  - DOMAIN-SUFFIX,messenger.com,Final
  - DOMAIN-SUFFIX,oculus.com,Final
  - DOMAIN-SUFFIX,oculuscdn.com,Final
  - DOMAIN-SUFFIX,rocksdb.org,Final
  - DOMAIN-SUFFIX,whatsapp.com,Final
  - DOMAIN-SUFFIX,whatsapp.net,Final
  - DOMAIN-KEYWORD,facebook,Final
  - DOMAIN-SUFFIX,pscp.tv,Final
  - DOMAIN-SUFFIX,periscope.tv,Final
  - DOMAIN-SUFFIX,t.co,Final
  - DOMAIN-SUFFIX,twimg.co,Final
  - DOMAIN-SUFFIX,twimg.com,Final
  - DOMAIN-SUFFIX,twitpic.com,Final
  - DOMAIN-SUFFIX,vine.co,Final
  - DOMAIN-KEYWORD,twitter,Final
  - DOMAIN-SUFFIX,t.me,Final
  - DOMAIN-SUFFIX,tdesktop.com,Final
  - DOMAIN-SUFFIX,telegra.ph,Final
  - DOMAIN-SUFFIX,telegram.me,Final
  - DOMAIN-SUFFIX,telegram.org,Final
  - IP-CIDR,67.198.55.0/24,Final
  - IP-CIDR,91.108.4.0/22,Final
  - IP-CIDR,91.108.8.0/22,Final
  - IP-CIDR,91.108.12.0/22,Final
  - IP-CIDR,91.108.16.0/22,Final
  - IP-CIDR,91.108.56.0/22,Final
  - IP-CIDR,109.239.140.0/24,Final
  - IP-CIDR,149.154.160.0/20,Final
  - IP-CIDR,205.172.60.0/22,Final
  - DOMAIN-SUFFIX,line.me,Final
  - DOMAIN-SUFFIX,line-apps.com,Final
  - DOMAIN-SUFFIX,line-scdn.net,Final
  - DOMAIN-SUFFIX,naver.jp,Final
  - IP-CIDR,103.2.30.0/23,Final
  - IP-CIDR,125.209.208.0/20,Final
  - IP-CIDR,147.92.128.0/17,Final
  - IP-CIDR,203.104.144.0/21,Final
  - DOMAIN-SUFFIX,4shared.com,Final
  - DOMAIN-SUFFIX,520cc.cc,Final
  - DOMAIN-SUFFIX,9cache.com,Final
  - DOMAIN-SUFFIX,9gag.com,Final
  - DOMAIN-SUFFIX,abc.com,Final
  - DOMAIN-SUFFIX,abc.net.au,Final
  - DOMAIN-SUFFIX,abebooks.com,Final
  - DOMAIN-SUFFIX,amazon.co.jp,Final
  - DOMAIN-SUFFIX,apigee.com,Final
  - DOMAIN-SUFFIX,apk-dl.com,Final
  - DOMAIN-SUFFIX,apkfind.com,Final
  - DOMAIN-SUFFIX,apkmirror.com,Final
  - DOMAIN-SUFFIX,apkmonk.com,Final
  - DOMAIN-SUFFIX,apkpure.com,Final
  - DOMAIN-SUFFIX,aptoide.com,Final
  - DOMAIN-SUFFIX,archive.is,Final
  - DOMAIN-SUFFIX,archive.org,Final
  - DOMAIN-SUFFIX,arte.tv,Final
  - DOMAIN-SUFFIX,artstation.com,Final
  - DOMAIN-SUFFIX,arukas.io,Final
  - DOMAIN-SUFFIX,ask.com,Final
  - DOMAIN-SUFFIX,avgle.com,Final
  - DOMAIN-SUFFIX,badoo.com,Final
  - DOMAIN-SUFFIX,bandwagonhost.com,Final
  - DOMAIN-SUFFIX,bbc.com,Final
  - DOMAIN-SUFFIX,behance.net,Final
  - DOMAIN-SUFFIX,bibox.com,Final
  - DOMAIN-SUFFIX,biggo.com.tw,Final
  - DOMAIN-SUFFIX,binance.com,Final
  - DOMAIN-SUFFIX,bitcointalk.org,Final
  - DOMAIN-SUFFIX,bitfinex.com,Final
  - DOMAIN-SUFFIX,bitmex.com,Final
  - DOMAIN-SUFFIX,bit-z.com,Final
  - DOMAIN-SUFFIX,bloglovin.com,Final
  - DOMAIN-SUFFIX,bloomberg.cn,Final
  - DOMAIN-SUFFIX,bloomberg.com,Final
  - DOMAIN-SUFFIX,blubrry.com,Final
  - DOMAIN-SUFFIX,book.com.tw,Final
  - DOMAIN-SUFFIX,booklive.jp,Final
  - DOMAIN-SUFFIX,books.com.tw,Final
  - DOMAIN-SUFFIX,box.com,Final
  - DOMAIN-SUFFIX,businessinsider.com,Final
  - DOMAIN-SUFFIX,bwh1.net,Final
  - DOMAIN-SUFFIX,castbox.fm,Final
  - DOMAIN-SUFFIX,cbc.ca,Final
  - DOMAIN-SUFFIX,cccat.cc,Final
  - DOMAIN-SUFFIX,cdw.com,Final
  - DOMAIN-SUFFIX,change.org,Final
  - DOMAIN-SUFFIX,ck101.com,Final
  - DOMAIN-SUFFIX,clarionproject.org,Final
  - DOMAIN-SUFFIX,clyp.it,Final
  - DOMAIN-SUFFIX,cna.com.tw,Final
  - DOMAIN-SUFFIX,comparitech.com,Final
  - DOMAIN-SUFFIX,conoha.jp,Final
  - DOMAIN-SUFFIX,crucial.com,Final
  - DOMAIN-SUFFIX,cts.com.tw,Final
  - DOMAIN-SUFFIX,cw.com.tw,Final
  - DOMAIN-SUFFIX,cyberctm.com,Final
  - DOMAIN-SUFFIX,dailymotion.com,Final
  - DOMAIN-SUFFIX,dailyview.tw,Final
  - DOMAIN-SUFFIX,daum.net,Final
  - DOMAIN-SUFFIX,daumcdn.net,Final
  - DOMAIN-SUFFIX,dcard.tw,Final
  - DOMAIN-SUFFIX,deepdiscount.com,Final
  - DOMAIN-SUFFIX,depositphotos.com,Final
  - DOMAIN-SUFFIX,deviantart.com,Final
  - DOMAIN-SUFFIX,disconnect.me,Final
  - DOMAIN-SUFFIX,discordapp.com,Final
  - DOMAIN-SUFFIX,discordapp.net,Final
  - DOMAIN-SUFFIX,disqus.com,Final
  - DOMAIN-SUFFIX,dns2go.com,Final
  - DOMAIN-SUFFIX,dowjones.com,Final
  - DOMAIN-SUFFIX,dropbox.com,Final
  - DOMAIN-SUFFIX,dropboxusercontent.com,Final
  - DOMAIN-SUFFIX,duckduckgo.com,Final
  - DOMAIN-SUFFIX,dw.com,Final
  - DOMAIN-SUFFIX,dynu.com,Final
  - DOMAIN-SUFFIX,earthcam.com,Final
  - DOMAIN-SUFFIX,ebookservice.tw,Final
  - DOMAIN-SUFFIX,economist.com,Final
  - DOMAIN-SUFFIX,edgecastcdn.net,Final
  - DOMAIN-SUFFIX,edu,Final
  - DOMAIN-SUFFIX,elpais.com,Final
  - DOMAIN-SUFFIX,enanyang.my,Final
  - DOMAIN-SUFFIX,esoir.be,Final
  - DOMAIN-SUFFIX,euronews.com,Final
  - DOMAIN-SUFFIX,feedly.com,Final
  - DOMAIN-SUFFIX,firech.at,Final
  - DOMAIN-SUFFIX,flickr.com,Final
  - DOMAIN-SUFFIX,flitto.com,Final
  - DOMAIN-SUFFIX,foreignpolicy.com,Final
  - DOMAIN-SUFFIX,friday.tw,Final
  - DOMAIN-SUFFIX,ftchinese.com,Final
  - DOMAIN-SUFFIX,gate.io,Final
  - DOMAIN-SUFFIX,getlantern.org,Final
  - DOMAIN-SUFFIX,getsync.com,Final
  - DOMAIN-SUFFIX,globalvoices.org,Final
  - DOMAIN-SUFFIX,goo.ne.jp,Final
  - DOMAIN-SUFFIX,goodreads.com,Final
  - DOMAIN-SUFFIX,gov,Final
  - DOMAIN-SUFFIX,gov.tw,Final
  - DOMAIN-SUFFIX,gumroad.com,Final
  - DOMAIN-SUFFIX,hbg.com,Final
  - DOMAIN-SUFFIX,heroku.com,Final
  - DOMAIN-SUFFIX,hightail.com,Final
  - DOMAIN-SUFFIX,hk01.com,Final
  - DOMAIN-SUFFIX,hkbf.org,Final
  - DOMAIN-SUFFIX,hkbookcity.com,Final
  - DOMAIN-SUFFIX,hkej.com,Final
  - DOMAIN-SUFFIX,hket.com,Final
  - DOMAIN-SUFFIX,hkgolden.com,Final
  - DOMAIN-SUFFIX,hootsuite.com,Final
  - DOMAIN-SUFFIX,hudson.org,Final
  - DOMAIN-SUFFIX,hyread.com.tw,Final
  - DOMAIN-SUFFIX,ibtimes.com,Final
  - DOMAIN-SUFFIX,i-cable.com,Final
  - DOMAIN-SUFFIX,icij.org,Final
  - DOMAIN-SUFFIX,icoco.com,Final
  - DOMAIN-SUFFIX,imgur.com,Final
  - DOMAIN-SUFFIX,initiummall.com,Final
  - DOMAIN-SUFFIX,insecam.org,Final
  - DOMAIN-SUFFIX,ipfs.io,Final
  - DOMAIN-SUFFIX,issuu.com,Final
  - DOMAIN-SUFFIX,istockphoto.com,Final
  - DOMAIN-SUFFIX,japantimes.co.jp,Final
  - DOMAIN-SUFFIX,jiji.com,Final
  - DOMAIN-SUFFIX,jinx.com,Final
  - DOMAIN-SUFFIX,jkforum.net,Final
  - DOMAIN-SUFFIX,joinmastodon.org,Final
  - DOMAIN-SUFFIX,justpaste.it,Final
  - DOMAIN-SUFFIX,kakao.com,Final
  - DOMAIN-SUFFIX,kakaocorp.com,Final
  - DOMAIN-SUFFIX,kik.com,Final
  - DOMAIN-SUFFIX,kobo.com,Final
  - DOMAIN-SUFFIX,kobobooks.com,Final
  - DOMAIN-SUFFIX,kodingen.com,Final
  - DOMAIN-SUFFIX,lemonde.fr,Final
  - DOMAIN-SUFFIX,lepoint.fr,Final
  - DOMAIN-SUFFIX,lihkg.com,Final
  - DOMAIN-SUFFIX,listennotes.com,Final
  - DOMAIN-SUFFIX,livestream.com,Final
  - DOMAIN-SUFFIX,logmein.com,Final
  - DOMAIN-SUFFIX,mail.ru,Final
  - DOMAIN-SUFFIX,mailchimp.com,Final
  - DOMAIN-SUFFIX,marc.info,Final
  - DOMAIN-SUFFIX,matters.news,Final
  - DOMAIN-SUFFIX,medium.com,Final
  - DOMAIN-SUFFIX,mega.nz,Final
  - DOMAIN-SUFFIX,mil,Final
  - DOMAIN-SUFFIX,mingpao.com,Final
  - DOMAIN-SUFFIX,mobile01.com,Final
  - DOMAIN-SUFFIX,myspace.com,Final
  - DOMAIN-SUFFIX,myspacecdn.com,Final
  - DOMAIN-SUFFIX,nanyang.com,Final
  - DOMAIN-SUFFIX,naver.com,Final
  - DOMAIN-SUFFIX,newstapa.org,Final
  - DOMAIN-SUFFIX,nhk.or.jp,Final
  - DOMAIN-SUFFIX,nicovideo.jp,Final
  - DOMAIN-SUFFIX,nii.ac.jp,Final
  - DOMAIN-SUFFIX,nikkei.com,Final
  - DOMAIN-SUFFIX,nofile.io,Final
  - DOMAIN-SUFFIX,now.com,Final
  - DOMAIN-SUFFIX,nrk.no,Final
  - DOMAIN-SUFFIX,nyt.com,Final
  - DOMAIN-SUFFIX,nytchina.com,Final
  - DOMAIN-SUFFIX,nytcn.me,Final
  - DOMAIN-SUFFIX,nytco.com,Final
  - DOMAIN-SUFFIX,nytimes.com,Final
  - DOMAIN-SUFFIX,nytimg.com,Final
  - DOMAIN-SUFFIX,nytlog.com,Final
  - DOMAIN-SUFFIX,nytstyle.com,Final
  - DOMAIN-SUFFIX,ok.ru,Final
  - DOMAIN-SUFFIX,okex.com,Final
  - DOMAIN-SUFFIX,on.cc,Final
  - DOMAIN-SUFFIX,orientaldaily.com.my,Final
  - DOMAIN-SUFFIX,overcast.fm,Final
  - DOMAIN-SUFFIX,paltalk.com,Final
  - DOMAIN-SUFFIX,pbxes.com,Final
  - DOMAIN-SUFFIX,pcdvd.com.tw,Final
  - DOMAIN-SUFFIX,pchome.com.tw,Final
  - DOMAIN-SUFFIX,pcloud.com,Final
  - DOMAIN-SUFFIX,picacomic.com,Final
  - DOMAIN-SUFFIX,pinimg.com,Final
  - DOMAIN-SUFFIX,pixiv.net,Final
  - DOMAIN-SUFFIX,player.fm,Final
  - DOMAIN-SUFFIX,plurk.com,Final
  - DOMAIN-SUFFIX,po18.tw,Final
  - DOMAIN-SUFFIX,prism-break.org,Final
  - DOMAIN-SUFFIX,proxifier.com,Final
  - DOMAIN-SUFFIX,pts.org.tw,Final
  - DOMAIN-SUFFIX,pubu.com.tw,Final
  - DOMAIN-SUFFIX,pubu.tw,Final
  - DOMAIN-SUFFIX,pureapk.com,Final
  - DOMAIN-SUFFIX,quora.com,Final
  - DOMAIN-SUFFIX,quoracdn.net,Final
  - DOMAIN-SUFFIX,rakuten.co.jp,Final
  - DOMAIN-SUFFIX,readingtimes.com.tw,Final
  - DOMAIN-SUFFIX,readmoo.com,Final
  - DOMAIN-SUFFIX,reddit.com,Final
  - DOMAIN-SUFFIX,redditmedia.com,Final
  - DOMAIN-SUFFIX,resilio.com,Final
  - DOMAIN-SUFFIX,reuters.com,Final
  - DOMAIN-SUFFIX,rfi.fr,Final
  - DOMAIN-SUFFIX,roadshow.hk,Final
  - DOMAIN-SUFFIX,scmp.com,Final
  - DOMAIN-SUFFIX,scribd.com,Final
  - DOMAIN-SUFFIX,seatguru.com,Final
  - DOMAIN-SUFFIX,shadowsocks.org,Final
  - DOMAIN-SUFFIX,shopee.tw,Final
  - DOMAIN-SUFFIX,slideshare.net,Final
  - DOMAIN-SUFFIX,softfamous.com,Final
  - DOMAIN-SUFFIX,soundcloud.com,Final
  - DOMAIN-SUFFIX,startpage.com,Final
  - DOMAIN-SUFFIX,steamcommunity.com,Final
  - DOMAIN-SUFFIX,steemit.com,Final
  - DOMAIN-SUFFIX,steemitwallet.com,Final
  - DOMAIN-SUFFIX,t66y.com,Final
  - DOMAIN-SUFFIX,tapatalk.com,Final
  - DOMAIN-SUFFIX,teco-hk.org,Final
  - DOMAIN-SUFFIX,teco-mo.org,Final
  - DOMAIN-SUFFIX,teddysun.com,Final
  - DOMAIN-SUFFIX,theguardian.com,Final
  - DOMAIN-SUFFIX,theinitium.com,Final
  - DOMAIN-SUFFIX,tineye.com,Final
  - DOMAIN-SUFFIX,torproject.org,Final
  - DOMAIN-SUFFIX,tumblr.com,Final
  - DOMAIN-SUFFIX,turbobit.net,Final
  - DOMAIN-SUFFIX,tutanota.com,Final
  - DOMAIN-SUFFIX,tvboxnow.com,Final
  - DOMAIN-SUFFIX,udn.com,Final
  - DOMAIN-SUFFIX,unseen.is,Final
  - DOMAIN-SUFFIX,upmedia.mg,Final
  - DOMAIN-SUFFIX,uptodown.com,Final
  - DOMAIN-SUFFIX,ustream.tv,Final
  - DOMAIN-SUFFIX,uwants.com,Final
  - DOMAIN-SUFFIX,v2ray.com,Final
  - DOMAIN-SUFFIX,viber.com,Final
  - DOMAIN-SUFFIX,videopress.com,Final
  - DOMAIN-SUFFIX,vimeo.com,Final
  - DOMAIN-SUFFIX,voachinese.com,Final
  - DOMAIN-SUFFIX,voanews.com,Final
  - DOMAIN-SUFFIX,voxer.com,Final
  - DOMAIN-SUFFIX,vzw.com,Final
  - DOMAIN-SUFFIX,w3schools.com,Final
  - DOMAIN-SUFFIX,washingtonpost.com,Final
  - DOMAIN-SUFFIX,wattpad.com,Final
  - DOMAIN-SUFFIX,whoer.net,Final
  - DOMAIN-SUFFIX,wikimapia.org,Final
  - DOMAIN-SUFFIX,wikipedia.org,Final
  - DOMAIN-SUFFIX,winudf.com,Final
  - DOMAIN-SUFFIX,wire.com,Final
  - DOMAIN-SUFFIX,wordpress.com,Final
  - DOMAIN-SUFFIX,workflow.is,Final
  - DOMAIN-SUFFIX,worldcat.org,Final
  - DOMAIN-SUFFIX,wsj.com,Final
  - DOMAIN-SUFFIX,wsj.net,Final
  - DOMAIN-SUFFIX,xhamster.com,Final
  - DOMAIN-SUFFIX,xnxx.com,Final
  - DOMAIN-SUFFIX,xvideos.com,Final
  - DOMAIN-SUFFIX,yahoo.com,Final
  - DOMAIN-SUFFIX,yandex.ru,Final
  - DOMAIN-SUFFIX,ycombinator.com,Final
  - DOMAIN-SUFFIX,yesasia.com,Final
  - DOMAIN-SUFFIX,yes-news.com,Final
  - DOMAIN-SUFFIX,yomiuri.co.jp,Final
  - DOMAIN-SUFFIX,you-get.org,Final
  - DOMAIN-SUFFIX,zaobao.com,Final
  - DOMAIN-SUFFIX,zb.com,Final
  - DOMAIN-SUFFIX,zello.com,Final
  - DOMAIN-SUFFIX,zeronet.io,Final
  - DOMAIN-KEYWORD,github,Final
  - DOMAIN-KEYWORD,jav,Final
  - DOMAIN-KEYWORD,pinterest,Final
  - DOMAIN-KEYWORD,porn,Final
  - DOMAIN-KEYWORD,wikileaks,Final
  - DOMAIN-SUFFIX,apartmentratings.com,Final
  - DOMAIN-SUFFIX,apartments.com,Final
  - DOMAIN-SUFFIX,bankmobilevibe.com,Final
  - DOMAIN-SUFFIX,bing.com,Final
  - DOMAIN-SUFFIX,booktopia.com.au,Final
  - DOMAIN-SUFFIX,centauro.com.br,Final
  - DOMAIN-SUFFIX,clearsurance.com,Final
  - DOMAIN-SUFFIX,costco.com,Final
  - DOMAIN-SUFFIX,crackle.com,Final
  - DOMAIN-SUFFIX,depositphotos.cn,Final
  - DOMAIN-SUFFIX,dish.com,Final
  - DOMAIN-SUFFIX,dmm.co.jp,Final
  - DOMAIN-SUFFIX,dmm.com,Final
  - DOMAIN-SUFFIX,dnvod.tv,Final
  - DOMAIN-SUFFIX,esurance.com,Final
  - DOMAIN-SUFFIX,extmatrix.com,Final
  - DOMAIN-SUFFIX,fastpic.ru,Final
  - DOMAIN-SUFFIX,flipboard.com,Final
  - DOMAIN-SUFFIX,fnac.be,Final
  - DOMAIN-SUFFIX,fnac.com,Final
  - DOMAIN-SUFFIX,funkyimg.com,Final
  - DOMAIN-SUFFIX,fxnetworks.com,Final
  - DOMAIN-SUFFIX,gettyimages.com,Final
  - DOMAIN-SUFFIX,go.com,Final
  - DOMAIN-SUFFIX,here.com,Final
  - DOMAIN-SUFFIX,jcpenney.com,Final
  - DOMAIN-SUFFIX,jiehua.tv,Final
  - DOMAIN-SUFFIX,kknews.cc,Final
  - DOMAIN-SUFFIX,mailfence.com,Final
  - DOMAIN-SUFFIX,nationwide.com,Final
  - DOMAIN-SUFFIX,nbc.com,Final
  - DOMAIN-SUFFIX,nexon.com,Final
  - DOMAIN-SUFFIX,nordstrom.com,Final
  - DOMAIN-SUFFIX,nordstromimage.com,Final
  - DOMAIN-SUFFIX,nordstromrack.com,Final
  - DOMAIN-SUFFIX,read01.com,Final
  - DOMAIN-SUFFIX,superpages.com,Final
  - DOMAIN-SUFFIX,target.com,Final
  - DOMAIN-SUFFIX,thinkgeek.com,Final
  - DOMAIN-SUFFIX,tracfone.com,Final
  - DOMAIN-SUFFIX,uploader.jp,Final
  - DOMAIN-SUFFIX,vevo.com,Final
  - DOMAIN-SUFFIX,viu.tv,Final
  - DOMAIN-SUFFIX,vk.com,Final
  - DOMAIN-SUFFIX,vsco.co,Final
  - DOMAIN-SUFFIX,xfinity.com,Final
  - DOMAIN-SUFFIX,zattoo.com,Final
  - DOMAIN,testflight.Apple.com,Final
  - DOMAIN-SUFFIX,appsto.re,Final
  - DOMAIN,books.itunes.Apple.com,Final
  - DOMAIN,hls.itunes.Apple.com,Final
  - DOMAIN,apps.Apple.com,Final
  - DOMAIN,itunes.Apple.com,Final
  - DOMAIN,api-glb-sea.smoot.Apple.com,Final
  - DOMAIN,lookup-api.Apple.com,Final
  - DOMAIN,gspe1-ssl.ls.Apple.com,Final
  - DOMAIN-SUFFIX,Apple.news,Final
  - DOMAIN,news-client.Apple.com,Final
  - DOMAIN,news-edge.Apple.com,Final
  - DOMAIN,news-events.Apple.com,Final
  - DOMAIN,Apple.comscoreresearch.com,Final
  - DOMAIN-SUFFIX,abc.xyz,Final
  - DOMAIN-SUFFIX,android.com,Final
  - DOMAIN-SUFFIX,androidify.com,Final
  - DOMAIN-SUFFIX,dialogflow.com,Final
  - DOMAIN-SUFFIX,autodraw.com,Final
  - DOMAIN-SUFFIX,capitalg.com,Final
  - DOMAIN-SUFFIX,certificate-transparency.org,Final
  - DOMAIN-SUFFIX,chrome.com,Final
  - DOMAIN-SUFFIX,chromeexperiments.com,Final
  - DOMAIN-SUFFIX,chromestatus.com,Final
  - DOMAIN-SUFFIX,chromium.org,Final
  - DOMAIN-SUFFIX,creativelab5.com,Final
  - DOMAIN-SUFFIX,debug.com,Final
  - DOMAIN-SUFFIX,deepmind.com,Final
  - DOMAIN-SUFFIX,firebaseio.com,Final
  - DOMAIN-SUFFIX,getmdl.io,Final
  - DOMAIN-SUFFIX,ggpht.com,Final
  - DOMAIN-SUFFIX,gmail.com,Final
  - DOMAIN-SUFFIX,gmodules.com,Final
  - DOMAIN-SUFFIX,godoc.org,Final
  - DOMAIN-SUFFIX,golang.org,Final
  - DOMAIN-SUFFIX,gstatic.com,Final
  - DOMAIN-SUFFIX,gv.com,Final
  - DOMAIN-SUFFIX,gwtproject.org,Final
  - DOMAIN-SUFFIX,itasoftware.com,Final
  - DOMAIN-SUFFIX,madewithcode.com,Final
  - DOMAIN-SUFFIX,material.io,Final
  - DOMAIN-SUFFIX,polymer-project.org,Final
  - DOMAIN-SUFFIX,admin.recaptcha.net,Final
  - DOMAIN-SUFFIX,recaptcha.net,Final
  - DOMAIN-SUFFIX,shattered.io,Final
  - DOMAIN-SUFFIX,synergyse.com,Final
  - DOMAIN-SUFFIX,tensorflow.org,Final
  - DOMAIN-SUFFIX,tfhub.dev,Final
  - DOMAIN-SUFFIX,tiltbrush.com,Final
  - DOMAIN-SUFFIX,waveprotocol.org,Final
  - DOMAIN-SUFFIX,waymo.com,Final
  - DOMAIN-SUFFIX,webmproject.org,Final
  - DOMAIN-SUFFIX,webrtc.org,Final
  - DOMAIN-SUFFIX,whatbrowser.org,Final
  - DOMAIN-SUFFIX,widevine.com,Final
  - DOMAIN-SUFFIX,x.company,Final
  - DOMAIN-SUFFIX,youtu.be,Final
  - DOMAIN-SUFFIX,yt.be,Final
  - DOMAIN-SUFFIX,ytimg.com,Final
  - DOMAIN-SUFFIX,1drv.com,Final
  - DOMAIN-SUFFIX,1drv.ms,Final
  - DOMAIN-SUFFIX,live.com,Final
  - DOMAIN-SUFFIX,live.net,Final
  - DOMAIN-SUFFIX,livefilestore.com,Final
  - DOMAIN-SUFFIX,storage.msn.com,Final
  - DOMAIN-SUFFIX,0rz.tw,Final
  - DOMAIN-SUFFIX,4bluestones.biz,Final
  - DOMAIN-SUFFIX,9bis.net,Final
  - DOMAIN-SUFFIX,allconnected.co,Final
  - DOMAIN-SUFFIX,amazonaws.com,Final
  - DOMAIN-SUFFIX,aol.com,Final
  - DOMAIN-SUFFIX,bcc.com.tw,Final
  - DOMAIN-SUFFIX,bit.ly,Final
  - DOMAIN-SUFFIX,bitshare.com,Final
  - DOMAIN-SUFFIX,blog.jp,Final
  - DOMAIN-SUFFIX,blogimg.jp,Final
  - DOMAIN-SUFFIX,blogtd.org,Final
  - DOMAIN-SUFFIX,broadcast.co.nz,Final
  - DOMAIN-SUFFIX,camfrog.com,Final
  - DOMAIN-SUFFIX,cfos.de,Final
  - DOMAIN-SUFFIX,citypopulation.de,Final
  - DOMAIN-SUFFIX,cloudfront.net,Final
  - DOMAIN-SUFFIX,ctitv.com.tw,Final
  - DOMAIN-SUFFIX,cuhk.edu.hk,Final
  - DOMAIN-SUFFIX,cusu.hk,Final
  - DOMAIN-SUFFIX,discuss.com.hk,Final
  - DOMAIN-SUFFIX,dropboxapi.com,Final
  - DOMAIN-SUFFIX,edditstatic.com,Final
  - DOMAIN-SUFFIX,flickriver.com,Final
  - DOMAIN-SUFFIX,focustaiwan.tw,Final
  - DOMAIN-SUFFIX,free.fr,Final
  - DOMAIN-SUFFIX,gigacircle.com,Final
  - DOMAIN-SUFFIX,hk-pub.com,Final
  - DOMAIN-SUFFIX,hosting.co.uk,Final
  - DOMAIN-SUFFIX,hwcdn.net,Final
  - DOMAIN-SUFFIX,iphone4hongkong.com,Final
  - DOMAIN-SUFFIX,iphonetaiwan.org,Final
  - DOMAIN-SUFFIX,iptvbin.com,Final
  - DOMAIN-SUFFIX,jtvnw.net,Final
  - DOMAIN-SUFFIX,linksalpha.com,Final
  - DOMAIN-SUFFIX,manyvids.com,Final
  - DOMAIN-SUFFIX,myactimes.com,Final
  - DOMAIN-SUFFIX,newsblur.com,Final
  - DOMAIN-SUFFIX,now.im,Final
  - DOMAIN-SUFFIX,nowe.com,Final
  - DOMAIN-SUFFIX,redditlist.com,Final
  - DOMAIN-SUFFIX,signal.org,Final
  - DOMAIN-SUFFIX,smartmailcloud.com,Final
  - DOMAIN-SUFFIX,sparknotes.com,Final
  - DOMAIN-SUFFIX,streetvoice.com,Final
  - DOMAIN-SUFFIX,supertop.co,Final
  - DOMAIN-SUFFIX,tv.com,Final
  - DOMAIN-SUFFIX,typepad.com,Final
  - DOMAIN-SUFFIX,udnbkk.com,Final
  - DOMAIN-SUFFIX,urbanairship.com,Final
  - DOMAIN-SUFFIX,whispersystems.org,Final
  - DOMAIN-SUFFIX,wikia.com,Final
  - DOMAIN-SUFFIX,wn.com,Final
  - DOMAIN-SUFFIX,wolframalpha.com,Final
  - DOMAIN-SUFFIX,x-art.com,Final
  - DOMAIN-SUFFIX,yimg.com,Final
  - GEOIP,CN,China-Websites
  - MATCH,Final
