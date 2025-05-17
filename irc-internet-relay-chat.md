# IRC (Internet Relay Chat)

### IRC (Internet Relay Chat) Nedir?

IRC (Internet Relay Chat; İnternet Aktarmalı Sohbet), kullanıcıların birbirleriyle anlık olarak sohbet edebildiği bir iletişim protokolüdür. Aslen 1988 yılında Finlandiya'da Oulu Üniversitesi öğrencisi Jarkko Oikarinen tarafından geliştirilmiş olup günümüze kadar varlığını sürdürmüştür. IRC, esasen bir sunucu ve istemci ağından oluşur. Bu ağ, farklı sunuculardaki kullanıcıların birbirleriyle iletişim kurabilmeleri ve aynı sohbet kanallarında buluşabilmeleri için tasarlanmıştır. Özel mesajlar aracılığıyla birebir iletişim, sohbet, veri aktarımı ve dosya paylaşımına olanak tanır. Zamanının en popüler sohbet ağlarından biri olmasına rağmen, günümüzde popülerliğini yitirmiştir. Bunun sebepleri arasında görselliğe çok fazla hitap etmemesi ve diğer sohbet sistemlerine kıyasla arkasında büyük yazılım şirketlerinin değil, basit firmaların ya da toplulukların bulunması sayılabilir.

### IRC Bağlantısı Nasıl Uygulanır?

IRC protokolü, temelde socket programlama kullanılarak gerçekleştirilir. Bunun nedeni, TCP/IP tabanlı bir protokol olması ve socket programlama yoluyla sunuculara bağlanma, veri gönderme ve veri alma işlemlerinin yapılabilmesidir. Socket programlama, ağ iletişimini sağlamak için kullanılan bir yöntemdir. Bir soket, bir ağ üzerindeki iki nokta arasındaki iletişimi temsil eder. Socket'ler, IRC sunucularında daha esnek ve özelleştirilmiş bir etkileşim sağlar. IRC sunucuları da birer ağ noktasıdır ve kullanıcıların bu noktalara bağlanarak iletişim kurmalarına izin verir. Yani her şey bir sunucuya bağlanır, sunucu verileri kendi yapısına göre işler ve geri iletir. IRC, diğer mesajlaşma sistemlerinden bu noktada ayrılır; diğer sistemler bağlantılar arasında bir aracı köprü kurmazken, IRC'de bu köprü yapısı mevcuttur.

<figure><img src="../.gitbook/assets/img1.jpeg" alt=""><figcaption><p>IRC ağı</p></figcaption></figure>

### IRC Server ve Client Nedir?

IRC kanallarına bağlanmak istediğinizde mutlaka bir Client (bağlantı programı) kullanmanız gerekmektedir. Client, bir ağ üzerinde sunucu bilgisayarlardan hizmet alan kullanıcı bilgisayarıdır. Bu client'lar, kullanıcıların sunuculara bağlanarak kanallar veya özel mesajlar aracılığıyla birbirleriyle iletişim kurmalarını sağlar. Bazı IRC servisleri, web üzerinden bir client sunarak kişilerin sohbete ulaşmasını sağlarken, bazıları sadece IRC client üzerinden bağlantı kurmanıza izin verir.

IRC sunucuları (server), kullanıcıların IRC ağına bağlanmasına izin verir ve mesajlarını, kanal bilgilerini ve diğer verilerini iletir. Bilgiye erişim yetkileri sunucu tarafından belirlenir. Genellikle dağıtık bir yapıda çalışır ve birden fazla sunucu arasında veri senkronizasyonu sağlamak için protokoller kullanır. Bu protokoller, genellikle IRC protokolü olarak bilinen standart bir metin tabanlı protokol üzerinden gerçekleştirilir.

Bazı sunucularda, kullanıcı adı (nickname) ve şifre gibi kimlik doğrulama bilgileri gereklidir. Sunuculara giriş yaptıktan sonra, IRC komutları kullanarak kanallara katılabilir, diğer kullanıcılara mesaj gönderebilir ve birçok IRC işlemini gerçekleştirebilirsiniz.

<figure><img src="../.gitbook/assets/img2.webp" alt=""><figcaption><p>IRC Server ve Client Yapısı</p></figcaption></figure>

#### IRC Server ve Client Yapısı

* **mIRC**: mIRC, programı icat eden kişinin baş harflerinden oluşur: Mardam Khaled Internet Relay Chat. Ne yazık ki, Mardam Khaled bu icadının getirdiği şöhret ve paraya mağlup olmuştur. İlk yıllarında altın çağını yaşayan bu istemci program, Facebook'un gündeme girmesiyle eski popülerliğini yitirmiştir. mIRC, en basit anlatımla sohbet programlarının ilk versiyonudur ve IRC sunucularına bağlanarak sohbet etmeyi sağlar. Bu konuda uzman kişiler, programdaki hazır komutları güncelleyebilir ve düzenleyebilir, böylece kullanıcılarına birçok hazır seçenek sunar. Windows tabanlı bir IRC istemcisidir ve ücretlidir.Comment
* **HexChat**: HexChat, XChat yazılımından çatallanmış bir IRC istemcisidir. Çoklu sunucu desteği ve sayısız özelleştirme imkânı gibi özelliklere sahiptir. Windows, macOS ve Linux gibi farklı platformlarda çalışabilen, ücretsiz ve açık kaynak kodlu bir IRC istemcisidir. Kullanıcı dostu bir arayüze sahip olup pek çok özelliği destekler.Comment
* **Irssi**: Linux ve macOS gibi Unix tabanlı sistemlerde kullanılabilen ücretsiz ve açık kaynak kodlu bir IRC istemcisidir. Linux üzerinde konsol tabanlı bir istemci olan Irssi, görevini başarıyla yerine getiren bir IRC istemcisidir.Comment
* **WeeChat**: Linux, macOS, BSD ve Windows gibi farklı platformlarda çalışabilen, ücretsiz ve açık kaynak kodlu bir IRC istemcisidir. Komut satırı tabanlı bir arayüze sahiptir.

#### Geçmişten Günümüze Popüler Sunucular

* **EFnet**, 1990'dan günümüze
* **Undernet**, 1992'den günümüze
* **DALnet**, 1994'ten günümüze
* **freenode**, 1995'ten günümüze
* **IRCnet**, 1996'dan günümüze
* **QuakeNet**, 1997'den günümüze
* **Open and Free Technology Community**, 2001'den günümüze
* **Rizon**, 2002'den günümüze
* **Libera Chat**, 2021'den günümüze

### IRC Komutları

IRC, bir sanal oda üzerinde kullanılan sohbet yazılımı olduğundan, sohbet ederken bazı komutlar kullanarak istediğiniz işlevleri gerçekleştirebilirsiniz. Örneğin, rastgele bir nick ile giriş yaptıktan sonra:

```bash
/ns register şifre email-adresi
```

komutunu kendinize göre doldurup Enter'a bastıktan sonra bu nick'i sunucuya sizin olarak kaydedebilir, böylece bir sonraki ziyaretlerinizde aynı nick'i kullanarak karışıklıkları önleyebilirsiniz.

Yukarıda gösterdiğimiz örnek gibi, IRC sunucularında kullanılabilen birçok farklı komut bulunmaktadır. Bu komutlar, sunucudan sunucuya değişiklik gösterebilir. Bir IRC sunucusundayken:

```bash
/help veya /raw help
```

komutlarını yazıp Enter'a bastıktan sonra o sunucuda hangi komutların kullanılabileceğini ve bu komutların ne işe yaradığını öğrenebilirsiniz.

Birkaç komut örneği vermek gerekirse:

* **/JOIN Komutu**\
  Kullanıcı, “/join #kanaladı” şeklinde bir komutla belirli bir kanala katılabilir.
* **/NICK Komutu**\
  Kullanıcı, “/nick nickname” şeklinde bir komutla takma adını değiştirebilir.
* **/MSG Komutu**\
  /msg kullanıcıadı mesaj komutuyla özel mesaj gönderebilir.
* **/QUIT Komutu**\
  Kullanıcı, "/quit" komutunu kullanarak IRC ağından çıkabilir.

### **Dark Web'de IRC Kullanımı: Tor ve I2P Üzerinden Anonim İletişim**

#### 1. Onion IRC

Dark Web üzerindeki IRC (Internet Relay Chat) ağlarına bağlanmak için Tor proxy'si kullanabilirsiniz. Bunun için HexChat veya Irssi gibi bir IRC istemcisiyle aşağıdaki adımları takip edebilirsiniz:

* Tor ağına bağlanın.
* IRC istemcinizin SOCKS5 proxy ayarlarını yapılandırın.
* Örnek bağlantı: `irc://exampleonion.onion`
* HexChat için Tor proxy ayarları:

```
/set proxy_type 5
/set proxy_host 127.0.0.1
/set proxy_port 9050
/server add -ssl irc.exampleonion.onion 6697
```

#### 2. I2P IRC Ağları

I2P (Invisible Internet Project), kullanıcılarına daha fazla anonimlik sağlayan bir ağdır. I2P üzerindeki IRC sunucuları, dış dünyayla doğrudan bağlantı kurmadan iletişim imkânı sunar.

**Özellikler:**

* Uçtan uca şifreleme sunar.
* I2P ağı dışındaki kullanıcılarla doğrudan iletişim sağlanamaz.
* Yerel bir proxy başlatarak erişim sağlanır.

**Bağlantı Örnekleri:**

* `irc.example.i2p`
* `irc.example2.i2p`

#### 3. Freenet Üzerinden IRC

Freenet, merkeziyetsiz bir ağ olup, sansüre karşı dayanıklıdır. Üzerinde çalışan bazı IRC servisleri de bulunmaktadır, ancak bunların erişilebilirliği değişkenlik gösterebilir.

#### 4. ZeroNet ve IRC

ZeroNet, merkeziyetsiz ve P2P tabanlı bir iletişim ağıdır. Bu ağda, IRC benzeri sohbet sistemleri mevcuttur.

**Özellikleri:**

* Sansüre dayanıklı, merkeziyetsiz sohbet sistemleri sunar.
* Dark Web kullanıcıları tarafından güvenli bir iletişim alternatifi olarak tercih edilir.

#### 5. Özel IRC Ağları

Dark Web üzerindeki bazı IRC ağları, yalnızca belirli kullanıcıların erişebileceği özel platformlar olarak çalışır.

**a) HiddenIRC**

**Özellikler:**

* Şifre korumalı kanallar içerir.
* Kullanıcıların gerçek IP adreslerini gizler.
* Giriş sırasında genellikle PGP anahtarlarıyla kimlik doğrulama gerektirir.

**b) IRC Network "The Hub"**

**Özellikler:**

* Yüksek güvenlik seviyesine sahip protokoller kullanır.
* Kapalı bir topluluk tarafından işletilir.
* Anonim ticaret kanallarına sahiptir.

#### 6. Dark Web IRC Bağlantı Senaryosu

**Tor Üzerinden Bağlantı:**

1. Tor Browser veya Tor servislerini çalıştırın.
2. HexChat veya Irssi gibi bir IRC istemcisi yükleyin.
3. Aşağıdaki komutlarla bir sunucuya bağlanın:

```bash
/server irc.exampleonion.onion 6667
```

4. SSL kullanımı için:

```bash
/server -ssl irc.exampleonion.onion 6697
```

#### 7. IRC Güvenlik ve Anonimlik Araçları

**ZNC (Bouncer)**

ZNC, kullanıcıların bağlantılarını anonim hale getirerek oturum yönetimi sağlar.

**Avantajları:**

* Çevrimdışıyken gelen mesajları depolar.
* Tüm bağlantıları Tor veya I2P üzerinden yönlendirir.

**OTR (Off-the-Record Messaging)**

IRC istemcileri için uçtan uca şifreleme sağlayan bir güvenlik protokolüdür.

**Özellikler:**

* Mesajlar sadece alıcı ve gönderici tarafından çözülebilir.
* İnkar edilebilirlik özelliği sayesinde mesajların yazıldığı kanıtlanamaz.

#### 8. IRC Alternatifleri

Dark Web kullanıcıları için IRC dışında da güvenli iletişim sağlayan alternatifler mevcuttur:

* **Matrix Protokolü:** Modern, güvenli ve merkeziyetsiz bir iletişim protokolüdür.
* **RetroShare:** P2P tabanlı, uçtan uca şifreli bir iletişim ve dosya paylaşım platformudur.
* **Briar:** Tor üzerinden çalışan, merkeziyetsiz mesajlaşma ve forum uygulamasıdır.

#### 9. Dark Web'deki Önemli IRC Ağları

Dark Web üzerinde bilinen bazı IRC ağları şunlardır:

* BlackBook
* Torbook
* The Campfire
* Lucky Eddie’s Home
* MadIRC Chat Server

Dark Web üzerindeki IRC ağları, kullanıcıların anonim şekilde iletişim kurmasını sağlar. Tor ve I2P gibi anonim ağlar aracılığıyla bu sunuculara bağlanarak, sansüre dayanıklı ve güvenli bir sohbet ortamı oluşturabilirsiniz. Ancak, bu tür platformları kullanırken güvenlik önlemlerine dikkat etmek büyük önem taşımaktadır.

{% @github-files/github-code-block url="https://github.com/emircanaltuntas" %}



***
