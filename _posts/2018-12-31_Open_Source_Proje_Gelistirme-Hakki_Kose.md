---
layout: post
title:  "Open Source Proje Geliştirme - Hakkı Köse"
categories: ["Açık Kaynak"]
tags: ["Açık Kaynak", hakkikose]
permalink: acik_kaynak_hakki_kose
---

[Pdf Versiyon](assets/acik-kaynak/hakki-kose/Open_Source_Hakki_Kose.pdf)

# Open Source Proje Geliştirme

## Open Source Nedir?

Yazılım kopyalanabilir. Yazılım kullanılabilir. Yazılım değiştirilebilir. Bu haklardan faydalanabilmek için
bu hakları başkalarına vermek zorundayız. Bu 4 madde ile bir yazılım ekosistemi oluşturuldu aslında.
Özgür yazılım bir iş birliği fikri gibi düşünebiliriz.

Açık kaynak kodlu yazılımın ardındaki fikir, kullanıcıların etkili bir şekilde ortak geliştiriciler olması,
onu geliştirmenin ve hataların ve sorunların giderilmesine yardımcı olmanın yollarını önermektir. Bu,
dilerseniz kendi ihtiyaçlarınıza göre değiştirebilir, yeni işletim sistemlerine taşıyabilir ve başkalarıyla
paylaşabilirsiniz.

Open source’un açılımı;

Open: Herkesle iş birliğine açık

Source: Kaynak kod serbest şekilde paylaşılır

## Tarihçesi

Eskiden bilgisayarlar büyük kurumların tekelindeydi. Üniversite IBM gibi büyük firmaların. Yavaş
yavaş kişisel bilgisayarlar insanların kullanımına açıldıkça yazılım sektörü doğmaya başladı. Bunun
sonucunda da daha çok yazılımcı ortaya çıkmaya başladı. Bunun hızlanması için Richard Stallman
1 983 bir atılım yapıyor. GNU isimli proje ortaya çıkıyor.

Amaç o zamanlar çok yaygın olan Unix işletim sisteminin herhangi bir kodu kullanılmadan tamamen
açık kaynak kodla ve başkalarının kullanmasına serbestlik sağlayacak bir işletim sistemi geliştirmek.
İşletim sistemi tamamen bir araya gelmiyor. Çeşitli modülleri yazılıyor ama sonra Linux çekirdeği
ortaya çıkıyor. Richard Stallman bu düşüncenin felsefesini başlatan kişidir ve vakfın kurulmasına
öncülük eden kişidir.

1989 yılına kadar çeşitli yazılımlar üretiliyor ama hepsinin farklı farklı lisansları var. Diyorlar ki bir tane
lisans olsun ve bütün yazılımlara uygulanabilir olsun. Temel bir felsefe getirelim deniyor.

4 temel kuralı vardır.

0. Kural: Programın sınırsın kullanma özgürlüğü – Ücretsiz kullanma özgürlüğü
1. Kural: Programın nasıl çalıştığı inceleme ve amaçlara uygun değiştirme özgürlüğü – Kaynak
    kodu açık olacak. Derlenmiş bile olsa yanında kaynak kodu verilecek ve nasıl çalıştığını
    inceleme şansı tanıyacak.
2. Kural: Programın kopyalarını sınırsız dağıtma özgürlüğü
3. Kural: Programın değiştirilmiş hali de dağıtılabilir – Örn. Kopyası alınan bir koda değişiklik
    yaptınız yeni bir verdiniz ve yeniden dağıtabilirsiniz.

Bu temel kurallar özgür yazılım vakfının temel felsefedir. Buradan yola çıkarak genel kamu lisansı
(GPL)ortaya çıkmıştır. Bu lisansı kullanarak geliştiriciler kendi yazdığı yazılımları lisanslamaya
başlayabiliyorlar.

Genel kamu lisansının (GPL) temel felsefesi ise GPL ile lisanslanmış bir yazılım kullanıldığı zaman
ortaya çıkarılan yeni yazılımının da GPL lisansı olmak zorundadır. Örneğin Linux çekirdeğini alıp
kullandığınızı varsayalım ve bu yazılım üzerinde değişiklikler yapıp yeni bir işletim sistemi ortaya
çıkardığımızı düşünelim. Bu yeni işletim sistemini insanların kullanımına sunduğumuzda kaynak
kodumuzu yine açık olarak paylaşmak zorundayız. Paralı satılması önünde bir engel yok ancak kaynak
kodlarımızı paylaşmak zorundayız. Başkası da bunu alarak istediği gibi değiştirebilir ve kullanabilir.
Burada amaç yazılım geliştirme işini kolaylaştırsın ve etkileşime girmesini sağlamaktır.

Özgür yazılım ve açık kaynak birebir aynı şey demek değildir. 90 ’ların sonunda sektörde şöyle bir şey
olmuş. Bir grup siz böyle çok özgür yazılım diyorsunuz felsefesini öne çıkarıyorsunuz ancak bu durum
büyük firmaları , ticari firmaları korkutuyor. Biz ayrı bir inisiyatif başlatıyoruz diyorlar ve open source
inisiyatifi diyorlar. Bu özgür yazılım felsefesini çok önce çıkarmadan temelde aynı şeyi yaparak açık
kaynak ortaya konuluyor. İşin felsefesini çok bastırmadan dile getiriliyor.

Richard Stallman bu konuda bir yazı yazmıştır. Aralarında bir düşmanlık yok ancak bir anlayış farkı
bulunmakta. RS diyor ki açık kaynak koda sadece pragmatik açıdan bakıyorlar. Bir geliştirme
metodolojisi olarak görüyorlar. Özgür yazılım bir sosyal sorundur bir olaya bu açıdan bakıyoruz diyor.

Linux’ta kullanılan bazı GNU lisanslı modüller GCC (Compiler), Bash (Terminal) bunun gibi temel
modüller özgür yazılım ile ortaya çıkmıştır.

## Lisanslama Seçenekleri

Pek çok lisans türü vardır ve lisans türleri yıllar içinde değişikliğe uğramıştır ve yeni versiyonları ortaya
çıkmıştır. İhtiyaca göre kendi lisanslama seçeneğinizde bu ortama koyabilirsiniz tabi benimsenip
benimsenmeyeceği topluluğun ihtiyaçlarına bağladır.

### GPL - GNU Genel Kamu Lisansı

Kaynak kodun herkese açık hale getilrilmesi gereklidir. Yazılımda
yapılan düzenlemeler aynı lisans altında yayınlanmalıdır. Kaynak
kodda yapılan değişiklikler dokümante edilmelidir.

Bu lisans türü ile üretilmiş en önemli yazılımlardan biri Git’tir. Git ücretsiz ve açık kaynak kodlu
projeleri geliştirirken kullanılan versiyonlama sistemlerinden biridir Git. Github ise git kullanana
yazılım projeleri için bir depolama servisidir. Github açık kaynak kodlu projeler tarafından en çok
tercih edilen servistir.

### LGPL- GNU Kısıtlı Genel Kamu Lisansı

GPL’den türeyen ihtiyaçtan doğan bir lisansıdır. Bazı geliştiriciler GPL lisanslı bir yazılımı kullandıkları
paylaşmak zorundaydı ama bunu istemişler. LGPL ile lisanslanmış bir ürünü kullandığınızda bu imkan
sağlanmış olur.

### MIT

En popüler yazılım lisanslama türlerinden biridir. Yazılım
yayınlandığında kaynak kodun genel erişiminin olması gerekmez.
Yeniden kullanımla ilgili çok sınırlı kısıtlamalar koyar. Yapılan
değişiklikler herhangi bir lisans türü altında yeniden yayınlanabilir.
Örnek yazılımlar, jQuery, AngularJS

### Apache Lisansı

Google Android bu lisansa sahiptir. Değişlik yapılabiliyor ancak ana lisansı
yeni yazılıma mutlaka eklemek gerekiyor. Ana kütüphanem budur demek
gibi. Apache lisansında yapılan değişiklikler herhangi bir lisans türü altında
paylaşılabilir.

### Mozilla Public License - Mozilla Lisansı

İstenildiği gibi değişiklik yapılabiliyor ancak yeni yazılımdan gelir elde edilirse pay
vermek gerekebiliyor. GPL’e göre daha zayıf özellikler barındıran bir lisans türüdür.

Detaylı açık kaynak lisanslama çeşitleri için aşağıdaki linkten erişim sağlayabilirsiniz.

[Yaygın yazılım lisansları arasındaki lisans uyumluluğu](https://en.wikipedia.org/wiki/Comparison_of_free_and_open-source_software_licenses)

## Açık kaynaklı yazılımın avantajları nelerdir?

En önemli faydalarından biri yazılım eforu gerektirmeyen bir açık kaynak kod kullanımında bu
yazılımın istemediğiniz özelliklerini dışarıda bırakıp kendi ihtiyaçlarınıza göre düzenleme şansınızın
olmasıdır.

Yazılım maliyeti düşüyor. Bazıları ücretsiz olabiliyor.

Pek çok kullanıcı katkı yaptığı için uygulama açıkları kapatılabiliyor. Ve çok kullanıcı kontrol ettiğinden
bu hızlı bir zamanda gerçekleşiyor.

Genelde ücretsizdir- açık kaynaklı yazılımın işletmelere toplu olarak yılda 60 milyar dolar kazandırdığı
tahmin edilmektedir.

Sürekli olarak gelişmektedir; bu, tescilli sistemlere göre daha iyi kalite ve daha güvenli ve hatalara
daha az eğilimli olabileceği anlamına gelir.

Açık kaynaklı yazılımın kullanılması, yalnızca diğer sistemleriyle çalışan belirli bir satıcının sistemini
kullanmaya zorunlu olmadığınız anlamına da gelir.

Açık kaynak kodlu yazılımı kendi gereksinimleriniz için, değiştirebilir ve uyarlayabilirsiniz.

## Açık kaynaklı yazılımın dezavantajları nelerdir?

Açık kaynaklı olduğu için ortaya çıkacak problemler üzerinde sorumluluk kabul edilmez.

Ticari bir ürün yaratma zorunluluğu olmadığı için, açık kaynaklı yazılımlar, geliştiricilerin istekleri
doğrultusunda son kullanıcının gereksinimlerine göre daha fazla gelişme eğiliminde olabilir.


Aynı sebepten dolayı, daha az "kullanıcı dostu" olabilirler ve kullanımı kolay olmayabilir, çünkü
kullanıcı ara yüzünü geliştirmeye daha az dikkat edilir.

Açık kaynaklı yazılımın kendisi çoğunlukla ücretsiz olsa da, harici destek için ödeme yapmak gibi bazı
dolaylı maliyetler de olabilir.

Açık bir sisteme sahip olmak, birçok insanın hataları tespit edip düzeltmek anlamına gelmesine
rağmen, kötü niyetli kullanıcıların potansiyel olarak görebilecekleri ve tüm güvenlik açıklarından
yararlanabilecekleri anlamına gelebilir.

## Neden Açık Kaynak?

Açık kaynak, yazılımı dağıtmanın sadece etkili bir yolu
değildir. En iyi ürünü mümkün kılmak için etkili bir
yoldur. Her indirme, projenin gelişmesi ve gelişmesi
için bir fırsattır. Kullanıcılar kodu incelerken güvenlik
güçlenir. Güvenilirlik ve esneklik, çeşitli mimariler ve
ortamlarda yapılan sıkı testler ile daha da geliştirilir.

> Yazılım oluşturmak iyidir, ancak yazılımınızın etrafında bir topluluk oluşturmak daha iyidir.

Herkes aynı kod üzerinde çalıştığından, ürünlerimiz bir tür doğal seçilim ile büyür. Belirli bir grup, neyin dahil edileceğine dair nihai kararı verir. Bu, isteğe bağlı özelliklere sahip olmadığımız, yalnızca ürünleri daha güçlü ve daha iyi yapan özelliklere sahip olduğumuz anlamına gelir.

## Nasıl iyi bir “Open Source Citizen” oluruz?

Açık kaynak bir topluluğu bir araya getirir ve bu topluluğun bir vatandaşı olarak bazı
sorumluluklarımız vardır. Bu topluluğun büyümesi verimliliğinin artması ve yaygınlaşması gibi. Sadece
kodu paylaşmak iyi bir vatandaş için yeterli olmamalı.

İş birliği yapmak, var olan uygulamaların gelişmesine katkıda bulunmak, başkalarının kodlarını gözden
geçirerek güvenliği arttıran hataları ise indirgeyecek bir yöntem olan pull requestleri değerlendirin.
Sadece bir kod satırı değil yazılan kodların yapısı, tasarımı gibi konularında gözden geçirilmesi ileride
uygulamanın ölçeklenebilir bir yapıya kavuşması için çok önemlidir.

Kendi kodlarımızın da başkaları tarafından gözden geçirilmesini sağlamalı ve tüm geribildirimlere açık
olmalıyız. Hata raporlarını paylaşmak, yapılan değişiklikleri dokümante etmek topluluğun
benimsemesini kolaylaştıracak önemli davranışlardır. Yapılan değişikliklerin testlerinin olmaması da
ileride başa bela olabilecek sorunlar doğurabilir. Bu yüzden code coverage oranının yüksek olması
oldukça önemli maddelerden biridir. Kötü kod stilleri hem hata ayıklamayı zorlaştırır hem de
uygulamanıza destek olacak diğer kişilerin benimsememesine neden olabilir.

Bir diğer konu yapılan her değişiklik gözden geçirme olarak iletildiğinde sadece açıklamasında yer alan
kadar iş barındırmalı. Birden fazla işin bir araya getirilerek birleştirmek doğru değildir. Her özellik ayrı
ayrı yer almalı istenildiği zaman dışarıda bırakılabilir özellikte sistemde yer almalıdır.

## Dünyada ve Türkiye’de açık kaynak

Dünyadaki bir çok inovasyon girişiminin temelinde açık kaynak bulunmaktadır. Günümüzde Microsoft
gibi yazılım devlerinin bile açık kaynak yazılım ve altyapılara yatırım yapıyor olması gelecekte ne denli
önem taşıdığına işaret ediyor aslında. Açık kaynağın yaygınlaşma hızı ve gelişme hızı artık genel
varsayılan geliştirme türlerinin ötesine geçmeye başladı. Bu yüzden girişimcilerin dışında artık büyük
şirketlerde bu ortak community’lere içerik üretmeye ve kendi uygulamalarını bu platformlarda
paylaşmaya başladılar.

Üst bölümde GPL lisansından bahsederken Andorid işletim sisteminde aslında bir açık kaynak kodlu
işletim sistemi olduğunu belirtmiştik. Bu aslında bu sistemlerden oluşan sistemlerin en kadar çok
yaygınlaştığına dair çok büyük bir örnek.

Google’ın, Facebook’un, Amazon’un yanı sıra Microsoft’unda ileriye dönük açık kaynak vizyonları
ileride bu altyapıların neredeyse tüm sistemlerin altyapısını oluşturacağını söylememiz çok yanlış
olmayacaktır.

Türkiye’de bu konuyla ilgili çok önemli bir adım atıldı. Sanayi ve Teknoloji bakanı Mustafa Varank
Türkiye Açık Kaynak Platformunun kurulacağını açıkladı. Bu artık sadece özel şirketlerin değil
devletlerinde bu konuya verdiği önemin çok önemli bir kanıtı aslında. Yazılım geliştirme
maliyetlerinin, dış bağımlılıkların azalması bu konudaki en büyük beklentilerin başında geliyor. Bu
büyük ekosistemin bugün inşa edilmeye başlaması gelecekte yeni teknolojilerin altyapısını
oluşturacak büyük bir adım olacak. Türkiye’de genellikle kapalı yazılımların, kurumlara özel yazılımlar
üretilmesi yurt dışına ihraç konusunda engel oluşturuyordu. Artık bu platformlardan üretilen
yazılımlar bir ürün vizyonu ile geliştirilecek olup global bir topluluk tarafından da desteklenirse önemli
noktalara gelebilecek uygulamalar ortaya çıkabilir.

Dünyada ve ülkemizde artık bir çok bulut sitemi altyapısı ve sistemler açık kaynak kodlu yazılımları
temel alıyor. Bugünden bu sistemlere uyumlu altyapılara geçmez ve geliştirmelerimizi bu ortamlara
taşımazsak ileride çok daha sancılı geçiş süreçleri yaşanabilir. Kapalı sistemlerdeki içerik her geçen
gün büyürken bu açık sistemlerde çözümlerin buraya uygulanamıyor oluşu(Lisans) daha fazla efor ve
maliyet getirmektedir.

## Doğuş Teknoloji ve Open Source

Dünyada ve Türkiye’de açıkladığımız gelişmeler bu sistemlerin bir parçası olan Doğuş Teknoloji içinde
geçerli olacaktır.

Öncelikle geliştirilen uygulamaların yurt dışına dahi ihraç edilebileceği bir vizyona sahip ürün olması
şirketin yurt içindeki bağımlılıklarını azaltacaktır.

Open source commuity’lerde bulunan birçok hazır çözüm kendi uygulamalarımıza entegre edilebilir
olacaktır. Bu birçok modülün geliştirme eforunu düşürecek hem zaman hem de maliyetinin
azalmasını sağlayacaktır. Maliyet şirketler için oldukça önemli bir konu zira müşteriye sunulan
hizmetlerin fiyatını belirleyen önemli bir kalem. Bu konuda maliyetlerin azalması müşteriler
tarafından daha çok tercih edilen bir şirket olma konusunda önemli bir nokta oluşturur. Birçok hazır
sunulan modül, uygulama hazır olarak kullanılabilir durumda olacaktır. Uygulamaların ölçeğine göre
yeterli performans ihtiyacını karşılayabilecek veri tabanı uygulamaları buna bir örnek olabilir. MS SQL
gibi yüksek maliyetli uygulamalar yerine PL/SQL gibi uygulamaları geçilmeye başlandı bile.

Büyük comminiteyler yer alan çözümlerin kullanılması aynı zamanda büyük bir desteğinde arkanızda
yer alması anlamına gelir.

Topluluk tarafından geliştirilen bir çok uygulama güvenlik zafiyetlerinden de kurtulur.
Community’deki birçok kişi tarafından gözden geçirilen uygulamalar hem güvenlik açıklarının
azalmasına hem de daha hızlı gelişmesine katkıda bulunacaktır.

Yine bir diğer fayda sağlayabilecek durum topluluk tarafından iletilen hata bildirimleri olacaktır.
Uygulamanın daha hatasız ve güvenilir olmasını sağlayacak bir durum olacaktır. Open Source
Citizen’dan bahsederken bu topluluk içerisindeki insanların sorumluluklarından biri de test
coverage’larının olmasıydı. Bu sayede uygulama üzerindeki değişikliklerin birbirini etkisinin minimum
olacağı stabil bir uygulama ortaya konulabilecektir.

Uygulama geliştirirken 4 - 5 kişi ile geliştirilen uygulama mı yoksa büyük bir topluluk tarafından
geliştirilen bir uygulama mı daha iyidir? Yüzlerde kişinin katkı sağladığı ve sürekli güncellenen yeni

özellikler kazanan bir uygulama yapısı için tabi ki de büyük comminity’lerde yer alan uygulamalar
geliştirmek bunların open source paylaşmak çok daha kaliteli uygulamalar yapmaya olanak
sağlayacaktır.

Yine sadece kendi geliştirdiği uygulamalarda değil toplulukta paylaşılmış gereksinimlere uygun
yazılımı geliştirilen uygulamalara özelleştirerek implemente etmeye olanak sağlayacaktır.

Özgürlük... Tüm platformlarda çalışabilen lisans maliyetlerini en aza indirebilecek bu sayede yaşam
döngüsü daha uzun olacak hem de müşterilerine daha uygun fiyatlarla hizmet verebilecek çözümler
üretebilme imkânı olacaktır.

Open source yazılımlarla tasarlanan sistemler daha düşük sistem gereksinimlerinde bile çalışma
imkânı sunabilir. Bu da uygulamaların hayata geçtikleri zaman daha esnek tüm platformlarda çalışma
imkânı sağlaması anlamına gelir.

Günümüzde artık birçok geliştirici profili açık kaynak yazılımlara yönelmektedir. Bu alanlarda yapılan
çalışmalar ile şirketin adının geçmesi hem şirketin çalışan profilini geliştirecek, marka değerini
arttıracaktır. Bulunmak isteyeceğiniz şirketin bu imkanları sağlıyor olması hem bireyin gelişim planları
hem de şirketin gelişim planları ile kesiştiğinden çok daha verimli çalışmaların ortaya çıkmasını
sağlayacaktır.

Teknoloji artık açık kaynak kod tarafında gelişiyor. Gelecekteki birçok sistemin altyapısının olacağı bir
dünyada Doğuş Teknoloji’de bu dönüşümlere bugünden başlayarak uyum sağlayacaktır. Belki tüm
sistemleri dışarıya açmak mümkün olmayacaktır ancak hibrit çalışabilecek platformlarda oluşmasını
sağlayacak yapılar geliştirerek birçok uygulamanın bu yeni dünyaya hazır olmasını sağlayacak bir
geliştirme ortamı sağlamak mümkün olabilir.

# Referanslar

[https://medium.com/gitcoin/a-brief-history-of-open-source-3928cb](https://medium.com/gitcoin/a-brief-history-of-open-source-3928cb)
[https://www.digitalocean.com/community/tutorials/Free-vs-Open-Source-Software](https://www.digitalocean.com/community/tutorials/Free-vs-Open-Source-Software)
[https://www.gnu.org/gnu/gnu.html](https://www.gnu.org/gnu/gnu.html)
[https://pdfs.semanticscholar.org/48b7/64286fde00991c9b8ffc2b88ee8a6c7207b3.pdf](https://pdfs.semanticscholar.org/48b7/64286fde00991c9b8ffc2b88ee8a6c7207b3.pdf)
[https://medium.com/launch-school/understanding-git-and-github-8ac987877a](https://medium.com/launch-school/understanding-git-and-github-8ac987877a)
[https://blogs.vmware.com/opensource/2017/10/12/good-open-source-citizen/](https://blogs.vmware.com/opensource/2017/10/12/good-open-source-citizen/)
[https://webrazzi.com/2016/09/02/dunyada-ve-turkiyede-acik-kaynak-kodlu-yazilim-kullanimi-ne-durumda/](https://webrazzi.com/2016/09/02/dunyada-ve-turkiyede-acik-kaynak-kodlu-yazilim-kullanimi-ne-durumda/)
