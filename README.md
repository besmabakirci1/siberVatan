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

