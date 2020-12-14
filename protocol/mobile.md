```
GET https://mobile.alsi.cn/ HTTP/1.1
Host: mobile.alsi.cn
Connection: keep-alive
Cache-Control: max-age=0
Upgrade-Insecure-Requests: 1
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/80.0.3987.163 Safari/537.36
Sec-Fetch-Dest: document
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.9
Sec-Fetch-Site: none
Sec-Fetch-Mode: navigate
Sec-Fetch-User: ?1
Accept-Encoding: gzip, deflate, br
Accept-Language: zh-CN,zh;q=0.9,en;q=0.8
```
```
HTTP/1.1 403 Forbidden
Server: nginx/1.17.8
Date: Fri, 30 Oct 2020 15:23:11 GMT
Content-Type: text/html
Content-Length: 555
Connection: keep-alive

<html>
<head><title>403 Forbidden</title></head>
<body>
<center><h1>403 Forbidden</h1></center>
<hr><center>nginx/1.17.8</center>
</body>
</html>
<!-- a padding to disable MSIE and Chrome friendly error page -->
<!-- a padding to disable MSIE and Chrome friendly error page -->
<!-- a padding to disable MSIE and Chrome friendly error page -->
<!-- a padding to disable MSIE and Chrome friendly error page -->
<!-- a padding to disable MSIE and Chrome friendly error page -->
<!-- a padding to disable MSIE and Chrome friendly error page -->
```
```
POST https://mobile.alsi.cn/mrcube/appUpdate/checkVersion HTTP/1.1
token: undefined
userid: undefined
Content-Type: application/json
Content-Length: 40
Host: mobile.alsi.cn
Connection: Keep-Alive
Accept-Encoding: gzip
User-Agent: okhttp/3.12.1

{"platform":"android","version":"1.0.6"}
```
```
HTTP/1.1 200
Server: nginx/1.17.8
Date: Mon, 14 Dec 2020 13:37:55 GMT
Content-Type: application/json;charset=utf-8
Content-Length: 400
Connection: keep-alive

{
    "code": 0,
    "data": {
        "appSize": "25666",
        "description": "1.修复非首次登录后出现的请求异常问题\r\n2.修复部分图标显示错误的问题\r\n3.启动页样式调整，适配不同分辨率的机型",
        "downloadUrl": "https://mobile.alsi.cn/download/app.html",
        "enable": "1",
        "id": 36,
        "mandatory": "1",
        "platform": "android",
        "updateDate": "2020-11-05",
        "version": "1.0.7"
    },
    "msg": "i18n_versionUpToDate"
}
```
