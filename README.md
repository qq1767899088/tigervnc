```
openssl req -new -newkey rsa:2048 -days 36500 -nodes -x509 -keyout key.yxf -out cert.yxf
```

```
session=i3
SecurityTypes=X509Vnc

X509Key=/home/yxf/bvnc_x509vnc/key.yxf
X509Cert=/home/yxf/bvnc_x509vnc/cert.yxf
```
