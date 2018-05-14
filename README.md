# dingdingtalk-auto
auto dingding


# 发送日报或周报

## POST https://landray.dingtalkapps.com/alid/reportpc/client/create

test demo: http://coolaf.com/tool/gp

- body

```
{
	"atperson": [],
	"attachmentUri": [],
	"templateid": "15755c2f31a68dc07b0d92c493388e3d",
	"groupid": "",
	"userid": "15226340085374539",
	"auths": "",
	"remark": "a",
	"images": [],
	"detail": [{
		"key": "本周完成工作",
		"value": "a",
		"type": "1",
		"sort": "0"
	}, {
		"key": "本周工作总结",
		"value": "a",
		"type": "1",
		"sort": "1"
	}, {
		"key": "下周工作计划",
		"value": "a",
		"type": "1",
		"sort": "2"
	}, {
		"key": "需协调与帮助",
		"value": "a111",
		"type": "1",
		"sort": "3"
	}],
	"isOrgConv": 0,
	"masterLevels": "",
	"msgMediaId": "",
	"isSyncCircle": false,
	"isToChat": false
}
```

- Headers

```
Host:landray.dingtalkapps.com
Connection:keep-alive
Accept:application/json, text/javascript, */*; q=0.01
random-numbers:15263078993562397123
Origin:https://landray.dingtalkapps.com
X-Requested-With:XMLHttpRequest
User-Agent:Mozilla/5.0 (Macintosh; Intel Mac OS X 10_12_6) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/62.0.3202.94 Safari/537.36 DingTalk(4.3.0-macOS) nw
Content-Type:application/json
Referer:https://landray.dingtalkapps.com/alid/app/reportpc/createreport.html?corpid=dinge9db926556c2586a35c2f4657eb6378f&comeFromInside=1
Accept-Encoding:gzip, deflate, br
Accept-Language:zh-CN,zh;q=0.9
```

- Cookie

```
_bl_uid=********************
```
