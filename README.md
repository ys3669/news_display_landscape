## 横長の液晶(640x48)にニュースを表示させるやつ
---
chromiumとfbcpに逃げた

![image](https://i.imgur.com/KTKnEYG.jpg?2 "image")

⭕️マジョカアイリス

❌マジョリカアイリス

- Need
    - https://github.com/Akkiesoft/fb_majocairisLCD-dkms

    - https://github.com/tasanakorn/rpi-fbcp

    - feeds.jsonの形式でjson を吐くなにか

    https://news.yahoo.co.jp/rss :
    > (RSSから取得した情報を用いたウェブサイトやアプリケーションなどのプログラムを作成して公開することは許可しておりません。また、RSSの再配信や再提供も許可しておりません。)

/boot/config
```
hdmi_force_hotplug=1
hdmi_ignore_edid=0xa5000080

hdmi_group=2
hdmi_mode=87

hdmi_cvt=640 48 20
```
