# Marmara University Campus Area Network (CAN) Design & Implementation

Bu proje, Marmara Üniversitesi Göztepe ve RTE kampüsleri için ölçeklenebilir, güvenli ve yedekli bir kurumsal ağ altyapısı tasarımıdır. Cisco'nun üç katmanlı (Core, Distribution, Access) hiyerarşik modeline dayanmaktadır.

## 🚀 Proje Özellikleri

* **Dinamik Yönlendirme:** Kampüsler arası iletişim için OSPF (Open Shortest Path First) protokolü.
* **Yedeklilik:** Gateway yedekliliği için HSRP, bağlantı yedekliliği için LACP/EtherChannel.
* **Segmentasyon:** VLAN yapısı ile kullanıcı, yönetim, WLAN ve sunucu ağlarının ayrıştırılması.
* **Güvenlik:** Port Security (Sticky MAC), BPDU Guard, DHCP Snooping ve ACL (Access Control Lists).
* **Servisler:** DMZ bölgesinde konumlandırılmış merkezi DHCP, DNS, WEB ve FTP sunucuları.

## 🛠 Kullanılan Teknolojiler
* Cisco Packet Tracer
* Cisco IOS CLI

## 📂 Proje İçeriği

* **`/Simulation`**: Marmara-University-CAN.pkt (Cisco Packet Tracer simülasyon dosyası)
* **`/Document`**: BLM2006-Rapor.pdf (Detaylı teknik proje raporu)
* **`/Presentation`**: Proje-Sunumu.pptx (Proje sunum dosyası)

## 👥 Hazırlayanlar
* Nesrin Güler
* Fatih Kaya
* Kerem Sadık Hacıömeroğlu
