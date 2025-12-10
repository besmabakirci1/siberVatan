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
<img width="1720" height="820" alt="image" src="https://github.com/user-attachments/assets/0eae9293-77cb-4813-a9f2-9174a5c0e679" />



Donanım Katmanı (Hardware): Bu, bilgisayarın işlemcisi (CPU), belleği (RAM), depolama için sabit disk ve klavyeler, fareler ve yazıcılar gibi çevre birimlerinden oluşan sistemin fiziksel temelidir.

Çekirdek Katmanı (Kernel): Linux'un kalbinde yer alan çekirdek (kernel), işletim sistemi için hayati öneme sahiptir. Yazılım ile donanım arasında aracı olarak hareket eder. Çekirdek, bellek tahsisi, işlem planlaması (CPU'nun ne zaman ve hangi görevleri gerçekleştireceğine karar verme) ve yazılımdan gelen giriş/çıkış isteklerini yönetme gibi görevleri üstlenir. Bu katman, sistemde çalışan farklı programların ve kullanıcıların birbirlerine müdahale etmemelerini ve çalışmak için gerekli kaynaklara sahip olmalarını sağlar.

Kabuk Katmanı (Shell): Kabuk(shell), çekirdeğin hizmetlerine erişmek için kullanılan kullanıcı arayüzüdür. Genellikle kullanıcıların komutlar yazdığı bir komut satırı arayüzü (CLI) olsa da, grafik kabuklar da vardır. Kabuk, kullanıcıların komut yazarak veya grafik bir arayüz kullanarak programların çalıştırılması, dosya yönetimi ve diğer hizmetlerin talep edilmesi için çekirdekle iletişim kurmalarını sağlar.

Sistem Yardımcı Programı Katmanı (System Utility): Bu katman, bilgisayarda görevleri gerçekleştirmek için gerekli olan çeşitli araçları ve uygulamaları içerir. Sistem yardımcı programları, dosya yönetim araçlarından yazılım yükleyicilere, ağ yapılandırma araçlarına ve daha fazlasına kadar değişebilir. Kullanıcının komutlarını (kabukta girilen veya grafik bir arayüz aracılığıyla) çekirdeğin bu komutları işlemesine köprü görevi görürler.

Özetle, Linux mimarisi, bir bilgisayarın donanımı ile kullanıcının etkinlikleri arasındaki etkileşimi, fiziksel bileşenlerden yazılım uygulamalarına kadar, iyi tanımlanmış bir yönetim ve kontrol katmanı aracılığıyla düzenler.

Linux Dağıtımları
Linux, tek bir işletim sistemi değil, Linux çekirdeği üzerine kurulu açık kaynaklı işletim sistemlerinin bir ailesidir. Bu varyantlar "dağıtımlar" veya "distrolar" olarak bilinir. Her dağıtım, çeşitli kullanıcı türleri, cihazlar ve amaçlar için özelleştirilmiş farklı bir Linux lezzeti sunar. Bu bölüm, Linux dağıtımlarının kavramını, önemini ve popüler distroların örneklerini keşfeder.

Linux Dağıtımları Nedir?
Bir Linux dağıtımı, Linux çekirdeği etrafında inşa edilmiş tam bir işletim sistemidir. Çekirdeği, geniş bir yazılım uygulamaları, kütüphaneler ve isteğe bağlı bir grafik kullanıcı arayüzü (GUI) içerir. Distrolar, kullanım kolaylığı, stabilite, güvenlik veya özelleştirme gibi çeşitli ihtiyaçlara odaklanarak farklı organizasyonlar, topluluklar ve hatta bireyler tarafından geliştirilir.

Neden Farklı Dağıtımlar Var?
Linux dağıtımlarının çeşitliliği, özgürlük ve esneklik felsefesinden kaynaklanır. Farklı kullanıcıların, kişisel bilgisayarlardan sunuculara, başlangıç seviyesinden uzmanlara ve eski donanımlar için hafif sistemlerden modern makineler için özelliklerle dolu ortamlara kadar farklı ihtiyaçları vardır. Dağıtımlar, özel yazılım paketleri, kullanıcı arayüzleri ve yönetim araçları sunarak bu çeşitli gereksinimleri karşılar.

Bir Dağıtımın Temel Bileşenleri
Her dağıtım benzersiz özellikler ve yazılım sunsa da, hepsi birkaç temel bileşeni paylaşır:

Linux Çekirdeği: İşletim sisteminin çekirdeği, donanım kaynaklarını yönetir.
Sistem Kütüphaneleri: Uygulamaların çalışması için temeldir, çekirdekle etkileşim için standart yollar sağlar.
Yazılım Uygulamaları: Sistem yardımcı programlarından son kullanıcı uygulamalarına kadar değişir.
Paket Yöneticisi: Yazılım uygulamalarını ve bileşenlerini yüklemek, güncellemek ve yönetmek için bir araç.
Önyükleyici (Bootloader): Donanımın açılmasından sonra bilgisayarın önyükleme sürecini yöneten yazılım.
Grafik Kullanıcı Arayüzü (GUI): İsteğe bağlı olsa da, çoğu distro kullanım kolaylığı için bir GUI sunar, örneğin GNOME, KDE veya XFCE.
Popüler Linux Dağıtımları
Ubuntu

Hedef Kitle: Başlangıç seviyesindeki ve düzenli masaüstü kullanıcıları.
Özellikler: Kullanıcı dostu, kurulum kolaylığı ve kullanılabilirliğe güçlü bir odaklanma. Geniş dokümantasyon ve topluluk desteği.
Kullanım Durumları: Masaüstleri, sunucular ve bulut.
Fedora

Hedef Kitle: Geliştiriciler ve sistem yöneticileri.
Özellikler: Keskin teknoloji, Linux topluluğu ile yakın uyum, özgür yazılıma güçlü vurgu.
Kullanım Durumları: Geliştirme, sunucu ve iş istasyonu.
CentOS

Hedef Kitle: Sunucular ve kurumsal kullanıcılar.
Özellikler: Stabilite ve uzun vadeli destek, RHEL (Red Hat Enterprise Linux) ile ikili uyumluluk.
Kullanım Durumları: Sunucular, kurumsal ortamlar.
Debian

Hedef Kitle: İleri düzey kullanıcılar ve stabiliteye odaklanan ortamlar.
Özellikler: Geniş paket deposu, katı özgür yazılım kuralları, stabilite.
Kullanım Durumları: Sunucular, masaüstleri, gömülü sistemler.
Arch Linux

Hedef Kitle: Deneyimli kullanıcılar ve meraklılar.
Özellikler: Rolling release modeli, özelleştirmeye ve minimalizme odaklanan kullanıcı merkezli yaklaşım.
Kullanım Durumları: Masaüstleri, geliştirme, kişisel sunucular.
Kali Linux

Hedef Kitle: Güvenlik profesyonelleri ve etik hackerlar.
Özellikler: Penetrasyon testi, güvenlik araştırması, bilgisayar adliyesi ve tersine mühendislik için önceden yüklenmiş geniş bir araç koleksiyonu.
Kullanım Durumları: Güvenlik araştırmaları, penetrasyon testleri ve etik hacking.
Doğru Dağıtımı Seçmek
Doğru dağıtımı seçmek, belirli ihtiyaçlarınıza, uzmanlık düzeyinize ve tercihlerinize bağlıdır. Şu faktörleri göz önünde bulundurun:

Amaç: Masaüstü kullanımı, sunucu, geliştirme vb.
Kullanım Kolaylığı: Başlangıç dostu mu yoksa Linux uzmanlığı gerektiriyor mu?
Destek ve Topluluk: Dokümantasyona, forumlara ve topluluk desteğine erişim.
Donanım Uyumluluğu: Özellikle eski veya özelleşmiş ekipmanlar için donanımınızı destekler.
Yazılım Kullanılabilirliği: İhtiyacınız olan yazılım paketlerinin kullanılabilirliği.
Sonuç olarak, Linux dağıtımları, her seviyeden ve amaç için kullanıcılara geniş bir seçenek yelpazesi sunar. Her distronun benzersiz özelliklerini ve hedef kitlesini anlayarak, ihtiyaçlarınıza en uygun olanı seçebilirsiniz.

Dosya ve Klasör İşlemleri
Linux'un güçlü komut satırı arayüzünde, dosyalar ve klasörlerle çalışmak için birçok komut vardır. Bu bölümde, dosya ve klasör oluşturma, kopyalama, taşıma, silme ve arama işlemlerini nasıl gerçekleştireceğinizi öğreneceksiniz. Ayrıca, dosya ve klasör izinlerini değiştirmek için kullanılan bazı temel komutları inceleyeceğiz.

Dosya ve Klasör Oluşturma

Linux'ta dosya oluşturmak için touch komutu kullanılmaktadır. Bu komut, mevcut dosyaların erişim ve değiştirme zamanlarını güncellemek için de kullanılır, ancak adı verilen dosya yoksa, yeni bir dosya oluşturur.

user@hackerbox:~$ touch readme.txt
Yukarıdaki komut, bulunduğunuz dizinde readme.txt adında boş bir dosya oluşturdu.

Klasör oluşturmak için ise mkdir (make directory) komutu kullanılır.

user@hackerbox:~$ mkdir documents
Bu komut, documents adında yeni bir klasör oluşturur.

Dosya ve Klasörleri Kopyalama

Dosya kopyalamak için cp komutu kullanılır. Komutun genel kullanımı cp kaynak_dosya hedef_dosya şeklindedir.

user@hackerbox:~$ cp readme.txt readme_copy.txt
Bu komut, readme.txt adlı dosyanın bir kopyasını readme_copy.txt adı altında oluşturur.

Klasörler kopyalanırken, -r (recursive) seçeneğinin kullanılması gerekir, bu da klasörün içindeki tüm alt klasörleri ve dosyaları da kopyalar.

user@hackerbox:~$ cp -r documents documents_copy
Bu komut, documents ve içeriğinin tümünü documents_copy adı altında kopyalar.

Dosya ve Klasörleri Taşıma veya Yeniden Adlandırma

Dosyaları taşımak veya yeniden adlandırmak için mv komutu kullanılır. Bu komut, dosya ve klasörleri yeni bir konuma taşırken, aynı zamanda dosya veya klasörleri yeniden adlandırmak için de kullanılabilir.

user@hackerbox:~$ mv readme_copy.txt readme_moved.txt
Bu komut, readme_copy.txt dosyasını readme_moved.txt olarak yeniden adlandırır.

user@hackerbox:~$ mv readme_moved.txt documents/
Bu komut, readme_moved.txt dosyasını documents klasörüne taşır.

Dosya ve Klasörleri Silme

Dosya silmek için rm (remove) komutu kullanılır.

user@hackerbox:~$ rm readme_moved.txt
Bu komut, readme_moved.txt dosyasını siler.

Klasör silmek için ise rm -r komutunu kullanabilirsiniz. Bu komut, klasörün içindeki dosyalar dahil olmak üzere klasörü ve içeriğini siler.

user@hackerbox:~$ rm -r documents
Bu komut, documents klasörünü ve içeriğini siler.


Linux'ta Dosya ve Klasörleri Bulma Yöntemleri
Linux'ta dosya ve klasör arama işlemleri, kullanıcıların dosya sistemleri üzerinde etkili bir şekilde gezinmelerini sağlar. Bu bölümde, find, locate ve which komutları kullanılarak dosya ve klasörleri nasıl bulabileceğinizden bahsedeceğiz. Bu komutlar, farklı senaryolar ve ihtiyaçlar için uygun çözümler sunar.

find Komutu ile Arama
find komutu, belirli kriterlere göre dosya ve klasörleri aramak için kullanılır. Derinlemesine arama yapabilme yeteneği ile, büyük ve karmaşık dosya sistemlerinde etkili sonuçlar üretir.

Temel Kullanım

find [arama yolu] [arama kriteri] [eylem]
İsimle Arama: -name seçeneği ile dosya adına göre arama yapılır.
find / -name "notlar.txt"
Tipine Göre Arama: -type seçeneği ile dosya tipine göre (örneğin, düzenli dosyalar f, dizinler d) arama yapılır.
find /home/user -type d -name "Proje*"
Boyuta Göre Arama: -size seçeneği ile dosyaları boyutlarına göre arama yapabilirsiniz.
find / -size +50M
Değiştirilme Zamanına Göre Arama: -mtime, -atime veya -ctime ile dosyaları zaman kriterlerine göre filtreleyebilirsiniz.
find / -mtime -7
locate Komutu ile Arama
locate komutu, sistemdeki dosyaları bulmak için kullanılır. locate, updatedb adlı bir veritabanını kullanır. Bu veritabanı, sisteminizdeki dosyaların bir dizinini içerir ve locate komutu bu veritabanında hızlı bir şekilde arama yapar.

Temel Kullanım:
locate notlar.txt
locate komutunun hızlı sonuçlar vermesi, dosya sistemindeki değişikliklerin updatedb tarafından periyodik olarak güncellenmesine bağlıdır. Bu yüzden, çok yeni dosyaları bulamayabilir.

which Komutu ile Komut Dosyalarını Bulma
which komutu, belirli bir komutun yolu hakkında bilgi edinmek için kullanılır. Bu, özellikle birden fazla sürümü yüklü olan programların hangisinin kullanıldığını anlamak için faydalıdır.

Temel Kullanım:
which python
Bu komut, python komutunun hangi yolda olduğunu gösterir. Bu, genellikle sistemdeki varsayılan python sürümünün konumunu öğrenmek için kullanılır.

Özet
Linux'ta dosya ve klasör arama işlemleri, find, locate ve which komutları ile kolayca gerçekleştirilebilir. find komutu, derinlemesine ve kriter bazlı aramalar için idealdir. locate komutu, hızlı sonuçlar elde etmek istediğinizde kullanışlıdır ancak en güncel sonuçları sağlamayabilir. which komutu ise, özellikle komutların sistemdeki yerlerini bulmak için kullanılır. Bu araçlar, Linux kullanıcılarının dosya sistemleri üzerinde etkin bir şekilde gezinmelerini ve ihtiyaç duydukları dosyaları ve programları bulmalarını sağlar.

Filtreler
Filtreler, düz metni (bir dosyada saklanan ya da başka bir program tarafından üretilen) standart girdi olarak alan, anlamlı bir biçime dönüştüren ve daha sonra standart çıktı olarak döndüren programlardır. Linux çok sayıda filtreye sahiptir.

Cat
Cat komutunun temel amacı bir veya birden fazla metin dosyasının içeriğini terminalde göstermektir. Bu komutu kullanarak dosya içeriklerini hızlı bir şekilde görüntüleyebilmekteyiz.

root@hackerbox:~$ cat /etc/ssh/sshd_config
# Port 22
# AddressFamily any
# ListenAddress 0.0.0.0
# ListenAddress ::
PermitRootLogin no
PasswordAuthentication yes
PermitEmptyPasswords no
ChallengeResponseAuthentication no
UsePAM yes
Yukarıdaki örnekte, SSH servisinin /etc/ssh/sshd_config yolundaki ayar dosyasının içeriği cat komutu ile ekrana yazdırılmıştır.

Head
head komutu, belirtilen bir dosyanın en başından belirli sayıda satırı görüntülemek için kullanılır. Varsayılan olarak, head komutu dosyanın ilk 10 satırını gösterir, ancak bu sayı -n parametresi ile değiştirilebilir.

Bu komut, dosya içeriğinin tamamını değil, sadece başlangıç kısmını hızlıca gözden geçirmek istediğinizde kullanışlıdır.

root@hackerbox:~$ head -n 3 /var/log/apache2/access.log
192.168.1.1 - - [15/Mar/2024:10:00:00 +0000] "GET /index.html HTTP/1.1" 200 612 "-" "Mozilla/5.0 (Windows NT 10.0; Win64; x64)"
192.168.1.2 - - [15/Mar/2024:10:00:02 +0000] "POST /login.php HTTP/1.1" 200 452 "http://example.com/login" "Mozilla/5.0 (Linux; Android 6.0; Nexus 5 Build/MRA58N)"
192.168.1.3 - - [15/Mar/2024:10:00:03 +0000] "GET /wp-admin HTTP/1.1" 403 497 "-" "Mozilla/5.0 (Macintosh; Intel Mac OS X 10_11_6)"
Yukarıdaki örnekte, Apache2 Web Server servisine ait /var/log/apache2/access.log yolundaki erişim kayıtlarını barındıran dosyanın içeriğinin ilk 3 satırı ekrana yazdırılmıştır.

Tail
tail komutu, belirtilen bir dosyanın sonundan itibaren belirli sayıda satırı görüntülemek için kullanılır. Varsayılan olarak, tail komutu dosyanın son 10 satırını gösterir, ancak bu sayı -n parametresi ile değiştirilebilir.

Bu komut, özellikle log dosyaları gibi sürekli büyüyen dosyaların en son eklenen içeriğini gözlemlemek için son derece yararlıdır.

root@hackerbox:~$ tail -n 3 /var/log/auth.log
Mar 15 12:00:00 servername sshd[23456]: Failed password for invalid user admin from 192.168.1.1 port 54321 ssh2
Mar 15 12:01:00 servername sshd[23457]: Accepted password for user1 from 192.168.1.2 port 65432 ssh2
Mar 15 12:02:00 servername sshd[23458]: Failed password for user2 from 192.168.1.3 port 76543 ssh2
Yukarıdaki örnekte,  auth.log dosyasının son üç satırı ekrana yazdırılmıştır. auth.log dosyası, Linux sisteminde kullanıcı kimlik doğrulama işlemleri ile ilgili olayların kaydedildiği bir log dosyasıdır. Sistemdeki kullanıcı giriş ve çıkışları, sudo komutu kullanımları, SSH oturumları ve diğer kimlik doğrulama ile ilgili olaylar bu dosyaya kaydedilir.

Sort
sort komutu, verilen dosyanın içeriğini alfabetik sıralar.

root@hackerbox:~$ cat names.txt
Bob
Charlie
Alice

root@hackerbox:~$ sort names.txt
Alice
Bob
Charlie
Yukarıdaki örnekte, "names.txt" içerisinde yer alan isimleri "alfabetik" olarak ekrana yazdırdık.

Uniq
uniq komutu, ardışık olarak tekrar eden satırları filtreleyerek dosya içerisindeki benzersiz satırları gösterir.

Genellikle sort komutu ile birlikte kullanılır çünkü tek başına kullanıldığında sadece ardışık olarak tekrar eden satırları tespit eder. Dosyanın tamamındaki tekrarları ele almak için, önce verinin sort komutu ile sıralanması önerilir.

root@hackerbox:~$ cat names.txt
Alice
Charlie
Alice
Bob

root@hackerbox:~$ uniq names.txt
Alice
Charlie
Alice
Bob
Yukarıdaki örnekte, "Alice" ismi names.txt içerisinde iki defa geçmesine rağmen uniq komutu isimleri benzersiz hale getirmemiştir çünkü yalnızca ardışık olarak tekrarlayan satırları benzersizleştirmektedir.

Bu nedenle, ardışık olmayan tekrarlayan satırlar içeren dosyalarda önce tekrarlayan satırların ardışık hale gelmesi için sort komutu ile satırlar alfabetik olarak sıralanır ve sonrasında uniq ile tekrarlayan satırlar silinir.

root@hackerbox:~$ sort names.txt | uniq
Alice
Bob
Charlie
Grep
grep komutu, dosyalar içindeki belirli metin dizelerini aramak, satırları filtrelemek ve eşleşen sonuçları göstermek için kullanılır.

grep çok güçlü bir araçtır ve log dosyaları, konfigürasyon dosyaları veya herhangi bir metin dosyası üzerinde aramalar yapmak için sıkça kullanılır.

root@hackerbox:~$ grep '192.168.1.1' /var/log/apache2/access.log
Bu komut, /var/log/apache2/access.log konumunda bulunan Apache 2 web sunucusuna ait erişim loglarının içerisinde yalnızca IP adresi 192.168.1.1 olan kayıtları ekrana yazdıracaktır.

root@hackerbox:~$ grep '192.168.1.1' /var/log/apache2/access.log
192.168.1.1 - - [15/Mar/2024:10:00:00 +0000] "GET /index.html HTTP/1.1" 200 612 "-" "Mozilla/5.0 (Windows NT 10.0; Win64; x64)"
192.168.1.1 - - [15/Mar/2024:10:00:02 +0000] "POST /login.php HTTP/1.1" 200 452 "http://example.com/login" "Mozilla/5.0 (Linux; Android 6.0; Nexus 5 Build/MRA58N)"
192.168.1.1 - - [15/Mar/2024:10:00:03 +0000] "GET /wp-admin HTTP/1.1" 403 497 "-" "Mozilla/5.0 (Macintosh; Intel Mac OS X 10_11_6)"
Wc
wc (word count) komutu, dosyaların ne kadar büyük olduğunu veya ne kadar veri içerdiğini hızlıca anlamanızı sağlar.

root@hackerbox:~$ wc /etc/passwd
46   67 2544 /etc/passwd
Yukarıdaki örnekte wc komutu, Linux işletim sistemlerindeki kayıtlı kullanıcıların listesini içeren /etc/passwd dosyasının sırasıyla satır, kelime ve toplam karakter sayısını getirmiştir.

Sütun değeri	Açıklama
46	Satır sayısı
67	Kelime sayısı
2544	Karakter sayısı
/etc/passwd	Dosya yolu
wc komutunun farklı parametreleri de bulunmaktadır:

-l: Sadece satır sayısını gösterir.
-w: Sadece kelime sayısını gösterir.
-c: Sadece bayt cinsinden karakter sayısını gösterir.
-m: Sadece karakter sayısını gösterir (çok baytlı karakter setleri için).
Örneğin, Apache 2 web sunucusunun bugüne kadar kaydettiği log kayıtlarının toplam kaç satır olduğunu görmek istersek,-l parametresini kullanarak  aşağıdaki komutu çalıştırabiliriz:

root@hackerbox:~$ wc -l /var/log/apache2/access.log
54230 /var/log/apache2/access.log
Yukarıdaki çıktıdan toplam 54230 satır log kaydı mevcut olduğu anlaşılmaktadır.

Sed
sed (stream editor) komutu metinleri işlemek, değiştirmek, eklemek, silmek veya dosyalar arasında yer değiştirmek gibi çeşitli metin düzenlemeleri yapabilen bir araçtır.

sed komutu, genellikle metinleri filtrelemek ve dönüştürmek için kullanılır.

root@hackerbox:~$ cat names.txt
Alice
Charlie
Bob

root@hackerbox:~$ sed 's/Alice/George/' names.txt
George
Charlie
Bob
Yukarıdaki örnekte, names.txt içerisinde bulunan Alice ismi, sed komutu yardımıyla George olarak değiştirilmiştir. Ancak, sed komutunun dosyada değişiklik yapmayıp, yalnızca ekrana yeni yapılan değişikliği yazdırmıştır.

Awk
awk komutu metin ve veri işleme görevleri için tasarlanmıştır ve özellikle sütun bazlı verilerle çalışırken oldukça etkilidir. Dosyaları satır satır okuyup, her satırı alanlara (sütunlara) ayırır ve belirtilen koşullara göre işlem yapar. awk, karmaşık metin işlemleri için çok sayıda fonksiyon ve kontrol yapıları sunar.

root@hackerbox:~$ cat names.txt
John Doe
Emily Clark
Alex Turner

root@hackerbox:~$ awk '{print $1}' names.txt
John
Emily
Alex
Bu örnekte, names.txt adlı bir dosya içerisinde üç isim-soyisim çifti bulunmaktadır: John Doe, Emily Clark ve Alex Turner. awk '{print $1}' names.txt komutu, awk programını kullanarak bu dosyanın içeriğini işler. awk, metin dosyalarını satır satır okuyarak her satırı boşluk veya tab karakterlerine göre alanlara ayırır. Bu örnekte {print $1} ifadesi, her satırın ilk alanını (yani ismi) yazdırması talimatını verir.

Paket Yönetimi
Linux işletim sistemlerinin günlük kullanımında ve sistem yönetiminde, yazılım paketlerinin yönetimi kritik bir öneme sahiptir. Linux dağıtımları, yazılım kurulumu, güncellemesi ve kaldırılması gibi işlemleri kolaylaştırmak için çeşitli paket yöneticileri sunar. Bu paket yöneticileri, yazılımları paket formatında, bağımlılıkları ile birlikte yönetmenize olanak tanır.

Her Linux dağıtımı, belirli paket yönetim sistemlerini ve paket formatlarını kullanır. Bu bölümde, Debian tabanlı Linux dağıtımlarında yaygın olarak kullanılan paket yönetim araçlarını ve bu araçların temel kullanımlarını ele alacağız.

Paket Yöneticilerinin Temel Özellikleri
Linux paket yöneticileri, yazılım paketlerinin yönetimi için çeşitli özellikler sunar:

Paket İndirme: Yazılım paketlerini ve bağımlılıklarını internet üzerinden otomatik olarak indirme.
Bağımlılık Çözümleme: Bir paketin gerektirdiği bağımlılıkları belirleme ve bunları otomatik olarak kurma.
Paket Kurulumu ve Kaldırılması: Yazılım paketlerini sisteme kurma ve gerektiğinde kaldırma.
Güncellemeler ve Yükseltmeler: Yüklü paketlerin yeni sürümlerini kontrol etme ve güncelleme.
Yapılandırma Dosyaları ve Dizinleri: Yazılım paketlerinin yapılandırma dosyaları ve dizinleriyle ilgili standartlar sunma.
Advanced Package Manager (APT)
APT (Advanced Package Tool), Debian ve türevleri gibi Linux dağıtımlarında yazılım paketlerini yönetmek için kullanılan güçlü bir araçtır. Bu araç, kullanıcıların yeni yazılımları kolayca kurmalarına, mevcut yazılımları güncellemelerine, gereksiz olanları kaldırmalarına ve tüm bu işlemleri yaparken yazılımlar arasındaki bağımlılıkları otomatik olarak çözümlemelerine olanak tanır. Basit komut satırı komutlarıyla, kullanıcılar sistemlerini güncel ve güvenli tutabilir, aynı zamanda ihtiyaç duydukları yazılımlara hızlıca erişebilirler. APT'nin sunduğu kolaylık ve verimlilik, onu Linux kullanıcıları arasında popüler bir seçenek haline getirmiştir.

Paket Listelerini Güncellemek

apt paket listelerini yerel sisteminizde bir veritabanı içerisinde tutar. Her arama yaptığınızda sunuculara bağlanmaz. Böylelikle daha hızlı sonuç verir ancak aldığınız sonuçlar güncel olmayabilir. Güncel sonuç almak için listelerinizi güncellemeniz gerekir.

apt ile paket listenizi güncellemek için update komutunu kullanabilirsiniz.

user@hackerbox:~$ sudo apt update
Hit:1 http://security.ubuntu.com/ubuntu bionic-security InRelease
Hit:2 http://us.archive.ubuntu.com/ubuntu bionic InRelease
Hit:3 http://us.archive.ubuntu.com/ubuntu bionic-updates InRelease
Hit:4 http://us.archive.ubuntu.com/ubuntu bionic-backports InRelease
Reading package lists... Done
Building dependency tree       
Reading state information... Done
All packages are up to date.
Paket Listelerinde Arama Yapmak

Paket listelerini tutan veritabanını güncellediğimize göre artık paket listeleri içerisinde arama yapabiliriz. Örneğin adında htop geçen bir paket ismi ararsak şöyle arama yapabiliriz.

user@hackerbox:~$ sudo apt search htop
aha - ANSI color to HTML converter
htop - interactive processes viewer
libauthen-oath-perl - Perl module for OATH One Time Passwords
Sonuca bakacak olursak, içinde htop paketinin yer alması dışında, ilgisi olmayan paketler de geldi. Aslında apt search komutu, paketlerin açıklamalarının içerisinde de arama yaptığı için. Örneğin aha paketinin açıklamasına bakarsak htop geçen satırı görebiliriz.

apt search regular expression desteklemektedir. Örneğin sadece htop ile başlayan ifadeler arasaydık şöyle yapabilirdik.

user@hackerbox:~$ sudo apt search ^htop
htop - interactive processes viewer
Veya, sadece isminde htop ifadesi geçen paketleri arayabilirdik.

user@hackerbox:~$ sudo apt search --names-only htop
htop - interactive processes viewer
Paket Yüklemek ve Güncellemek

Bulduğumuz bir paketi yüklemek için apt komutunu kullanabiliriz.

user@hackerbox:~$ sudo apt install htop
Reading package lists... Done
Building dependency tree       
Reading state information... Done
The following NEW packages will be installed:
  htop
0 upgraded, 1 newly installed, 0 to remove and 0 not upgraded.
Need to get 80.0 kB of archives.
After this operation, 201 kB of additional disk space will be used.
Get:1 http://archive.ubuntu.com/ubuntu bionic/universe amd64 htop amd64 2.1.0-3 [80.0 kB]
Fetched 80.0 kB in 1s (110 kB/s)    
Selecting previously unselected package htop.
(Reading database ... 32507 files and directories currently installed.)
Preparing to unpack .../htop_2.1.0-3_amd64.deb ...
Unpacking htop (2.1.0-3) ...
Setting up htop (2.1.0-3) ...
Processing triggers for man-db (2.8.3-2ubuntu0.1) ...
Bu komut aynı zamanda mevcut yüklü bir paketi güncellemeye de yarar. Yüklü bir paketi apt install ile kullanırsak, en son sürüme güncellenecektir.

Eğer sisteminizdeki bütün paketleri güncellemek isterseniz, upgrade komutunu kullanabilirsiniz.

user@hackerbox:~$ sudo apt upgrade
Bu yöntem, ekstra paket yüklemeyecek, veya artık kullanılmayan paket/kütüphaneleri kaldırmayacaktır. Eğer bunu önemsemiyorsanız, dist-upgrade komutunu kullanabilirsiniz.

user@hackerbox:~$ sudo apt dist-upgrade
Paket Kaldırmak

Kaldırma işlemi için remove komutu kullanılabilir.

user@hackerbox:~$ sudo apt remove htop
Reading package lists... Done
Building dependency tree       
Reading state information... Done
The following packages will be REMOVED:
  htop
0 upgraded, 0 newly installed, 1 to remove and 0 not upgraded.
After this operation, 201 kB disk space will be freed.
(Reading database ... 32558 files and directories currently installed.)
Removing htop (2.1.0-3) ...
Processing triggers for man-db (2.8.3-2ubuntu0.1) ...
Yukarıdaki çıktıda, htop paketinin sistemden başarıyla kaldırıldığını ve bu işlem sonucunda 201 kB disk alanının serbest bırakıldığını göstermektedir.

remove komutu, htop için gerekli ayar dosyalarını ve deb dosyalarını kaldırmaz. Eğer bunları da kaldırmak isteseydik, purge komutunu kullanmamız gerekirdi.

user@hackerbox:~$ sudo apt purge htop
Reading package lists... Done
Building dependency tree       
Reading state information... Done
The following packages will be REMOVED:
  htop*
0 upgraded, 0 newly installed, 1 to remove and 0 not upgraded.
After this operation, 201 kB disk space will be freed.
(Reading database ... 32558 files and directories currently installed.)
Removing htop (2.1.0-3) ...
Processing triggers for man-db (2.8.3-2ubuntu0.1) ...
Purging configuration files for htop (2.1.0-3) ...
Kullanıcı Yönetimi
Linux işletim sistemlerinde kullanıcı yönetimi, sistem güvenliği ve kaynakların etkin bir şekilde paylaşımı açısından hayati bir öneme sahiptir. Bu bölümde, Linux'ta kullanıcıların nasıl oluşturulacağı, yönetileceği ve silineceği üzerine odaklanacağız.

Linux'ta Kullanıcı Nedir?
Linux sistemlerinde kullanıcılar, sisteme giriş yaparak çeşitli işlemleri yapan bireyler veya kurumlar olarak tanımlanır. Güvenli erişim kontrolü, kaynak dağılımı ve sistem yönetimi açısından kullanıcı yönetimi büyük önem taşır.

Linux'ta bir kullanıcı, kimliklerini ve sistem içindeki ayrıcalıklarını tanımlayan birkaç özelliğe sahip kullanıcı hesabı ile ilişkilendirilir. Bu özellikler kullanıcı adı, UID (Kullanıcı ID'si), GID (Grup ID'si), ana dizin, varsayılan kabuk ve şifredir.

Her kullanıcı hesabı yukarıda listelenen benzersiz özelliklere sahiptir.

Kullanıcı Türleri
Linux, iki tür kullanıcıyı destekler: sistem kullanıcıları ve normal kullanıcılar.

Sistem kullanıcıları sistem tarafından kurulum sırasında oluşturulur ve sistem servisleri ile uygulamaları çalıştırmak için kullanılır.

Normal kullanıcılar yönetici tarafından oluşturulur ve izinlerine bağlı olarak sisteme ve kaynaklarına erişebilirler.

Kullanıcı Oluşturma
Kullanıcı oluşturmak için useradd komutu kullanılır. Örneğin, "John" isimli bir kullanıcı oluşturmak istersek şu komutu kullanırız:

root@hackerbox:~$ useradd -u 1002 -d /home/john -s /bin/bash john
Bu komutla John için bir kullanıcı hesabı oluşturulur; bu hesap 1002 numaralı kullanıcı kimliğine (UID), /home/john olarak belirlenen bir ana dizine ve varsayılan kabuk olarak /bin/bash'e sahip olacak şekilde ayarlanmıştır.

Oluşturulan yeni kullanıcı hesabını id john komutunu çalıştırarak kontrol edebiliriz. Bu komut, john kullanıcısının ID'sini ve grup üyeliklerini gösterir.

root@hackerbox:~$ id john
uid=1002(john)	gid=1002(john)	groups=1002(john)
Kullanıcı Özellikleri
Linux sistemlerde, kullanıcı hesapları çeşitli özelliklere sahiptir. Bu özellikler, kullanıcıların özelliklerini ve erişim ayrıcalıklarını tanımlar.

Kullanıcı Adı: Her kullanıcıya, Linux sistem içinde tanımlayıcı olarak hizmet eden benzersiz bir kullanıcı adı atanır. Örneğin, John'un kullanıcı adı john olarak belirlenmiştir.
UID (Kullanıcı Kimliği) ve GID (Grup Kimliği): Her kullanıcı hesabı bir UID ve GID ile ilişkilendirilir. UID, kullanıcıya atanmış sayısal bir değerken, GID kullanıcının ait olduğu ana grubu temsil eder. Örneğin, John'un UID'si 1002 ve ana grubunun GID'si de 1002 olabilir.
Ana Dizin: Her kullanıcının kişisel dosya ve ayarlarının bulunduğu belirlenmiş bir ana dizini vardır. John'un ana dizini /home/john'dur.
Varsayılan Kabuk: Varsayılan kabuk, kullanıcı giriş yaptığında kullanılan komut yorumlayıcısını belirler. Bu, kullanıcının etkileşimli ortamını tanımlar. John'un varsayılan kabuğu Linux'ta popüler olan /bin/bash olarak ayarlanmıştır.
Şifre: Kullanıcı hesapları, sisteme erişim ve kimlik doğrulama için şifrelere ihtiyaç duyar.
Grup: Grup üyeliği, kullanıcının hangi sistem kaynaklarına erişebileceğini ve hangi kullanıcıların kullanıcının dosyalarına erişebileceğini belirler.
Linux sistemlerde kayıtlı kullanıcılar /etc/passwd yolundaki dosya içerisinde tutulur. Sistemdeki tüm kullanıcıların listesini görmek için bu dosyanın içeriğini yazdırabiliriz.

root@hackerbox:~$ cat /etc/passwd
root:x:0:0:System Administrator:/root:/bin/bash
john:x:1002:1002:John Doe:/home/johndoe:/bin/bash
/etc/passwd dosyası içerisinde bulunan kullanıcı listesi, aşağıdaki formattaki gibidir:

Sütun Değeri	Açıklama
john	Kullanıcı adı
x	Kullanıcının şifresinin şifrelenmiş halini içerir. Güvenlik nedeniyle, şifre /etc/shadow dosyasında saklandığı için bu alan x karakteri ile değiştirilmiştir.
1002	Kullanıcı hesabının UID'si (Kullanıcı Kimliği), sistemin kullanıcıya atadığı benzersiz sayısal tanımlayıcıdır.
1002	Kullanıcı hesabının GID'si (Grup Kimliği), kullanıcının ana grup üyeliğini temsil eder.
,,,:	GECOS alanı, "General Electric Comprehensive Operating System" anlamına gelir. Bu alan, kullanıcının tam adı veya iletişim bilgileri gibi ek bilgileri saklamak için kullanılır. Bu durumda, kullanıcı hesabı oluşturulurken ek bilgi verilmediği için alan boştur.
/home/john	Kullanıcı hesabının ana dizini, kullanıcının dosyalarının ve kişisel verilerinin saklandığı yerdir.
/bin/bash	Kullanıcı hesabının varsayılan kabuğu, terminalde kullanıcı tarafından girilen komutları işlemek için kullanılan komut yorumlayıcıdır. Bu durumda, varsayılan kabuk Bash'tir, Linux'ta en yaygın kullanılan kabuktur.
Kullanıcı Parolası Değiştirme
Kullanıcıların parolaları passwd komutu ile kolayca değiştirilebilir. Örneğin, john kullanıcısına yeni bir parola atamak için aşağıdaki komutu kullanabiliriz.

root@hackerbox:~$ sudo passwd john
Bu komut interaktif bir şekilde parola girmenizi ister, parolayı tuşladığınızda ekranda bir hareket görülmeyecek. Endişelenmeyin, bastığınız tuşlar güvenlik gerekçesi ile ekrana yansıtılmamaktadır. Yeni parolayı girip ENTER tuşuna basmanız yeterli.

Kullanıcı Silme
John isimli kullanıcıyı ve ilgili dosyaları kaldırmak için userdel komutunu kullanabiliriz.

root@hackerbox:~$ sudo userdel john

Bu komut john kullanıcısının hesabını, ev dizini ve kullanıcının sahip olduğu tüm dosya/dizinlerle birlikte silecektir.

Kullanıcı Yönetimi

Linux işletim sistemlerinde kullanıcı yönetimi, sistem güvenliği ve kaynakların etkin bir şekilde paylaşımı açısından hayati bir öneme sahiptir. Bu bölümde, Linux'ta kullanıcıların nasıl oluşturulacağı, yönetileceği ve silineceği üzerine odaklanacağız.

Kullanıcı Nedir ve Neden Önemlidir?

Linux, doğası gereği çok kullanıcılı (multi-user) bir işletim sistemidir. Bu, aynı bilgisayar üzerinde aynı anda birden fazla kişinin çalışabileceği anlamına gelir.

Kullanıcı Kavramı:

Kimlik (Identity): Her kullanıcının bir adı (username) ve benzersiz bir numarası (UID - User ID) vardır.
İzolasyon: Her kullanıcının kendine ait dosyaları, ayarları ve ev dizini (/home/kullaniciadi) vardır. Bir kullanıcı, izin verilmediği sürece diğerinin dosyalarını göremez.
Yetki (Privilege): Her kullanıcının yapabilecekleri sınırlıdır. Sadece root kullanıcısı (Süper Kullanıcı) her şeyi yapabilir.
Bu yapı, sistemin güvenliğini sağlar. Bir kullanıcı hata yapsa veya virüs bulaştırsa bile, bu durum diğer kullanıcıları veya sistemin genelini etkilemez (tabii ki root yetkisi yoksa).

Kullanıcı Türleri

Linux, iki tür kullanıcıyı destekler: sistem kullanıcıları ve normal kullanıcılar.

Sistem kullanıcıları sistem tarafından kurulum sırasında oluşturulur ve sistem servisleri ile uygulamaları çalıştırmak için kullanılır.

Normal kullanıcılar yönetici tarafından oluşturulur ve izinlerine bağlı olarak sisteme ve kaynaklarına erişebilirler.

1. Kullanıcı Oluşturma

İki komut vardır: adduser (Kolay) ve useradd (Zor).

Önerilen Yöntem (adduser):
Size sorular sorar ve ev dizinini otomatik ayarlar.

user@hackerbox:~$ sudo adduser mehmet
Adding user `mehmet' ...
Adding new group `mehmet' (1001) ...
Adding new user `mehmet' (1001) with group `mehmet' ...
Creating home directory `/home/mehmet' ...
Copying files from `/etc/skel' ...
New password:
Retype new password:
passwd: password updated successfully
Full Name []: Mehmet Yilmaz
Is the information correct? [Y/n] Y
Alternatif Yöntem (useradd):

user@hackerbox:~$ sudo useradd -m -s /bin/bash ali
-m: Ev dizini oluştur.
-s: Shell'i belirle.

2. Kullanıcı Bilgilerini Görme (id, who, w)

Bir kullanıcının kimliğini ve gruplarını görmek için id kullanılır.

user@hackerbox:~$ id mehmet
uid=1001(mehmet) gid=1001(mehmet) groups=1001(mehmet)
Sistemde kimlerin aktif olduğunu görmek için:

who: Kimler bağlı?
user@hackerbox:~$ who
root     pts/0        2023-10-01 10:00 (192.168.1.5)
mehmet   pts/1        2023-10-01 10:05 (192.168.1.6)
w: Kimler ne yapıyor?
user@hackerbox:~$ w
 10:10:01 up 1 day,  2 users,  load average: 0.00, 0.01, 0.05
USER     TTY      FROM             LOGIN@   IDLE   JCPU   PCPU WHAT
root     pts/0    192.168.1.5      10:00    1.00s  0.10s  0.00s w
mehmet   pts/1    192.168.1.6      10:05    2:00   0.05s  0.05s top
last: Kim ne zaman girdi?
user@hackerbox:~$ last
mehmet   pts/1        192.168.1.6      Sun Oct  1 10:05   still logged in
3. Kritik Dosyalar

Kullanıcı yönetiminde bilmeniz gereken üç temel dosya vardır.

a) /etc/passwd Dosyası:

Bu dosya, sistemdeki tüm kullanıcıların temel bilgilerini saklar. Sistemdeki herkes tarafından okunabilir. Her satır bir kullanıcıyı temsil eder ve : ile ayrılmış 7 alandan oluşur.

Örnek Satır:

root@hackerbox:~$ cat /etc/passwd | tail -n 5
cups-pk-helper:x:111:117:user for cups-pk-helper service,,,:/home/cups-pk-helper:/bin/false
gnome-initial-setup:x:112:118::/run/gnome-initial-setup/:/bin/false
gdm:x:113:119:Gnome Display Manager:/var/lib/gdm3:/bin/false
mehmet:x:1001:1001:Mehmet Yilmaz,,,:/home/mehmet:/bin/bash
ali:x:1002:1002::/home/ali:/bin/sh
Alanların Anlamları Tablosu:

Sıra	Alan Adı	Örnek	Açıklama
1	Kullanıcı Adı	mehmet	Sisteme giriş yaparken kullanılan isim. 1-32 karakter arası olmalıdır.
2	Parola	x	Eskiden burada parola yazardı. Şimdi güvenlik için x yazar, asıl parola /etc/shadow dosyasındadır.
3	UID	1001	Kullanıcı Kimlik Numarası (User ID). Root her zaman 0'dır.
4	GID	1001	Grup Kimlik Numarası (Group ID). Kullanıcının birincil grubu.
5	Açıklama	Mehmet Yilmaz,,,	(GECOS) Kullanıcının tam adı, telefon numarası gibi ek bilgiler.
6	Ev Dizini	/home/mehmet	Kullanıcı giriş yaptığında düştüğü dizin.
7	Kabuk (Shell)	/bin/bash	Kullanıcının kullandığı komut yorumlayıcısı.
b) /etc/shadow Dosyası:

Kullanıcıların parolarının hash (kriptolanmış) halini ve parola geçerlilik sürelerini saklar. Güvenlik nedeniyle sadece root kullanıcısı okuyabilir.

Örnek Satır:

mehmet:$6$aB1...:19450:0:99999:7:::
Alanların Anlamları Tablosu:

Alan	Açıklama
Kullanıcı Adı	Kullanıcının oturum açma adı.
Parola Hash'i	$6$ ile başlıyorsa SHA-512 algoritmasıyla şifrelenmiştir. ! veya * varsa hesap kilitlidir.
Son Değişiklik	1 Ocak 1970'ten (Epoch) bu yana geçen gün sayısı.
Min Gün	Parolanın tekrar değiştirilebilmesi için geçmesi gereken minimum gün.
Max Gün	Parolanın geçerli olduğu maksimum gün sayısı (Süresi dolunca değiştirmek zorunludur).
Uyarı	Parola süresi dolmadan kaç gün önce uyarı verileceği.
c) /etc/skel Dizini (Skeleton):

Yeni bir kullanıcı oluşturulduğunda (örneğin useradd -m ile), bu dizinin içindeki her şey yeni kullanıcının ev dizinine kopyalanır.

Örneğin .bashrc dosyasını buraya koyarsanız, yeni açılan her kullanıcının otomatik olarak bu ayarı almasını sağlarsınız.
4. Kullanıcı Yönetimi (usermod)

Mevcut bir kullanıcıyı değiştirmek için kullanılır.

Gruba Ekleme (-aG):

sudo usermod -aG sudo mehmet
(Mehmet artık yönetici yetkisine sahip).

Hesabı Kilitleme (-L):

sudo usermod -L mehmet
(Mehmet artık giriş yapamaz).

Kilidi Açma (-U):

sudo usermod -U mehmet
5. Parola Zamanını Düzenleme (chage)

Kullanıcının parolasını ne zaman değiştirmesi gerektiğini ayarlar.

user@hackerbox:~$ sudo chage -l mehmet
Last password change					: Aug 01, 2023
Password expires					: never
Password inactive					: never
Account expires						: never
Örnek: Parola 90 günde bir değişsin

sudo chage -M 90 mehmet
6. Kullanıcı Silme

sudo userdel -r mehmet
Grup Yönetimi

Linux işletim sistemlerinde, grup yönetimi de kullanıcı yönetimi kadar önem taşır. Gruplar, birden fazla kullanıcıya aynı erişim haklarını ve izinleri toplu olarak atamak için kullanılır. Bu sayede, sistem yöneticileri kaynakların ve erişimin kolayca kontrol edilmesini sağlayabilir. Bu bölümde, Linux'ta grupların nasıl oluşturulacağı, yönetileceği ve silineceği üzerine odaklanacağız.

Grup Nedir ve Neden Kullanılır?

Linux sistemlerinde bir grup, belirli izinlere ve erişim haklarına sahip kullanıcıların topluluğudur. Gruplar, dosya sistemlerindeki erişim kontrolünü kolaylaştırmak ve kullanıcı yönetimini daha verimli hale getirmek için kullanılır.

Bir şirkette çalıştığınızı düşünün. "Muhasebe" departmanındaki 50 kişinin, sadece muhasebe dosyalarına erişmesi gerekiyor. Eğer grup sistemi olmasaydı:

50 kişi için tek tek dosya izni ayarlamanız gerekirdi.
Yeni biri işe başladığında yine tek tek izin vermeniz gerekirdi.
Grup sistemi sayesinde:

Bir "Muhasebe" grubu oluşturursunuz.
Dosyaların iznini bu gruba verirsiniz.
50 kullanıcıyı bu gruba eklersiniz.
Yeni biri geldiğinde sadece gruba eklemeniz yeterlidir.
Özetle gruplar, yetki yönetimini toplu hale getirerek işimizi kolaylaştırır ve güvenliği artırır.

Temel Komutlar

Komut	Açıklama
groupadd	Grup oluşturur.
groupdel	Grubu siler.
groups	Üye olunan grupları gösterir.
getent group	Bir grubun detaylarını gösterir.
/etc/group Dosyası ve Anlamı
Grupların tanımlandığı dosya /etc/group dosyasıdır.

yazilim:x:1002:mehmet,ali
Sütunların Anlamları:

Alan	Örnek	Açıklama
Grup Adı	yazilim	Grubun ismi.
Parola	x	Grup parolası (Genelde kullanılmaz).
GID	1002	Grup Kimlik Numarası (Group ID).
Üyeler	mehmet,ali	Gruba dahil kullanıcıların listesi.
Örnek: Grup Oluşturma ve Sorgulama

user@hackerbox:~$ sudo groupadd yazilim
user@hackerbox:~$ getent group yazilim
yazilim:x:1002:
Gruba Üye Ekleme

En güvenli yöntem usermod -aG kullanmaktır.

Örnek Senaryo: Mehmet'i 'yazilim' grubuna ekle

Önce kontrol edelim:

user@hackerbox:~$ id mehmet
uid=1001(mehmet) gid=1001(mehmet) groups=1001(mehmet)
Ekleyelim:

user@hackerbox:~$ sudo usermod -aG yazilim mehmet
Tekrar kontrol edelim:

user@hackerbox:~$ id mehmet
uid=1001(mehmet) gid=1001(mehmet) groups=1001(mehmet),1002(yazilim)
(Görüldüğü gibi yazilim grubu eklendi).

Dikkat: -a (Append) kullanmazsanız, kullanıcının üye olduğu diğer tüm grupları siler!

Gruba Üye Çıkarma

Kullanıcıyı gruptan çıkarmak için gpasswd kullanılabilir.

user@hackerbox:~$ sudo gpasswd -d mehmet yazilim
Removing user mehmet from group yazilim
Pratik Senaryo: Ortak Proje Dizini

Bir proje dizini yapalım ve sadece proje grubundakiler erişebilsin.

Grubu oluştur:
user@hackerbox:~$ sudo groupadd proje
Kullanıcıyı ekle:
user@hackerbox:~$ sudo usermod -aG proje ali
Dizini oluştur:
user@hackerbox:~$ sudo mkdir /opt/proje
Dizinin grubunu değiştir:
user@hackerbox:~$ sudo chown :proje /opt/proje
İzinleri ayarla:
user@hackerbox:~$ sudo chmod 770 /opt/proje
(Sahibi ve Grup tam yetkili, diğerleri giremez).

İzinler

İzin Nedir ve Neden Önemlidir?

Linux, çok kullanıcılı bir sistem olduğu için her dosyanın kime ait olduğu ve kimin o dosyayla ne yapabileceği sıkı kurallara bağlanmıştır. Bu kurallara Dosya İzinleri denir.

Neden İzinler Var?

Gizlilik: Kişisel dosyalarınızı (örneğin e-postalarınızı) başka kullanıcıların okumasını engellemek için.
Bütünlük: Önemli sistem dosyalarının yetkisiz kişilerce değiştirilmesini veya silinmesini önlemek için.
Güvenlik: Kötü amaçlı bir yazılımın (virüs vb.) sistem genelinde çalışmasını ve yayılmasını engellemek için.
Eğer izinler olmasaydı, herhangi bir kullanıcı sistemdeki kritik bir dosyayı silebilir ve sistemi çökertebilirdi.

1. İzinleri Okuma

Linux dosya sisteminde her dosya ve dizinin, sistemdeki kullanıcılar tarafından nasıl erişilebileceğini belirleyen izinleri vardır. Bu izinler, dosyanın güvenliğini ve bütünlüğünü sağlamak için kritiktir. İzin yapısını anlamak için ls -l komutunun çıktısını detaylıca incelememiz gerekir.

root@hackerbox:~$ ls -l
-rwxr--r-- 2 john development 4096 Jul  29 12:34 notes.txt
ls -l çıktısı örneği: -rwxr--r--

Bu ifade, aslında bir dizi karakterden oluşur ve her karakterin özel bir anlamı vardır.

-l parametresi ile elde ettiğimiz çıktıdaki sütunların açıklamaları aşağıdaki gibidir:

Sütun içeriği	Açıklama
d	Dosya türü. Eğer dizin ise d, dosya ise - karakteri ile gösterilir. Bu örnekte d karakteri olduğu için bu bir dizin.
rwxr--r--	Dosya izinleri
2	Dosyaya/dizine verilen sabit bağlantı (hard link) sayısı
john	Dosya/dizinin sahibi olan kullanıcı
development	Dosya/dizinin sahibi olan grup
4096	Dosyanın boyutu veya dizin bilgilerini saklamak için kullanılan blok sayısı
Jul 29 12:34	Dosya/dizinin oluşturulma veya son düzenlenme tarihi
notex.txt	Dosya/dizinin ismi
r, w, x ve - Karakterleri
İzinler temel olarak üç farklı yetki türü ve bir de yetkisizlik durumu ile ifade edilir:

r (Read): Dosyanın içeriğini okuma iznini ifade eder. Eğer bu izin bir dizin (dizin) için verilmişse, o dizinin içindeki dosyaları listeleme (ls) yetkisi verir.
w (Write): Dosyanın içeriğine yazma veya dosyayı düzenleyebilme iznini ifade eder. Bir dosya üzerinde değişiklik yapmak, içeriğini silmek veya üzerine yazmak için bu izne ihtiyaç vardır. Dizinler için ise, o dizinin içine yeni dosya oluşturma veya silme yetkisi verir.
x (Execute): Dosyayı çalıştırabilme iznini ifade eder. Bu izin, genellikle scriptler (komut dosyaları) veya derlenmiş programlar için verilir. Eğer bir dosya çalıştırılabilir bir programsa ancak x izni yoksa, sistem bu dosyanın çalışmasına izin vermez. Dizinler için ise, o dizinin içine erişim (cd ile girme) yetkisi verir.
- (Tire): Eğer r, w veya x karakterlerinden herhangi biri yerine - yazılmışsa, o pozisyondaki izin verilmemiş demektir.
Kullanıcı, Grup ve Diğer (User, Group, Others)
Linux izin sistemi, yetkileri üç farklı kitleye böler. ls -l çıktısındaki 10 karakterlik izin dizisinin ilk karakteri dosya tipini belirtirken, geri kalan 9 karakter üçerli gruplar halinde bu kitleleri temsil eder:

---         ---     ---
rwx         rwx     rwx
kullanıcı   grup    diğer
Kullanıcı (User - u):

İzin dizisinin ilk üçlü grubudur (2, 3 ve 4. karakterler).
Dosyanın veya dizinin sahibi olan kullanıcının yetkilerini ifade eder.
Genellikle dosyayı oluşturan kişi sahibidir.
Grup (Group - g):

İzin dizisinin ikinci üçlü grubudur (5, 6 ve 7. karakterler).
Dosyanın atandığı gruba dahil olan tüm kullanıcıların yetkilerini ifade eder.
Bu özellik, bir proje üzerinde çalışan birden fazla kullanıcının aynı dosyalara erişebilmesi için kullanılır.
Diğer (Others - o):

İzin dizisinin son üçlü grubudur (8, 9 ve 10. karakterler).
Sistemde bulunan, dosyanın sahibi olmayan ve dosyanın grubuna dahil olmayan diğer tüm kullanıcıların yetkilerini ifade eder.
Genellikle "dünya" (world) olarak da adlandırılır.
İzinleri Okuyalım
Öncelikle yukarıdaki örnekte verilen izinleri (-rwxr-xr--) parçalayarak analiz edelim:

-: En baştaki karakter dosya tipini gösterir. - olduğu için bunun bir dosya olduğunu anlıyoruz (d olsaydı dizin olurdu).
rwx (Sahip): Dosya sahibi dosyayı okuyabilir (r), yazabilir (w) ve çalıştırabilir (x). Tam yetkiye sahiptir.
r-x (Grup): Gruba dahil kullanıcılar dosyayı okuyabilir (r) ve çalıştırabilir (x), ancak dosyaya yazamazlar (-).
r-- (Diğerleri): Diğer herkes dosyayı sadece okuyabilir (r). Yazamaz ve çalıştıramazlar.
Örnek Çıktı Analizi:

user@hackerbox:~$ ls -l script.sh
-rwxr-xr-- 1 mehmet yazilim 450 Aug 01 14:00 script.sh
Sahip (mehmet): Okur, yazar, çalıştırır (rwx).
Grup (yazilim): Okur, çalıştırır (r-x).
Diğerleri: Sadece okur (r--).
2. İzin Değerleri (Oktal)

İzinler sayılarla ifade edilir:

r (Read) = 4
w (Write) = 2
x (Execute) = 1
İzin	Sayısal Karşılık	Anlamı
rwx	7 (4+2+1)	Tam yetki.
rw-	6 (4+2)	Okur/Yazar.
r-x	5 (4+1)	Okur/Çalıştırır.
r--	4	Sadece Okur.
İzinlerin Sayısal Karşılıkları Tablosu
İzin Grubu	İzinler	Oktal Değer	Anlamı
Sahip	rwx	7	Oku, Yaz, Çalıştır
Grup	r-x	5	Oku, Çalıştır (Yazamaz)
Diğer	r--	4	Sadece Oku
TOPLAM	rwxr-xr--	754	Dosyanın tam izni
3. İzinleri Değiştirme (chmod)

Örnek Senaryo: Bir scripti çalıştırılabilir yapma

script.sh için çalıştırma izni ekleme (755):

user@hackerbox:~$ ls -l script.sh
-rw-r--r-- 1 user user 0 Aug 01 12:00 script.sh
user@hackerbox:~$ chmod 755 script.sh
user@hackerbox:~$ ls -l script.sh
-rwxr-xr-x 1 user user 0 Aug 01 12:00 script.sh
Herkese tam yetki (777) — güvensizdir:

user@hackerbox:~$ chmod 777 dosya.txt
user@hackerbox:~$ ls -l dosya.txt
-rwxrwxrwx 1 user user 0 Aug 01 12:00 dosya.txt
Sadece sahip okur/yazar (600):

user@hackerbox:~$ chmod 600 ozel.txt
user@hackerbox:~$ ls -l ozel.txt
-rw------- 1 user user 0 Aug 01 12:00 ozel.txt
notes.txt dosyasında diğer kullanıcılara (o) yazma izni ekleyelim:

root@hackerbox:~$ chmod o+w notes.txt
root@hackerbox:~$ ls -l notes.txt
-rw-rw-rw- 1 john development 4096 Jul 29 12:34 notes.txt
Tek seferde tüm gruplara tüm izinleri vermek isterseniz:

root@hackerbox:~$ chmod ugo+rwx notes.txt
root@hackerbox:~$ ls -l notes.txt
-rwxrwxrwx 1 john development 4096 Jul 29 12:34 notes.txt
4. Özel İzinler (SUID, SGID, Sticky)

Bu izinler güvenlik ve işbirliği için kritiktir.

Ad	Sayısal	Nerede	Ne Yapar?	Örnek
SUID	4000	Dosya	Çalıştıran kişi, dosya sahibinin yetkisiyle çalıştırır.	passwd
SGID	2000	Dizin	İçinde oluşturulan dosyalar dizinin grubunu alır.	Ortak projeler.
Sticky	1000	Dizin	Sadece dosya sahibi dosyasını silebilir.	/tmp
Örnek: SUID Ayarlama

user@hackerbox:~$ chmod 4755 dosya
user@hackerbox:~$ ls -l dosya
-rwsr-xr-x 1 root root 0 Aug 01 12:00 dosya
(x yerine s geldi. Dosya artık root yetkisiyle çalışacak).

Örnek: Sticky Bit Ayarlama (/tmp dizini)

user@hackerbox:~$ chmod 1777 /tmp
user@hackerbox:~$ ls -ld /tmp
drwxrwxrwt 10 root root 4096 Aug 01 12:00 /tmp
(t harfi Sticky Bit'i gösterir).

5. Umask Hesaplama

Varsayılan izinleri belirler. Standart değer 022'dir.

Dosya: 666 - 022 = 644 (rw-r--r--)
Dizin: 777 - 022 = 755 (rwxr-xr-x)
Kendi umask değerinizi görmek için:

user@hackerbox:~$ umask
0022
6. Dosya Öznitelikleri (chattr ve lsattr)

İzinlerden daha güçlü koruma sağlar. Bir dosyayı değiştirilemez (immutable) yapmak için kullanılır.

chattr +i dosya: Dosyayı kilitler. Root bile silemez.
lsattr dosya: Öznitelikleri gösterir.
user@hackerbox:~$ sudo chattr +i kritik_dosya.conf
user@hackerbox:~$ rm kritik_dosya.conf
rm: cannot remove 'kritik_dosya.conf': Operation not permitted
(Kilidi açmak için sudo chattr -i kullanılır).


Process Yönetimi

Process Nedir ve Nasıl Çalışır?

Linux işletim sisteminde, o an çalışan her programa veya komuta Process (Süreç) denir. Siz bir programa (örneğin Firefox'a) tıkladığınızda veya terminale bir komut (örneğin ls) yazdığınızda, işletim sistemi bu işlem için bellekte bir yer ayırır ve ona benzersiz bir kimlik numarası (PID) verir.

Process'lerin Temel Özellikleri:

PID (Process ID): Her process'in TC Kimlik numarası gibi benzersiz bir numarası vardır.
Sahip (User): Process'i başlatan kullanıcıdır.
Ebeveyn (Parent): Bir process, başka bir process tarafından başlatılabilir. (Örneğin terminalden Firefox açarsanız, terminal "baba", Firefox "çocuk" process olur).
Process'leri yönetmek, sistemin performansını kontrol etmek ve kilitlenen programları kapatmak için hayati önem taşır.

1. Süreç Türleri

Ön Plan (Foreground) Process'leri
Varsayılan olarak tüm process'ler ön planda yürütülür. Klavyeden girdi alırlar ve ekrana çıktı sağlarlar. pwd komutunu çalıştırmak buna iyi bir örnektir.

user@hackerbox:~$ pwd
/home/user
Örnekte, pwd komutu tarafından yürütülen process ön planda çalışarak çıktı sağladı ve görevini yerine getirdikten sonra çıkış yaptı. Ön planda çalışan process'ler görevini yerine getirene kadar terminali kilitleyip, başka bir işlem yapmaya izin vermezler.

Arka Plan (Background) Process'leri
Arka plan process'leri, çalıştırıldığında terminali kitlemez ve arka planda çalışmaya başlar. Arka plan process'leri çalıştırıldığında, paralel olarak bir çok process çalıştırılabilir.

Bir komutu arka planda çalıştırmak istersek sonuna & karakteri ekleyebiliriz.

user@hackerbox:~$ ping 127.0.0.1 &
[1] 54017
[1] ifadesi, process'in iş (job) numarasının 1 olduğunu belirtiyor. 54017 ise process'in arka planındaki PID (Process ID) değeridir.

2. Mevcut Terminal Oturumunda Çalışan Process'lerin Yönetimi

Arka planda çalışan işleri listelemek için jobs kullanılır.

user@hackerbox:~$ jobs
[1]    running    ping 127.0.0.1
Arka planda çalışan bu komutu tekrar ön plana almak için fg (foreground) komutunu kullanabiliriz.

user@hackerbox:~$ fg %1
ping 127.0.0.1
Durdurmak için CTRL+C kullanabiliriz veya arka plana atıp duraklatmak için CTRL+Z kullanabiliriz.

3. Sistem Genelinde Çalışan Process'lerin Yönetimi (ps, top)

Sadece mevcut terminal oturumumuzda değil, tüm sistemde çalışan process'ler de bulunmaktadır.

ps aux: Tüm process'lerin anlık fotoğrafını çeker.

user@hackerbox:~$ ps aux | head -n 10
USER         PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
root           1  0.0  0.1 168436 10240 ?        Ss   08:00   0:02 /sbin/init
root           2  0.0  0.0      0     0 ?        S    08:00   0:00 [kthreadd]
root        1234  0.0  0.5 123456 23456 ?        Sl   08:05   0:10 /usr/sbin/apache2
syslog       850  0.0  0.0 220100  5000 ?        Ssl  08:00   0:01 /usr/sbin/rsyslogd -n
message+     855  0.0  0.1   8500  4200 ?        Ss   08:00   0:01 /usr/bin/dbus-daemon --system
root         950  0.0  0.1  15000  6500 ?        Ss   08:00   0:00 /usr/sbin/sshd -D
mehmet      5432  1.5  3.2 567890 65432 pts/0    R+   10:30   0:05 python3 script.py
mehmet      5433  0.0  0.1   9000  4000 pts/0    S+   10:31   0:00 tail -f log.txt
root        6000  0.1  2.0 400000 50000 ?        S    09:00   0:15 /usr/bin/containerd
Sütunların Anlamları:

Sütun	Açıklama
USER	Process'i başlatan kullanıcı.
PID	Process ID - process'in benzersiz kimlik numarası.
%CPU	İşlemci kullanım oranı.
%MEM	Bellek (RAM) kullanım oranı.
STAT	Durum (R: Çalışıyor, S: Uyuyor, Z: Zombi).
START	Başlangıç zamanı.
COMMAND	Çalıştırılan komut.
top: Sistemdeki process'leri canlı olarak izlemek için kullanılır. (Çıkmak için q).

top - 14:30:00 up 10 days,  4:20,  1 user,  load average: 0.05, 0.10, 0.05
Tasks: 123 total,   1 running, 122 sleeping,   0 stopped,   0 zombie
%Cpu(s):  1.0 us,  0.5 sy,  0.0 ni, 98.5 id,  0.0 wa,  0.0 hi,  0.0 si,  0.0 st
MiB Mem :   3900.0 total,   1500.0 free,   1200.0 used,   1200.0 buff/cache
4. Çalışan Process'i Durdurmak (kill)

Çalışan process'leri durdurmak için kill komutu kullanılır. PID numarasına ihtiyaç duyar.

user@hackerbox:~$ kill 5432
Süreç Sinyalleri (Process Signals):
Bir process'i durdurmak için ona sinyal göndeririz. kill varsayılan olarak 15 numaralı sinyali gönderir.

Sinyal No	Ad	Anlamı
15	SIGTERM	Nazikçe kapan. (Varsayılan). Dosyaları kaydetmeye izin verir.
9	SIGKILL	Derhal öl. Kaydetmeye izin vermez. Zorla kapatır.
1	SIGHUP	Yeniden başla (Config dosyasını tekrar oku).
2	SIGINT	Kesme sinyali. Klavyeden CTRL+C tuşuna basıldığında gönderilir.
19	SIGSTOP	Process'i duraklatır (Pause). CTRL+Z ile gönderilir.
18	SIGCONT	Duraklatılmış process'i devam ettirir (Continue).
Eğer process normal kill ile kapanmıyorsa, zorla kapatmak için -9 kullanılır:

user@hackerbox:~$ kill -9 5432
İsmine Göre Öldürme (pkill, killall):
PID aramadan ismiyle kapatmak için:

user@hackerbox:~$ pkill python
user@hackerbox:~$ killall firefox
5. Öncelik Ayarı (nice, renice)

Linux'ta process'lerin önceliği vardır (-20 en yüksek, 19 en düşük). Varsayılan 0'dır.

nice: Programı başlatırken öncelik verir.

user@hackerbox:~$ nice -n 10 tar -czf yedek.tar.gz /home
(Yedekleme işlemi düşük öncelikle çalışsın, bilgisayarı yormasın).

renice: Çalışan process'in önceliğini değiştirir.

user@hackerbox:~$ renice -n -5 -p 5432
6. Servis Yönetimi (systemd)

Modern Linux sistemlerinde (Ubuntu, CentOS vb.) arka plan servislerini systemd yönetir. Komut aracımız systemctl'dir.

Örnek: Nginx Servisi

Durumunu gör:

user@hackerbox:~$ systemctl status nginx
● nginx.service - A high performance web server
   Active: active (running) since Mon 2023-10-01 ...
Başlat / Durdur:

sudo systemctl start nginx
sudo systemctl stop nginx
Otomatik Başlat (Bilgisayar açılınca):

sudo systemctl enable nginx


ı oluşturmak için ssh-keygen komutunu kullanabilirsiniz:

ssh-keygen
Bu komutu çalıştırdıktan sonra, oluşturulan açık anahtarı (public key) uzaktaki sunucuya kopyalamanız gerekecektir:

ssh-copy-id user@ip_address
Örneğin:

ssh-copy-id root@192.168.1.100
Bu işlem tamamlandıktan sonra, parola girmeden SSH ile bağlanabilirsiniz.

SSH Yapılandırma Dosyası
SSH yapılandırma ayarları genelde /etc/ssh/sshd_config dosyasında bulunur. Bu dosya üzerinde çeşitli SSH ayarlarını yapabilirsiniz. Örneğin, SSH portunu değiştirmek, root oturumlarını kapatmak gibi yapılandırmalar bu dosya üzerinde yapılabilir:

sudo nano /etc/ssh/sshd_config
Dosya içeriğinde, Port ayarını bulup düzenleyerek port numarasını değiştirebilirsiniz:

Port 2222
Değişiklikleri yaptıktan sonra SSH servisini yeniden başlatmanız gerekecektir:

sudo systemctl restart ssh
Bu bölümde SSH kullanımı hakkında temel bilgileri öğrendik. Şimdi, SSH ile ağ üzerinde güvenli bağlantılar kurabilir ve uzaktaki sunucuları yönetebilirsiniz.

Bu değişiklikler ile ağ yönetimi bölümünüz kapsamlı bir şekilde güncellenmiş oldu.
