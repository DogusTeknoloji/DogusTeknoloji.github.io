---
layout: post
title:  "Open Source Proje Geliştirme - Duygu Özkan"
categories: ["Açık Kaynak"]
tags: ["Açık Kaynak", duyguozkan]
permalink: acik_kaynak_duygu_ozkan
---

[Pdf versiyon](/assets/acik-kaynak/duygu-ozkan/Duygu_Ozkan-Open_Source_Proje_Gelistirme.pdf)

# AÇIK KAYNAK KODLU YAZILIM GELİŞTİRMENİN GEÇMİŞİ

Açık kaynak kodlu yazılım geliştirme dediğimizde Richard Matthew Stallman internet dünyasında
bilinen ismiyle RMS’den bahsetmemek büyük haksızlık olur kanısındayım. Amerikalı özgür yazılım
aktivisti, sistem uzmanı ve yazılım geliştirici olan Stallman, GNU Projesi ve Özgür Yazılım Vakfı’nın da
kurucusudur. 1971 senesinde, Harvard Üniversitesi birinci sınıf öğrencisiyken katıldığı MIT Yapay Zeka
laboratuvarında oradaki meslektaşlarıyla birlikte [TECO](http://www.wikizeroo.net/index.php?q=aHR0cHM6Ly9lbi53aWtpcGVkaWEub3JnL3dpa2kvVEVDT18odGV4dF9lZGl0b3Ip), [Emacs](http://www.wikizeroo.net/index.php?q=aHR0cHM6Ly9lbi53aWtpcGVkaWEub3JnL3dpa2kvRW1hY3M)‘ın ilk versiyonları ve [Lips](http://www.wikizeroo.net/index.php?q=aHR0cHM6Ly9lbi53aWtpcGVkaWEub3JnL3dpa2kvTGlzcF9tYWNoaW5l) işletim sistemi
üzerinde çalışmalar yapmıştır.

Ne yazık ki, laboratuvardaki güzel günler çok uzun sürememiş,1970’lerin sonuna 1980’lerin başında,
üretici firmaların telif haklarıyla alakalı yaptıkları baskılar sonucu dünyada artık “Proprietary software”
denilen telif haklarının üretici firmalar tarafından sahiplenildiği tescilli yazılımlar hüküm sürmeye
başladı. Bunun sonucu burada çalışan yetenekli çalışanlar özel şirketlere kaptırıldı, iş birliği azaldı, işler
sıradanlaştı ve maalesef 1980’lerin başında MIT Yapay Zeka Laboratuvarı kapatıldı. Stallman bu duruma
çok içerledi ve kendisine aşağıda direkt kendi cümlelerinden oluşan şu soruyu sordu. **Toplumun neye
ihtiyacı var?**

_“Toplumun ihtiyacı nedir? Vatandaşların gerçekten ulaşılabilir bilgiye ihtiyacı var – örneğin, insanların
sadece kullanmakla kalmayıp okuyabileceği, düzeltebileceği, adapte olup geliştirebileceği programlar
gibi. Fakat elimizde yazılım üreticilerinin sunduğu, bizim içeriğini değiştirip üzerinde çalışmalar
yapamayacağımız kapalı kutu niteliğinde programlar var._

_Toplumlar aynı zamanda özgürlüğe ihtiyaç duyuyor. Bir programın sahibi varsa, kullanıcılar kendi
yaşamlarının bir bölümünü kontrol etme özgürlüğünü kaybederler._

_Ve hepsinden öte, toplumun vatandaşlarında gönüllü işbirliği ruhunu teşvik etmesi gerekir. Yazılım
sahipleri bize, komşularımıza doğal bir şekilde yardım etmenin “korsanlık” olduğunu söylediğinde,
toplumumuzun sivil ruhunu kirletiyorlar._

_Bu nedenle, özgür yazılımın fiyat değil, özgürlük meselesi olduğunu söylüyoruz._

_— Richard Stallman, [Why Software Should Not Have Owners](https://www.gnu.org/philosophy/why-free.html)_

Stallman bundan sonra tüm enerjisini açık kaynak kodlu yazılım savunuculuğuna yöneltti, bu sıralarda
dünyanın bir çok yerinde açık kaynak kodlu yazılım geliştirme zaten uygulanmaktaydı. University of
California’da kurulan BSD(Berkeley Software Distribution) buna ilk örneklerden sayılabilir. BSD
geliştirdiği yazılımları, ki aralarında TCP/IP protokol takımı gibi Internetin belkemiğini oluşturan kodlar
da vardır, tamamen açık şekilde herkesin takdirine sunmaktaydı. Fakat tıpkı MIT AI Lab gibi, BSD’de
kendi geliştirdiği kodların bir başkası tarafından alınarak ticari amaçla kullanılmasını yaşamıştır.

Stallman tüm bunların ışığında, 1984’te GNU Projesini başlatmıştır. Özgür bir yazılım topluluğu
oluşturmak için en gerekli şeyin açık kaynak kodlu ve ücretsiz bir işletim sistemi yaratmak olduğuna
inandı ve GPL (General Public Licence) lisans altyapısını öne sürdü. Böylece herkesin katkı sağlayıp
geliştirebileceği verimli bir ortam yaratılmış olacaktı.

1985’te GNU projesini destekleyecek fonu sağlayabilmek adına Özgür Yazılım Vakfı kuruldu. Bu vakıf
bir yazılımın özgür olup olmadığını tanımlamak için günümüzde hala geçerli olan 4 kuralı uygular.

- Herhangi bir amaç için programı istediğiniz gibi çalıştırabilirsiniz.
- Programı kendi ihtiyaçlarınıza göre değiştirebilirsiniz. (Bu özgürlüğü pratikte etkin kılmak için,
    kaynak koduna sahip olmadan bir programda değişiklik yapmak son derece zor olduğundan,
    kaynak koduna erişiminiz olmalıdır.)
- Program kopyalarını ücretsiz olarak dağıtabilirsiniz.
- Programın değiştirilmiş versiyonlarını dağıtın, böylece topluluk geliştirmelerinizden
    yararlanabilir.

GNU projesi 1990’ların başında Linux ile birleşerek, Stallman’ın çok önceden ön gördüğü özgür işletim
sistemi böylece GNU/Linux olarak vücut buldu ve şu an dünyada en büyük kurulum sayısına sahip genel
amaçlı işletim sistemi olmuştur.

Açık kaynak kodlu yazılım geliştirmenin gelişiminde mihenk taşı sayılabilecek bir diğer önemli gelişme
ise, 1997 yılında Eric S. Raymond tarafından yayınlanan [The Cathedral and the Bazaar](http://www.wikizeroo.net/index.php?q=aHR0cHM6Ly9lbi53aWtpcGVkaWEub3JnL3dpa2kvVGhlX0NhdGhlZHJhbF9hbmRfdGhlX0JhemFhcg) makalesinde
birleşmelerinden önce, Linux ve GNU Projesinin geliştirilme şeklini karşılaştırmıştır. Raymond’un bu
makalede tariflediği -Release Early,Release Often, Refactoring of Code- gibi prensiplerin çoğu daha
sonra Agile geliştirmenin ve Devops kültürünün temelini oluşturmuştur.

1998'de Eric Raymond makalesini yazmasından kısa bir süre sonra, Netscape, “The Bazaar”
yaklaşımından büyük ölçüde etkilenen Netscape Communicator kodunu açmaya karar verdi.

Bu kadar tarih dersinden sonra, açık kaynak kodlu yazılım geliştirmenin nasıl bu kadar önem
kazandığını, dünyanın ticari yazılım devlerini bile bu akıma katmayı başaran gücünü nereden aldığını
inceleyemeye başlayalım. :)

# AÇIK KAYNAK KODLU YAZILIM GELİŞTİRMENİN GÜCÜ VE YAYGINLAŞMA NEDENLERİ

Fɾee Softwaɾe Foundation'ın yaygınlaştıɾdığı GPL gibi açık lisanslama yöntemleɾi ADSL Modemleɾ,
Wiɾeless (Wifi) cihazlaɾın ("Embedded Linux" gibi uygulamalaɾ sayesinde) üst düzeyde peɾfoɾmansı en
hesaρlı şekilde sunmasını sağlamıştıɾ. Bu bağlamda Inteɾnet pɾotokolü yazılımlaɾının (öɾneğin "TCP/IP
Stack") 90'lı yıllaɾda Inteɾnet'in patlamasına yol açması gibi günümüzde ADSL, WiFi, GPRS/EDGE/3G
cihazlaɾının milyaɾlaɾca insan taɾafından benimsenip kullanılmasının da teknolojileɾin özgüɾ şekilde
geliştiɾilip heɾkese açık şekilde sunulması sayesinde geɾçekleşmiş olduğundan bahsedilebiliɾ.

Aslında tarihçesini incelediğimizde adım adım nasıl büyüdüğünü, gücünü felsefesinden aldığını açıkça
görüyoruz.

1990'ların sonlarında, bir dizi yüksek profilli olaylar serbest ve açık kaynaklı yazılımların
profesyonelleşmesinde büyük bir artışa yol açtı. Bunlar arasında, en yüksek profilli olaylar 1999'da VA
Linux ve Red Hat'in halka arz şirketleri oldu. Her iki şirketin de halka açık şirketler olarak açılış
günlerinde hisse fiyatlarında büyük kazanımlar oldu.

Ayrıca 1999'da IBM, geliştirilmesine 1 milyar dolar yatırım yaparak Linux’u desteklediklerini açıkladı,
bu da geleneksel kurumsal kullanıcılar için daha az riskli olduğunu belirtti. Ertesi yıl Sun Microsystems,
kaynak kodunu platformlar arası ofis paketi StarOffice'e yayınladı ve OpenOffice.org projesini yarattı.

Açık kaynaklı projelerin büyük Silikon Vadisi fonlarının bir araya getirilmiş etkisi, Wall Street'in açık
kaynaklı yazılım etrafında inşa edilen genç şirketler için dikkatleri ve IBM ve Sun Microsystems gibi
teknoloji devlerinin getirdiği pazar güvenilirliği, açık kaynağın büyük ölçüde benimsenmesini sağlamak
için birleşti. ve gelişmesine yardımcı olan açık kalkınma modelinin benimsenmesi bugün teknoloji
endüstrisinde Linux'un ve açık kaynakların hakimiyetine yol açtı.

2010 yılında yapılan bir anket, işletmelerin %98’inin açık kaynaklı yazılım kullandığını göstermiştir.

Lisanslı yazılımların dünya üzerindeki en büyük ismi olarak Microsoft’u vermek yanlış olmaz sanıyorum,
açık kaynak kodlu yazılımların günümüzde aldığı önem ve yerin en büyük ispatı olarak, Microsoft’un
açık kaynak kodu destekler yönde yaptığı hareketleri gösterebiliriz.

Peki neredeyse tüm dünya bu felsefenin bilincine ve öneminin farkına varmışken, biz nasıl iyi bir açık
kaynak kodlu yazılım geliştiricisi veya gönüllüsü (bilinen adıyla open source citizen) oluruz?

Bunun cevabını ben kendi adıma şu şekilde veriyorum, açık kaynak kodlu geliştirme özünde tüm
insanlığın yararına üretilmiş bir akım olduğuna göre, ben de dünyaya katkıda bulunabilirim hissi ile
yaklaşırsak işin felsefesini kavrayabilirsek her şey aydınlanacaktır aslında. Örneğin, yararlandığınız bir
kaynak kod çalışmıyor ise “bu çalışmıyor” demek yerine çalışması için neler yapabilirim diye araştırma
yapmak, geliştirmesine katkı sağlamak, yapıcı geri bildirimler vermek, açık kaynak paylaşım
platformlarında bu şekilde aktif katılımcı olmak hem sizi hem de dünyayı geliştirecektir. İyi bir open
source citizen olmak için illaki sıfırdan birşeyler üretip github vs. ortamlarda paylaşma şartı olmadığını,
mevcuttaki çalışmalar kodlama yapmasak bile aktif katılımcı olarak, fikirlerimizle, geri bildirimlerimizle
bile katkı sağlayabileceğimizi düşünüyorum. Sonuçta hepsi insanlık ve dünya için

Burada Paul McCartney’in güzel bir sözü ile bitirebilim sözü :

_“In the end, the love you take is equal to the love you make.”_

Konunun biraz daha teknik detaylarına bakalım birazda. Lisanslama seçenekleri...

# AÇIK KAYNAK KODLU LİSANSLAMA SEÇENEKLERİ

Açık kaynak lisansları ilk bölümde bahsettiğim, açık kaynak tanımlarına uyan lisanslardır, kısaca;
yazılımların serbestçe kullanılmasına, değiştirilmesine ve dağıtılmasına izin verir. Lisans sistemi, açık
kaynaklı yazılım hareketi ve altında yatan felsefeyi geliştirebilmek adına hazırlanmış ve yazılım
geliştiren kişiler tarafından ortak bir projeye katkı sunmadan önce üzerinde anlaşılması gereken bir
yeniden uyarlama ve yeniden kullanabilme politikası olarak anlaşılmalıdır.

Açık Kaynak Girişimi(OSI) tarafından onaylanması için bir lisansın Açık Kaynak Girişimi lisans inceleme
sürecinden geçmesi gerekir.


**Copyleft** kavramı: Copyleft, bir programın (veya başka bir çalışmanın) özgür yazılım haline getirilmesi,
programın tüm değiştirilmiş ve genişletilmiş sürümlerinin de özgür yazılım haline getirilmesi için genel
bir yöntemdir.

Bir programı özgür hale getirmenin en basit yolu, telif hakkını kaldırıp programı kamu malı haline
getirmektir.

Bir programı copyleft etmek için, ilk olarak telif hakkının olduğunu ifade ederiz; daha sonra yalnızca
dağıtım terimleri değişmemişse, bu programdan elde edilen herhangi bir programın ya da bu program
kodunun kullanım haklarının, değiştirme ve yeniden dağıtım haklarının herkese verildiği yasal bir araç
olan dağıtım terimlerini ekleriz. Bu nedenle, kod ve özgürlükler yasal olarak ayrılamaz hale gelir.

OSI tarafından kabul görmüş en popüler lisansları aşağıdaki gibi özetleyebiliriz.

- Apache License 2.
- BSD 3-Clause "New" or "Revised" license
- BSD 2-Clause "Simplified" or "FreeBSD" license
- GNU General Public License (GPL)
- GNU Library or "Lesser" General Public License (LGPL)
- MIT license
- Mozilla Public License 2.
- Common Development and Distribution License
- Eclipse Public License

## Lisanslar Yapabilecekleriniz Yapamayacaklarınız Zorunda olduklarınız

| Lisanslar | Yapabilecekleriniz | Yapamayacaklarınız | Zorunda olduklarınız |
|-----------|--------------------|--------------------|----------------------|
| GNU | - Ticari olarak kullanabilirsiniz<br>- Değiştirebilirsiniz<br>- Dağıtabilirsiniz<br>- Yazarı sorumlu tutamazsınız | - Lisanslayamazsınız | - Orjinalini bulundurmalısınız |
| MIT | - Ticari olarak kullanabilirsiniz<br>- Değiştirebilirsiniz<br>- Dağıtabilirsiniz<br>- Lisanslayabilirsiniz<br>- Hususi Kullanabilirsiniz | - Yazarı sorumlu tutamazsınız | - Telif bulundurmalısınız<br>- Lisansı bulundurmalısınız |
| Apache | - Ticari olarak kullanabilirsiniz<br>- Değiştirebilirsiniz<br>- Dağıtabilirsiniz<br>- Lisanslayabilirsiniz<br>- Hususi Kullanabilirsiniz | - Yazarı sorumlu tutamazsınız<br>- Yazarların isimlerini kullanamazsınız | - Telif bulundurmalısınız<br>- Lisansı bulundurmalısınız<br>- Değişiklikleri belirtmelisiniz<br>- Değişiklikleri bildirmelisiniz |

Lisanslamak için yapmanız gereken lisansınızın tam kopyasını projenizin içine LICENCE adlı bir dosyaya
koymaktır. Bunu haricinde yazılan her dosyanın başına lisans bilgisini koymak faydalıdır.

# AÇIK KAYNAK KODLU GELİŞTİRMEYE HİZMET VEREN SERVİSLER

Açık kaynak kodlu uygulama geliştirme denince aklımıza gelen üç sistemi sıralayarak başlayabiliriz.

**Git** - Yazdığımız projeleri ve uygulamaları, bilgisayarımızda ya da harici disklerde değil de internet
üzerinde tutmamızı ve yönetmemizi sağlayan bir versiyon kontrol sistemidir.

**Github** - GNU Genel Kamu Lisansı’nın 2. sürümüyle lisanslanmış bir özgür yazılımdır.An itibariyle açık
kaynak kodlu projeler tarafından tercih edilen en popüler depolama servisidir.

**GitLab** - Github’ın kullanıcılara sağladığı işlevlerin tamamını sunan bir Git servisidir. Açık kaynak(open
source) projelerinizi bu servis üzerinde ücretsiz bir şekilde oluşturabilir ve yönetebilirsiniz. Gitlab daha
çok firmalarda tercih ediliyor çünkü : Ücretsiz sürümünde kendi sunucularınıza kurarak sadece kurum
içi kullanıcıların erişebileceği Gitlab servisi hizmeti bulunmaktadır.

**.NET Core** - Daha önce de bahsettiğim gibi, açık kaynak kodlu yazılım geliştirmenin gücünün en büyük
ispatı olarak en büyük ticari yazılım sağlayıcılardan olan Microsoft’un bu dünyaya girmesiydi.
Microsoft’un bu konuda yaptığı en büyük atılımın; bildiğimiz Asp.Net platformunun açık kaynak kodlu,
sadece Windows özelinde değil tüm sistemler üzerinde çalışabilecek, modern, bulut tabanlı, internet
bağlantılı uygulamalar oluşturmaya yönelik platformlar arası, yüksek performanslı .Net Core
frameworkünü yayınlaması olarak görüyorum.

**Visual Studio Code** - Yine Microsoft tarafından; Windows, Linux ve macOS için geliştirilmiş açık kaynaklı
ve ücretsiz bir kaynak kod editörüdür. Hata ayıklama, yerleşik Git kontrolü, sözdizimi vurgulama, akıllı
kod tamamlama gibi özelliklerle oldukça kullanışlı bir kod editörüdür.

**PostgreSQL** - Güvenilirliği, özellik sağlamlığı ve performansı için güçlü bir üne sahip olan 30 yılı aşkın
aktif gelişimi ile güçlü, açık kaynaklı bir ilişkisel veritabanı sistemidir. Şuan da açık kaynak kodla
geliştirilmiş en popüler ilişkisel veritabanıdır.

**MongoDB –** İlişkisel veri tabanlarına alternatif olarak ortaya çıkan NoSQL yaklaşımını (doküman tabanlı,
key/value tabanlı ve grafik tabanlı )destekleyen sistemlerden dokuman tabanlı açık kaynak veri
tabanıdır. MongoDB’de her kayıt, aslında bir dökümandır. Dökümanlar MongoDB’de JSON benzeri
Binary JSON(BSN) formatında saklanır. BSON belgeleri, sakladıkları elemanların sıralı bir listesini içerir
nesnelerdir. Her bir eleman, bir alan adı ve belirli tipte bir değerden oluşur.

**Cordova** - Apache Foundation sponsorluğundaki Cordova, mobil geliştiricilerin HTML, CSS ve JavaScript
gibi Web geliştirme teknolojilerini kullanarak iOS, Android, Windows ve diğer platformlar için
yazmasına olanak tanır.

Açık kaynak kodlu geliştirmeye hizmet veren sayısız hizmet olmakla beraber sözü çok da uzatmamak
adına konuyu burada noktalamak istiyorum. Ancak tüm dünyayı etkisine almayı başarmış açık kaynak
kodlu geliştirme felsefesi kendisine gün geçtikçe yeni destekçiler ve entegre sistemler bulmaktadır.

Gelelim işin Türkiye’deki yansımalarına ve dünya ile karşılaştırıldığımızda nerede olduğumuza 

# DÜNYADA AÇIK KAYNAK KODLU YAZILIM GELİŞTİRME

Tarihçesinde de bahsettiğim gibi, temelli yaklaşık 1970’lere dayanan açık kaynak kodlu yazılım
geliştirmenin gücü tüm dünyada kabul görmüş durumda. ABD, Çin, Hindistan, Avustralya ve özellikle
batıda yer alan Avrupa Birliği üye ülkeleri açık kaynağı teşvik eden bir rol üstleniyorlar.

Avrupa Komisyonu 1998 yılından bu yana Özgür Yazılım Çalışma Grubu’nun oluşturulmasıyla başlayan
süreçte çeşitli açık kaynak kodlu yazılım girişimlerine destek vermiştir. Avrupa Komisyonu tarafından
Avrupa için Sayısal Gündem (Digital Agenda for Europe) kapsamında hazırlanan “Avrupa’nın Dijital
Rekabet Edebilirlik Raporu 2010”da açık kaynak kodlu yazılımın faydalarına dikkat çekilerek açık kaynak
kodlu yazılım pazarının çok düşük seviyedeki pazar payının her yıl yaklaşık yüzde 30 - 40 artacağı
belirtilmektedir.

2016’da Network World tarafından yapılan bir araştırma aşağıdaki haritada detaylarını
görebileceğimiz, ülkelerin açık kaynak kodlu yazılım geliştirmeye karşı tutumunu ve yasal olarak
değerlendirildiğinde nerede konumlandıklarını gözler önüne sermiştir.

Red Hat CEO’su Jim Whitehurst’in 2008’de şöyle bir açıklaması var;

_“Bugün yazılan yazılımların büyük çoğunluğu yeniden satılmak üzere değil kurumsal olarak yazılmıştır.
Ve bunun büyük çoğunluğu aslında hiç kullanılmaz. IT yazılım geliştirme alanındaki atık olağanüstüdür.
... Sonuç olarak, açık kaynağın tüm dünyadaki tüm müşterilerimize değer katması için, müşterilerimize_

_yalnızca açık kaynaklı ürünlerin kullanıcıları olarak değil, aynı zamanda gerçekten açık kaynakla
ilgilenen ve geliştirme topluluğuna katılan müşterilerimize ulaşmamız gerekiyor.”_

Bana göre buradan çıkarılması gereken şey; dünyada açık kaynaklı yazılımlar kabul görmüş durumda
evet ama felsefesi tam olarak kavranmamış. Görünen o ki, neredeyse herkes işin maliyet boyutunda,
yani lisans ücreti ödemeden masraflarını azaltıp ihtiyaçlarını giderme derdinde, oysa ki açık kaynaklı
kod geliştirmenin temeli “Toplumun neye ihtiyacı var” cümlesi idi, yapılması gereken sadece kendi
ihtiyacına yönelik geliştirmeler yapıp bunun yeniden kullanılamaz bir şekilde üretilmesi değil,
mevcuttaki topluluklara, yazılımlara birer birer eklenerek güçlü bir yazılım alt yapısı çıkarmak, iyi bir
open source citizen olmakta belki de :)

Yine de geldiği nokta itibari ile gelecek heyecan verici. Farkındalıkların daha da artacağı ise artık
yasalara bile girmesinden dolayı aşikâr.

Dünyadaki açık kaynak kodlu yazılım üreten firmalara da birkaç örnek vermek isterim.

**FACEBOOK :** Facebook, 2016 yılında, GitHub'a en fazla katkıda bulunan şirketler listesinde ikinci
olmuştur.(15,682). En popüler açık kaynaklı projeleri arasında React, Flow, HHVM, Relay ve diğerleri
yer alıyor.

**GITHUB :** GitHub, açık kaynaklı projeler için fiili bir depo haline geldi. 2016 raporunda, 5.8 milyondan
fazla aktif kullanıcısı, 331.000'den fazla aktif kuruluşu ve 19.4 milyondan fazla aktif deposu
bulunmaktadır. Şirket ayrıca Atom metin editörü, Hubot ve Git Büyük Dosya Depolama (LFS) dahil
olmak üzere kendine ait birkaç açık kaynaklı proje yarattı.

**GOOGLE :** 2.000'den fazla açık kaynaklı projenin yayınlanmasına veya katkıda bulunmasına neden olan
Google, en ateşli kurumsal kullanıcılardan ve açık kaynak destekçilerinden biridir. 2016'da en fazla
GitHub katılımcısı olan şirketler listesinde beşinci oldu (ve listede dördüncü sırada yer alan Angular’e
de sahipti.) Tanınmış Google açık kaynaklı projeleri arasında Android, Chromium, Dart, Go, Kubernetes,
TensorFlow ve daha birçok proje yer almaktadır.

**MICROSOFT :** Daha önce de bahsettiğim gibi, açık kaynak dünyasının belki de en ezeli rakibi olan
Microsoft’ta artık açık kaynak dünyasına en çok katkı sağlayan şirketler arasında verilebilir. Github
üzerindeki birçok projeye destek veren Microsoft aynı zamanda aralarında RedHat gibi önde gelen açık
kaynak firmaları ile partner olarak çalışmaktadır. Visual Studio Code, .Net Core, Powershell
Core,TypeScript,Redis gibi birçok projesi vardır.

**NETFLIX :** Akışlı video hizmeti, açık kaynaklı projelere katkıda bulunmak ve şirket içinde geliştirdiği
araçları açık bir şekilde tedarik etmek konusunda son derece aktif olmuştur. Projeleri arasında Genie,
Inviso, Ruj, Aegisthus, Nebula, Aminator, Spinnaker, Eureka, Archaius, Kurdele, Hystrix, Karyon,
Governator, Fenzo, Fotoğraf, Dynomite, Atlas, Chaos Monkey ve diğerleri yer alıyor.

**NPM :** Etkili açık kaynaklı projeler listesinde 11. sırada yer alan npm, kendisini " the package manager
for JavaScript and the world’s largest software registry" olarak nitelendiriyor. Node.js kullanıcıları
arasında oldukça popüler.

**ORACLE :** Sun Microsystems'ı satın aldığında, Oracle, Java, MySQL veritabanı, OpenOffice ofis
üretkenlik platformu ve Hudson sürekli entegrasyon aracı dahil dünyanın en popüler açık kaynaklı
teknolojisinin bir kısmını devraldı.

**RED HAT :** Red Hat Enterprise Linux, büyük kuruluşlar için en popüler Linux dağıtımlarından biri. Önde
gelen Linux katılımcılarının listesinde ikinci olan Red Hat, Apache Software Foundation ve OpenStack

Foundation'ın bir üyesi veya sponsoru. Linux dağıtımına ek olarak, OpenShift, Gluster, CloudForms de
dahil olmak üzere başka birçok açık kaynaklı projeyi de yönetiyor.

**SUSE :** Tıpkı Red Hat gibi, popüler bir Linux dağıtımıdır. Ayrıca Linux çekirdeğine de büyük katkı
sağlamaktadır. Ayrıca OpenStack, Ceph, The Open Container Initiative de dahil olmak üzere diğer
birçok açık kaynaklı projede yer aldı.

**TWITTER :** Twitter kendisini “açık kaynak kodlu yazılım üzerine kurulu” bir platform olarak
addediyor.Dahili olarak geliştirilen araçlarının çoğunu açık kaynak lisansları altında yayınladı. GitHub'da
139'dan fazla halka açık deposu bulunuyor.

**DOCKER** : Geçtiğimiz birkaç yıl boyunca Docker konteyner teknolojisi, kurumsal kullanıcılar için en etkili
açık kaynaklı projelerden biri olarak ortaya çıkmıştır. GitHub'da 32.000'den fazla yıldızı olan proje 8
milyardan fazla kez indirildi. Ayrıca Docker olarak adlandırılan teknolojinin arkasındaki şirket, 2016'da
en fazla GitHub katılımcısı olan şirketler listesinde üçüncü sırada yer aldı.

**ELASTIC** : Açık kaynak kodlu Elasticsearch projesi için en iyi bilinen Elastic, "herhangi bir kaynaktan,
herhangi bir biçimde, herhangi bir biçimde verileri güvenilir ve güvenli bir şekilde alabilen ve gerçek
zamanlı olarak arayabilen, analiz edebilen ve görselleştirebilen" eksiksiz bir ürün yığını sunar.
Elasticsearch, popüler açık kaynaklı projeler endeksinde yedinci sırada yer aldı ve GitHub'da 25 binden
fazla yıldızı var. Elastic'ın ayrıca Kibana, Beats ve Logstash gibi başka birçok açık kaynaklı projesi var.

**ADOBE :** GitHub sitesinde 250'den fazla genel depoya sahiptir. En iyi bilinen açık kaynaklı projelerden
bazıları, PhoneGap web geliştirme çerçevesi, Brackets metin editörü ve Topcoat CSS kütüphanesi gibi
geliştirici araçlardır. Adobe personeli ayrıca Gecko, Blink, WebKit, Apache Cordova, Flex, Felix ve
diğerleri gibi diğer açık kaynaklı projelere düzenli olarak katkıda bulunur.

Gelelim bizim ülkemizdeki durumlara, güzel ülkem en azından bu konuda biraz hassas davranmayı
başarsa, bir şansımız olur dünyadaki gelişmiş ülkelerin refahını yakalamaya belki de...

# TÜRKİYE’DE AÇIK KAYNAK KODLU YAZILIM GELİŞTİRME

Yukarıda bahsettiğim araştırmada Türkiye’nin durumu şu : “Açık Kaynaklı Kod Geliştirmeyi Dikkate
Alın!”

Artık genel seçimlerdeki seçim kampanyalarında bile kendine yer bulmayı başarmış açık kaynak dünyası
için, Kalkınma Bakanlığı’nın Bilgi Toplumu Dairesi Başkanlığı tarafından hazırlanan 2015-2018 Bilgi
Toplumu Stratejisi ve Eylem Planı raporunda ise ne mutlu ki açıkça “başta PARDUS olmak üzere kamuda
Açık kaynak kodlu yazılım kullanımı yaygınlaştırılacak, kamu kurumlarına bu çerçevede destek
verilecektir. Açık kaynak kodlu yazılım konusunda özel sektör ekosisteminin gelişmesi sağlanacaktır”
ibaresi yer almaktadır. (s. 150)

Yine aynı raporda yine dünyadaki örneklere yer verilerek açık kaynak kod kullanımı için toplum
cesaretlendirilmeye çalışılmıştır.

Ülkemizdeki açık kaynak kodlu geliştirmeler henüz dünya ile boy ölçüşecek durumda olmasa da, ben
bizim topraklardan da umutluyum :)

Bugüne kadar geliştirilen projelerden birkaç örnek verecek olursam;

**PARDUS :** Pardus, TÜBİTAK tarafından geliştirilen Milli işletim sistemi olarak tanımlanıyor. Pardus; 2003
yılında temelleri atılan milli işletim sistemi olan, Türkiye'de TÜBİTAK-UEKAE tarafından geliştirilen,
özgür, hızlı kurulabilen, kolay kullanılır, çoklu dil içeren, bilgisayar kullanıcılarının temel masaüstü
ihtiyaçlarını gidermek üzere halihazırdaki linux dağıtımlarının üstün taraflarını kullanan; kurulum,
yapılandırma ve kullanım kolaylığı sağlayan açık kaynak bir işletim sistemidir. Ancak dünyada beklenen
başarıyı ve popüleriteyi yakalayamamıştır. Kamuda birçok alanda kullanılıyor ve yukarıda örnek
verdiğim raporda yine Pardus işletim sisteminin kullanılması için toplum cesaretlendirilmeye çalışılıyor.

**ENGEREK :** Yine Pardus çatısı altında geliştirilen Engerek, Web tabanlı geliştirilmiş bir kimlik yönetim
sistemidir. Java programlama dili ile geliştirilmiştir. Temel hedefi kurum kullanıcılarını ve hesaplarını
merkezden yönetmektir. Açık kaynaklı olarak geliştirilmiştir. Tomcat uygulama sunucusu üzerinde
çalışmakta, kimlik deposu olarak MariaDB / MySQL / PostgreSQL veritabanlarını desteklemektedir.

**AHTAPOT :** Yine Pardus tarafından geliştirilen bir siber güvenlik sistemidir. Açık Kaynak Kodlu bileşenler
kullanılmaktadır; bu sayede denetlenemeyen ve arka kapı bulundurması muhtemel olan, bununla
birlikte pahalı olan siber güvenlik çözümlerine bağımlılığı azaltmaktadır.

**LİDERAHENK :** Kurumsal ağ üzerindeki, sınırsız sayıda farklı sistemi ve kullanıcılarını tek merkezden
yönetebilmeyi, izlemeyi ve denetlemeyi sağlayan, TÜBİTAK ULAKBİM tarafından geliştirilen açık
kaynaklı bir yazılım sistemidir.


**ULAKBÜS :** ULAKBÜS, Ulusal Açık Kaynaklı Bütünleşik Üniversite Sistemi Projesi, üniversitelerin
kaynaklarının optimum düzeyde kullanılabilmesi ve tek çatı altında çözüm bulmak üzere
geliştirilmektedir. ULAKBÜS, üniversitelerin hem akademik hem de idari ihtiyaçlarının tamamını
karşılamak üzere, 360 derece tüm hizmetleri kapsayacak şekilde tümleşik bir yapı olarak tasarlanmıştır.

# DOĞUŞ TEKNOLOJİ ve AÇIK KAYNAK KODLU YAZILIM GELİŞTİRME

Açık kaynak kodlu yazılım geliştirmenin Doğuş Teknoloji’ye birçok açıdan fayda sağlayacağını
düşünüyorum. İçinde bulunduğumuz ekonomik bulanımda geliştirme yapılmasa, sadece geliştirilmiş
açık kaynak ürünleri kullansak lisans maliyetlerimizin büyük kısmını azaltacağımız için ilk faydasını
görmüş olacağız. Ancak tüm yazı boyunca vurgulamaya çalıştığım şey işin felsefesi idi. Ve açık kaynak
kod kullanmanın amacı maliyetlerden ziyade bu topluma sağlanabilecek katkılar olmalı. Zira bu katkılar
dünyayı geliştirecek ve dolayısıyla bizi 

Açık kaynak kod geliştirmenin sağlayabileceği birkaç katkıyı aşağıdaki maddelerle özetlemek isterim.

**Community (Topluluk) :** İşletmeye yönelik açık kaynaklı çözümler genellikle, hem kuruluşun hem de
toplumun fayda sağladığı (ve buna inandığı) bir çözümü desteklemek ve iyileştirmek için ortak bir dürtü
ile bağlı, etraflarında gelişen topluluklara sahiptir. Bu çözümleri geliştirmek için birleşmiş olan küresel
topluluklar, özel çözümler üzerinde çalışan iç ekiplerden daha hızlı, daha iyi ve daha etkili yeni
kavramlar ve yetenekler sunmaktadır. Doğuş teknoloji olarak açık kaynak dünyasına aktif olarak katkı
sağlamak hem prestij hem de büyük bir topluluğu arkanıza alarak katlanarak çoğalmak demek. Bunun
getireceği katkı diğerlerinin yanında belki de en büyük katkı olacaktır.

**Transparency (Şeffaflık) :** Açık kaynak kodlu yazılım geliştirmenin anlamı tam da budur; topluluğun
özellikleri nasıl geliştirdiği ve hataları nasıl çözdüğü hakkındaki tüm tartışmaların yanı sıra kod
tabanında tam olarak görünürlük kazanırsınız. Buna karşılık, gizlilik içinde üretilen özel kod,
öngörülemeyen sınırlamalar ve diğer istenmeyen sürprizlerle birlikte gelebilir. Doğuş Teknoloji olarak
kullandığımız kapalı sistemlerin yerine açık kaynaklı sistemlerle ön göremeyeceğimiz ve
yönetemeyeceğimiz risklerin önüne geçmiş oluruz.

**Reliability (Güvenilirlik) :** Üzerinde daha fazla göz olduğundan, açık kaynak kodunun güvenilirliği de
üstün olma eğilimindedir. Bir şirket içindeki bir ekip yerine bir kod tabanını destekleyen dünya çapında
bir toplulukla kod çevrimiçi forumlarda geliştirilir ve uzmanlar tarafından yönlendirilir. Çıktı son derece
sağlam, denenmiş ve test edilmiş bir kod olma eğilimindedir. Aslında, açık kaynak kodu şimdi internetin
yaklaşık% 90'ına güç veriyor ve bu nedenle büyük şirketler arasında hızla kabul görüyor. Doğuş
Teknoloji olarak açık kaynaklı kodlarımızı Github gibi platformlarda yayınlamamız toplumlar ve dünya
içinde güvenilirliğimizi kanıtlayacaktır.

**Securiy (Güvenlik) :** Güvenilirlikte olduğu gibi, açık kaynaklı yazılımın kodu genellikle daha güvenlidir,
çünkü topluluk tarafından çok daha ayrıntılı bir şekilde incelenir ve onaylanır (ve ortaya çıkan herhangi
bir sorun daha titizlikle yatar). Açık kaynağın kurumsal olarak benimsenmesi için uzun süredir tereddüt
etme noktası, güvenlikle ilgili endişeler bugün bir sorun değil. Doğuş Teknoloji olarak açık kaynak kod
geliştirmemiz hem bizim güvenlikle alakalı benimsediğimiz standartların dünyaya duyurulması hem de
kaynağını görebildiğimiz kodları kullandığımız için kendi sistemlerimizin güvenliğini garanti altına alır.

**Faster time to market(Piyasaya açılma hızı) :** Açık kaynaklı çözümler Github gibi tüm dünyaya açık olan
ortamlarda kolayca bulunabilir ve tanınmanız daha kolaydır. Reklam maliyetleri ve yaygınlaştırılma
işlemleri çok kolaydır. Doğuş Teknoloji olarak geliştirdiğimiz uygulamaların bu platformlarda bulunması
hem tanınmışlığımızı arttıracak hem de geliştirdiğimiz ürünlerin piyasaya sürülmesi kolaylaşacaktır.


**Cost Effective(Uygun Maliyet) :** Açık kaynaklı çözümler sadece özgür yazılımlardan daha fazla
düşünülmekle birlikte, herhangi bir lisans ücreti gerektirmemeleri, bir çözümün toplam maliyetine
bakarken belirleyici bir avantaj olarak durmaktadır. Daha önce de bahsettiğim gibi Doğuş teknoloji
olarak maddi kazanç sağlayacağımız aşikar.

**Freedom from lock-in(Bağımlılıklardan Kurtulma) :** Telifli programlar, işletmeleri tedarikçi firmalara
bağımlı kılar. Bu durumda işletmeler, fiyat artışlarında tedarikçilerin insafına kalır ve kolayca ve kolayca
değiştiremeyecekleri bağımlılıkları yaşarlar. Açık kaynak yazılımları istediğimiz gibi değiştirip, geliştirip,
dağıtabileceğimiz için bağımlılıklardan kurtulmuş ve esneklik kazanmış oluruz. Doğuş Teknoloji olarak
dış firma ve kapalı paket yazılım kısıtlarından kurtulmuş oluruz.

# KAYNAKLAR

[https://opensource.com/article/18/2/pivotal-moments-history-open-source](https://opensource.com/article/18/2/pivotal-moments-history-open-source)

[https://medium.com/gitcoin/a-brief-history-of-open-source-3928cb](https://medium.com/gitcoin/a-brief-history-of-open-source-3928cb)

[https://www.cnet.com/news/microsofts-long-history-of-open-source-acrimony/](https://www.cnet.com/news/microsofts-long-history-of-open-source-acrimony/)

[http://www.wikizeroo.net/index.php?q=aHR0cHM6Ly9lbi53aWtpcGVkaWEub3JnL3dpa2kvVGhlX0NhdGhlZHJhbF9hbmRfdGhlX0JhemFhcg](http://www.wikizeroo.net/index.php?q=aHR0cHM6Ly9lbi53aWtpcGVkaWEub3JnL3dpa2kvVGhlX0NhdGhlZHJhbF9hbmRfdGhlX0JhemFhcg)

[https://startuphukuku.com/acik-kaynak-yazilimlar-nedir-open-source/](https://startuphukuku.com/acik-kaynak-yazilimlar-nedir-open-source/)

[http://www.sozkimin.com/a/1366-richard-stallman-kimdir-sozleri-ve-hayati.html](http://www.sozkimin.com/a/1366-richard-stallman-kimdir-sozleri-ve-hayati.html)

[https://hackernoon.com/being-a-good-open-source-citizen-9060d0ab9732?gi=](https://hackernoon.com/being-a-good-open-source-citizen-9060d0ab9732?gi=)

[https://opensource.org/licenses](https://opensource.org/licenses)

[https://opensource.org/faq#free-software](https://opensource.org/faq#free-software)

[https://www.gnu.org/licenses/gpl-howto.html](https://www.gnu.org/licenses/gpl-howto.html)

[http://blog.honeypot.io/most-exciting-open-source-projects-2018/](http://blog.honeypot.io/most-exciting-open-source-projects-2018/)

[https://opensourceforu.com/2018/03/ten-popular-open-source-tools-for-developers/](https://opensourceforu.com/2018/03/ten-popular-open-source-tools-for-developers/)

[http://ifosslawbook.org/](http://ifosslawbook.org/)
[https://www.itnews.com/article/3114619/open-source-tools/which-countries-have-open-source-laws-on-the-books.html](https://www.itnews.com/article/3114619/open-source-tools/which-countries-have-open-source-laws-on-the-books.html)

[https://www.datamation.com/open-source/35-top-open-source-companies-1.html](https://www.datamation.com/open-source/35-top-open-source-companies-1.html)

[https://www.developer.com/open/seven-key-benefits-of-open-source-software.html](https://www.developer.com/open/seven-key-benefits-of-open-source-software.html)

[http://open-source.gbdirect.co.uk/migration/benefit.html](http://open-source.gbdirect.co.uk/migration/benefit.html)
