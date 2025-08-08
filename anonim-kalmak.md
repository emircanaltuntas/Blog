---
layout:
  width: default
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
---

# Anonim Kalmak

## NASIL ANONİM OLURUZ?

İnternette kesin olarak tamamen gizli olmak diye bir şey yoktur. Örneğin, bir\
bankayı veya benzeri bir kurumu hacklerseniz, ne kullanırsanız kullanın\
yakalanma ihtimaliniz her zaman vardır. Ancak, yasa dışı işler yapmamakla\
birlikte gizliliğinizi artırmak için Tor tarayıcı, anonim e-posta servisleri ve\
NordVPN gibi log tutmayan VPN hizmetlerini kullanabilirsiniz.

<figure><img src=".gitbook/assets/tor-vs-vpn.avif" alt=""><figcaption></figcaption></figure>

Gizliliği bir üst seviyeye taşımak isteyen kullanıcılar için VDS (Virtual Dedicated Server) kullanımı daha güvenli ve etkili bir seçenek sunar.

### VDS ne işe yarar?

VDS (Virtual Dedicated Server), kullanıcıya özel kaynaklar sunarak web sitesi barındırma, uygulama çalıştırma, VPN kurma ve veri güvenliğini artırma gibi işlemlerde yüksek performans ve gizlilik sağlar.

VDS kullanmanın en önemli avantajlarından biri, bir web sitesinde IP engeliyle karşılaşıldığında, proxy ayarlarını sadece birkaç dakika içinde değiştirerek yeni bir IP adresiyle erişimin yeniden sağlanabilmesidir. Bu sayede bağlantılar hızlı, esnek ve güvenli bir şekilde yönetilebilir.

<figure><img src=".gitbook/assets/VDS-Cesitleri-1024x576.webp" alt=""><figcaption></figcaption></figure>

#### Nereden Satın Alınabilir?

* Microsoft Azure
* Amazon Web Services (AWS)
* DigitalOcean
* Vultr
* Hetzner
* Linode
* OVHcloud
* Contabo

## Nasıl Tespit Edilirsiniz?

**"VPN veya Tor kullanıyorum, kimse beni bulamaz."** düşüncesindeyseniz, aşağıdaki senaryoyu dikkatle inceleyin:

1. Örnek bir durumda, bir kişi sosyal medya üzerinden (örneğin Instagram) bir başka kullanıcıya hakaret veya tehdit gibi bir eylemde bulundu.
2. Mağdur kişi, bu eylemi delilleriyle birlikte savcılığa şikâyet etti.
3. Savcılık, Siber Suçlarla Mücadele Birimi aracılığıyla Instagram'ın bağlı olduğu Meta şirketine resmi bir e-posta göndererek, şikâyet konusu hesaba ait giriş bilgilerini talep eder.
4. Instagram, ilgili tarihte hesaba hangi IP adresiyle giriş yapıldığını ve hesaba kayıtlı e-posta adresini bildirir. Örneğin:\
   “Random” kullanıcı adlı hesaba 198.\*\*_._.\* IP adresi ile erişilmiş, kayıtlı e-posta adresi de _random@gmail.com_ olarak iletilir.
5. Polis, IP adresinin bir VPN hizmetine ait olduğunu fark eder. VPN şirketine, resmi bir yazıyla şu bilgileri sorar:\
   “Bu IP adresini hangi kullanıcıya tahsis ettiniz? Bahsi geçen tarihte bu VPN hizmetine hangi gerçek IP adresiyle bağlantı sağlandı?”
6. Eğer kullanılan VPN hizmeti ücretsiz veya güvenlik konusunda zayıf bir sağlayıcıysa, bu bilgiler yetkililerle paylaşılır. Örneğin:\
   “random@gmail.com adresi ile üye olan kişi, 30 Şubat günü 198.\*\*_._.\* IP adresiyle VPN’e bağlanmıştır.”
7. Bu gerçek IP adresi, internet servis sağlayıcısına (ISS) iletilir. Polis, resmi bir talep veya mahkeme kararıyla bu IP’yi kimin kullandığını öğrenmek ister.\
   Servis sağlayıcı da bağlantı bilgilerini (isim, adres, tarih/saat gibi) resmi kurumlara sunar.

**Sonuç:**

Bir süre sonra, adınıza düzenlenmiş bir tebligat PTT aracılığıyla size ulaşır. Tebligatta savcılık tarafından ifadeye çağrıldığınız belirtilir. Bazı durumlarda ise doğrudan evinize polis gelip sizi gözaltına alabilir.

<figure><img src=".gitbook/assets/2139598-0-16453100-1745553794-hacker-handcuffs-laptop-cybercrime-cyber-crime-arrested-100937828-orig.webp" alt=""><figcaption></figcaption></figure>

**Önemli Not:**

VPN veya Tor gibi araçlar gizliliği artırabilir, ancak tamamen anonimlik sağladıklarını düşünmek yanlıştır. Uzmanlara göre, yasal yollarla yapılan teknik takipler sonucu kimliğinize ulaşılması mümkündür.

Anonim kalmak, yalnızca ağ trafiğinizi gizlemekle sınırlı değildir; aynı zamanda gerçekleştirdiğiniz tüm işlemleri de gizlemeniz gerekir. Özellikle yasa dışı faaliyetlerde iz bırakmamak isteyen kişiler, tespit edilmemek adına çok katmanlı önlemler alır. İşte bu noktada, hackerların kimliklerini gizleyerek para aklama işlemlerinde kullandıkları bazı temel yöntemler devreye girer.

### Kripto Paralar

Kripto paralar, herhangi bir ülkenin resmi para birimini kullanmadan dijital ortamda alışveriş yapma imkânı sunar ve bu yönüyle anonim işlemler için etkili bir araç görevi görür.

### Kripto Cüzdanlar

Merkeziyetsiz ve KYC (Know Your Customer) gerektirmeyen cüzdanlar, kripto paralarınızı kimlik bilgisi paylaşmadan güvenli bir şekilde saklamanızı sağlar.

### Kripto Borsaları

Merkeziyetsiz ve KYC gerektirmeyen borsalar, kullanıcıların kendi kripto para cüzdanları üzerinden herhangi bir aracıya ihtiyaç duymadan alım-satım işlemleri gerçekleştirmelerine olanak tanır.

<figure><img src=".gitbook/assets/kriptopara-cuzdani-nedir-1068x712.png" alt=""><figcaption></figcaption></figure>

### Anonimlik İçin Kullanılan Bazı Kripto Paralar

#### MONERO

Monero, gizlilik odaklı yapısıyla öne çıkan bir kripto para birimidir. Bitcoin'den temel farkı ise işlem şeffaflığına yaklaşımıdır. Bitcoin ağında, bir kullanıcının başka bir kullanıcıya ne kadar para gönderdiği herkese açık şekilde görüntülenebilirken; Monero, kullanıcı gizliliğini korumak amacıyla bu bilgileri gizler. Monero, işlemleri anonimleştirmek için RingCT (Halka Gizli İşlemler), gizli adresler ve halka imzalar gibi çeşitli güvenlik katmanları kullanarak tam gizlilik sağlar.

#### ZCASH

Zcash, Bitcoin’e kıyasla daha gelişmiş gizlilik özellikleri sunan bir kripto para birimidir. Merkeziyetsiz bir blokzincir teknolojisi üzerine kuruludur ve yalnızca işlem tutarlarını değil, aynı zamanda işlemi gerçekleştiren tarafların kimliklerini de gizleyerek tam anonimlik sağlar.

#### DASH

Dash, merkezsiz yapısıyla öne çıkan bir kripto para birimidir. İşlem hızını artırarak daha işlevsel bir finansal gizlilik sunmayı hedefler. Ayrıca merkezsiz bir fonlama ve yönetim sistemi oluşturarak, Bitcoin'de karşılaşılan bazı sorunlara çözüm getirdiğini savunur.

<figure><img src=".gitbook/assets/xmr-delist2.png" alt=""><figcaption></figcaption></figure>

### Anonimlik İçin Kullanılan Kripto Para Cüzdanları

**Kripto cüzdanları kendi arasında 3 e ayrılır bunlar:**

#### Donanım Cüzdanları (Soğuk Cüzdanlar):

Donanım cüzdanları, diğer adıyla soğuk cüzdanlar, kripto paraları çevrimdışı (offline) olarak sakladıkları için en güvenli saklama yöntemlerinden biridir. İnternete bağlı olmadıkları için hacklenme riskleri son derece düşüktür. Genellikle ücretli olan bu cihazlar, üst düzey şifreleme teknolojileri ile donatılmıştır. Güvenli donanım cüzdanlarına örnek olarak _Ledger Nano X_ ve _Trezor_ verilebilir.

#### Yazılım Cüzdanları:

Yazılım cüzdanları, kripto para kullanıcıları arasında en yaygın kullanılan cüzdan türlerinden biridir. Bilgisayara veya mobil cihaza indirerek kolayca kullanılabilirler. Genellikle KYC (Kimlik Doğrulama) gerektirmeyen bu cüzdanlara örnek olarak _MetaMask_, _Electrum_, _Trust Wallet_, _Phantom_ ve _Solflare_ verilebilir.

#### Mobil Cüzdanlar

Cep telefonunuzda kripto para saklamanıza imkan tanır. Yazılım cüzdanı gibi doğrudan cihazınıza indirebilirsiniz.\
En iyi anonim mobil cüzdan olarak Bread Cüzdan örnek verilebilir.

<figure><img src=".gitbook/assets/hot-cold-wallets.jpg" alt=""><figcaption></figcaption></figure>

{% embed url="https://github.com/emircanaltuntas" %}
Bu makale Emircan Altuntaş tarafından hazırlanmıştır.
{% endembed %}

***
