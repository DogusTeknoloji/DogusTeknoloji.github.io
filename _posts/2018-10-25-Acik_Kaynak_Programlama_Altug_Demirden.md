---
layout: post
title:  "Açık Kaynak Programlama - Altuğ Demirden"
categories: ["Açık Kaynak"]
tags: ["Açık Kaynak", altugdemirden]
redirect_from: "/assets/Acik_Kaynak_Programlama_Altug_Demirden.pdf"
permalink: acik_kaynak_altug_demirden
---

[Pdf versiyon](/assets/acik-kaynak/altug-demirden/Acik_Kaynak_Programlama_Altug_Demirden.pdf)

# AÇIK KAYNAK PROGRAMLAMA GELİŞTİRME

![OpenSource](/assets/acik-kaynak/altug-demirden/0.png)

## İÇERİK

- AÇIK KAYNAK PROGRAMLAMA GELİŞTİRME
- Açık Kaynak Programlama Tarihçesi
- Gücü ve Yaygınlaşmasının Nedenleri
- Lisanslama Seçenekleri
- Açık Kaynak Projelere hizmet veren servisler:
  - GitHub:
  - GitLab:
- Türkiye’de ve Dünyada Açık Kaynak Programlama:
- Doğuş Teknoloji ve Açık Kaynak Programlama:
- Kaynaklar

## Açık Kaynak Programlama Tarihçesi

Açık kaynak, bugün BT sektöründe önemli bir role sahiptir. Geçtiğimiz 40 yıl içerisinde en küçük
gömülü sistemlerden en büyük süper bilgisayara, cebimizdeki telefonlardan, web sitelerini çalıştıran
yazılımlara ve içerisinde olduğumuz şirketlerin altyapısına kadar her yerde örnekleri bulunmaktadır.

1970'lerin sonlarında, Richard M. Stallman (RMS) MIT'de bir personel programcısıydı.

![Richard M. Stallman (RMS)](/assets/acik-kaynak/altug-demirden/1.png)
**Resim 1:** Richard M. Stallman (RMS)

Departmanı, birçok üniversitedeki gibi, bir PDP-10 bilgisayarı (bkz. Resim 2 ) ve tek bir yazıcıyı
kullanıyordu. Kağıdın yazıcıda düzenli olarak sıkışması ve bir yazdırma işinin bir kişi sıkışmayı giderene
kadar kuyruğa yığılmasına neden olması sorunları ile karşılaşıyorlardı. Bu sorunu çözmek için, MIT
personeli güzel bir çözüm önerisi getirdi: Yazıcı sürücüsü için bir kod yazdılar; böylece kağıt
sıkıştığında, o anda bir yazdırma işi için bekleyen herkese bir mesaj gönderilecek: "Yazıcı sıkıştı, lütfen
düzeltin." Bu yöntem ile birlikte, uzun süre boyunca hiç takılma yaşanmadı.

1980 yılında laboratuvar, yepyeni bir lazer yazıcı bağışını kabul etti. Stallman, sistemdeki kullanıcıları
bir kağıt sıkışması konusunda bilgilendirmek için kullandığı çözüm önerisini yeniden kurgulamak
amacıyla yazıcı sürücüsünün kaynak kodunu sorduğunda, bunun özel bir bilgi olduğu cevabını aldı. Bir
araştırma projesinin kaynak kodunu taşıyan farklı bir üniversitedeki araştırma görevlisinden haberdar
olan Stallman, meslektaşından kaynak kodunu paylaşmasını istedi ve reddettiklerinde şok oldu.
Stallman'ın hacker kültürüne ihanet ettiği bir gizlilik anlaşması (NDA) imzaladılar.

![PDP 10 Bilgisayarı](/assets/acik-kaynak/altug-demirden/2.png)
**Resim 2** : PDP 10 Bilgisayarı

70'lerin sonları ve 80'lerin başında, geleneksel olarak kaynak kod biçimindeki donanımla birlikte
verilen yazılımın değerli olduğu bir dönemi temsil ediyordu. Giderek artan bir şekilde, MİT
araştırmacıları yazılım şirketleri kuruyordu ve yazılıma lisans satmak iş modellerinin anahtarıydı.
Gizlilik sözleşmeleri ve tescilli yazılım lisansları norm haline geldi ve en iyi programcılar MIT gibi
üniversitelerden, artık paylaşamayacakları ya da iş birliği yapamayacakları özel yazılım geliştirme
projelerinde çalışmak üzere işe alındı.

Buna tepki olarak Stallman, kullanıcıları nasıl çalıştığını anlama özgürlüğünden yoksun bırakacak ve
istedikleri takdirde değişiklik yapmalarına izin verecek tam bir işletim sistemi yaratmayı kararlaştırdı.
Bu karar açık kaynak yazılım hareketinin doğuşu oldu.

1983'ün sonlarına doğru Stallman projesini duyurmaya ve destekçileri ve yardımcıları yanına almaya
hazırdı. 1983 yılının Eylül ayında, GNU projesinin oluşturulmasını duyurdu (GNU = “GNU’s Not Unix”
anlamına geliyordu). Projenin amacı, kullanıcılara tam özgürlük verecek bir sistem oluşturmak için
Unix işletim sistemini klonlamaktı.

Ocak 1984'te proje üzerinde tam zamanlı çalışmaya başladı, önce bir derleyici sistemi (GCC) ve çeşitli
işletim sistemi programları oluşturuldu. 1985'in başlarında, programcıların çabalarına katılmaları için
bir çağrı niteliğindeki "GNU Manifestosu" nu yayınladı ve çalışmaları desteklemek için bağışları kabul
etmek üzere Özgür Yazılım Vakfı'nı başlattı. Bu belge, özgür yazılım hareketinin kurucu sözleşmesidir.

1989'a kadar, Özgür Yazılım Vakfı ve RMS tarafından yazılan ve yayınlanan yazılımların tek bir lisansı
yoktu. Emacs Emacs lisansı altında yayınlandı, GCC GCC lisansı altında piyasaya sürüldü, vb. Ancak,
Unipress adında bir şirket Stallman'ın James Gosling'den (Java şöhretinden) edindikleri bir Emacs
uygulamasının kopyalarını dağıtmaya son vermesinden sonra, kullanıcı özgürlüklerini güvence altına
alma lisansının önemli olduğunu düşünüyordu.

GNU Genel Kamu Lisansı'nın ilk versiyonu 1989'da piyasaya sürüldü ve copyleft'in değerlerini
(kelimelerdeki bir oyun — telif hakkının tersi nedir?) Kapsülledi: Kapsanan yazılımı kullanabilir,
kopyalayabilir, dağıtabilir ve değiştirebilirsiniz. Lisansı, ancak değişiklik yaparsanız, değiştirilmiş ikili
kodun yanında değiştirilmiş kaynak kodunu paylaşmanız gerekir. 1990'larda internetin gelişiyle
birlikte modifiye edilmiş yazılımı paylaşmak için bu basit gereksinim, özgür yazılım hareketinin
merkezi olmayan, işbirlikçi kalkınma modelinin gelişmesine olanak vermiştir.

1990'ların ortasına gelindiğinde, Linux başlıyordu ve özgür yazılım daha çok ana akım haline gelmişti.
Linux çekirdeği, daha önce insanların gördüğü her şeyden tamamen farklı bir şekilde geliştirildi ve çok
başarılı oldu. Çekirdek topluluğunun kaosundan sıyrılıp, hızlı hareket eden bir proje geldi.

![The Cathedral & The Bazaar](/assets/acik-kaynak/altug-demirden/3.png)
**Resim 3:** The Cathedral & The Bazaar

1997'de, Eric S. Raymond, GCC ve Linux çekirdeğinin gelişim metodolojilerini ve sosyal yapısını
karşılaştıran ve Fetchmail projesinde “pazar” geliştirme modeli ile kendi deneyimlerini anlatan “The
Cathedral and the Bazaar” (bkz. Resim 3) adlı makaleyi yayınladı. Raymond'un bu makalede anlattığı
ilkelerin bir çoğu, daha sonralarda gelişen Agile yazılım geliştirme ve DevOps hareketinin, kodun
yeniden düzenlenmesi (re-factoring) ve kullanıcıların birlikte geliştiriciler olarak çalışmaları, modern
yazılım geliştirme için temel teşkil etmektedir.

Bu makale, açık kaynak yazılımın daha geniş bir kitleye ulaştırılmasına ve yazılım şirketlerinde açık
kaynak yazılım lisansı altında yazılımların kullanımını destekleyen yöneticilere öncülük etmiştir.
Raymond, “açık kaynak” terimi ile Açık Kaynak Enstitüsü'nün yaratılmasında etkili olmaya devam etti.

## Gücü ve Yaygınlaşmasının Nedenleri

“The Cathedral and the Bazaar”, Netscape web tarayıcısı Mozilla'nın kaynak kodunun 1998'de
yayımlanmasında kilit bir belge olarak kabul edildi. O zamanlar, yaygın olarak kullanılan bir yazılım
programının açık kaynak yazılım olarak kullanılmasının ilk büyük örneğidir ve kamuoyunun dikkatini
çekmiştir.

1985'e kadar, yazılım bağımsızlığını tanımlamak için kullanılan "free” kelimesinin muğlak doğası,
RMS'nin kendisi tarafından sorunlu olarak tanımlandı. GNU Manifestosu'nda sıfır fiyat ve kullanıcı
özgürlüğünü karıştıran terimler olarak “serbest bırakmak” (give away) ve “bedava” (for free) olarak
tanımladı. Açık kaynak yazılımın 1990'ların sonlarında ana akım kitlesine ulaşmasıyla çeşitli mantralar
yaygınlaştı, ancak birçok tanınmış topluluk figürü, kavramı daha erişilebilir kılan bir terime ihtiyaç
olduğunu savundu.


Netscape 1998'de Mozilla'nın kaynak kodunu yayınladıktan sonra (bkz. # 4), Eric Raymond, Bruce
Perens, Michael Tiemann, Jon "Maddog" Salonu ve özgür yazılım dünyasının önde gelen ışıklarının
birçoğu gibi bir grup insan Palo Alto'da alternatif bir terimi tartışmak için toplandı. “Açık kaynak”
terimi Christine Peterson tarafından özgür yazılımı tanımlamak için yapılmıştır ve Açık Kaynak
Enstitüsü daha sonra Bruce Perens ve Eric Raymond tarafından kurulmuştur. Sahip oldukları özel
yazılım ile temel fark, kaynak kodun kullanılabilirliğiydi ve bu yüzden ilk önce markalaşmada öne
sürülmesi gereken şeydi.

Bu yılın ilerleyen zamanlarında, Tim O'Reilly tarafından düzenlenen bir zirvede, özgür yazılımlar için
çeşitli yeni markaları tartışmak üzere özgür yazılım dünyasındaki en etkili insanlardan bazıları
toplandılar. Sonunda, "açık kaynak" toplumdaki birçok proje tarafından benimsenmeye başladı.

Ancak bazı anlaşmazlıklar vardı. Richard Stallman ve Özgür Yazılım Vakfı, "özgür yazılım" (free
software) terimini savunmaya devam ettiler, çünkü onlara göre, özel yazılımla temel fark, kullanıcı
özgürlüğü idi ve kaynak kodun kullanılabilirliği, bunun için sadece bir yoldu. Stallman, özgürlüğe
odaklanmanın kaynak kodun kullanılabileceği bir geleceğe yol açacağını savundu, ancak yazılımın
kullanıcısı yazılımı değiştirme özgürlüğünden yararlanamayacaktı. Web tabanlı bir yazılım olarak
hizmet veren ve cihazlara gömülü açık kaynaklı bir firmware yazılımının ortaya çıkmasıyla başlayan
savaş bugün hala devam etmektedir.

1990'ların sonlarında, bir dizi yüksek profilli etkinlik, özgür ve açık kaynaklı yazılımların
profesyonelleştirilmesinde büyük bir artışa yol açtı. Bunlar arasında en yüksek profilli olaylar 1999
yılında VA Linux ve Red Hat'in IPO'larıydı. Her iki şirketin de açık ticaretin artık ticari ve ana akım
haline geldiğini kanıtlayan halka açık şirketler olarak açılış günlerinde hisse fiyatlarında büyük artışlar
oldu.

Ayrıca, 1999 yılında IBM geliştirmeye 1 milyar dolar yatırım yaparak Linux'u desteklediklerini
duyurdu; bu da geleneksel işletme kullanıcıları için daha az riskli hale gelmesi anlamına geliyordu.
Ertesi yıl, Sun Microsystems, kaynak kodunu, çapraz platformlu ofis paketi StarOffice'e bıraktı ve
OpenOffice.org projesini oluşturdu.

Açık kaynaklı projelere yönelik büyük Silikon Vadisi fonlarının birleşik etkisi, açık kaynak yazılımlar
etrafında inşa edilen genç şirketler için Wall Street'in dikkati ve IBM ve Sun Microsystems gibi
teknoloji devlerinin getirdiği pazar güvenilirliği, açık kaynağın kitlesel olarak benimsenmesi için bir
araya getirildi ve gelişmesine yardımcı olan açık kaynak programlama modelinin benimsemesi,
günümüzde teknoloji endüstrisinde Linux ve açık kaynak hakimiyetine yol açmıştır.

## Lisanslama Seçenekleri

Bugün, Stallman'ın öncülük ettiği GPL lisansı üçüncü versiyonu (GNU GPLv3) var olan birkaç düzine
açık kaynak lisansından sadece bir tanesidir. Açık kaynak yazılımını tanıtmak ve terimin kullanımını
normalleştirmek için 1998 yılında kurulmuş olan Open Source Initiative, 80'den fazla açık kaynak
lisansını onaylamıştır. Bu 80 lisans genellikle iki kategoriden birine girer: “Permissive” ve “Copyleft”.

“Permissive” lisans basittir ve en basit açık kaynak lisansı türüdür. Bu, bildirim gereksinimlerine
uyduğunuz sürece yazılımla ne yapmak istediğinizi sağlar. “Permissive” lisanslar, yazılımı garantisiz
olarak sağlar. Bu tipteki lisanslar aşağıdaki şekilde özetlenebilir:

```
▪ Kodla dilediğinizi yapabilirsiniz.
▪ Sorumluluk kullanıcıya aittir.
▪ Yazan/katkı sağlayanlar tanınacaktır.
```
“Copyleft” lisansları “Permissive” lisanslara ek gereksinimler ekler. Yukarıda listelenen gereksinimlere
ek olarak, “Copyleft” lisansları şunları da gerektirir:

```
▪ Kodun dağıtımı yapılıyorsa, kaynak kodu dağıtım yapılanların da erişimine açık olmalıdır.
▪ Kaynak kodu, kodu aldığınız aynı “Copyleft” koşulları altında mevcut olmalıdır.
▪ Lisansa, lisansı verenin belirlediğinden başkaca ek kısıtlamalar getiremezsiniz.
```
Aşağıdaki tablo, “Permissive” ve “Copyleft” çerçeveleri altındaki popüler açık kaynak lisanslarını
kategorize etmektedir. Copyleft lisansları ayrıca, en güçlüsünden en alttan en zayıfına kadar, artan
kuvvet sırasına göre listelenir. “Mukavemet”, çevredeki yazılımların aynı copyleft gereksinimlerine
tabi olmasının gerekebileceği derecedir. Örneğin GPL güçlüdür, çünkü GPL kodunu içeren herhangi bir
programın yalnızca GPL kodunu içermesi gerekir. LGPL daha zayıftır çünkü bağlı olduğu kodun aynı
GPL gereksinimlerine tabi tutulmadan diğer özel kodlara dinamik olarak bağlanmasına izin verir. EPL
ve MPL en zayıf kopyaları, EPL veya MPL kodu kendi dosyasında olduğu sürece, diğer kodlarla her
türlü entegrasyona izin verir.

| Permissive Licenses | Copyleft Licenses |
|-|-|
| BSD | (Berkeley Software Distribution) Affero GPL (AGPL) |
| MIT | GPL |
| Apache 2 | Lesser GPL (LGPL) |
| | Mozilla Public License (MPL) |
| | Eclipse Public License (EPL) |
| | Common Development and Distribution License (CDDL) |

## Açık Kaynak Projelere hizmet veren servisler:

Depo yönetimi hizmeti, işbirlikçi yazılım geliştirmenin temel öğelerinden biridir. Başarılı bir teslimat,
bir yazılım tedarik zinciri oluşturmak için birlikte kullanılan açık kaynak ve üçüncü taraf bileşenlerinin
birleşimine bağlanır. Yazılım geliştirme yaşam döngüsüne uyan bu tedarik zinciri depo olarak
adlandırılır. Projeniz için uygun bir depo seçmek, yazılım geliştirme girişimlerinizi hızlandırırken, daha
hızlı ve daha güvenilir yapılar için verimliliği artırır. “Git”, depoları aracılığıyla sorunsuz ve verimli bir
yazılım geliştirme iş akışı sağlamak için kullanılan en popüler sürüm kontrol sistemidir. GitHub ve
GitLab, Git deposu barındırma hizmetlerinde öne çıkan iki isimdir.

### GitHub:

![GitHub](/assets/acik-kaynak/altug-demirden/4.png)

GitHub, web tabanlı bir havuz yönetimi hizmeti ve dünyanın en büyük kaynak kod deposu olan
yazılım geliştirici projelerinde işbirliği yapmak için tek bir çatı altında en büyük geliştirici topluluğunu
bir araya getirmektedir. İlk olarak 2008'de bir web sitesi olarak kurulan GitHub, dünyanın dört bir
yanından 80 milyondan fazla projede işbirliği yapan 27 milyondan fazla geliştiriciden oluşan bir
topluluğa sahip dünyanın en büyük Git depo havuzu olmak için hizmet vermektedir. Dünyanın en
büyük kod deposudur ve kullanıcıların 300'den fazla benzersiz programlama dilinde yazılmış açık
kaynak projelerini geliştirmelerine, paylaşmalarına ve katkıda bulunmalarına olanak tanır. Yazılım
oluşturmak ve bir takım olarak milyonlarca açık kaynaklı projede birlikte çalışmak ve daha iyi bir
yazılım geliştirme iş akışı için fikirleri paylaşmak merkezi bir yerdir.

### GitLab:

![GitLab](/assets/acik-kaynak/altug-demirden/5.png)

GitLab, modern yazılım geliştirme projeleri için GitLab Inc. tarafından geliştirilen web tabanlı bir Git
deposu yöneticisidir. Sony, IBM, Alibaba, NASA, O’Reilly Media, SpaceX, CERN ve daha fazlası gibi
büyük kuruluşlar tarafından kullanılan basit ama modern, tam özellikli bir Git sunucusudur. GitHub'un
aksine, ücretsiz ve açık bir kaynaktır. GitLab, tam yazılım geliştirme yaşam döngüsü için işbirlikçi iş
akışlarınızı kolaylaştırmak amacıyla Sorun İzleyicisi, Grup Kilometre Taşları, Sorun Tahtaları, Yol
Haritaları, Zaman Takibi ve daha fazlası gibi esnek proje yönetim araçları sağlar. Git depolarının,
kullanıcıların Git depolarında tam erişim ve kontrol sağlamasına olanak tanıyan merkezi bir sunucuda
tutulması en etkili yoldur. GitHub'a çok benzer ancak GitHub, Google Code, Bitbucket vb. gibi diğer
popüler Git depolarından kolayca içe aktarma gibi ek özelliklerine de sahiptir.


## Türkiye’de ve Dünyada Açık Kaynak Programlama:

Türkiye'de özgür yazılım farkındalığı yoğunluklu olarak Linux ile özdeşleşmiştir. Türkiye'de özgür
yazılım topluluğunun tohumları 1992 yılında atılmış, 1993 yılında linux@bilkent.edu.tr listesi
etrafında örgütlenmeye başlamış, 1995 yılında ilki düzenlenen "Türkiye'de İnternet" Konferansı'nda
ilk kez yüz yüze bir araya gelmiştir. Türkiye'de Linux ve Özgür Yazılım, "Türkiye'de İnternet"
Konferansı (inet-tr.org.tr), İnternet Haftası (internethaftasi.org.tr) ve Akademik Bilişim Konferansları
(ab.org.tr) içinde ve desteğini alarak gelişmiştir. Bunların içinde çeşitli kurs ve seminerler yapılmış,
ortalama bir salon Linux ve Özgür Yazılıma ayrılmıştır. Yer yer CD'ler ve kitapçıklar dağıtılmıştır.
1995'ten 2000 yılı ortasına kadar Türkiye Linux Kullanıcıları Grubu adı ile bir birlik oluşturan Türk
özgür yazılım gönüllüleri, 2000 Mayıs ayında başlatılan girişimler ile bir derneğe kavuşarak, Linux
Kullanıcıları Derneği adı ile ilk genel kurullarını Kasım 2001'de gerçekleştirmiştir. LKD Mayıs 2002'de
Ankara Üniversitesi'nde 1. Linux ve Özgür Yazılım Şenliğini gerçekleştirilmiştir. Etkinlikler her yıl
yinelenmektedir. LKD İnternet Haftalarında "Gezici Seminerler" adıyla Anadolu'da ağırlıklı olarak
Üniversitelerde, ve Bilişim etkinliklerinde Linux ve Özgür Yazılım seminerleri vermiştir. LKD'nin Linux
ve Özgür Yazılım Şenliğine paralel olarak, Bilgi Üniversitesi "Açık Kaynak Günleri" adıyla Özgür Yazılım
Etkinliği yapmış, Türkiye Özgür Yazılım Dünyası ile Uluslararası özgür yazılım dünyasının Liderlerini
tanıştırmıştır. LKD, Bilgi Üniversitesi etkinliklerine katkıda bulunmuştur. LKD’nin 1000 civarında üyeye
sahiptir. LKD'ye ek olarak Alternatif Bilişim Derneği, İnternet Teknolojileri Derneği, Pardus Kullanıcıları
Derneği ve çeşitli Özgür Yazılım Grupları (PHP, Mint, Debian, ...) sivil toplum kurumları olarak ÖAKY
ekosistemi içerisindeler. Linux ve Özgür yazılım eko sistemi içinde yazılım geliştiren, çözüm üreten,
eğitim ve destek veren çeşitli firmalara [http://www.linux.org.tr](http://www.linux.org.tr) portalinde ulaşmak mümkün.

Linux faaliyetlerin ek olarak çeşitli uluslararası popüler açık kaynak projelerinin yerelleştirme
çalışmaları için destek veren grupların ülkemizdeki ekosistemin bir parçası. Bugün düzenli yapılan
özgür yazılım temalı/kaynaklı etkinlik olarak, Linux ve Özgür Yazılım Günleri, Özgür Web Teknolojileri
Günleri, Akademik Bilişim Konferansı, İnternet Konferansı ve İnternet Haftalarında ve yıla yapılmış
Üniversitelerde yapılan Özgür yazılım Seminerleridir. Buna KAK eklenmiştir. Yerel Özgür Yazılımlar ile
ilgili ortak bir kütüphane yada depo bulunmuyor. https://linux.org.tr/yerel-ozguryazilimlar/ verilen
bağlantılara göre 95'i aktif, 37 durmuş ulusal açık kaynak projemiz var. Türkiye’de geliştirilen özgür
Linux dağıtımlarının sayısı ise (aktif ve aktif olmayan) 11 adet olarak verilmektedir. Türkiye'deki Linux
ve özgür yazılım topluluğu varlığını büyüyerek sürdürmektedir.

Eğitim teknoloji ve içeriklerinin açık olarak üretilmesi ve paylaşılabilmesi önemli gelişmelerden biridir.
ABD ve çeşitli ülkelerde gittikçe artan sayıda kurum hem teknolojilerini hem de içeriklerini açık
şekilde paylaşmaktadır. Türkiye'de Fatih projesi çerçevesinde açık eğitim içerikleri oluşturulması için
çalışmalar ve araştırmalar yapılmaktadır. Eğitim ve öğrenimin toplumun tüm katmanlarına
açılabilmesi ve erişilebilir kılınması Türkiye'de eğitimli insan potansiyelimizin ilerlemesinde önemli yer
tutacaktır.

2007 yılında Türkiye Bilimler Akademisi, Massachusetts Institute of Technology'de (MlT) 2000
yılından beri yürütülmekte olan Açık Ders Malzemeleri Projesi'nin Türkiye'de de uygulanması için
harekete geçti. Sadece Amerika değil, Çin, Japonya, Fransa, Hollanda, Hindistan, Vietnam ve Tayland
ile İspanyolca konuşulan ülkelerde benzer şekillerde uygulanan Açık Ders Malzemeleri Projesi
konusunda üniversitelere aracılık yapan Akademi, konuya ilgi gösteren 24 üniversite, YÖK, DPT ile
TÜBİTAK-ULAKBİM temsilcilerinden oluşuyor. Türk üniversitelerinin benzer girişimlerinin ele alındığı
toplantıda; üniversitelerimizde, öğretim üyelerinin bireysel girişimi olarak ders malzemelerini kişisel
web ortamında veya üniversitenin bir açık erişim hizmeti içinde sunma çabalarının teşvik edilmesi,
yabancı dersleri çevirmenin yanı sıra üniversitelerimizin özgün Türkçe ders malzemelerini bir web


ortamında tüm Türkiye'nin yararlanmasına sunmalarının desteklenmesi ve bu amaçla ulusal eşgüdüm
ve farkındalığının sağlanması amaçlanıyor.

Kamuda açık kaynak kullanımı yoğunluklu olarak işletim sistemi Linux/Pardus, Ofis ve e-posta gibi
sistemlerin kullanımına odaklıdır. Pardus veya Libre Office gibi devlet kurumlarında destek bulmayan
projelerde kamuda yaygınlaşmanın önünde yazılımların güçlü bir kuruluş tarafından
desteklenmemesi, geliştirilmesine son verilmesi riski gibi olumsuzluklar ön plana çıkmaktadır. Bu algı
kamunun paydaş olduğu güçlü açık yazılım ekosistemlerinin eksikliğine işaret etmektedir.

## Doğuş Teknoloji ve Açık Kaynak Programlama:

Özel yazılımlar, getirecekleri maliyetin yanı sıra, hizmet sağlayıcı tarafından sağlanamama riskini de
içerir. Bununla birlikte satıcıların fiyat artışlarına maruz kalabilirler. Doğuş Teknoloji içerisinde de,
özellikle sunulan hizmetler açısından güvenilir açık kaynak kodlu yazılımlar kullanılabilir ve az maliyet
ile çeşitli iş modelleri kurularak gelir elde edilebilir.

BT liderleri, işletmeleri için temel olarak esneklik ve çeviklik sağlamalıdır. Çeviklikle rekabet
edemezseniz, rekabette geride kalma riski ile karşı karşıya kalınması kaçınılmazdır. Açık kaynak,
genellikle sorunları çözmek için birçok yol sunan teknolojik çevikliği sağlar. Açık kaynak yazılım
kullanılması durumunda, bir kuruluştan temin edilen bir program içerisinde belirli bir özellik
sunulmadığı durumda kuruluşunuzun kendine özel çözüm sunmasına yardımcı olur. Satıcının bu
yeteneği sunmasını beklemek yerine, kendiniz oluşturabilirsiniz. Bu bağlamda Doğuş Teknoloji
tarafından açık kaynak kullanılması halinde, grup veya şirketlere özel çözümlerin de eklenti olarak
programlara eklenmesi mümkün hale gelecektir.

İşletmeye yönelik açık kaynaklı çözümler genellikle hem kurum hem de toplumun fayda sağladığı (ve
inandığı) bir çözümü desteklemek ve iyileştirmek için ortak bir itici güçle bağlı, etraflarında gelişen
topluluklara sahiptir. Bu çözümleri geliştirmek için bir araya gelen küresel topluluklar, yeni
konseptleri ve yetenekleri, tescilli çözümler üzerinde çalışan iç ekiplerden daha hızlı, daha iyi ve daha
etkili bir şekilde ortaya koymaktadır. Bu bağlamda, Doğuş Teknoloji tarafından bir açık kaynak
programlama platformu geliştirilerek, yeni ürün oluşturulmasına açık bir zemin oluşturulabilir; yanı
sıra kurulacak bu platform üzerinden yeni yeteneklerin keşfedilmesi de sağlanabilecektir.

Pek çok kişinin bir araya gelmesi güçlü sonuçlar verebilir. Harmoni içerisinde çalışan yetenekli
bireylerden oluşan bir topluluğun kolektif gücü, yalnızca daha fazla fikir sağlamaz, yanı sıra sorunlar
ortaya çıktığında daha hızlı geliştirme ve sorun giderme sağlar. Bu bağlamda Doğuş Teknoloji
tarafından seçilecek belli projelerin -önceki paragrafta bahsedilen- açık kaynak platformu üzerinde
geliştirme yapılmasına olanak sağlanabilir. Kurumsal sorunlar bakım maliyetleri etkili bir şekilde
paylaştırarak çözülebilir. Açık kaynağın temel avantajlarından biri de toplum katılımıdır. Bir uygulama
yazmaktan ve onu sürdürmek yerine, birden çok taraf arasında uygulama maliyetleri paylaştırılabilir.
Özellikle mevcut ekonomik durum itibariyle maliyet konusunun önem kazandığı bu günlerde,
geliştirme maliyetlerinin azaltılması için son derece faydalı olacağı görüşündeyim.

Açık kaynak kodu, yalnızca, kod tabanıyla ilgili tam bir görünürlük elde etmenin yanı sıra, topluluğun
özellikleri nasıl geliştirdiği ve hataları nasıl ele aldığıyla ilgili tüm tartışmalara da sahip olmanız
anlamına gelir. Bu bağlamda, Doğuş Teknoloji tarafından sunulacak platform üzerinde çalışan tüm
yazılım geliştiren kişilerin tecrübeleri ve sorunlara yaklaşımları da bilgi birikimi olarak şirketimize katkı
sağlayacaktır.


Açık kaynak çözümleri açık bir şekilde kullanılabilir olduğundan ve ücretsiz olarak
keşfedilebildiğinden, seçenekleri araştırmak ve çözüm üretmek için genellikle çok daha hızlıdır. Bu
bağlamda Doğuş Teknoloji tarafından geliştirilecek yeni ürünlerin açık kaynak platformu üzerinden
yayılması ve kullanıcılar tarafından denenerek geliştirilmesi sağlanabilir.


## Kaynaklar

```
➢ What is open source?
https://opensource.com/resources/what-open-source
```
```
➢ FOSS History in Retrospect: 3 Generations of Open Source Coders and Users
https://www.channelfutures.com/open-source/foss-history-retrospect- 3 - generations-open-
source-coders-and-users
```
```
➢ The 9 most important events in Open Source history
https://royal.pingdom.com/2010/01/15/the- 9 - most-important-events-in-open-source-
history/
```
```
➢ A Visual History of Open Source
https://www.infoworld.com/article/2832394/a-visual-history-of-open-source.html
```
```
➢ Difference Between Different Types Of Open Sources Licenses
https://fossbytes.com/open-sources-license-type/
```
```
➢ Open Source Software and Licensing
https://www.kynetics.com/docs/2018/open-source-software-and-licensing/
```
```
➢ Özgür Açık Kaynak Yazılım Stratejilerinin Türkiye Bilgi Toplumu Hedefleri İçerisindeki Önemi
(Naci Dai, Sait Ölmez - Sabancı Üni.)
```
```
➢ Choosing an open-source license
https://www.software.ac.uk/resources/guides/adopting-open-source-licence
```

