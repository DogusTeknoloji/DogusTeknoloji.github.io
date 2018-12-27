---
layout: post
title:  "Open Source Proje Geliştirme - Sercan Solmaz"
categories: ["Açık Kaynak"]
tags: ["Açık Kaynak", sercansolmaz, srcnslmz, sercansolmazphoto]
redirect_from: "/assets/Open_Source_Proje_Gelistirme_Sercan_Solmaz.pdf"
permalink: acik_kaynak_sercan_solmaz
---

[Pdf versiyon](/assets/acik-kaynak/sercan-solmaz/Open_Source_Proje_Gelistirme-Sercan_Solmaz.pdf)

<img src="/assets/acik-kaynak/sercan-solmaz/0.png" alt="OpenSource" width="699"/>

# Açık Kaynak Kodlu Yazılım

Açık kaynak kodlu yazılım, yazılım özgürlüğünü amaçlar ve bilgisayar kullanıcılarının yazılım üzerinde kullanım, dağıtım ve değiştirme özgürlükleri olduğunu vurgular.

Yazılımların donanımlar ile dağıtıldığı dönemlerde, bir donanım satın alındığında ihtiyacı olan yazılımla birlikte gelirdi ve o yazılım sadece o donanımla beraber çalışabilirdi. Bu durumda o yazılımı belirli sınırlar çerçevesinde dilediğiniz gibi değiştirme ve geliştirme imkânınız vardı. Zamanla kişisel bilgisayarların yaygınlaşması, farklı karmaşık yazılımların ortaya çıkması, beraberinde yazılım üreticilerinin ürünlerini korumaya yönelmesine ve telif haklarına başvurmasına, önceden donanımı kullanan uzman kişilerin değiştirebilmesi için açık kaynak olan kodların kapatılmasına, yazılımla beraber dağıtılmamasına neden oldu. Artık satın aldığınız bir yazılım ürününü çevrenizdekilerle paylaşmanız mümkün olmadığı gibi, kaynak kodlara erişip değişiklik yapma imkanınızda ortadan kalkmış oldu.

Ancak yazılım ürünlerinin açık kaynak kodlu yazılım olarak dağıtılması ile bu sınırlamalar ortadan kalkmaktadır.

## Gücü ve Yaygınlaşmasının Nedenleri

Ticari bir sır olarak da görülebilecek bir kaynak kodun ücretsiz bir şekilde paylaşılmasının arkasında yatan sebepler şunlar olabilir:

1. Ürün sahibinin ürünün tasarımı ve uygulama detayları için erişimi ve ücretsiz yeniden dağıtımı teşvik eden bir felsefe ya da pragmatik yöntem bilimi olarak açık kaynak akım savunucusu ve taraftarı olması ya da pazardaki benzer ürünlerin lisans ücretlerini gereksiz ya da yüksek bulması,
2. Ürünün bir sahibi olmayabilir; hibe edilmiş, gönüllülerce ortak yaratılmış olabilir, yani zaten kimsenin sırrı olmadığından saklanmaması,
3. Yazılım ürününün kullanımının yaygınlaşmasının sağlanması,
4. Yazılım ürününün kitle kaynak yöntemiyle bedavaya denenip hatalarının bulunup temizlenmesinin sağlanması,
5. Ürün sahibinin daha önce düşünmediği, ama pazarda ihtiyaç olan uygulama alanlarının ortaya çıkmasının sağlanması,
6. Ürün sahibinin itibarını arttırması,
7. Yazılım ürününün daha gelişmiş bir çeşidinin daha kolay satılması için pazar yaratılması,
8. Ürünün kârlı bir şekilde pazarlanabilmesine engel olan rakip yazılımları saf dışı etmesi.

Açık kaynak kodlu programın kullanımı genelde ücretsizdir ve düzenlenmesini herkes için açık tutar. Açık kaynaklı yazılımlar içinde özgür bir yazılım lisansı ile lisanslanmış olan yazılımlar, özgür yazılım sınıfına girerler. Tüm özgür yazılımlar, aynı zamanda açık kaynaklı yazılımlardır. Ancak her açık kaynak yazılım, özgür yazılım olmayabilir.

## Open Source Proje Geliştirmenin Tarihçesi

1970'li yıllarda Richard M. Stallman, MIT’nin Yapay Zekâ laboratuvarlarında serbest yazılımı bir yaşam şekli olarak benimsemiş bir grupla beraber 1980'li yılların başına kadar yazılım geliştirici olarak çalışmıştır. Bu grup ile olan birlikteliğinin sona erişinin ardından kendisini o dönemlerde ivme kazanan bazı akımlardan dolayı benimsenmeye başlanılmış yeni bir sosyal sistem içerisinde bulmuştur, Stallman bir röportajında o günleri şu şekilde nitelendirmekte:

“Kendimi özgür olmayan (kaynak kodu kapalı olan) yazılımların hâkim olduğu ve kullanıcıların yardımsız bırakıldığı, parçalanmış ve birlikte çalışmanın korsanlık olarak nitelendirildiği çirkin bir sosyal sistemin içinde buldum. Bu tür bir yaşantıyı reddettim. Ancak işimi özgürlüğe ve birlikte çalışmaya adadığım zaman yaptıklarımdan gurur duyabileceğime karar verdim.”

Ve 1984 yılında tamamen özgür yazılımların meydana getirdiği bir işletim sistemi ve işletim sisteminin araçlarının geliştirilmesi çalışması böylece başlamış oldu, işte bu çalışmanın adı GNU idi. Yazılan özgür yazılımların bir şemsiye altında toplanması için 1985 yılında yine Stallman tarafından FSF (Özgür Yazılım Vakfı) kuruldu ve GNU yazılımları korumak üzere GPL (Genel Kamu Lisansı) adı verilen yazılım lisansı duyuruldu. GPL lisansı ile lisanslanan özgür yazılımların amaçları özgürlüklerini korumaktan başka bir şey değildir.

<img src="/assets/acik-kaynak/sercan-solmaz/1.png" alt="OpenSource" width="599"/>

Richard Stallman

## Open Source Lisanslama Seçenekleri

### MIT

Telif hakkı ve lisans bildirimlerinin korunması şartlarını barındıran bir izin belgesidir. Lisanslı çalışmalar ve değişiklikler kaynak kodu olmadan dağıtılabilir.

**GNU General Public License v3.0 (GNU GPLv3)**

Yazılımı yeniden dağıtmak ve değiştirmek için özgürlük sağlamaktır. Bu nedenle, GNU yazılımını kamuya açık hale getirmek yerine, “copyleft” uygulamayı tavsiye eder. Copyleft değiştirerek ya da değiştirmeyerek yazılımı dağıtan kişinin, yazılımı kopyalamak ve değiştirmek isteyen kişilere bu özgürlüğü aktarmaları gerektiğini söyler. Copyleft, her kullanıcının özgürlüğe sahip olmasını garantileyen, bir programın (veya başka bir çalışmanın) özgür yazılım haline getirilmesi, programın tüm değiştirilmiş ve genişletilmiş sürümlerinin de özgür yazılım haline getirilmesi için genel bir yöntemdir.

**Apache**

Apache Yazılım Vakfı (ASF) tarafından yayımlanmıştır. Tüm yazılım sürümlerini telif hakkı koruması altına alır. Lisans, özgür ve açık kaynak kodlu yazılımın geliştirilmesi için kaynak kodlarının kullanımına da izin vermektedir.

## Open Source Kullanmanın Verdiği Özgürlükler

**- Güvenilirlik:** Açık kaynak kodlu bir yazılım, doğası gereği geliştirilmesi sürecinden kullanımı zamanına değin on binlerce göz tarafından denetlenmektedir. Var olması muhtemel bir güvenlik problemi ya da kötü niyetli bir programcı tarafından bilinçli olarak yerleştirilebilecek bir kod parçası yazılım kullanıcının eline ulaşmadan tespit edilmekte ve hızla düzeltilmekte ya da kullanıcıya ulaşması engellenmektedir.

**- Esneklik:** Kaynak kodu açık bir yazılım hızla ve kolaylıkla yeni bir sistem üzerinde çalışacak şekilde yeniden yapılandırılabilmekte, bir kısmı çıkarılarak kapsamı daraltılabilmekte ya da eklenen yeni fonksiyonlarla kapsamı genişletilebilmektedir.

**- Uygulama Desteği:** Çok geniş bir yelpazede ve çeşitlilikteki birçok açık kaynak kodlu özgür yazılım her gün duyurulmaktadır. Herhangi bir konudaki ihtiyaç açık kaynak kodlu yazılımlarla hızlı ve kaliteli bir şekilde çözüme kavuşturulabilmektedir.

**- Sağlamlık:** Yine açık kaynak kodlu yazılımların doğal geliştirme süreci içerisinde çok sayıda insan tarafından denenmeleri ve kaynak kodlarının gözden geçirilmesi sonucunca ortaya yüksek kalitede, satabil ve kuvvetli yazılımlar çıkmaktadır.

## Open Source Kullanmanın Ekonomik Katkısı

Bugüne kadar kendi yazdığı yazılımın kaynağını sır olmaktan çıkaranlar arasında o yazılımdan gelir elde etme yaklaşımları bakımından bazı düzenlemelerin başarılı olduğu çeşitler vardır:

1. Gelir beklemeden sırf yaratma aşkıyla yapılanlar: Wikipedia'ya katkıda bulunanlar, bazı sanatçılar.
2. Bağış / Gönlünüzden ne koparsa: Sokak çalgıcıları ve Wikipedia'nın çalışıyor olmasını sağlayanlar.
3. Güçlü himayeci: Bazı ülkelerde devlet desteğiyle araştırma yaparken üretilen yazılımlar.
4. Bedava seçkin / Freemium: Ürünün basit bir çeşidi bedava verilen, daha karmaşık / kıymetli işlevler içeren başka bir çeşidi para karşılığı satılan, birinin öbürü için reklam / tanışıklık / bağımlılaştırma işlevi gördüğü düzen.
5. Ürün bedava, bağlı ya da başka bir ürün veya hizmet ücretli.
6. Pazar payı kazanmak, kendi başka ürünlerinin yolunu daha açık tutmak için bir ürünün bedava verilmesi; Internet gezgini savaşları buna örnek olarak görülebilir.
7. Kendi kullanımı için yazıp bedava dağıtarak başkalarının deneyip buldukları hataları bildirmesi, daha geliştirilmiş ya da ondan yola çıkarak daha başka faydalı yazılımlar üretmesi gibi geri dönüşlerde umudu olan yaklaşım.

Bir sürü yetenekli yazılımcının, neden maaş almadan ürünün üretimine katkıda bulunduklarını anlamak oldukça zor. Örneğin neden Apache, Perl ve Sendmail gibi büyük ürünler özgür yazılımdır ve ücretsiz temin edilebilirler? Ekonomik açıdan bakıldığında özgür yazılım geliştirmedeki bu özelliklerin büyük bir kısmının çözümü “kariyer kaygısı” ile açıklanabilir.

Özgür yazılım gelişiminin geleceği ve kullanım alanları geçmişten gelen ve ezber olmuş ekonomik modeller ile ölçülmemelidir. Ancak buna rağmen konunun daha önceki literatürlerde geçen “teknolojik yenilik” kavramı ile yakından ilgili de vardır. Özgür yazılımların geliştirilme süreci, diğer birçok sektörde görülen “kullanıcı odaklı yenilik” kavramının değişik bir şeklidir. 1976 yılında geliştirilen Rosenberg ve 1988 yılında geliştirilen Hippel'in çalışmalarında belirttiği gibi; belirli kullanıcılar için geliştirilmiş kişisel çözümler sonradan daha geniş kitlelerin sorunlarının çözülmesinde kullanılmıştır.

## Yazılım Lisanslarının GSMH İçindeki Payı

Gelişmekte olan ülkelerde, yeteneklerin düşük maliyetler ile gelişmesi özgür yazılımın promosyonu açısından önemlidir. Ancak gelişmiş ülkeler ile kıyaslandığı zaman maliyetlerin de özgür yazılım kullanılması açısından önemli olduğunu görürüz. Gelişmiş ülkelerde yapılan toplam sahip olma maliyeti çalışmalarına göre, özgür yazılım kullanımı toplam kullanım ve bakım maliyetlerine çok fazla yansımamaktadır. Bunun nedeni gelişmiş ülkelerde ücretlerin yüksek ve özgür yazılım lisans ücretlerinin göreli olarak düşük olmasından kaynaklanmaktadır. Gelişmiş ülkelerde yapılan toplam sahip olma maliyetleri çalışmaları, bu ülkelerde lisans giderlerinin toplam maliyetlerde %5-10; bakım, entegrasyon, destek ve eğitim hizmetlerinin ise %60- 85 arasında olduğunu göstermiştir. Ücretlerin yüksek olması ekonominin emek yoğun bileşenlerinin toplam maliyetler içerisinde daha büyük paya sahip olmasına neden olmaktadır. Özgür yazılım kullanımından meydana gelen kesin tasarruf sıfır lisans ücreti olduğu için, bu çalışmalarda lisans maliyetlerinden doğan avantajlar net olarak görülememektedir. Buna karşın, ücretlerin düşük olduğu gelişmekte olan ülkelerde, lisans ücretlerinin toplam sahip olma maliyetleri içerisindeki payı çok daha büyüktür.

Bu ilişki ülkedeki lisans ücretleri fark edilebileceği gibi, gelişmekte olan ülkelerdeki alım gücü açısından, indirim yapılmış bile olsa ticari yazılımların lisans ücretleri çok fazladır. Amerika'da, gerekli olan standart yazılımlar için (Örneğin Windows 10 + Office 365) ödenmesi gereken lisans ücreti $560 civarındadır. Bu bedel Güney Afrika'nın 2.5 ay, Vietnam'ın ise 16 ay ötesindedir. Bu Amerika'da tek bir kullanıcı için, sırasıyla, $7,541 ve $48.011 lisans ücreti demektir ve istenen bu miktarın karşılanamayacağı çok barizdir. Yine aynı yönteme bakılarak lisans ücretlerine yapılacak herhangi bir indirimin bu maliyetleri önemli miktarda azaltmayacağı ve bu indirimlerin uzun dönem refahtan çok kullanıcıları arz edilen yazılımlara bağımlı olma amaçlı olduğu görülmektedir.

Korsan yazılım kullanım oranı ile etkin yazılım lisans ücreti doğru orantılıdır. Yazılım ücreti arttıkça korsan yazılım kullanım oranı da artmaktadır.

## Dünyadaki Popüler Open Source Yazılımlar

- WordPress
- Mozilla Firefox
- Apache OpenOffice
- My SQL
- NotePad ++
- Android
- VS Code
- Atom
- Eclipse CHE
- FreeCAD
- GNUCash
- Kodi
- MyCollab
- OpenToonz
- Roundcube

## Türkiye’de Open Source Kullanımı

Zekanıza değil de hislerinize hitap eden ifadeler ile size bir şeyler satılmaya çalışılıyorsa, muhtemelen kandırılıyorsunuz demektir.

Siyasette yapılan hatalar yerli ve milli lafları ile kapatılmaya çalışılırken bu hikâyeye yazılımcıların da inanmış olması oldukça vahimdir. Yerli ve milli arama motoru, yerli işletim sistemi, yerli ve milli robotlar, milli mesajlaşma yazılımları vs. gibi tamamen hislere hitap ederek insanları kandırma amacı olan iddialar ile sunulan yazılımların var olduğuna gerçekten inanmaya başlanıyor. Bu emekler elbette takdir edilesidir ama bunu pazarlarken yerli ve milli ifadeleri ile pazarlanan ürünlerdeki hangi ayıplar örtülmeye çalışıyorlar diye merak etmiyor değilim. Yerli ve milli diye pazarlanan ürünün parçasından üretimi için kullanılan araçlarına kadar çoğu kısmı dışarıdan geliyor. Orada yerli ve milli olan sadece parçaları birleştiren kişi.

Bir belediye yukarıdan gelen bir emirle Pardus’a geçiyoruz diye Windows işletim sistemine Pardus duvar kâğıdı koymak suretiyle yerli ve milli insanları kandırmaya devam etme kararı almıştı. Hangisi daha vahim: Bu kadar cahil olmak mı yoksa milleti kandırmak için Windows’u Pardus diye pazarlamak mı?

Pardus’un meydana gelmesi için hemen hemen her şey neredeyse yüzyıldır yurtdışında geliştiriliyor ve ülke olarak buna bir gram katkımız olmadı. Bakalım bu yerli ve milli işletim sistemimiz olan Pardus’un neleri yurtdışından geliyor:

1. Linux Kernel.
2. C++ ve C programlama dilleri. Eğer kullanıyorsa diğer tüm programlama dilleri, mesela Java, Go, Python.
3. Geliştirme için kullanılan IDE programlar.
4. Pardusu geliştirmek için kullanılan işletim sisteminin kendisi.
5. Pardusta ki resimleri tasarlamak için kullanılan resim editör uygulamaları.
6. Pardusun geliştirilmesi için kullanılan bilgisayarın kendisi.
7. Kaynak kodların saklanması için kullanılan source code versioning aracı.
8. İnternete bağlanabilmek için gerekli router.

Eğer bir değişim yapmak istiyorsak bunu tüm dünya ile entegre olarak yapmalıyız. Gelişmiş ülkeler arasındaki bilgi alışverişi ve rekabet birbirlerini geliştirmekle sonuçlanıyor. Volkswagen son model bir araba yaparken, içine Apple tarafından üretilmiş yazılımlar eklerse ortaya kaliteli bir ürün çıkar. Benzer şekilde yazılım mühendislerinin dışarıya açılmaları, İngilizce öğrenmeleri, yurtdışında ki yazılımcılar ile de bir şeyler yapmaya çalışmaları ve bu şekilde oluşturdukları ağlarda yeni şeyler geliştirmeleri gibi adımları atmaları çözümün bir parçasıdır. Bugün milyonlarca yerli ve milli mühendisin para kazanmasına ve ailelerini geçindirmeye yarayan kodlar bu düşünce ile geliştirilmiş açık kaynak kodlu kütüphaneler, uygulamalar, web siteleri, framework’lerdir. Açık kaynak kodlu projelere dünyanın her yerinden insanlar katkı sağlar.

## Doğuş Teknoloji ve Open Source

İçinde bulunduğumuz ekonomik tedirginlik ve dengesizliklerden dolayı bana göre bir teknoloji firmasının bu durumda yapacağı en önemli değişiklik finansal giderlerini dert etmek olmalıdır. Bu nedenle açık kaynağın getireceği fırsatlardan yararlanmak mantıklı olacaktır. Bununla beraber çeşitli açık kaynak komitelerinden alınacak yazılım geliştirme desteği de fayda sağlayacaktır.

Farklı uzmanlıklardaki kişilerin birlikte çalışması, mevcut durumdan çok daha iyi sonuçlar verebilir. Kolektif bir çalışma planı bir teknoloji firması için oldukça verimlidir. Bu sebeple açık kaynak komitelerinin desteği ile çok daha verimli çalışmaların yapılması beklenen bir durumdur. Özellikle şirketin içinde bulunduğu Agile dönüşüm süreci ile hem doğrudan müşteri hem de farklı açılımlar yapılması piyasa şartlarında hız ve esneklik açısından çok daha fazla önem kazanmaktadır. Bazı belirgin noktalardaki çözüm arayışının şirket dışında, özellikle de açık kaynakta aranması doğru bir yaklaşımdır.

Bu çözüm arayışı elbette çift taraflıdır. Bir taraftan şirket içerisindeki projelere çözüm ararken, diğer taraftan da Doğuş Teknoloji’nin geliştirdiği çözümün piyasada kullanılması olumlu sonuçlar doğuracaktır. Hem kaynak paylaşımı hem de piyasada tanınırlık açısından bu önemli bir konudur. Bu da açık kaynağın önemli bir avantajıdır.

Doğul Teknoloji’nin açık kaynaklı çözümlere yönelmesi hem şirket içerisinde hem de topluma fayda sağlanan bir çözümün desteklenip yaygınlaştırılmasında önemli bir potansiyel taşımaktadır. Bu çözümleri geliştirmek için bir araya gelen farklı topluluklar ve kurumlar global boyutta farklı yetenek ve çözümleri de beraberinde getireceklerdir. Bu sebeple, Doğuş Teknoloji tarafından bir açık kaynak programlama platformu geliştirmek ya da çözümün bir parçası olmak, yeni ürünün tasarlanmasına imkan sağlayacağı gibi, kurumun piyasada daha da tanınmasına ve bazı belirgin alanlarda daha fazla söz sahibi olmasının da önünü açmış olacaktır.

Genelde piyasada popüler olmuş marka değeri taşıyan çoğu ürünün sunduğu imkanların bir kısmı şirketlerde kullanılmaz. Bu durum Doğuş Teknoloji’nin piyasadan temin ettiği ürünler için de geçerlidir. Ancak imkanlar kullanılmıyor diye elbette fiyatlandırma politikalarında bariz bir değişiklik olmaz. Bu da şirketlere ekonomik olarak yük olmaktadır. Diğer taraftan tüm imkanlar bir ihtiyacı karşılıyor olsa dahi ücretsiz ya da daha düşük ücretli piyasadaki yeni oyunculara imkan sağlamak gerekir. Şu an Doğuş Teknoloji içerisindeki en sıcak konu veri tabanı mimarisidir. Mevcutta kullanılan Microsoft ürünü olan MSSQL oldukça yüksek maliyetli bir çözümdür. Bu ürüne alternatif olarak kullanılabilecek ve benzer imkanlar sunan ürün olan PostgreSQL ise tamamen ücretsizdir. Benzer bir konu olarak tüm clientların neredeyse standart olarak barındırdığı ofis paketleri de oldukça yüksek fiyatlı Microsoft ürünleridir. Elbette ücretsiz bir alternatif olarak Libre Office ya da Open Office tercih edilebilir. Benzer bir konuda projelere ait repoların saklanması ve versiyonlanması için tercih edilen platform ile ilgildir. Önceden kullanılan TFS yine bir Microsoft ürünüydü ve yüksek lisans maliyetine sahipti. Aynı ihtiyacı BitBucket gibi bir alternatif ile çözmek ekonomik açıdan fayda sağlayacaktır.

## Kaynak

https://teknolojiprojeleri.com/programlar/acik-kaynak-kod-ozgur-yazilim-nedir-nasil-yazilir 

https://tr.wikipedia.org/wiki/Açık_kaynak

http://yunus.hacettepe.edu.tr/~elcin.keles12/calismalarim/BBY262/web06/avantajlariVeDezavantajlari.html

https://en.wikipedia.org/wiki/Open-source_software

https://opensource.com/resources/what-open-source

https://forum.pardus.org.tr/t/acik-kaynak-sadece-kaynak-koda-erisim-anlamina-gelmez

https://shiftdelete.net/2016-yilinin-en-iyi-acik-kaynak-kodlu-projeleri-78609

https://medium.com/@kurtulussahin/neden-ozgur-yazilim-f8fd02363f7d

https://insights.stackoverflow.com/survey/2018/

http://www.minepla.net/2015/05/visual-studio-code-nedir-ne-degildir/

https://www.pardus.org.tr/donusum/

https://medium.com/@atarikguney/yerli-ve-milli-yazılım-safsatası-2b3cc8d81ab

https://webrazzi.com/2018/03/13/stackoverflow-2018-anketine-gore-yilin-en-populer-programlama-dilleri-ve-diger-yazilim-araclari/