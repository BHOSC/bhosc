## Planet Beihang-OSC ##

[Planet Beihang-OSC](https://www.google.com/reader/bundle/user%2F05633959152623275806%2Fbundle%2FPlanet%20Beihang-OSC)。用 Google Reader 订阅。

## HTML snippet ##

可以加到你的网站上的 HTML snippet:

```
<script type="text/javascript" src="https://www.google.com/reader/ui/publisher-en.js"></script>
<script type="text/javascript" src="https://www.google.com/reader/public/javascript-sub/user/05633959152623275806/bundle/Planet Beihang-OSC?callback=GRC_p(%7Bc%3A%22blue%22%2Ct%3A%22Planet%20Beihang-OSC%22%2Cb%3A%22true%22%7D)%3Bnew%20GRC"></script>
```

有两个选项可以改，

```
>>> urllib.unquote("?callback=GRC_p(%7Bc%3A%22blue%22%2Ct%3A%22Planet%20Beihang-OSC%22%2Cb%3A%22true%22%7D)%3B")
'?callback=GRC_p({c:"blue",t:"Planet Beihang-OSC",b:"true"});'
```

c 指颜色，可以为 black, blue, grey, green, khaki, pink, slate 或 -。

t 是 title。