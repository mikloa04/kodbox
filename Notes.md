config/setting.php ---> https://api.kodcloud.com/?  ---> cần xây dựng 1 api server giống con này

Querry string : 
```
plugin/platform/=
type=github
kodid=e64032f86989f21245fa9698599edbb0
timestamp=1637305430
data={"action":"github_login","link":"https:\/\/desktop2.namek.edu.vn\/#user\/bindInfo&client=1","isJson":1}
sign=936E583F1817483AE2495B3E78E1A26D
```

Response string:

```
HTTP/2 302 Found
server: nginx
date: Fri, 19 Nov 2021 07:03:51 GMT
content-type: text/html; charset=utf-8
location: https://github.com/login/oauth/authorize?client_id=0e438a5d63ffc1237f2d&redirect_uri=https%3A%2F%2Fapi.kodcloud.com%2F%3Fplugin%2Fplatform%2F%26type%3Dgithub%26kodid%3De64032f86989f21245fa9698599edbb0%26timestamp%3D1637305431%26data%3D%257B%2522link%2522%253A%2522https%253A%255C%252F%255C%252Fdesktop2.namek.edu.vn%255C%252F%2523user%255C%252FbindInfo%2526client%253D1%2522%252C%2522action%2522%253A%2522github_login%2522%252C%2522isJson%2522%253A1%257D%26sign%3DFE28F02B850DD2B86948557F4D3E988C&scope=user&state=d6adb9f6ffe8b26771c488fdeb429f13
x-powered-by: PHP/7.1.5
set-cookie: KOD_SESSION_ID=d057914d6bf4191b6d6833d98f266cfb; expires=Fri, 19-Nov-2021 11:03:51 GMT; Max-Age=14400; path=/; HttpOnly
X-Firefox-Spdy: h2
```
