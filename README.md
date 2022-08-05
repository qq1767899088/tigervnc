```
mkdir ~/bvnc_x509vnc
openssl req -new -newkey rsa:2048 -days 36500 -nodes -x509 -keyout ~/bvnc_x509vnv/key.yxf -out ~/bvnc_x509vnc/cert.yxf
```

```
session=i3
SecurityTypes=X509Vnc

X509Key=/home/yxf/bvnc_x509vnc/key.yxf
X509Cert=/home/yxf/bvnc_x509vnc/cert.yxf
```
