# Ağ
Cihazların birbirleriyle iletişim kurmasını sağlayan yapıdır.
## Bir ağın 3 ana işi vardır:
1-Veri paylaşımı
2-Kaynak paylaşımı
3-İletişim
# Client (İstemci)
İstek gönderen cihazdır.
# Server (Sunucu)
İsteğe cevap veren güçlü bilgisayardır.
İnternette:Her şey REQUEST (istek) ve RESPONSE (cevap) mantığıyla çalışır.
# IP Adresi(Internet Protocol Address)
Ağdaki her cihazın benzersiz kimliği / adresi.
## IP Nasıl Görünür?
4 parçadan oluşur.Her bölüm 0 – 255 arasında olur.
En yaygın format (IPv4):192.168.1.1
2 Tür IP Vardır.
1️-Private IP (Yerel IP):Evindeki cihazlara verilir.Sadece ev ağında çalışır.İnternette görünmez.Telefon, laptop bunu kullanır.
2-Public IP (Genel IP):İnternette seni temsil eden adrestir.Modemine verilir.Evde 10 cihaz olabilir,ama dış dünyaya tek IP görünür.
# NAT 
Private IP adreslerini tek bir Public IP üzerinden internete çıkaran çeviri sistemidir.
Bu işi yapan cihaz:Router / Modem
# DNS(Domain Name System)
Domain isimlerini (google.com gibi) IP adreslerine çeviren sistemdir.
# Router
DNS değildir,ama DNS isteğini internete iletir
# Packet(Paket) 
İnternette gönderilen hiçbir veri tek parça halinde gitmez.Tüm veriler küçük veri parçalarına bölünür.
Bu parçalara Packet (Veri Paketi) denir.
Her paket şunları taşır:Gönderen IP,Alıcı IP,Paket numarası,Veri parçası
# TCP(Transmission Control Protocol)
Verinin eksiksiz ve doğru şekilde ulaşmasını garanti eden iletişim protokolüdür.
Paket kaybolursa tekrar gönderir.Sıra karışırsa düzeltir.Eksik veri varsa bekler.
TCP bağlantı kurmadan veri göndermez.
## TCP Nerelerde Kullanılır?
Hata kabul edilmeyen yerlerde:
Web siteleri (HTTP / HTTPS),Login işlemleri,Dosya indirme,E-posta
Çünkü veri tam gelmek zorunda.
## Ama her Şey TCP Kullanmaz…
Bazı durumlarda hız, doğruluktan daha önemlidir.
Örnek:Online oyun,Canlı yayın,Görüntülü konuşma
Burada başka bir protokol kullanılır:
# UDP 
UDP kaybolan veri olursa göndermez,devam eder
# OSI (Open Systems Interconnection) 
Ağ iletişimini anlamak ve standartlaştırmak için oluşturulmuş 7 katmanlı modeldir.
# MAC Address 
Ağ kartına üretim sırasında verilen fiziksel ve benzersiz donanım adresidir.
IP adresi değişebilir ama MAC adresi:cihazın kimliğidir,fabrikada atanır,normalde değişmez
# Hub
Hub eski bir ağ cihazıdır.Gelen veriyi herkese gönderir.
# Switch = akıllı hub.
MAC adreslerine bakarak veriyi sadece doğru cihaza gönderen cihazdır.
# Ping 
Ping, iki cihaz arasında bağlantı olup olmadığını test eder.
# Traceroute 
Paketin hedefe giderken hangi cihazlardan geçtiğini gösterir.
# nslookup Nedir?

Bu tamamen DNS test aracıdır.Domain adının hangi IP adresine çözüldüğünü gösterir.

