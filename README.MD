# ocserv-cn-no-route

## OpenConnect VPN Server

��ҳ��[http://www.infradead.org/ocserv/](http://www.infradead.org/ocserv/)

���أ�[http://www.infradead.org/ocserv/download.html](http://www.infradead.org/ocserv/download.html)

������ʷ��[http://www.infradead.org/ocserv/changelog.html](http://www.infradead.org/ocserv/changelog.html)

Դ�룺[https://gitlab.com/ocserv/ocserv.git](https://gitlab.com/ocserv/ocserv.git)

## OpenConnect VPN Client

��ҳ��[http://www.infradead.org/openconnect/](http://www.infradead.org/openconnect/)

���أ�[http://www.infradead.org/openconnect/download.html](http://www.infradead.org/openconnect/download.html)

������ʷ��[http://www.infradead.org/openconnect/changelog.html](http://www.infradead.org/openconnect/changelog.html)

Դ�룺[http://git.infradead.org/users/dwmw2/openconnect.git](http://git.infradead.org/users/dwmw2/openconnect.git)

## Cisco AnyConnect VPN Client

���أ�[https://cnlic.com/share/client.html](https://cnlic.com/share/client.html)

## ע�����

1��0.10.5 ��֮ǰ�汾ocserv��Ҫ�޸�src/vpn.h��֧�ֳ���96��(ocservĬ��ֵ)��������200��(Cisco AnyConnect���ֵ)��·�ɱ�:

```
#define MAX_CONFIG_ENTRIES 96
```

96��Ϊ200����

0.10.6 ��֮��汾ocserv����Ҫ�޸ģ��ο�[https://gitlab.com/ocserv/ocserv/issues/17](https://gitlab.com/ocserv/ocserv/issues/17)

2������[Cisco�ٷ��ĵ�](http://www.cisco.com/c/en/us/products/collateral/security/ios-sslvpn/prod_white_paper0900aecd80512071.html)��no-route��route����ͬʱʹ�á�

```
You can specify either split-include or split-exclude, but you cannot specify both options.
```

## ϲѶ

2015/12/08 Debian�йٷ�ocservԴ�ˣ�[https://tracker.debian.org/pkg/ocserv](https://tracker.debian.org/pkg/ocserv)

```
echo 'deb http://ftp.debian.org/debian/ unstable main contrib non-free' >> /etc/apt/sources.list
apt-get update
apt-get install ocserv
```