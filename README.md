# 😎 CentOS_Proxi

![Repo Boyutu](https://img.shields.io/github/repo-size/keyiflerolsun/CentOS_Proxi) ![Views](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https://github.com/keyiflerolsun/CentOS_Proxi&title=Profile%20Views)

**CentOS v7 Sunucunuzu Proxy Server'a Dönüştürün**

*1 Adet IPv4* - *1 Adet SOCKS5* -  *İstediğiniz Kadar IPv6*

## 🚀 Kullanım

```bash

yum install wget nano -y
wget https://raw.githubusercontent.com/higarez/centos7deneme/main/CentOS_Proxi.sh --no-check-certificate --no-cache --no-cookies
nano /etc/rc.local (Son Satırı Sil sırasıyla Ctrl+x > Y > Enter tuşlarına bas)
chmod +x /etc/rc.local
chmod +x CentOS_Proxi.sh 
./CentOS_Proxi.sh (İşlem bittikten sonra)
nano CentOS_Proxi.sh 
(
cat >>/etc/rc.local <<EOF
bash ${YOL}/iptable_yapilandir.sh >/dev/null
bash ${YOL}/ifconfig_yapilandir.sh >/dev/null
ulimit -n 10048
service 3proxy start
EOF
) Satırlarını Sil SırasıylaCtrl+x > Y > Enter tuşlarına bas)


# Proxy Kullanıcı Adı ve Şifresi Dosyanın En Üstünde Tanımlıdır..

chmod +x CentOS_Proxi.sh

./CentOS_Proxi.sh

# Akış Esnasında IPv6 için Kaç Adet İstediğinizi Soruyor
'''
        IPv4 » 70.34.222.151 | IPv6 için Sub » 2a05:f480:2000:10d4

Kaç adet IPv6 proxy oluşturmak istiyorsunuz? Örnek 500 :
'''
```

### Çıktı

```
         Proxyler Hazır! Format » IP:PORT:KULLANICI:SIFRE

 IPv6 Zip İndirme Bağlantısı: https://file.io/t5Ysvv5yMIkL
 IPv6 Zip Şifresi: RnzNy

 IPv4   Proxy » 45.77.88.54:3310:tarak:kurek
 SOCKS5 Proxy » 45.77.88.54:5110:tarak:kurek
```

### Video Anlatım

[![CentOS_Proxi](https://img.youtube.com/vi/-tqliMAo8Mc/0.jpg)](https://www.youtube.com/watch?v=-tqliMAo8Mc)

## 📝 Teşekkürler

- IPv4           için *[squid](https://github.com/squid-cache/squid)*
- IPv6           için *[3proxy](https://github.com/3proxy/3proxy)*
- SOCKS5         için *[dante](https://github.com/Lozy/danted)*
- Dosya yüklemek için *[file.io](https://www.file.io/developers)*

## 🌐 Telif Hakkı ve Lisans

- _Copyright (C) 2022 by_ [keyiflerolsun](https://github.com/keyiflerolsun) ❤️️
- [GNU GENERAL PUBLIC LICENSE Version 3, 29 June 2007](https://github.com/keyiflerolsun/CentOS_Proxi/blob/main/LICENSE) _Koşullarına göre lisanslanmıştır.._

## ♻️ İletişim

_Benimle iletişime geçmek isterseniz, **Telegram**'dan mesaj göndermekten çekinmeyin;_ [@keyiflerolsun](https://t.me/keyiflerolsun)

## 💸 Bağış Yap

**[☕️ Kahve Ismarla](https://keyiflerolsun.me/Kahve)**

##

> **[@KekikAkademi](https://t.me/KekikAkademi)** _için yazılmıştır.._
