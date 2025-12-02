# siberVatan

Giriş
Bilgi, genellikle, geçerliliği veya doğruluğu varsayılacak şekilde mümkün olan en yüksek kesinlik derecesi ile karakterize edilen, kişiler veya gruplar için mevcut olan bir dizi gerçek.

Ref: Wikipedia

Bilginin en önemli özelliği, bize çevremizdeki dünya hakkında anlam ve bağlam sunmasıdır. Örneğin, bir kitap okuduğumuzda veya birisiyle konuştuğumuzda yeni bilgiler öğrenir, bu bilgileri kullanarak düşüncelerimizi ve davranışlarımızı şekillendiririz.

Bilgi Güvenliği

Bilgi güvenliği, bilgilerin izinsiz kullanımından, izinsiz ifşa edilmesinden, izinsiz yok edilmesinden, izinsiz değiştirilmesinden, bilgilere hasar verilmesinden koruma, veya bilgilere yapılacak olan izinsiz erişimleri engelleme işlemi.

Ref: Wikipedia

Bilgi güvenliğini bilginin yanlış ellerde zarar görmesini önlemek için alınan önlemler bütünü olarak da tanımlayabiliriz.

Bilgi Güvenliği İlkeleri: CIA Üçlüsü

Gizlilik (Confidentiality): Bilginin sadece yetkili kişilerin erişimine açık olması, başkalarının görmesinin önlenmesini sağlar.

Bütünlük (Integrity): Bilginin doğru ve değiştirilmeden kalması, yanlışlıkla ya da kasıtlı olarak bozulmaması anlamına gelir.

Erişilebilirlik (Availability): Bilginin ihtiyaç duyulduğunda, yetkili kullanıcılar tarafından kolayca erişilebilir olmasıdır.

<img width="516" height="486" alt="image" src="https://github.com/user-attachments/assets/0e6001f7-9425-4fd4-95ef-69839907c0f6" />


Bilgi güvenliği, hem fiziksel dokümanların hem de elektronik verilerin korunmasını içerir. Bu, şifreleme tekniklerinden, erişim kontrol sistemlerine, antivirüs yazılımlarına kadar geniş bir yelpazede önlemleri kapsar.

Günümüzde, özellikle internetin yaygın kullanımıyla birlikte, bilgi güvenliği hem bireyler hem de kurumlar için hayati önem taşır.





Sızma Testi Türleri
Sızma testi, sağlanan bilgi düzeyine göre üç ana kategoriye ayrılır; White Box, Grey Box, Black Box.

White Box

Testi gerçekleştirecek ekibe sistem hakkında geniş kapsamlı bilgi ve yetki verilir. Bu yaklaşım, sistem hakkında derinlemesine bir analiz ve test yapılmasını sağlar.

Grey Box

Testi gerçekleştirecek ekibe sistem hakkında kısmi bilgi ve yetki sağlanır. Bu, daha gerçekçi bir test senaryosu oluşturur ve pentesterların kısmi bilgiyle nasıl ilerleyebileceklerini gösterir.

Black Box

Test ekibi, sistem hakkında hiçbir ön bilgiye sahip olmadan testi gerçekleştirir. Bu, gerçek bir saldırganın perspektifinden en gerçekçi senaryoyu sunar.

Sızma Testi Metodolojileri
Sızma testi metodolojileri, güvenlik zafiyetlerini sistematik bir şekilde belirleyip değerlendirmek için kullanılan standartlaşmış yaklaşımlardır. Bu metodolojiler, sızma testlerinin hem etkinliğini hem de verimliliğini artırır.

OWASP

Open Web Application Security Project (OWASP), web uygulamalarının güvenliğini artırma amacı güden küresel bir girişimdir. OWASP sızma testi metodolojisi, web uygulamaları ve hizmetlerindeki güvenlik zafiyetlerini belirlemek, değerlendirmek ve bunlara karşı önlemler almak için bir çerçeve sunar. Bu metodoloji, hem geliştiricilere hem de güvenlik uzmanlarına, uygulamaların güvenliğini sağlama konusunda rehberlik eder.

OSSTMM

Open Source Security Testing Methodology Manual (OSSTMM), bilgi güvenliği testleri için bir metodoloji sunar ve ağ güvenliği, uygulama testleri, ve fiziksel güvenlik denetimleri gibi geniş bir yelpazede uygulanabilir. OSSTMM, güvenlik testlerinin şeffaf, objektif ve tekrarlanabilir bir şekilde yürütülmesini sağlayan detaylı bir metodoloji sağlar. Ayrıca, güvenlik performansının ölçülmesi ve güvenlik duruşunun sürekli olarak iyileştirilmesi için rehberlik eder.

NIST

National Institute of Standards and Technology (NIST) tarafından geliştirilen sızma testi metodolojisi, özellikle devlet kurumları ve büyük ölçekli kuruluşlar için standartlar ve en iyi uygulamalar sunar. NIST'in siber güvenlik metodolojisi, risk yönetimi, güvenlik zafiyetlerinin değerlendirilmesi ve ihlal sonrası olay yönetimi süreçlerini kapsar. Bu metodoloji, kuruluşların kapsamlı bir güvenlik değerlendirmesi yapmalarına ve uyum gerekliliklerini karşılamalarına yardımcı olur.





Temel Bilgiler
Port
Portlar, bilgisayarlar arası iletişimde veri transferi için kullanılan sanal veya fiziksel bağlantı noktalarıdır.

Fiziksel Portlar

Fiziksel portlar, bilgisayarlarda donanımsal olarak bulunan bağlantı noktalarıdır. Örneğin, USB, Ethernet, HDMI ve DisplayPort gibi portlar, çeşitli cihazların bilgisayara bağlanması ve veri transferi için kullanılır.

Sanal Portlar

Sanal portlar, ağ üzerinden iletişimde kullanılan ve bir kısmı belirli bir hizmet veya protokole atanmış 0 ile 65535 arasında değişen numaralardır. İnternet üzerinden yapılan tüm veri transferleri, bu sanal portlar üzerinden gerçekleşir.

Örneğin, web sitelerini ziyaret ederken web sitesinin barındığı sunucunun 80 ya da 443 nolu portuna bağlantı kurarız.

Bazı yaygın olarak kullanılan servisler ve protokoller belirli portlarda çalışır. En sık kullanılan bazı portlar ve servisler aşağıdaki tabloda yer almaktadır.

Port Numarası	Servis / Protokol
21	FTP
22	SSH
23	Telnet
25	SMTP
53	DNS
80	HTTP
443	HTTPS
3306	MySQL
3389	RDP
5432	PostgreSQL
Zafiyet
Zafiyet, bilgisayar sistemlerindeki güvenlik açıklarını ifade eder. Bu açıklar, saldırganların yetkisiz erişim sağlaması, veri çalması veya sistemi zarar verici amaçlar için kullanması riskini barındırır.

OWASP TOP 10: Web uygulamalarındaki en kritik güvenlik zafiyetlerini sıralayan bir liste.

CVE (Common Vulnerabilities and Exposures): Herkese açık, bilinen güvenlik zafiyetlerini ve açıklarını tanımlayan bir dizindir.

CVSS (Common Vulnerability Scoring System): Güvenlik zafiyetlerinin şiddetini ölçmek için kullanılan bir puanlama sistemidir.

Exploit
Exploit (İstismar), bir zafiyetin kötüye kullanılmasını sağlayan kod veya tekniktir. Bu, saldırganların sistemlere izinsiz erişim sağlamasına veya kontrol altına almasına olanak tanır.

PoC (Proof of Concept): Bir zafiyetin istismar edilebilirliğini gösteren demo içerik.

Zero Day: Henüz düzeltme yaması yayınlanmamış ve genel olarak kimsenin henüz bilmediği güvenlik açıkları.

Shell (Kabuk)
Shell, bir işletim sisteminin hizmetlerini kullanıcılara sunan ve arayüz sağlayan bilgisayar programlarıdır.

Bir sistemden shell almak, saldırganın hedef sistem üzerinde komutlar çalıştırmasını sağlayan bir arayüz sağlar.

Bind Shell: Saldırganın hedef makinede bir port açarak doğrudan bağlantı kurup komut çalıştırdığı shell türüdür.

Reverse Shell: Hedef makinenin, saldırganın kontrolündeki bir makineye bağlandığı ve komut çalıştırma imkanı sunduğu shell türüdür.

Web Shell: Web sunucusunda çalıştırılan ve saldırgana uzaktan komut çalıştırma yetkisi veren kötü amaçlı bir script içeren shell türüdür.

IP (Internet Protocol) Adresi
IP adresi, internet üzerindeki cihazların birbirini tanımlamasını ve iletişim kurmasını sağlayan benzersiz numaralardır.

IPv4: 32-bitlik adresleme sistemi kullanır ve yaklaşık 4.3 milyar benzersiz adres sunar.

IPv6: IPv4'ün adresleme kapasitesinin yetersiz kalması üzerine geliştirilmiş, 128-bitlik adresleme sistemi kullanır.


Kaynaklar
Sızma testi çalışmalarınız, sistem sıkılaştırma faaliyetleriniz ve sıklıkla kullanılan siber güvenlik araçları hakkında kılavuz niteliğinde, özenle hazırlanmış rehberlerimizi keşfedin.

Pentesting Tactics
Hem yeni başlayanlar hem de bu alandaki profesyonellere yönelik olarak hazırlanmış, kapsamlı sızma testi süreçlerini yürütmek için ihtiyacınız olan tüm bilgilere erişim sağlayabilirsiniz.

Her bir içerik, sizi pentesting alanındaki çeşitli kullanım senaryolarına yönlendirir ve yeteneklerinizi geliştirmenize yardımcı olacak pratik bilgiler sunar.

Pentesting Tactics'e Göz Atın

Hardening Tactics
Sistemlerinizi, ağlarınızı ve uygulamalarınızı siber tehditlere karşı koruma altına almak için tasarlanmış, kılavuz niteliğindeki sıkılaştırma taktikleri ile savunmalarınızı güçlendirin.

Bu kılavuzlar, altyapınızı daha korunaklı hale getirecek temel güvenlik adımlarını kavramanızı ve uygulamanızı kolaylaştırır. Hızlı ve etkili sıkılaştırma yöntemlerini keşfedin.

Hardening Tactics'e Göz Atın

Tools
Siber güvenlik araçlarına dair kapsamlı bir rehber arıyorsanız, Tools Tactics tam size göre. Bu içerik, çeşitli siber güvenlik araçlarının nasıl kullanılacağına dair özet bilgiler sunar.

Tools Tactics

Discord
Hackviser’ın Discord kanalına katılarak, siber güvenlik konularında yardım alabileceğiniz ve tecrübelerinizi paylaşabileceğiniz bir topluluğun parçası olun. Teknik sorunlarınızda destek alabileceğiniz, benzer ilgi alanlarına sahip kişilerle iletişim kurabileceğiniz bir ortam sunuyoruz.

Linux'a Giriş
Linux işletim sistemine yolculuğumuzun başına hoş geldiniz. Bu bölümde, temel kavramları, tarihçeyi, modern bilişim manzarasında Linux'un önemini ve bu güçlü işletim sisteminin altında yatan ana ilkeleri tanıtmayı amaçlıyoruz.

Linux Nedir?
Linux, 1991 yılında Linus Torvalds tarafından geliştirilen ve hala gelişmeye devam eden, Unix mimarisine dayanan ücretsiz ve açık kaynaklı bir işletim sistemidir (OS). O zamandan beri küresel bir fenomene dönüşen Linux, süper bilgisayarlardan sunuculara, cep telefonlarından kişisel bilgisayarlara kadar her şeyi güçlendirmektedir. Stabilitesi, güvenliği ve esnekliği ile tanınan Linux, hem kişisel hem de profesyonel kullanım için popüler bir seçenektir.

Linux Felsefesi
Linux, işbirliği ve özgürlük ruhunu temsil eder. Gelişimi, aşağıdaki ilkeleri kanıtlar:

Özgürlük: Linux, kullanıcılara yazılımlarını kontrol etme, değiştirme ve yeniden dağıtma özgürlüğü verir. Bu, inovasyon ve güvenlik ortamını teşvik eder.

İşbirliği: Dünya genelinde binlerce geliştirici Linux'a katkıda bulunur, böylece keskin, güvenli ve kullanıcı ihtiyaçlarına duyarlı kalır.

Şeffaflık: Linux'un açık kaynak doğası, mülkiyetli sistemlerle karşılaştırılamayacak bir şeffaflık seviyesi sağlar.

Linux Nasıl Çalışır?
Linux, Windows veya macOS gibi bir işletim sistemidir ancak nasıl çalıştığı ve ücretsiz, açık kaynak doğası açısından farklıdır. Kalbinde Linux çekirdeği bulunur, bu da sistemin temel parçasıdır. Çekirdek (kernel), bilgisayarın donanımını, CPU, bellek ve çevre birimleri gibi yönetmekten sorumludur ve tüm yazılım uygulamalarının fiziksel donanımla etkileşimde bulunmasını sağlar.

Çekirdek, yazılım uygulamaları ile bilgisayarın donanımı arasında bir köprü görevi görerek çalışır. Bir yazılım uygulaması, bir dosyayı kaydetmek veya ekranda bir şey göstermek gibi donanımla ilgili bir şey yapmak istediğinde, bir istek çekirdeğe gönderir. Çekirdek, bu isteği donanımın anlayacağı talimatlara çevirir.

Linux, çoklu görev ve çok kullanıcılı bir ortamı destekler. Bu, birden fazla kullanıcının aynı anda sistemi kullanabilmesi ve her birinin aynı anda birden fazla programı çalıştırabilmesi anlamına gelir. Bu, birçok kişinin farklı görevler için aynı sisteme erişmesi gereken sunucu ortamlarında özellikle yararlıdır.

Linux dosya sistemi, kök dizinden ("/" olarak gösterilir) başlayarak hiyerarşik olarak organize edilmiştir ve alt dizinlere genişler. Bu organizasyon, dosyaları yönetmeyi ve bulmayı kolaylaştırır.

Çekirdeğin etrafında, ek işlevsellik sağlayan birçok yazılım aracı ve kütüphane bulunur. Bunlar, grafik kullanıcı arayüzleri (GUI'ler), sistem yardımcı programları ve uygulama yazılımlarını içerebilir. Kullanıcılar, bu bileşenleri karıştırıp eşleştirerek özel ihtiyaçlarını karşılayan bir Linux dağıtımı oluşturabilir. Linux dağıtımları, çekirdeği bir yazılım seçimi ile paketleyerek kullanıma hazır tam bir işletim sistemi sunar. Popüler Linux dağıtımlarına Ubuntu, Fedora ve CentOS örnek verilebilir.

Linux Mimarisi
Linux işletim sistemi, bilgisayarın kaynaklarını yönetmek ve kullanıcı etkileşimini kolaylaştırmak için birkaç katmandan oluşmaktadır:



Donanım Katmanı (Hardware): Bu, bilgisayarın işlemcisi (CPU), belleği (RAM), depolama için sabit disk ve klavyeler, fareler ve yazıcılar gibi çevre birimlerinden oluşan sistemin fiziksel temelidir.

Çekirdek Katmanı (Kernel): Linux'un kalbinde yer alan çekirdek (kernel), işletim sistemi için hayati öneme sahiptir. Yazılım ile donanım arasında aracı olarak hareket eder. Çekirdek, bellek tahsisi, işlem planlaması (CPU'nun ne zaman ve hangi görevleri gerçekleştireceğine karar verme) ve yazılımdan gelen giriş/çıkış isteklerini yönetme gibi görevleri üstlenir. Bu katman, sistemde çalışan farklı programların ve kullanıcıların birbirlerine müdahale etmemelerini ve çalışmak için gerekli kaynaklara sahip olmalarını sağlar.

Kabuk Katmanı (Shell): Kabuk(shell), çekirdeğin hizmetlerine erişmek için kullanılan kullanıcı arayüzüdür. Genellikle kullanıcıların komutlar yazdığı bir komut satırı arayüzü (CLI) olsa da, grafik kabuklar da vardır. Kabuk, kullanıcıların komut yazarak veya grafik bir arayüz kullanarak programların çalıştırılması, dosya yönetimi ve diğer hizmetlerin talep edilmesi için çekirdekle iletişim kurmalarını sağlar.

Sistem Yardımcı Programı Katmanı (System Utility): Bu katman, bilgisayarda görevleri gerçekleştirmek için gerekli olan çeşitli araçları ve uygulamaları içerir. Sistem yardımcı programları, dosya yönetim araçlarından yazılım yükleyicilere, ağ yapılandırma araçlarına ve daha fazlasına kadar değişebilir. Kullanıcının komutlarını (kabukta girilen veya grafik bir arayüz aracılığıyla) çekirdeğin bu komutları işlemesine köprü görevi görürler.

Özetle, Linux mimarisi, bir bilgisayarın donanımı ile kullanıcının etkinlikleri arasındaki etkileşimi, fiziksel bileşenlerden yazılım uygulamalarına kadar, iyi tanımlanmış bir yönetim ve kontrol katmanı aracılığıyla düzenler.


