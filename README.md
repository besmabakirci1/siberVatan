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




Ağ Türleri

Ağlar kullanım amacına göre ve boyutuna göre kategorize edilmektedir. Örneğin, bir ağın boyutu bir evde veya küçük bir işletmede olabilirken, diğer bir ağ ise büyük bir kurumsal ortamda veya geniş bir coğrafi alanı kapsayabilir. LAN, MAN ve WAN, kapsadıkları alan üzerinde çalışmak üzere tasarlanmış üç ana ağ türüdür. Aralarında bazı benzerlikler ve farklılıklar vardır. En önemli farklardan biri kapsadıkları coğrafi alandır, LAN bir evi veya binayı, MAN şehir'i, WAN ülkeler hatta kıtaları kapsayabilir.

Local Area Network (LAN)

Local Area Network (LAN), coğrafi olarak sınırlı bir alanı kapsayan bir bilgisayar ağıdır. Bu ağ türü, genellikle bir ev, ofis veya  bina içindeki cihazları birbirine bağlamak için kullanılır. LAN'lar, cihazlar arasında hızlı veri transferi, kaynak paylaşımı (örneğin yazıcılar ve dosyalar) ve uygulamaların ağ üzerinden erişilebilir olmasını sağlar.

Küçük bir alanı kapsar, bu yüzden yüksek hızlı veri transferi yapabilirler.
Genellikle Gbps (Gigabit per second) düzeyinde veri transfer hızları sunar.
Ağa bağlı cihazlar, yazıcılar, dosyalar ve diğer ağ kaynakları gibi ortak kaynakları paylaşabilir.
Ağdaki verilerin korunması ve izinsiz erişimin önlenmesi için güvenlik protokolleri veya ağ güvenlik cihazları kullanılabilir.
Wide Area Network(WAN)

Wide Area Network (WAN), geniş coğrafi alanlarda dağılmış olan bilgisayarları ve ağları birbirine bağlayan bir ağ türüdür. WAN'lar, şehirler, ülkeler hatta kıtalar arası iletişimi mümkün kılarak, uzaktaki ağları birleştiren ve büyük mesafelerde veri, ses ve video gibi bilgilerin iletilmesini sağlayan geniş kapsamlı ağlardır.WAN'lar, çok geniş bir alanı kapsadıkları için, internetin kendisi de aslında bir çeşit WAN olarak düşünülebilir.

WAN'lar, LAN'ların aksine, çok geniş coğrafi alanlarda hizmet verir.
WAN ağında, fiber optik kablolar, uydu bağlantıları, telefon hatları gibi çeşitli iletişim teknolojileri kullanılabilir.
Geniş coğrafi alanları kapsadığı için WAN'ların kurulumu ve bakımı genellikle yüksek maliyetlidir.
WAN'lar, LAN'lara göre daha düşük veri transfer hızları sunar, çünkü veriler çok daha uzun mesafeler kat eder.
WAN'lar, küresel ölçekte iletişim ve kaynak paylaşımı sağlar.
Metropolitan Area Network(MAN)

Metropolitan Area Network (MAN), şehir ölçeğindeki bir coğrafi alanda dağılmış olan bilgisayar ağlarını ve cihazlarını birbirine bağlayan bir ağ türüdür. MAN ağı, genellikle birkaç binadan oluşan bir üniversite kampüsü, bir şehrin çeşitli bölümleri ya da birkaç yakın şehri kapsayabilir. WAN ve LAN arasında bir yerde konumlanan MAN'lar, bölgesel veri iletişimi ihtiyaçları için idealdir.

MAN'lar genellikle bir şehir kadar geniş bir alana yayılır ve kilometrelerce mesafeyi kapsayabilir.
MAN'lar, geniş bant genişliği ve yüksek hızlı veri iletimi sağlayarak, büyük dosyaların ve verilerin hızlı bir şekilde transfer edilmesine olanak tanır.
Farklı kuruluşlar ve kullanıcılar, MAN üzerinden kaynakları (yazılım, donanım, veri depolama vb.) paylaşabilir.
Bir MAN, ihtiyaçlara göre kolayca genişletilebilir ve özelleştirilebilir.
Şehir yönetimleri, kamu güvenliği, sağlık hizmetleri ve eğitim kurumları gibi kamu hizmetlerinin entegrasyonu için MAN'ları tercih eder.
MAN kurulumu ve yönetimi genellikle internet servis sağlayıcıları (ISS) veya büyük kuruluşların IT departmanları tarafından yapılır.
Internet/Intranet Ağı

Internet
Internet, dünya çapında milyarlarca cihazı birbirine bağlayan geniş bir ağdır. Bu ağ üzerinde veri alışverişi, bilgi paylaşımı, iletişim ve birçok çevrimiçi işlem gerçekleştirilebilir. Internet, farklı coğrafi konumlardaki kullanıcıların ve sistemlerin birbiriyle etkileşime geçmesini sağlayan küresel bir ağ altyapısına sahiptir.

Intranet
Intranet, bir organizasyon veya kuruluş içinde sınırlı kullanıcı grubuna özel olarak tasarlanmış özel bir ağdır. Genellikle şirket bilgileri, çalışan kaynakları ve iç iletişim araçları gibi kurumsal kaynaklara erişim sağlamak için kullanılır. Intranet, Internet'in aksine, genel erişime kapalıdır ve yalnızca belirli kullanıcıların erişimine izin verir


Ağ topolojisi

Ağ topolojisi, bir ağdaki cihazların (bilgisayarlar, yazıcılar, sunucular vb.) birbirine bağlanma şeklini ve iletişim kurma yolunu tanımlar. Hem fiziksel bağlantıları (kablolar, Wi-Fi, vb.) hem de mantıksal yapıları (veri akışı, sinyal yolu) içerir.

Star Topoloji
Tüm cihazlar merkezi bir noktaya, genellikle bir hub veya switch'e bağlanır. Bu merkezi nokta, ağdaki tüm iletişimin merkezidir.

Yeni cihazlar kolayca eklenebilir, arızalı cihazlar ağı etkilemeden çıkarılabilir.
Tek bir cihazın arızalanması, ağın geri kalanını etkilemez.
Merkezi cihaz arızalandığında, tüm ağ etkilenir.
Ev ağları, küçük ofislerlerde kullanılır
Ring Topoloji
Halka topolojisinde, her cihaz yalnızca iki komşusuyla bağlantılıdır ve bir halka oluşturacak şekilde dizilirler. Veriler, halka boyunca tek yönde akar.

Veri paketleri belirli bir yönde ilerler, çarpışmaları azaltır.
Her cihaz yalnızca iki bağlantıya ihtiyaç duyar.
Tek bir noktadaki arıza tüm ağı etkileyebilir.
Ağı genişletmek için halkayı kesmek gerekir, bu da karmaşıklık yaratır.
Metro ağları ve bazı Lan ağlarında kullanılır.
Bus Topoloji
Bus topolojisinde, tüm cihazlar tek bir iletim hattına, genellikle bir koaksiyel kablo üzerine bağlanır. Bu yapı, verilerin her iki yöne de akmasına olanak tanır.

Tek bir iletim hattı kullanıldığı için kablo maliyeti düşüktür.
Tüm cihazlar aynı iletim hattını paylaşır.
Kablo hasar gördüğünde, hatanın kaynağını bulmak zor olabilir.
Küçük ağlar, geçici veya basit kurulum gerektiren ağlarda tercih edilir.
Tree Topoloji
Tree topolojisi, yıldız topolojilerinin bir hiyerarşi içinde birleşimi şeklinde düzenlenir. Bir merkezi kökten dallanarak alt ağlar oluşturulur.

Yeni dallar eklemek kolaydır.
Ağ hiyerarşik olduğu için alt ağlar kolayca yönetilebilir.
Üst düzeydeki cihazların arızalanması, altındaki ağları etkiler.
Ağ büyüdükçe, kablo ihtiyacı artar.
Büyük kurumsal ağlar, geniş kampüs ağlarında kullanılır
Mesh Topoloji
Mesh topolojide, cihazlar arasında birçok bağlantı yolu vardır. Tam örgüde, her cihaz doğrudan diğer her cihazla bağlantılıdır. Kısmi örgüde ise, bazı cihazlar birden fazla bağlantıya sahiptir, ancak her cihaz her cihazla doğrudan bağlantılı değildir.

Birden fazla yol arasında seçim yaparak, tek bir noktadaki arıza ağı etkilemez.
Veriler, en verimli yolu takip ederek hedefine ulaşır.
Her cihazın birden fazla bağlantısı olması nedeniyle, kablo ve cihaz maliyeti artar.
Kritik iletişim ağları, veri merkezlerinde kullanılır
Peer to peer (P2P) Topoloji
Peer to peer  topolojide, her cihaz diğerleriyle eşit yetkilere sahiptir ve doğrudan iletişim kurabilir. Bu yapı, merkezi bir yönetim veya sunucu gerektirmez.

Yeni cihazlar kolayca eklenebilir ve ağa entegre edilebilir.
Merkezi bir sunucuya veya özel donanıma ihtiyaç duymaz.
Eşler arası ağlarda güvenlik ve yönetim daha karmaşık olabilir.
Büyük ağlarda, kaynakların eşit dağılımı zorlaşabilir.
Dosya paylaşımı, blockchain teknolojileri, bazı dağıtık uygulamalarda kullanılır.
Hybrid Topoloji
Hibrit topoloji, iki veya daha fazla farklı topolojinin birleşimidir. Bu yapı, farklı topolojilerin avantajlarını birleştirerek karmaşık ihtiyaçlara çözüm sunar.

Farklı topolojilerin avantajlarından yararlanılabilir.
İhtiyaçlara göre kolayca genişletilebilir veya özelleştirilebilir.
Farklı topolojilerin entegrasyonu yönetimi zorlaştırabilir.
Hibrit yapılar genellikle daha pahalıdır.
Büyük kurumsal ağlar, karmaşık ağ ihtiyaçları olan kuruluşlar tarafından tercih edilir.



İletişim Modları ve Türleri

İletişim Modları

Bilgisayar ağlarında iletişim modları, bilgisayarların ve diğer cihazların birbiriyle nasıl veri alışverişinde bulunduğunu tanımlar. İletim modu üç kategoriye ayrılmıştır:

Simpleks
Veri, sadece bir yönde akar. Gönderici, veriyi sürekli olarak alıcıya aktarırken, alıcı sadece veriyi alır ve geriye veri göndermez.Klavye ve Monitör, klavyenin yalnızca kullanıcıdan gelen verileri kabul edebilmesi ve monitörün yalnızca verileri ekranda görüntülemek için kullanılabilmesi nedeniyle simpleks iletişin modunun örnekleridir.

Half Duplex
Half dublex iletişim modunda, veriler her iki yönde de aktarılabilir, ancak bu aktarım aynı anda gerçekleşmez. Bir cihaz veri gönderirken, diğer cihaz veriyi alır ve sonra roller değişir. Bu iletişim türü, sınırlı bant genişliğine sahip ortamlarda etkilidir.Telsiz , Yarı çift yönlü modun bir örneğidir. 

Full Duplex
Full duplex iletişim modu, verilerin her iki yönde de aynı anda serbestçe akmasına olanak tanır. Bu, eş zamanlı iletişimi mümkün kılar ve en etkili iletişim modlarından biridir. Telefon görüşmeleri ve internet üzerinden yapılan canlı sohbetler, bu iletişim modunun örneklerindendir.

İletişim Türleri

Unicast
Unicast iletimi, ağ üzerinde tek bir göndericiden tek bir alıcıya veri gönderimi anlamına gelir. Bu, en yaygın kullanılan iletim modudur ve internet üzerindeki çoğu veri iletimi bu şekilde gerçekleşir.
Bir web sunucusundan bilgisayarınıza bir web sayfası yüklenmesi unicast bir iletimdir.
Multicast
Multicast iletimi, tek bir göndericiden belirli bir grup alıcıya veri gönderimi anlamına gelir. Aynı verinin birden fazla alıcıya ulaştırılması gerektiğinde verimli bir yöntemdir.
Canlı bir video yayını, multicast iletimi kullanılarak aynı anda birçok izleyiciye ulaştırılabilir.
Broadcast
Broadcast iletişimi, ağ üzerindeki tek bir göndericiden ağdaki tüm alıcılara veri gönderimi anlamına gelir. Gönderilen verinin ağdaki her cihaza ulaşması gerektiğinde kullanılır.
Bir ağ cihazı tarafından DHCP isteği gönderimi, genellikle broadcast iletimi kullanılarak yapılır, çünkü bu istek ağdaki tüm cihazlara ulaşmalıdır.



Bilgisayar Ağ Modelleri

Bilgisayar ağ modelleri, bilgisayarların birbiriyle nasıl iletişim kuracağını ve veri alışverişi yapacağını belirleyen kurallar ve protokoller bütünüdür. Bu modeller, ağın nasıl tasarlanacağını, verilerin nasıl paketleneceğini, iletilip alınacağını ve hataların nasıl düzeltilip yönetileceğini tanımlar. Ağ teknolojilerinin karmaşıklığını basitleştirerek bu teknolojileri daha iyi anlaşılması sağlanır.

Farklı katmanlar halinde düzenlenmiş modeller sayesinde, her bir katmanın işlevselliği bağımsız olarak incelenebilir ve tasarlanabilir. Bu ağ modelleri, farklı üreticiler tarafından geliştirilen ağ cihazları ve yazılımlarının birbiriyle uyumlu şekilde çalışabilmesi için bir standart sağlar. En yaygın iki model OSI (Open Systems Interconnection) ve TCP/IP'dir.

Bilgisayar Ağlarının Temel Bileşenleri
Ağ Araçları (Network Devices): Ağ kartları, modeller, switchler, routerlar gibi cihazlar veri iletimi ve yönlendirilmesi işlevlerini yerine getirir.
İletim Ortamları (Transmission Media): Bakır kablolar, fiber optik kablolar ve kablosuz bağlantılar gibi fiziksel veya sanal ortamlar, ağ cihazları arasında veri iletimini sağlar.
Protokoller (Protocols): TCP/IP, HTTP, FTP, SMTP gibi protokoller, ağ üzerinden veri iletimi için gerekli kuralları ve standartları belirler.
Ağ Yazılımları (Network Software): İşletim sistemleri ve ağ yönetim yazılımları, ağ cihazlarının etkileşimini ve veri akışını yönetir.
Ağ Modellemesi ve Standartlar
Ağ modellemesi, ağın nasıl çalıştığını anlamak ve tasarlamak için kullanılan soyut bir yaklaşımdır. Modelleme, ağın farklı yönlerini katmanlar halinde düzenleyerek, karmaşıklığı azaltır ve standartlaştırma sağlar. Bu katmanlar, ağın farklı işlevlerini temsil eder ve birbirleriyle belirlenen kurallar (protokoller) aracılığıyla iletişim kurar.

Standartlar, ağ cihazlarının ve yazılımlarının birbirleriyle uyumlu bir şekilde çalışabilmesi için gerekli olan teknik özellikleri ve protokolleri belirler. Bu standartlar, farklı üreticilerden gelen cihazların ve yazılımların birlikte çalışabilmesini sağlayarak, ağların genişletilmesi ve entegrasyonu konusunda büyük kolaylıklar sunar.

Ağ Protokolleri ve İletişim
Ağ protokolleri, ağ üzerinden veri iletimi sırasında uygulanan kurallar ve standartlardır. Protokoller, veri paketlerinin nasıl oluşturulacağını, adreslendirileceğini, iletilip alınacağını ve hataların nasıl kontrol edileceğini belirler. Bu protokoller, ağın farklı katmanlarında yer alır ve her katman, belirli görevleri yerine getirir.

Ağ iletişimi, veri paketlerinin bir kaynaktan hedefe doğru yolculuğunu içerir. Bu süreç, verilerin katmanlardan geçirilerek uygun biçimlere dönüştürülmesi, hedefe iletilmesi ve sonunda tekrar orijinal veriye dönüştürülmesi işlemlerini kapsar.

OSI Modeli
OSI (Open Systems Interconnection) modeli, uluslararası standartlar kuruluşu olan ISO tarafından geliştirilmiştir. Amaç, farklı sistemlerin birbiriyle uyumlu bir şekilde iletişim kurabilmesini sağlamaktır. OSI modeli yedi katmandan oluşur:

Fiziksel Katman (Physical Layer): Donanım düzeyindeki iletişimi, kablolar, kartlar ve diğer fiziksel yapılar üzerinden veri aktarımını sağlar.
Veri Bağlantı Katmanı (Data Link Layer): Ağ üzerindeki veri akışını düzenleyerek, verilerin doğru adreslere ulaşmasını sağlar. MAC (Media Access Control) adreslerini kullanır.
Ağ Katmanı (Network Layer): Verilerin farklı ağlar arası iletimini yönetir. Bu katmanda IP adresleri ve yönlendirme işlemleri bulunur.
Taşıma Katmanı (Transport Layer): Uçtan uca iletişimi yönetir ve veri aktarımının güvenilirliğini sağlar. TCP (Transmission Control Protocol) ve UDP (User Datagram Protocol) bu katmanda yer alır.
Oturum Katmanı (Session Layer): İletişim oturumlarını yönetir, bağlantıların başlatılmasını ve sonlandırılmasını kontrol eder.
Sunum Katmanı (Presentation Layer): Verilerin ağ üzerinden nasıl temsil edileceğini yönetir. Şifreleme ve sıkıştırma işlemleri bu katmanda gerçekleşir.
Uygulama Katmanı (Application Layer): Kullanıcıların ağ üzerindeki uygulamalarla etkileşime geçebilmesini sağlar. E-posta, web tarayıcıları ve diğer uç kullanıcı uygulamaları bu katmanda yer alır.
TCP/IP Modeli
TCP/IP modeli, internetin temelini oluşturan ve günümüzde en yaygın kullanılan ağ modelidir. OSI modeline göre daha basit bir yapıya sahiptir ve dört katmandan oluşur:

Ağ Arayüzü Katmanı (Network Interface Layer): Fiziksel ve veri bağlantı katmanlarının işlevlerini birleştirir ve donanım üzerinden veri iletimini sağlar.
İnternet Katmanı (Internet Layer): Ağ katmanına karşılık gelir ve IP adreslerini kullanarak verilerin yönlendirilmesini sağlar.
Taşıma Katmanı (Transport Layer): OSI modelindeki gibi uçtan uca iletişimi yönetir ve TCP ile UDP protokollerini içerir.
Uygulama Katmanı (Application Layer): OSI modelindeki oturum, sunum ve uygulama katmanlarının işlevlerini birleştirir. Kullanıcıların ağ uygulamalarıyla etkileşimini sağlar.
Her iki model de ağ tasarımı ve veri iletişimi konusunda temel prensipleri sağlar, ancak TCP/IP modeli pratikte daha yaygın kullanılmaktadır. OSI modeli ise eğitim ve teorik anlamda ağ kavramlarını anlamada yardımcı olur.



https://storage.hackviser.com/file/hackviser-prod/trainings/sections/images/634c04be-ed2c-43a1-99c8-5162bd190d73/osi-encapsulation-DeEncapsulation-2-5d7a355a0.webp<img width="740" height="366" alt="image" src="https://github.com/user-attachments/assets/04d0cf4a-4f7e-47ec-a673-59617af30f8b" />

OSI Modeli



OSI modeli, Uluslararası Standardizasyon Örgütü (ISO) tarafından 1984 yılında geliştirilmiş olup, günümüzde bilgisayarlar arası iletişimin mimari modeli olarak kabul edilmektedir. Bu model, veri iletim ve alımı sürecini yedi katmana ayırarak, her bir katmanın belirli görevleri yerine getirmesini ve birbirleriyle nasıl etkileşime gireceğini tanımlar. OSI modelinin amacı, farklı sistemlerin ve teknolojilerin birbiriyle uyumlu şekilde çalışabilmesi için bir çerçeve sunmaktır.



Üst Katmanlar: Kullanıcılar ve programlar, bu katman aracılığıyla birbirleriyle haberleşdiği katmanlardır. Yani üst katmanlar, yazılım tarafından gerçekleştirilen işlemlerdir. Uygulama, sunum, oturum katmanları üst katmandır.

Alt Katmanlar: Verinin nasıl taşınacağıyla ilgili katmanlardır. Verinin bir bilgisayardan diğerine fiziksel olarak nasıl aktarılacağıyla ilgilenir. Fiziksel, veri bağlantı, ağ ve taşıma katmanları alt katmandır.

1) Fiziksel katman (Physical Layer)
Verinin fiziksel olarak hat üzerinden bitler halinde bir noktadan diğerine taşımak için gerekli olan islevleri kapsar.
OSI modelinin en alt katmanıdır.
Kablo, konnektör standartlari bu katmandadır. (UTP, RJ45, RS-232C, V.35 ve diger port standartlar).
İki veya daha fazla cihazın fiziksel olarak nasıl bağlanabileceğini tanımlanır.
Ağdaki iki cihaz arasındaki iletim modunun simpleks, half-duplex veya full-duplex mod olacağını tanımlanır.
Donanım örnekleri ağ bağdaştırıcıları , tekrarlayıcılar, ağ hub'ları vb.'dir.
2) Veri Bağlantı Katmanı (Data Link Layer)
Ağ üzerinden bilgisayarlar veya ağ cihazları arasındaki veri aktarımını güvenilir bir şekilde gerçekleştiren katmandır. Verilerin çerçeveleme, adresleme (MAC adresleri ile) ve doğru adrese ulaşmasını ve veri iletiminde oluşabilecek hataların tespit işlemlerini gerçekleştirir.
Veri göndermek isteyen bir cihazdan gelen veriyi alır. Sonra, bu veriyi çerçevelere bölerek her çerçevenin başına ve sonuna, çerçevenin nereye gitmesi gerektiğini (adresleme) ve çerçevenin doğruluğunu kontrol etmeye yarayan bilgiler (hata kontrolü) ekler. Daha sonra, bu çerçeveler ağ üzerinden alıcı cihaza gönderilir.Alıcı cihazda, Veri Bağlantı Katmanı gelen çerçeveleri alır, hata kontrolü yapar ve veriyi doğru sırayla üst katmana (Ağ Katmanı) iletir. Eğer bir hata tespit edilirse, bu katman hatanın düzeltilmesi için gerekli işlemleri yapar.
Çerçeveleme: Gönderilen veriyi "çerçeve(frame)" halinde paketler. Veri paketlerinin başlangıç ve bitiş noktalarını belirler, böylece alıcı veriyi doğru bir şekilde algılayabilir.
Adresleme: Her ağ cihazı, bu katmanda kendine özgü bir fiziksel adres (MAC adresi) kullanır. Veri Bağlantı Katmanı, verinin doğru cihaza ulaşmasını sağlamak için bu adresleri kullanır.
Hata Kontrolü: Veri iletimi sırasında çeşitli hatalar meydana gelebilir. Veri Bağlantı Katmanı, iletilen çerçevelerdeki hataları tespit edebilir ve bazı durumlarda bu hataları düzeltebilir.
Akış Kontrolü: Veri akışını kontrol ederek alıcının fazla miktarda veri ile gelmesini önler. Veri gönderimi ve alımı arasında bir denge sağlar.
3) Ağ Katmanı

Farklı ağlar arasındaki veri iletimini yönetir.Mantıksal adresleme (IP adresleri), yönlendirme ve paketleme işlemlerinden sorumludur.
Bir veri paketi gönderildiğinde, Ağ Katmanı, paketin hedefine ulaşmak için takip etmesi gereken yolu belirler. Bu yol, bir dizi ağ geçidi veya yönlendirici(router) üzerinden geçebilir. Her bir geçiş noktasında, Ağ Katmanı, paketin bir sonraki varış noktasını belirler. Bu işlem, paket hedefine ulaşana kadar devam eder.
Ağ trafiğini yönlendirmek için kullanılan protokollere Ağ katmanı protokolleri denir. Protokol örnekleri IP ve Ipv6'dır.
Yönlendirme (Routing): Ağ Katmanı, veri paketlerinin kaynaktan hedefe giden yolu belirler. Bu işlem, çeşitli yönlendirme algoritmaları kullanılarak gerçekleştirilir ve ağın durumuna göre en uygun yolun seçilmesini sağlar.
Adresleme: Her cihazın ağ üzerinde benzersiz bir adresi (IP adresi gibi) vardır. Bu adresleri kullanarak veri paketlerinin doğru hedeflere ulaşmasını sağlar.
Paketleme: Veri, bu katmanda daha küçük birimler olan paketlere bölünür. Her paket, hedef adres gibi önemli kontrol bilgilerini içeren bir başlık eklenir.
Hata Tespiti ve Düzeltme: Paketlerin kaybı veya hatalı iletimi gibi sorunları tespit eder ve üst katmanlara bilgi verir.
Yönlendiriciler katman 3 cihazlarıdır, bu katmanda belirtilirler ve bir ağlar arası yönlendirme hizmetlerini sağlamak için kullanılırlar.
4) Taşıma Katmanı

Taşıma katmanı, uçtan uca veri iletiminin güvenilirliğini, eksizliğini ve verimliliğini ve sağlar.
Bu süreçler sırasında, veri akış kontrolü, hata kontrolü ve tıkanıklık kontrolü gibi işlemler yapılır.
Verileri üst katmandan alır ve bunları segment adı verilen daha küçük birimlere dönüştürür.
Taşıma Katmanı, üst katmandan(Oturum katmanı) gelen veriyi alır segmentlere böler ve her segmente, hedef bilgileri ve sıra numaraları gibi kontrol bilgileri eklenerek ağ katmanına iletilir.
Ağ Katmanından, gelen segmentleri alır, yeniden birleştirir ve üst katmana(Oturum katmanı) iletir.
Segmentasyon ve yeniden birleştirme: Taşıma katmanı mesajı üst katmandan aldığında, mesajı birden fazla segmente ayırır ve her segmente, her segmenti benzersiz şekilde tanımlayan bir sıra numarası atanır. Mesaj hedefe ulaştığında, taşıma katmanı mesajı sıra numaralarına göre yeniden birleştirir.
Bağlantı kontrolü: Taşıma katmanı iki hizmet sağlar Bağlantı odaklı hizmet ve bağlantısız hizmet. Bağlantısız bir hizmet, her segmenti ayrı bir paket olarak ele alır ve hepsi hedefe ulaşmak için farklı rotalarda seyahat eder. Bağlantı odaklı bir hizmet, paketleri teslim etmeden önce hedef makinedeki taşıma katmanıyla bağlantı kurar. Bağlantı yönelimli hizmette tüm paketler tek bir rotada hareket eder.
Hata kontrolü: Taşıma katmanı aynı zamanda Hata kontrolünden de sorumludur. Hata kontrolü tek bağlantı yerine uçtan uca gerçekleştirilir. Gönderici taşıma katmanı, mesajın hedefe hatasız ulaşmasını sağlar.



https://storage.hackviser.com/file/hackviser-prod/trainings/sections/images/634c04be-ed2c-43a1-99c8-5162bd190d73/osi-model-921d34ed6.webp<img width="750" height="495" alt="image" src="https://github.com/user-attachments/assets/757f93f0-7df8-46c8-b80c-7321396df8ef" />

https://storage.hackviser.com/file/hackviser-prod/trainings/sections/images/634c04be-ed2c-43a1-99c8-5162bd190d73/osi-ncapsulation-DeEncapsulation-afade08f0.webp<img width="728" height="305" alt="image" src="https://github.com/user-attachments/assets/13c7c47e-824a-464b-a91d-9550ad486ef3" />





TCP/IP Modeli

TCP/IP modeli, ağ iletişimi için temel bir çerçeve sağlayan ve internetin temelini oluşturan bir modeldir.
"Transmission Control Protocol/Internet Protocol" kelimelerinin kısaltmasıdır ve OSI modeline benzer şekilde, ağ üzerindeki veri iletim sürecini katmanlar halinde düzenler.
OSI modelinden önce geliştirilmiştir. Daha basitleştirilmiş bir yapıya sahiptir ve dört katmandan oluşur. Bu katmanlar, uygulama, taşıma, internet ve ağ erişim katmanlarıdır.
Her katman, ağ iletişiminin farklı bir yönünü ele alır ve bir üst katmana hizmetler sağlar.
TCP/IP, adını iki ana protokolden alır: TCP (Transmission Control Protocol) ve IP (Internet Protocol), sırasıyla Taşıma ve İnternet katmanlarının temel protokolleridir.
TCP/IP Protokolünde veri akışı:
https://storage.hackviser.com/file/hackviser-prod/trainings/sections/images/e46b2dee-f6fa-44de-86f2-a1e0c105d4e2/tcp-data-flow-76501ca5b.webp<img width="500" height="258" alt="image" src="https://github.com/user-attachments/assets/80bab4c2-ebf2-458c-8f73-1f6e5296580a" />

Uygulama katmanı

Uygulama katmanı, TCP/IP modelinde en üstteki katmandır.
Son kullanıcının ağ üzerindeki uygulamalarla etkileşime geçebilmesi için gerekli olan arayüzleri ve protokolleri sağlar. Web tarayıcıları, e-posta istemcileri ve çevrimiçi oyunlar gibi uygulamalar, Uygulama Katmanı'ndaki protokoller sayesinde çalışır.
Uygulama katmanında kullanılan bazı protokoller:
HTTP/HTTPS: Hyper Text Transfer Protokol(HTTP) ve Secure Hyper Text Transfer Protokol (HTTPS) internetin temelini oluşturur. İnternet tarayıcıları ve sunucular arasındaki iletişimi yönetmek için kullanılır. HTTPS, HTTP-Secure anlamına gelir. HTTP ile kriptolama protokolü olan SSL (Secure Socket Layerı) birleşimidir. Oturum açma,kimlik doğrulama gibi işlemlerin gerektiği durumlarda iletişimi şifreleyerek iletişimin güvenliğini sağlar.
SNMP:  Simple Network Management Protocol(SNMP),  TCP/IP protokol paketini kullanarak ağ cihazlarını(router,switch vb.) yönetmek için kullanılan bir çerçevedir.
SMTP: Simple Mail Transfer Protocol(SMTP), e-posta mesajları göndermek ve almak için kullanılan bir iletişim protokolüdür
DNS: İnternete bir bilgisayarı yada internet sitesini bağlantısını benzersiz bir şekilde tanımlamak için bir IP adresi kullanılır. Bu karmaşık IP adresi yerine adlandırılır. Domain Name System(DNS) de alan adlarını IP adreslerine çevirerek internet kaynaklarına erişebilmesini sağlar.
TELNET: Telecommunication Network(TELNET) Yerel bilgisayar ile uzak bilgisayar arasında terminal bağlantısı kurulmasını sağlar.
SSH: Secure Shell(SSH) ağ cihazlarına ve sunucularına erişmek için kullanılır. SSH TELNET protokolü temel farkı trafiği her iki yönde de şifreleyerek veri güvenliğini sağlar.
FTP: File Transfer Protocol(FTP), dosyaları bir bilgisayardan başka bir bilgisayara aktarmak için kullanılır.
Taşıma katmanı

Uçtan uca iletişiminden sorumludur. Veri akışını kontrol eder ve veri paketlerinin sıralı bir şekilde iletildiği katmandır.
İki ana protokol kullanılır:
Transmission Control Protocol(TCP)
Bir TCP paketi, header(başlık) ve data(veri) olmak üzere iki ana bölümden oluşur.

TCP Segment Formatı

https://storage.hackviser.com/file/hackviser-prod/trainings/sections/images/e46b2dee-f6fa-44de-86f2-a1e0c105d4e2/tcpsegment-b8f04ce25.webp<img width="571" height="386" alt="image" src="https://github.com/user-attachments/assets/041ae798-2b25-43a0-9132-3c145df18476" />


Header(Başlık): TCP paketi başlangıcında yer alır ve en az 20 bayttan oluşur. Başlık, veri iletimini kontrol etmek ve yönetmek için gerekli birçok kontrol bilgisini içerir.

Source(Kaynak) Port: İletişimi başlatan istemci cihazın kullandığı port numarasıdır. Source port numarası, gönderen cihazın hangi uygulamasının veri gönderdiğini belirtir.
Destination(Hedef) Port: : İletişimin hedefindeki bilgisayarın kullandığı port numarasıdır. Hedef port numarası, alıcı cihazdaki hedef uygulamanın tanımlayıcısıdır. Örneğin, web sunucuları - genellikle HTTP için 80, HTTPS için 443 port numaralarını kullanır.
Sequence Number(Sıra Numarası): Segmentin akışındaki sırasını belirler, verilerin doğru sırada yeniden birleştirilmesini sağlar.
Acknowledgment Number (Onaylama Numarası): Alınan segmentin sıra numarasını onaylar.
Header Length(Başlık Uzunluğu): Başlığın uzunluğunu belirtir ve genellikle 20-60 bayt arasındadır.
Flags(Bayraklar): Bağlantının kurulması, yönetilmesi ve sonlandırılması için kullanılan kontrol sinyallerini içerir. Örneğin, SYN, ACK, FIN.
Window Size(Pencere Boyutu): Alıcı tarafın alabileceği veri miktarını belirler, ağ tıkanıklığını önlemeye yardımcı olur.
Checksum(Hata Sınama Biti): Veri paketin hata kontrolünü sağlar.
Urgent Pointer(Acil İşaretçisi): Acil verilerin varlığını ve sıralamasını belirtir.
Data(Veri): Başlıktan sonra gelen bölüm, uygulama katmanından gelen asıl verileri içerir. Bu bölümün boyutu, ağın MTU (Maximum Transmission Unit) değerine ve başlığın uzunluğuna bağlı olarak değişebilir.

Ağ üzerinde iki cihaz arasında güvenilir bir bağlantı kurulmasını sağlayan bir süreçtir. Bu işlem, veri iletiminin doğru ve güvenilir bir şekilde gerçekleşmesini garantiler.Hatalı veya eksik paketleri algılayıp yeniden ilettiği için güvenilir bir protokoldür.

Gönderim sonunda TCP, mesajın tamamını segment olarak bilinen daha küçük birimlere böler ve her segment, çerçevelerin orijinal bir mesaj oluşturacak şekilde yeniden düzenlenmesi için gereken bir sıra numarası içerir. Alıcı tarafta TCP tüm veri paketlerini toplar ve sıra numaralarına göre yeniden sıralar.

TCP Three-Way Handshake
Three-Way Handshake, TCP/IP protokolü kullanılarak bir ağ üzerinde iki cihaz arasında güvenilir bir bağlantı kurulmasını sağlayan bir süreçtir. Bu işlem, veri iletiminin her iki uçta da doğru ve güvenilir bir şekilde gerçekleşmesini garantiler. Three-Way Handshake işlemi üç ana adımdan oluşur:

https://storage.hackviser.com/file/hackviser-prod/trainings/sections/images/e46b2dee-f6fa-44de-86f2-a1e0c105d4e2/tcp-three-way-handshake-ef54efadc.webp<img width="866" height="860" alt="image" src="https://github.com/user-attachments/assets/fec87f5b-928e-47ea-bea7-08bb7a7e8f64" />


1.Adım: SYN (Synchronize Sequence Numbers)
İstemci, sunucuya bir SYN paketi göndererek bağlantı isteği gönderir. Bu paket, bağlantının kurulması için gerekli olan parametreleri içerir ve istemcinin başlangıç dizilim numarasını (sequence number) taşır. Bu numara, gönderilen her paketin sırasını belirlemek için kullanılır ve veri iletimindeki bütünlüğü sağlar.
2.Adım: SYN-ACK (Synchronize-Acknowledgment)
Sunucu, istemcinin SYN paketini alır ve bağlantı kurma isteğini kabul ederse, bir SYN-ACK paketi geri gönderir. Bu paket, sunucunun kendi başlangıç dizilim numarasını ve istemcinin dizilim numarasının bir sonraki değerini onaylayan bir onaylama (acknowledgment) numarasını içerir.
3.Adım: ACK (Acknowledgment)
İstemci, sunucunun SYN-ACK paketini alır ve bu paketi bir ACK (acknowledgment) paketi ile yanıtlar. Bu ACK paketi, sunucunun SYN-ACK paketinde belirtilen dizilim numarasının bir sonraki değerini onaylar.
User Datagram Protokolü (UDP)
Uygulamaların veri aktarımında kullandığı protokollerden biridir.
Paketlerini taşımak için önceden bir bağlantı kurulmasına gerek duyulmaz.
Verinin karşı tarafa iletilip iletilmediği kontrol edilmez.
Kaybolan verinin tekrar gönderilmesi, akış kontrolü yoktur.
Genel olarak ses ve video gönderiminde kullanılır
UDP Segment Formatı
https://storage.hackviser.com/file/hackviser-prod/trainings/sections/images/e46b2dee-f6fa-44de-86f2-a1e0c105d4e2/udpsegment-1b32f5f43.webp<img width="675" height="248" alt="image" src="https://github.com/user-attachments/assets/a49d97e3-e126-4b99-a52d-1f5dedb75c3c" />


Başlık	Açıklama
Source(Kaynak) Port	İletişimi başlatan istemci cihazın kullandığı port numarasıdır. Source port numarası, gönderen cihazın hangi uygulamasının veri gönderdiğini belirtir.
Destination(Hedef) Port	İletişimin hedefindeki bilgisayarın kullandığı port numarasıdır.
Length(Uzunluk)	Bayt cinsinden toplam bayt sayısını tanımlar.
Checksum(Hata Sınama Biti)	Opsiyona bağlı hata kontrolünü sağlar.
İnternet Katmanı

https://storage.hackviser.com/file/hackviser-prod/trainings/sections/images/e46b2dee-f6fa-44de-86f2-a1e0c105d4e2/iplayer-e6604dcf4.webp<img width="500" height="306" alt="image" src="https://github.com/user-attachments/assets/30dedb52-1f03-493b-98c7-210edf013b22" />


İnternet'in omurgasını oluşturur ve global veri iletiminin temelini sağlar.
Bir üst katmandan gelen segmentleri alıcıya, uygun yoldan hatasız ulaştırılması sağlayan katmandır.
Internet Protocol(IP) bu katmanın en önemli protokolüdür ve bu katman internet protokolü olarakda bilinir.
Internet Protocol (IP) Protokolü:

https://storage.hackviser.com/file/hackviser-prod/trainings/sections/images/e46b2dee-f6fa-44de-86f2-a1e0c105d4e2/ipencap-fda5fc6c1.webp<img width="664" height="566" alt="image" src="https://github.com/user-attachments/assets/76f11965-f43a-4ff0-a9a6-2424952791f8" />

Her cihaz, IP adresi aracılığıyla tanımlanır. Bu adresleme, internet üzerindeki her cihazın benzersiz bir şekilde tanımlanmasını ve ulaşılabilir olmasını sağlar.
Linux işletim sistemine sahip bilgisayara "ifconfig" komut ile bilgisayara atanan IP adresi görülebilir
https://storage.hackviser.com/file/hackviser-prod/trainings/sections/images/e46b2dee-f6fa-44de-86f2-a1e0c105d4e2/ifconfig-1b09f1b3f.webp<img width="1380" height="404" alt="image" src="https://github.com/user-attachments/assets/c64492d2-a79e-4ae3-8ee9-1c973a67742c" />


Veri paketleri, kaynak ve hedef IP adresleri kullanılarak, ağ üzerinde en uygun yol üzerinden yönlendirilir. Bu işlem, çeşitli yönlendirme protokolleri (RIP, OSPF, BGP) tarafından gerçekleştirilir.
Taşıma katmanından gelen pakete IP başlığı ekleyerek adresleme yapar.
IP Adresleme: Bu protokol, IP adresleri olarak bilinen mantıksal ana bilgisayar adreslerini uygular. IP adresleri internet ve daha üst katmanlar tarafından cihazı tanımlamak ve ağlar arası yönlendirme sağlamak için kullanılır.
Host-to-host iletişimi: Verilerin iletileceği yolu belirler.
Veri Kapsülleme ve Biçimlendirme: Bir IP protokolü, taşıma katmanı protokolünden gelen verileri kabul eder. Bir IP protokolü, verilerin güvenli bir şekilde gönderilip alınmasını sağlar ve verileri, IP datagramı olarak bilinen mesaja kapsüller.
Parçalanma ve Yeniden Birleştirme: Veri bağlantısı katmanı protokolü tarafından IP datagramının boyutuna uygulanan sınır, Maksimum İletim birimi (MTU) olarak bilinir. IP datagramının boyutu MTU biriminden büyükse, IP protokolü datagramı yerel ağ üzerinde seyahat edebilmeleri için daha küçük birimlere böler. Parçalama gönderici veya ara yönlendirici tarafından yapılabilir. Alıcı tarafında tüm parçalar orijinal bir mesaj oluşturacak şekilde yeniden birleştirilir.
Yönlendirme: IP datagramının LAN, MAN, WAN gibi aynı yerel ağ üzerinden gönderilmesine doğrudan dağıtım denir. Kaynak ve hedef uzak ağda olduğunda IP datagramı dolaylı olarak gönderilir. Bu, IP datagramının yönlendiriciler gibi çeşitli cihazlar aracılığıyla yönlendirilmesiyle gerçekleştirilebilir.
https://storage.hackviser.com/file/hackviser-prod/trainings/sections/images/e46b2dee-f6fa-44de-86f2-a1e0c105d4e2/iprouting-fabbe7be8.webp<img width="500" height="204" alt="image" src="https://github.com/user-attachments/assets/92e20e86-ba97-4e15-be60-967e58397b8c" />


Yukarıdaki görselde IP adresi ile router cihazları paket yönlendirmesi ile hedefe ulaşması gösterilmektedir.
https://storage.hackviser.com/file/hackviser-prod/trainings/sections/images/e46b2dee-f6fa-44de-86f2-a1e0c105d4e2/iplayerdatagram-3c2b41a1b.webp<img width="377" height="278" alt="image" src="https://github.com/user-attachments/assets/ce53fe61-f6d2-4156-80e4-f349febbebda" />


Yukarıdaki görselde, bir üst katmandan(taşıma katmanı) gelen bir TCP segmentine IP Başlığı eklendiğindeki hali verilmiştir.
IP Datagram Formatı:

https://storage.hackviser.com/file/hackviser-prod/trainings/sections/images/e46b2dee-f6fa-44de-86f2-a1e0c105d4e2/ipsegment-511c069cc.webp<img width="670" height="540" alt="image" src="https://github.com/user-attachments/assets/90dbdc2e-09c6-46f5-a16f-b35127b8ec33" />

Alan	Açıklama
Version	IP sürümünü tanımlar.IPv4, IPv6 vs.
Internet Header Length (IHL)	Datagram başlığının gerçek uzunluğunu gösterir
Type Of Service (TOS)	Paketlerin ağda nasıl önceliklendirileceğini ve işleneceğini belirtir. Düşük gecikme, yüksek bant genişliği, yüksek güvenilirlik veya düşük maliyet gibi seçenekler içerir. Günümüzde DSCP ve ECN alanları için kullanılır.
Total Length (TL)	Datagramının bayt cinsinden toplam uzunluğunu belirtir.
Identification	Veri parçaların her biri için 16 bitlik değer içerir. Alıcı tarafından veriyi yeniden birleştirmek için kullanılır.
Flags	8 Byte'lik birimler halinde parçalarin (fragment) datagram içindeki konumunu gösterir. DF (Don't Fragment) yönlendiricilerden datagrami parçalara bölmemesini buyuran 1 bitlik bir istek alandir. Alicinin parçalar (fragment) birlestiremedigi durumlarda gereklidir. MF (More Fragment): Bir datagramin son parçasi disindaki tüm par-çalarinda MF = 1' dir.
Fragment Offset	Bir mesajın parçalanması meydana geldiğinde, bu alan, genel mesajda bu parçadaki verilerin gittiği ofseti veya konumu belirtir
Time To Live (TTL)	Datagramın ağda ne kadar süre dolaşmasına izin verildiğini belirtir. Her yönlendirici, TTL alanının değerini iletmeden önce azaltır (bir azaltır). TTL alanı sıfıra düşerse yok edilir
Protocol	Bir datagramın hangi üst katman protokolüne ait olduğunu belirtir(TCP,UDP,ICMP). Alıcı IP katmanı bu lana bakarak paketi bir üstünde bulunan protokolerden hangisine ileteceğini anlar
Header Checksum	Datagram başlığında bir bozulma olup olmadığını belirlemeye yara
Source Address	Gönderici internet adresi (IP)
Destination Address	Alıcı internet adresi (IP)
Options	Opsiyonel olarak farklı amaçlar için kullanılır; güvenlik, hata raporlarma vs.
Data	Bir üst katmandan(taşıma katması) gelen veridir
Internet Control Message Protocol (ICMP) Protokolü
Kontrol amaçlı bir protokoldur.
ICMP mesajları IP protokolü üzerinden gönderilir.
Alıcı cihazın aktif olmaması veya ağ tıkanıklığı gibi olağandışı koşullar nedeniyle verileri iletimiyorsa, göndericiye veri biriminin teslim edilemediğini bildirmek için ICMP protokolü kullanılır.
Bir ICMP protokolü temel olarak iki terim kullanır:
ICMP Testi: ICMP Testi hedefin ulaşılabilir olup olmadığını test etmek için kullanılır.
ICMP Yanıtı: ICMP Yanıtı, hedef cihazın yanıt verip vermediğini kontrol etmek için kullanılır.
ICMP protokolünün temel sorumluluğu sorunları düzeltmek değil rapor etmektir. Düzeltmenin sorumluluğu gönderene aittir.
Bir IP adresini veya domain adresini test etmek için ping komutu kullanılır.
https://storage.hackviser.com/file/hackviser-prod/trainings/sections/images/e46b2dee-f6fa-44de-86f2-a1e0c105d4e2/ping-be9de99d9.webp<img width="1264" height="760" alt="image" src="https://github.com/user-attachments/assets/3bafd7c5-957b-42e1-bfc9-4e33d457a02f" />


İlk Satır: Ping komutunun hedefi ve gönderilen veri boyutunu gösterir.
Sonraki Satırlar: Her bir Echo Reply için bilgi içerir:
* Byte miktarı: Alınan yanıtın boyutu.
* ICMP_seq: Paket sıra numarası.
* TTL (Time To Live): Paketin ağ üzerinde yaşayabileceği maksimum süre/hop sayısı.
* Time: Hedeften yanıtın alınma süresi (milisaniye cinsinden).

İstatistikler:

* Gönderilen ve alınan paket sayısı, paket kaybı yüzdesi ve toplam süre.
* Round Trip Time (RTT): Min, ortalama, maksimum ve standart sapma değerleri. Bu değerler, ağ gecikmesi hakkında bilgi verir.

Çıktının Önemi:
* Paket Kaybı (%): Ağın güvenilirliği hakkında bilgi verir. Yüksek paket kaybı, ağ problemlerini gösterebilir.
* Zaman (ms): Gecikme süresi veya törelansını ifade eder. Düşük süreler, daha iyi ağ performansını işaret eder.
* TTL Değeri: Paketin ağda ne kadar süre dolaştığına dair fikir verir. Düşük TTL değerleri, paketin uzak bir hedefe ulaştığını gösterebilir.

Adress (ARP) Protokolü
ARP, Adres Çözümleme Protokolü anlamına gelir .
ARP, IP adresinden fiziksel adresi bulmak için kullanılan bir ağ katmanı protokolüdür.
İki terim esas olarak ARP Protokolü ile ilişkilidir:
ARP isteği: Gönderici cihazın fiziksel adresini bilmek istediğinde ARP isteğini ağa yayınlar.
ARP yanıtı: Ağa bağlı her cihaz ARP isteğini kabul eder ve isteği işler, ancak yalnızca alıcı IP adresini tanır ve fiziksel adresini ARP yanıtı biçiminde geri gönderir. Alıcı, fiziksel adresi hem önbelleğe hem de datagram başlığına ekler.
Adres Çözümleme Protokolü (ARP)

IP adresini MAC Adresi yardımı ile çözer
Bir IP adresi için bir ana bilgisayarın donanım adresini bulur (ve RARP için tersi).
ARP Command: arp -a


https://storage.hackviser.com/file/hackviser-prod/trainings/sections/images/e46b2dee-f6fa-44de-86f2-a1e0c105d4e2/arp-a-f29ff8b02.webp<img width="742" height="218" alt="image" src="https://github.com/user-attachments/assets/150b0ecf-2c73-419f-9209-ef5a74c52884" />

Ağ Erişim Katmanı (Network Access Layer)

OSI referans modelinde tanımlanan Fiziksel katman ile Veri Bağlantısı katmanlarını kapsar.
Verilerin ağ üzerinden fiziksel olarak nasıl gönderilmesi gerektiğini tanımlar.
Bu katman esas olarak aynı ağdaki iki cihaz arasında veri aktarımından sorumludur.
Bu katman tarafından gerçekleştirilen işlevler, IP datagramının ağ tarafından iletilen çerçevelere kapsüllenmesi ve IP adreslerinin fiziksel adreslerle eşleştirilmesidir.
Bu katmanın kullandığı protokoller ethernet, token ring, FDDI, X.25, çerçeve rölesidir.
Ağ Erişim Katmanı, veri paketlerinin fiziksel ve lojistik ağ yapıları üzerinden nasıl iletilip alınacağını tanımlar. Bu katman, cihazların birbiriyle iletişim kurabilmesi için gerekli donanım adresleme mekanizmalarını içerir.

Donanım Adresleme: Her ağ cihazı, genellikle bir MAC adresi ile tanımlanır. Bu adresleme, ağ üzerindeki cihazların birbirini tanıması ve veri iletimi için gerekli olan fiziksel adresleri sağlar.

Veri Paketleme: Ağ Erişim Katmanı, verilerin ağ ortamında iletilmesi için paketlere bölünmesini ve çerçeveleme işlemini yönetir. Bu süreç, veri paketlerinin doğru biçimde kapsüllenmesini ve hedefe ulaştırılmasını sağlar.




Protokoller ve Port

Protokoller

Bilgisayarlar birbirleriyle ağ protokolleri ile iletişim kurar.
Protokoller, makinelerin nasıl veri alışverişi yapacağını düzenleyen kurallardır ve etkili iletişim sağlar.
Bir işletim sisteminde (OS), bir protokol bir süreç veya hizmet olarak çalışabilir.
Port

Bağlantı noktaları, bir protokol işlemine veya hizmetine benzersiz bir bağlantı noktası numarası bağlayan mantıksal yapılardır.
Bilgisayarlar, ağ uygulamalarının çoklu görevi nedeniyle bağlantı noktalarına ihtiyaç duyar.
Bir bilgisayarın yalnızca bir IP adresi olabileceğinden, üzerinde çalışan ağ protokollerini ve hizmetlerini ayırt etmek için bağlantı noktalarına ihtiyaç duyar.
TCP/IP'nin 65.536 bağlantı noktası vardır
0'dan 1023'e kadar olan port numaraları iyi bilinen portlar olarak tanımlanır. Bu portlar, IANA (Internet Assigned Numbers Authority) tarafından yönetilir ve tanımlanır.Bazı önemli rezerve edilen portlar:
Servis, Protokol veya Uygulama	Port Numarası	TCP/UDP
FTP (File Transfer Protocol)	20, 21	TCP
Secure FTP (SFTP)	22	TCP
SSH (Secure Shell Protocol)	22	TCP
Telnet	23	TCP
SMTP (Simple Mail Transfer Protocol)	25	TCP
DNS (Domain Name System)	53	UDP
DHCP (Dynamic Host Configuration Protocol)	67, 68	UDP
TFTP (Trivial File Transfer Protocol)	69	UDP
HTTP (Hypertext Transfer Protocol)	80	TCP
POP3 (Post Office Protocol version 3)	110	TCP
NTP (Network Time Protocol)	123	UDP
IMAP4 (Internet Message Access Protocol version 4)	143	TCP
SNMP (Simple Network Management Protocol)	161	UDP
LDAP (Lightweight Directory Access Protocol)	389	TCP
HTTPS (Hypertext Transfer Protocol Secure)	443	TCP
Server Message Block (SMB)	445	TCP
LDAPS (Lightweight Directory Access Protocol Secure)	636	TCP
RDP (Remote Desktop Protocol)	3389	TCP
ITU Telecommunication Standardization Sector A/V Recommendation (H.323)	1720	TCP
Session Initiation Protocol (SIP)	5060, 5061	TCP
Domain Name System (DNS)

Bir alan adını karşılık gelen IP adresine çözümlemek için kullanılan protokoldür.
hackviser.com → 162.0.232.236
Varsayılan olarak UDP 53 numaralı port kullanılır. Ancak, bölge transferleri veya daha büyük yanıtlar gibi özel durumlarda TCP 53 numaralı port kullanılır.
nslookup aracı kullanarak DNS sorgusu yapılabilir.
Komut İstemcisine veya Terminal'e nslookup [alan adı veya IP adresi] yazın.
Örneğin: nslookup google.com


Simple Network Management Protocol (SNMP)

Ağ cihazlarını izlemek ve yönetmek için kullanılan protokoldür
Yöneticilerin ağ cihazlarını ve trafiğini izlemelerini ve yönetmelerini sağlar. Ağ cihazlarının durumları bellek, CPU, bant genişliği bilgiler iletmesine izin verir:
Varsayılan olarak TCP bağlantı noktası 161'i kullanır
Lightweight Directory Access Protocol (LDAP)

Dizin hizmeti sistemlerine erişmek ve bunları sorgulamak için bir araç sağlayan protokoldür
Kullanıcı adları, Parolalar, Bilgisayar Hesapları, vb.
Tipik olarak Unix/Linux tabanlı veya Microsoft Active Directory tabanlı olarak çalışır.
Varsayılan olarak TCP 389 kullanır
LDAP Secure (LDAPS)

LDAP ağ trafiğini şifrelemek için SSL kullanan güvenli bir LDAP sürümüdür.
Varsayılan olarak TCP bağlantı noktası 636'yı kullanır
Server Message Block (SMB)

Microsoft ortamlarında yaygın olarak kullanılan ağ ve dosya paylaşım protokolüdür
Sistemlerin dosyalarını ve yazıcılarını diğer sistemlerle paylaşmasını sağlar
Varsayılan olarak TCP bağlantı noktası 445'i kullanır
Telnet

Uzak bir ana bilgisayara "güvensiz" bir şekilde bağlanmak için kullanılan eski protokoldür
Veriler açık metin olarak aktarılır, bu nedenle güvensiz olarak kabul edilir
Günümüzde öncelikle yönlendiriciler gibi yönetilen ağ cihazlarına seri bağlantı üzerinden erişmek için kullanılır
Varsayılan olarak TCP Bağlantı Noktası 23'ü kullanır
Secure Shell (SSH)

Uzak bir ana bilgisayara güvenli bir şekilde bağlanmak için kullanılan bir kriptografik protokoldür
Bir terminal konsolu kullanır
Verileri açık anahtar altyapısı (PKI) ile şifreleyerek güvenli hale getirir
Varsayılan olarak TCP bağlantı noktası 22'yi kullanır
Remote Desktop Protocol (RDP)

Kullanıcıların bir bilgisayara uzaktan bağlanmasına, görüntülemesine ve kontrol etmesine olanak tanıyan bir Microsoft protokolüdür
Uzak bilgisayardan Windows masaüstüne erişim sağlar .
Microsoft işletim sisteminde yerleşiktir.
Varsayılan olarak TCP bağlantı noktası 3389'u kullanır
File Transfer Protocol (FTP)

Bilgisayar arasında dosya aktarmak için kullanılan protokoldür
Yapılandırmaya göre kullanıcı adı ve parola ile kimlik doğrulaması yapabilir veya anonim girişleri kullanabilir.
Veriler açık metin olarak aktarılır, bu nedenle güvensiz kabul edilir
Dosyaları ve klasörleri görüntüleme, listeleme, ekleme, silme işlemleri yapılabilir.
Varsayılan olarak veri Transferleri için 20, kontrol için 21 portunu kullanır.
Secure File Transfer Protocol (SFTP)

SSH üzerinden şifreli bir şekilde dosya aktarımı sağlar
Varsayılan olarak TCP bağlantı noktası 22'yi kullanır (SSH ile aynı bağlantı noktası)
Simple Mail Transfer Protocol (SMTP)

E-postaları bir e-posta istemcisinden hedef e-posta sunucusuna iletmek için kullanılan e-posta protokolüdür.
Varsayılan olarak TCP Bağlantı Noktası 25'i kullanır
Post Office Protocol Version 3 (POP3)

Bir e-posta sunucusundan e-postaları almak için kullanılan e-posta protokolüdür
Varsayılan olarak TCP Bağlantı Noktası 110'u kullanır
Internet Message Access Protocol (IMAP)

POP3'ün yerini alan bir başka e-posta protokolüdür
Kullanıcıların sunuculardaki e-postalara erişmesine ve e-postayı sunucuda okumasına ya da istemci makineye indirmesine olanak tanır
Varsayılan olarak TCP bağlantı noktası 143'ü kullanır
Hypertext Transfer Protocol (HTTP)

World Wide Web (WWW) için tarama hizmetleri sağlayan protokoldür
Bir internet sayfasının içeriğini bir web sunucusundan alır.
İstekler hiper metin işaretleme dilinde (HTML) yapılır ve tarayıcınıza bu formatta döndürülür
Veriler düz metin olarak gönderilir
Varsayılan olarak TCP Bağlantı Noktası 80'i kullanır
HTTP Secure (HTTPS)s

HTTP içeriğini şifrelemek için SSL/TLS kullanan güvenli bir HTTP sürümüdür.
Açık Anahtar Altyapısı (PKI) kullanır
Varsayılan olarak TCP Bağlantı Noktası 443'ü kullanır



Media Access Control Address (MAC)

Ağ bağdaştırıcı kartının(NIC) fiziksel adresidir ve benzersizdir.
Altı bayt 48 bit 'den oluşur.
İlk üç bayt (24 bit) IEEE tarafından üreticiye atanır ve cihazın hangi üretici olduğu mac adresine bakılarak anlaşılabilir
Örnek bir MAC adresi : 00:21:70:6f:06
00-21-70-6F-06-F2
FF:FF:FF:FF:FF
adresi tüm cihazlara yayın yapmak (broadcast) için kullanılır.
Internet Protocol(IP)

IP Adresi, ağ üzerindeki bir cihazı benzersiz bir şekilde tanımlamak için kullanılan mantıksal bir adrestir.
IP sürüm 4 (IPv4 ve IP sürüm 6 (IPv6) olarak iki Versiyon vardır:
IPv4

Gösterim	1.Oktet (8 Bit)	2.Oktet (8 Bit)	3.Oktet (8 Bit)	4.Oktet (8 Bit)
Ondalık	192.	168.	1.	10
Binary	11000000	10101000	00000001	00001010
32 ikili bitten oluşmaktadır ve her biri Dört oktete bölünmüştür.

Her oktet ondalık sayıya dönüştürülür ve bir nokta ile ayrılır. Örnek IP adresi: 192.168.1.10

Her bir alan bir biti ifade eder ve her bir oktet 8 bitten oluşur.

Her bir bit yer sağdan sola doğru 2 nin kuveti artan şeklinde gösterilir.

Oktedi 192 olan bir IP adresini binary (ikili) forma çevirmek için, en soldan başlayarak uygun sayıda 1 eklenir. Eklenen her 1, bitin temsil ettiği 2'nin kuvveti olan bir değere karşılık gelir. Ardından, 1 eklenen değerler toplanarak kontrol edilir.

2⁷	2⁶	2⁵	2⁴	2³	2²	2¹	2⁰	
128	64	32	16	8	4	2	1	
1	1	0	0	0	0	0	0	128 + 64 = 192
Bir IP adresi iki bölüme ayrılır:

Ağ Adresi
Her ağı benzersiz bir şekilde tanımlar
Muhasebe birimini için oluşturulan bir ağ örnek verilebilir.
Host Adresi
Ağdaki her makineyi benzersiz bir şekilde tanımlar
Muhasebe biriminde bulunan bir bilgisayarı örnek verebiliriz.
IPv4 Adres Bileşenleri

Bir ağdaki her cihaza bir IP adresi, alt ağ maskesi ve varsayılan ağ geçidi atanır:
IP Adresi: Bir ağdaki her cihaza atanan benzersiz mantıksal adres.
Alt Ağ Maskesi(Subnet Mask): Alt Ağ Maskesi, bir cihazın hangi alt ağda olduğunu belirlemek için kullanılan bir değerdir. IP adresinin ağ kısmını ve cihazın kendisini belirler. Bu maskenin uzunluğu, belirli bir IP adresinin ağ kısmının ne kadar olduğunu belirtir. Örneğin, 255.255.255.0 (IPv4) alt ağ maskesi, son 8 bitin cihazı tanımladığını ve önceki 24 bitin ağ kısmını tanımladığını gösterir.
Varsayılan Ağ Geçidi(Default Gateway): Varsayılan Ağ Geçidi, yerel ağdaki cihazların diğer ağlarla iletişim kurmasını sağlayan bir ağ yönlendiricisinin IP adresidir. Bir cihaz, bir başka ağdaki bir cihaza veri göndermek istediğinde, bu veri önce varsayılan ağ geçidine iletilir ve ardından hedef ağdaki cihaza yönlendirilir. Bu, cihazın dış ağlarla iletişim kurmasını sağlar.
Windows bilgisayarlarda ipconfig(Internet Protocol Configuration), linux tabanlı işletimsistemlerinde ifconfig (Interface Config) komutu ile bilgisayarınıza atana IP, alt ağ maskesi ve Varsayılan ağ geçidi bilgileri görülür.





IPV4 Adress Sınıfları

Ağ adreslerine göre ve büyüklüklerine göre IP adresi sınıflara ayrılmıştır.

Sınıf	Ağ Bitleri	Host Bitleri	Adres Aralığı
A	8	24	1.0.0.0 - 126.255.255.255
B	16	16	128.0.0.0 - 191.255.255.255
C	24	8	192.0.0.0 - 223.255.255.255
Ağ bitleri o ağı gösterirken , host bitleri o ağdaki bilgisayarların gösterir.
Alt Ağlar(Subnet)

Alt ağlar, büyük bir ağı daha küçük ve daha yönetilebilir parçalara bölmek için kullanılan bir ağ tasarımı konseptidir. Ana ağdaki cihazları mantıksal olarak gruplayarak, ağ trafiğini daha iyi yönetmeyi ve ağ güvenliğini artırmayı sağlarlar.

Alt ağlar genellikle ağdaki cihaz sayısını azaltmak, ağ trafiğini yerel seviyede tutmak ve ağ yönetimini kolaylaştırmak amacıyla kullanılır. Ayrıca, alt ağlar, ağdaki farklı departmanlar veya işlevler arasında güvenlik duvarları oluşturarak ağ güvenliğini artırabilirler.

Alt ağlar, alt ağ maskesi (subnet mask) adı verilen bir değerle tanımlanır. Alt ağ maskesi, bir IP adresinin ağ kısmını ve cihaz kısmını ayırt etmek için kullanılır. Örneğin, 255.255.255.0  alt ağ maskesi, son 8 bitin cihazı tanımladığını ve önceki 24 bitin ağı tanımladığını belirtir.

Bu şekilde, alt ağlar, ağ yöneticilerine ağlarını daha iyi organize etme ve yönetme esnekliği sağlar ve ağdaki performansı ve güvenliği artırır.

Alt Ağlarda CIDR(Classless Inter-Domain Routing) Gösterimi
Alt Ağ Maskesinin ne olduğunu belirtmenin kısa yoludur.

192.168.1.0 /24 şeklinde gösterilir. IP adresi 192.168.1.0 olduğunu gösterirken ve alt ağ adresi adresinin 255.255.255.0 olduğunu gösterir
/24 = 11111111.11111111.11111111.00000000
/24 = 255.255.255.0
Hosts
Bir ağda kaç bilgisayar olduğunu bulmak için host bitleri sayısı 2 nin üssünün 2 eksiği formülü ile bulunur.

Bir ağda, ağ adresini tanımlamak için ve tüm cihazların yayın yapabildiği yayın adresi vardır.
İki çıkarıyoruz ağ adresi ve yayın adresi içerir.
192.168.1.0 /24   adresi için kaç tane bilgisayar  IP adresi verilebileceği gösterilmiştir.

Ağ Bitleri: 11111111.11111111.11111111.00000000 / 24
Host Bitleri: 00000000.00000000.00000000.11111111

2⁸-2  = 254  adet bilgisayar bu ağda adreslenebilir.

Genel ve Özel IP Adresleri

Genel IP Adresleri
Genel IP adresleri, internet üzerindeki cihazların birbirleriyle iletişim kurması için kullanılan, genellikle İnternet Servis Sağlayıcıları (ISS) tarafından atanmış olan benzersiz global IP adresleridir.
İnternet üzerindeki herhangi bir cihaz tarafından erişilebilir ve tanınabilir.
Bu adreslerin ataması, küresel bir IP adresi havuzundan yapılmaktadır ve uluslar arası kuruluşlar tarafından yönetilmektedir.
Genel IP adresleri, internete doğrudan erişilebilir ve genellikle halka açık sunucular, web siteleri, e-posta sunucuları vb. için kullanılır.
Özel IP Adresleri
Özel IP adresleri, yerel ağlarda kullanılan ve internet üzerinde kullanılmayan, benzersiz IP adresleridir.
Özel IP adresleri, RFC 1918 standartlarına uygun olarak belirlenmiş özel adres aralıklarından atanır.
Bu adresler, LAN (Yerel Ağ) veya ev ağlarında kullanılır ve internete doğrudan erişilemez.
Özel IP adresleri, NAT (Network Address Translation) kullanılarak internete erişim sağlayan cihazlar (örneğin, ev yönlendiricileri) tarafından genel IP adresleriyle çevrilir
Tür	Başlangıç IP Adresi	Bitiş IP Adresi	Alt Ağ Maskesi
Genel	0.0.0.0	126.255.255.255	0.0.0.0/1
128.0.0.0	191.255.255.255	128.0.0.0/2
192.0.0.0	223.255.255.255	192.0.0.0/3
224.0.0.0	239.255.255.255	224.0.0.0/4
240.0.0.0	255.255.255.254	240.0.0.0/4
Özel	10.0.0.0	10.255.255.255	10.0.0.0/8
172.16.0.0	172.31.255.255	172.16.0.0/12
192.168.0.0	192.168.255.255	192.168.0.0/16
169.254.0.0	169.254.255.255	169.254.0.0/16
Geri Döngü Adresi - The Loopback Address

Genellikle 127.0.0.1 şeklinde ifade edilen ve bilgisayar ağlarında kullanılan bir IP adresidir. Bu adres, bilgisayarın kendi ağ kartına yönlendirilen verilerin dönüp geri geldiği sanal bir adresdir. Loopback adresi, bir bilgisayarın kendi kendine iletişim kurması ve ağ uygulamalarını test etmesi için kullanılır.

Bir web geliştiricisi, yerel olarak bir web sunucusu çalıştırıyorsa ve bu sunucuya tarayıcıdan erişmek istiyorsa, web tarayıcısında http://127.0.0.1 veya http://localhost adresini kullanabilir. Bu adresler, bilgisayarın kendi kendine dönük iletişimini sağlar ve böylece geliştirici, web uygulamasını yerel makinesinde test edebilir.


IP Subnetting (Alt Ağ Oluşturma )

IP Subneting, IP (Internet Protocol) adreslerini daha küçük alt ağlara bölme işlemidir. Bu, ağ yöneticilerinin daha etkili bir şekilde IP adreslerini tahsis etmelerini ve ağ trafiğini yönetmelerini sağlar.
IP adreslerini mantıksal olarak gruplandırarak ağ trafiğini yönlendirme ve ağ segmentasyonunu kolaylaştırır.
A, B veya C sınıfı bir ağdan daha fazla alt ağ (alt ağ) oluşturmak için host bitlerinden ödünç alınarak alt ağlar oluşturulur.
Host bitinden ödünç alındığında yeni alt ağlar oluşur ve ağda kullanılabilecek IP adresi sayısı azalır.
Her alt ağ, kendi IP adres aralığına ve alt ağ maskesine sahiptir.
Alt ağın ilk adresi (network adresi), son adresi (broadcast adresi), ve kullanılabilir ilk ve son IP adresleri belirlenir.
FLSM ve VLSM

FLSM (Fixed Length Subnet Masking)
FLSM, tüm subnetlerin aynı boyutta olacağı şekilde bir IP adres alanını bölme yöntemidir. Bu yaklaşım, basit ve düzenli olması sebebiyle yönetimi kolaylaştırır, ancak IP adreslerinin verimsiz kullanımına yol açabilir.

Örnek:
192.168.1.0/24 ağ adresini 4 eşit host sayılı alt ağ bölmek için aşağıdaki adımlar uygulanır.

1.Alt ağ maskesi Bulma

Dört eşit subnete bölebilmek için 2 adet bit (2^2=4 ) ödünç alınır.
Bölünmeden önce  Ağ adresinin alt ağ maskesi

CIDR: /24
Binay: 11111111.11111111.11111111.00000000
Ondalık gösterim: 255.255.255.0
2 adet  ödünç bit alındığında yeni alt ağ maskesi:

CIDR: /26
Binay: 11111111.11111111.11111111.11000000
Ondalık gösterim: 255.255.255.192
Ödünç alınan oktet ile ağların ağ adresleri bulunur

2.Ağ adresleri Hesaplama

2⁷	2⁶	2⁵	2⁴	2³	2²	2¹	2⁰	Alt Ağın Başlangıç Adresi
1	1	0	0	0	0	0	0	
192.168.1.	0	0	0	0	0	0	0	0	0
192.168.1.	0	1	0	0	0	0	0	0	64
192.168.1.	1	0	0	0	0	0	0	0	128
192.168.1.	1	1	0	0	0	0	0	0	192
Ağ adresleri

Alt Ağlar	Ağ Adresi	Kullanılabilir Host Aralığı	Broadcast Adresi
1.	192.168.1.0/26	192.168.1.1 - 192.168.1.62	192.168.1.63
2.	192.168.1.64/26	192.168.1.65 - 192.168.1.126	192.168.1.127
3.	192.168.1.128/26	192.168.1.129 - 192.168.1.190	192.168.1.191
4.	192.168.1.192/26	192.168.1.193 - 192.168.1.254	192.168.1.255
VLSM (Variable Length Subnet Masking)

VLSM, subnetlerin farklı boyutlarda olabileceği bir IP adresi bölme yöntemidir. Bu yaklaşım, IP adreslerinin daha verimli kullanımını sağlar çünkü her subnetin ihtiyaç duyduğu adres sayısına göre ayarlanabilir.

Örnek

Alt ağ : 50 cihaz
Alt Ağ : 30 cihaz
Alt Ağ : 10 cihaz
Alt Ağ : 2 cihaz
192.168.1.0/24 ağ adresi için oluşturulacak alt ağlar ve bu ağlarda kullanılacak cihaz sayılarına göre alt ağlara bölmek için aşağıdaki adımlar uygulanır.

1.Alt ağ maskelerini Bulma:

Cihaz sayısına göre host biti bulunur ve host bitinin haricinde kalan bitler alt ağ maskesini verir.

Adreslenebilir host veya cihaz sayısını bulabilmek için 2^n-2 formülü kullanılır. Buradaki n host bitini ifade eder.

1. Ağ -  50 cihaz

2⁶ -2 = 62
6 bitlik bir host biti alınılarak yeterli sayıda IP oluşturulur.
Host : 00000000.00000000.00000000.00111111
Alt Ağ Maskesi: 11111111.11111111.11111111.11000000 (/26)
2. Ağ -  30 cihaz

2⁵ -2 = 32
5 bitlik bir host biti alınılarak yeterli sayıda IP oluşturulur.
Host : 00000000.00000000.00000000.00011111
Alt Ağ Maskesi: 11111111.11111111.11111111.11100000 (/27)
3. Ağ -  10 cihaz

2⁴ -2 = 14
4 bitlik bir host biti alınılarak yeterli sayıda IP oluşturulur.
Host : 00000000.00000000.00000000.00001111
Alt Ağ Maskesi: 11111111.11111111.11111111.11110000 (/28)
4. Ağ -  2 cihaz

2² -2 = 2
2 bitlik bir host biti alınılarak yeterli sayıda IP oluşturulur.
Host : 00000000.00000000.00000000.00000011
Alt Ağ Maskesi: 11111111.11111111.11111111.11111100 (/30)
2.Ağ adresleri Hesaplama

VLSM'de, alt ağlar başlangıçta en küçükten sıralanır ve adres oluşturulur.
Diğer ağların başlangıç adresi alt ağ maskesine ve önceki  ağın bitiş adresine göre belirlenir.

Bir önceki ağın host bitleri + 1 formülü ile ağın başlangıç adresi belirlenir 

Son Okted

2⁷	2⁶	2⁵	2⁴	2³	2²	2¹	2⁰	Ağ Adresi
1.Ağ	1	1	X	X	X	X	X	X	192.168.1.0\26
2.Ağ	1	1	1	X	X	X	X	X	192.168.1.64\27
3.Ağ	1	1	1	1	X	X	X	X	192.168.1.96\28
4.Ağ	1	1	1	1	1	1	X	X	192.168.1.112\30

