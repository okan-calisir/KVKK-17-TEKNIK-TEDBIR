# KVKK-17-TEKNIK-TEDBIR

KVKK 17 TEKNİK TEDBİR
<h4>1)Yetkilendirme Matrisinin Oluşturulmuş Olması</h4> 
Yetki matrisi bir nevi görev ve sorumlulukların dağıldığı tablodur. Bunu RACI Matrix adı
verilen uygulamayla kolayca yapabiliyoruz

<h4>2)Erişim Loglarının Tutulması</h4>
Log kayıtları iletişim sağlayan tüm elektronik cihazlar için önemlidir ve güvenlik açısından
siber olayların tespiti için zorunlu kılınmıştır (5651 Sayılı Kanun)

<h4>3)Yetki Kontrolünün Yapılması</h4>
KVKK için yetki kontrolü önemlidir. Her kullanıcı her kaynağa erişmemelidir. Kullanıcının
erişim talebini yetki kontolü yaparak belirliyoruz daha sonra talebe izin veya ret veriyoruz.

<h4>4)Kullanıcı Hesaplarının Yönetilmesi</h4>
Privileged Access Management(PAM) adı verilen Türkçe karşılığı ayrıcalıklı hesap yönetimi
olan PAM, kritik varlıklara erişimi kontrole etmemize, yönetmemize ve izlemememize
yardımcı olan bir çözümdür.

<h4>5)Ağ Güvenliğinin Sağlanması</h4>
NAC(Network Access Control) kullanıcı odaklı ağ tabanı erişim kontrolü sistemidir.
Kullanıcılar ağ sistemine ulaşabilmesi için bazı politikalara tabi tutulur ve bu doğrultuda
denetlenir.
Güvenlik Duvarı Çözümler(FireWall) İç ağa gelen ve iç ağdan çıkan tüm trafiği denetler ve
yetkisiz erişim, zaralı aktivite veya DDOS gibi saldırıları ayıklayarak ağa temiz bir trafik
yollar.
Diğer önlemler ise;
- Siber saldırı engelleme

- Web filtreleme

- Network Filtreleme

- Antivirüs

- Antispam

- Uygulama kontrolü

- Kullanıcı kontrolü

- Trafik Yönlendirme

- Log kayıtları

- VPN

<h4>6)Uygulama Güvenliğini Sağlanması</h4>
Güvenli yazılım geliştirme uygulama güvenliği açısından çok önemlidir. Yazılım hatalarından
yola çıkılabilecek birçok güvenlik açığı barındırabilir. Bunun çözümü olarak statik kod analizi
çözümleri kaynak kodu inceleyerek güvenlik açıklarının tespit edilip kapatılması.

<h4>7)Verilerin Şifrelenmesi</h4>
Eğer açık veri yani şifrelenmemiş veriyi konfigürasyonu düzgün yapılmamış bir network
üzerinden gönderiyorsak bunu arp poisoning atağı ile dinleyip trafiği kendi üzerine rahatlıkla
geçirebilirler.
Bu verileri belirli şifreleme algoritmalarıyla(AES, RSA, DES vb) ile güvenliği sağlanabilir.

<h4>8)Sızma Testlerini Yapılması</h4>
Sızma testleri belli bir rota üzerinden ziyade bir saldırgan gibi düşülerek yapılmalıdır. Sızma
testlerinin amacı zafiyet ve açıklık taramasını içten ve dıştan derinlemesine uygulamak.

<h4>9)Saldırı Tespit ve Önleme Sistemi Olması</h4>
Ağ saldırı tespit sistemi bir saldırgan bilgisayarın sistemine girmeye çalıştığını anlar ve bunu
saldırı olarak algılar NIDS(Network Intrusion Detection System) ağ üzerindeki paketleri
çözer ve kötü amaçlı bir etkinlik varsa bunu izler ve ağ trafiğini analiz eder
Saldırı Tespit Sitemi IDS(Intrusion Detection System) ağlara sistemlere ve uygulamalara
yapılan kötü niyetli saldırı veya ihlalleri tespit eder IDS yalnızca dinleme amaçlı yazılım veya
cihazdır.
Saldırı Önleme Sistemi
IPS(Intrusion Prevention System) dışarıdan gelecek herhangi bir tehdit veya ihlali tesipt
ederek buna cevap verir saldırıya yanıt verme özellikli bir önleme sistemidir.

<h4>10)Loglar İncelenip Yedeklenmesi</h4>
Loglarının incelenip ve yedeklenmesi siber suçları için önem arz etmektedir ve zorunlu
kılınmaktadır.

<h4>11)Veri Maskeleme Yapılması</h4>
Veri maskeleme veritabanında ki hassas ve gizli verilere erişimi engelleyen bir güvenlik
sistemidir bu sistem saldırgana gerçek veri yerine gerçek olamayan verileri gösterir.

<h4>12)Veri Kaybı Önleme Yazılımlarının Yapılması</h4>
Veri Kaybı önleme sistemi(DLP) hassas verilerin işlendiği ve aktarıldığı her türlü kanaldan
kasıtlı veya kasıt dışı sızmasını önleyen yazılımdır
<h4>13)Yedekleme sisteminin Kullanılması
Yedekleme sisteminin kullanılması oldukça önemlidir herhangi bir veri kaybında veya bir
saldırıda verilerin çalınması durumda yedeklenen veriler kullanılabilir.

<h4>14)Güncel Antivirüs</h4>
Sürekli ortaya çıkan siber tehditler yeni yöntemleri beraberinde getirmektedir ve buna karşı
antivirüsler sürekli güncellenerek bu yeni tehdit unsurlarından korunmamızı sağlar.

<h4>15)Verileri Silme Yok Etme gibi İşlemlerin Yapılması</h4>
Kişisel verilerin hukuka uygun olarak işlenmiş olmasına rağmen eğer kişi talebi üzerine
sorumlusu tarafından silinir yok edilir veya anonimleştirilir.

<h4>16)Güvenlik Duvarı</h4>
Güvenlik duvarları(Firewall) iç ve dış trafiği denetlememizi sağlayan cihazlardır bu duvar
sayesinde bilgisayarımızdaki yazılımlar bizim iznimiz dışında bilgi vermez.

<h4>17)Anahtarlama Yöntemi</h4>
Depola ve İlet: Dağıtıcı her bir paketi iletmeden önce ara belleğe alır ve bir kontrol toplamı
oluşturur. Oluşturulan kontrol paketi toplamı pakette kayıtlı olanla uyuşmazsa paketi iletmez
Kestirme: Dağıtıcı veri paketinde sadece MAC bilgisi okur ve iletime başlar Hata kontrolü
yapılmaz
Serbest Parça: Veri paketinin adresleme bilgisinin de içinde olduğu ilk 64 byte okunur ve
paket kontrol toplamı oluşturulmadan iletilir. Ethernetteki minimum veri büyüklüğü 6 byte’a
ulaşmayan paketler süzgeçlenerek silinir.
Uyarlamalı Anahtarlama: Yukarıdaki üç yöntem arasında kendi kendine seçim yapan bir
sistemdir.

