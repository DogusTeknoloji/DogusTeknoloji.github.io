---
layout: post
title:  "Open Source Proje Geliştirme - Dilara Kadakaloğlu"
categories: ["Açık Kaynak"]
tags: ["Açık Kaynak", dilarakadakaloglu]
redirect_from: "/assets/Open_Source_Proje_Gelistirme_Dilara_Kadakaloglu.pdf"
permalink: acik_kaynak_dilara_kadakaloglu
---

[Pdf versiyon](/assets/acik-kaynak/dilara-kadakaloglu/Open_Source_Proje_Gelistirme-Dilara_Kadakaloglu.pdf)

<img src="/assets/acik-kaynak/dilara-kadakaloglu/0.png" alt="OpenSource" width="200"/>

# Open Source Proje Geliştirme

Günümüzde giderek yayılan “Open Source (Açık Kaynak)” ve “Free Software (Özgür Yazılım)”
terimlerini oldukça sık duymaya başladık. Özellikle de Linux ve Android için bu terimler sıkça
kullanılıyor. Bu yazı da açık kaynak kodun ne olduğu, bugüne kadarki süreci, gücü ve avantajlarını,
biraz daha detayında da lisanslama seçeneklerinin ve hizmet verdiği servislerin neler olduğu konuları
ile ilgilidir.

Öncelikle open source yani açık kaynak kodlu yazılımın ne olduğu ile başlayalım.

# Açık Kaynak Kodlu Yazılım Nedir?

Açık kaynağın ne olduğunu, açık kaynak olmayan bir işletim sisteminden örneklemek ile başlayabiliriz.
İşletim sistemi Windows olan bir bilgisayara .exe uzantılı bir dosya ile programları kurabiliyoruz. Bu
.exe uzantılı dosyalar sadece programı kurar ve son kullanıcı programa müdahale edemez, kodları
göremez.

Open Source Software (OSS) yani açık kaynak koldu yazılım, source (kaynak) kodları herkese açık olan
yazılımdır. Bu, o yazılım üzerinde istediğimiz değişikliği yapabileceğimiz, kendi sürümümüzü
oluşturabileceğimiz anlamına gelir. Binlerce satır koddan oluşan programlar, bilgisayara
kurulduğunda derlenme işleminden geçtiği için bilgisayar artık o kodlara ihtiyaç duymaz ve son
kullanıcıya kaynak kodlar kapatılır. Dolayısı ile programın sadece son hali olan ara yüzünü görebiliriz.
Açık kaynak kodlu yazılımlar ise son kullanıcının kaynak kodları görebileceği şekilde yayınlanır.


Örneğin Android cihazla dikkat edersek, arayüz olarak HTC, Samsung, LG cihazların birbirinden farklı
olduğunu görürüz. Oysaki hepsi de Android işletim sistemini kullanmaktadır. Bu durum açık kaynak
kod ile gerçekleşmektedir. Şirketler kendilerine ait arayüzleri, kaynak kodu değiştirerek
yayınlamışlardır.

Açık kaynak sadece kaynak koduna erişim anlamına gelmez. Açık kaynaklı yazılımın dağıtım şartları
bazı belirlenmiş kriterlere de uygun olmalıdır.

## Açık Kaynak Dağıtım Koşulları

#### 1 - Dağıtım ücretsiz olmalı

Bir açık kaynak yazılım lisansı ile yazılımın satışı veya başka yazılımların bir parçası olarak dağıtılması
kısıtlanamaz ve bu satışlardan bir pay talep edilemez.

#### 2 - Kaynak kod

Programın derlenmiş haliyle birlikte kaynak kodunun da dağıtılmasına izin vermesi gerekir. Eğer
program ile birlikte kaynak kodlar verilmiyorsa, kullanıcıların internet ortamından ücretsiz bir şekilde
indirilmesine izin vermelidir. Kaynak kodun diğer yazılımcılar tarafından değiştirebileceği bir biçimde
olması gerekir. Kasten karmaşıklaştırılmış veya bir çeviriciden geçirilmiş kodlar kabul edilmez.

#### 3 - Türetilen işler

Bir açık kaynak lisansı değişikliklere ve türetilen işlere izin vermeli ve onların özgün yazılımın lisansı ile
aynı şartlarda dağıtılmasına izin vermelidir.

#### 4 - Yazarın kaynak kodunun bütünlüğü

Lisans, yazılımın kaynak kodunun değiştirilmiş halinin dağıtılmasını ancak tek bir durumda
kısıtlayabilir. Bunun mümkün olabilmesi için yazılım kaynak koduyla birlikte derleme zamanında
kullanılabilecek yama dosyalarının dağıtımına izin verilmelidir. Böyle bir şey yapıldığında lisansta
açıkça yazılımın değişiklik yapılmış kaynak koddan derlenebileceği belirtilmelidir. Yazılım kaynak
kodda değişiklik yapılıp derlendiğinde isminin veya sürüm numarasının değiştirilmesini gerekli
kılabilir.

Kullanıcılar kullandıkları yazılımdan kimin sorumlu olduğunu bilme hakkına sahiptir.

#### 5 - Kişi veya gruplara yönelik ayrımcılık yapılmamalı

Yazılım lisansıyla herhangi bir kişiye veya gruba yönelik bir kısıtlama getirilemez.

Süreçten maksimum fayda sağlayabilmek için, kişi ve grupların eşit derecede faydalanabiliyor olmaları
gerekir. Bu nedenle herhangi bir açık kaynak lisansının herhangi birisini süreçten çıkarması
yasaklamıştır.

Bazı ülkeler belirli yazılım türleri için ihracat kısıtlamalarına sahiptir. Ama lisansta bu yasalara uyma
gerekliliğini hatırlatılabilir ancak kendisi bu kısıtlamalara dahil olamaz.

#### 6 - Çalışma alanına yönelik ayrımcılık yapılmamalı

Yazılımın herhangi bir amaç için çalıştırılması engellenemez. Örneğin bir yazılımın ticari kullanım veya
genetik araştırmalar için kullanılması kısıtlanamaz.

#### 7 - Yeniden dağıtılan ürünlerde ek lisanslar olmamalı

Programa eklenen haklar ayrıca bir sözleşmeye gerek kalmadan programın yeniden dağıtıldığı herkes
için geçerli olmalıdır.


#### 8 - Lisans bir ürüne özgü olmamalı

Orijinal yazılımdan üretilen yeni program, yeniden dağıtıldığı tüm taraflarda aynı haklara sahip
olmalıdır.

#### 9 - Lisans diğer yazılımları kısıtlamamalı

Lisans, beraberinde dağıtılan diğer yazılımlara kısıtlama getirmemelidir. Örneğin, bir lisans
beraberindeki diğer yazılımların da illa açık kaynaklı olmasını zorlamamalıdır.

Açık kaynaklı yazılım dağıtıcıları kendi yazılımları hakkında kendi seçimlerini yapma hakkına sahiptir.

#### 10 - Lisans teknoloji bağımsız olmalı

Lisansın hiçbir hükmü bir teknolojiye veya arayüze bağımlı olmamalıdır. Kullanıcının bir arayüzde
koşulları kabul etmesi ve bir düğmeye tıklaması gibi zorunluluklar karşısında alternatifsiz bırakmasına
izin verilmemelidir.

# Açık Kaynak Kodlu Yazılım Gücü ve Tercih

# Nedenleri

#### Kontrolcü ve Özgürlükçü

Birçok kişi açık kaynak yazılımları tercih ediyor çünkü bu tür yazılımlar üzerinde daha fazla kontrole
sahipler. Programın yapmasını istemediği şeyler için ve/ya yapmadığından emin olmak için
inceleyebilir ve sevmedikleri kısımlarını değiştirebilirler. Yani kullanıcılar sadece açık kaynaklı
yazılımlara erişim sağlamakla kalmaz, aynı zamanda kontrol edebilir ve değiştirebilir.

Yazılımcı olmayan kullanıcılar da açık kaynaklı yazılımlardan fayda sağlarlar. Çünkü açık kaynak kodlu
yazılım, istedikleri yazılımı istedikleri özellikte kullanabilmeyi sağlar. Böylece son kullanıcı başkaları
tarafından dayatılan sınırlı özellikteki programları kullanmak zorunda kalmaz.

#### Kişisel Gelişim ve Eğitim

Açık kaynak yazılım, geliştiriciler için bir nevi kendilerini geliştirmek için iyi bir ortam sağlar.
Yazılımcıların daha iyi olmalarına yardımcı olur. Açık kaynak kodunun herkese açık bir şekilde
erişilebilir olmasının eğitime de katkısı oldukça fazladır. Öğrenciler çalışmalarını başkalarıyla global
olarak paylaşabilir, geliştirici ve kullanıcılardan feedback’ler alabilir, böylece becerilerini daha hızlı
geliştirebilirler. Hatta karşılaşılan hataları, diğer kişilerle birlikte çözüp birbirleri ile paylaşabilirler.

#### Güvenlik

Çoğu kullanıcı açık kaynak kodlu yazılımları kullanmayı tercih eder. Bunun en büyük sebebi kodlar
herkes tarafından görülebildiği için neler içerdiğinin de herkes tarafından kontrol edilebilmesidir.
Kullanıcı kod içerisinde istemediği bir fonksiyon olup olmadığını kontrol edebilir.

Ek olarak diğer yazılımcılar orijinal yazılım üzerinde istedikleri geliştirmeyi yapabilir ve/ya yakaladıkları
hataları düzeltip güncelleyebilirler. Bu da programın çok daha hızlı bir şekilde gelişmesine yardımcı
olur.

#### Kalite

Açık kaynak kodlu yazılımlarda hem güvenliği hem de kaliteyi arttırmak için çalışan birçok geliştirici ve
kullanıcı var. Kullanıcılar ilgili programları kullandıklarında edindiği tecrübelere göre feedback verir.


Geliştiriciler de kullanıcılardan gelen bu feedback’lere, kendi uygun gördükleri ek geliştirmelere ve/ya
yakaladıkları hatalara göre programı geliştirir. Tüm bunların sayesinde de hem güvenli hem de kaliteli
ürünler ortaya çıkar.

#### Sürekli Destek ve İstikrar

Genellikle şirketler, uzun vadeli kullanacağı projeler için, özel programlar yerine, açık kaynak kodlu
yazılımları tercih ediyor. Bunun en büyük sebebi, özel programların ileride bir gün sistem desteği
kapatma riskinden kaynaklanıyor. Açık kaynak kodlu yazılımlarda, geliştiriciler kaynak kodu herkese
açık olarak dağıttıkları için, bu yazılımlarda orijinal program geliştiricileri güncellemeleri bir gün
durdursa bile, program diğer geliştiricilerle güncellenmeye devam edebilir. Böylece şirketlerin o
programı kullanması riske girmeyecek ve istikrar sağlanmış olacaktır.

# İyi Bir “Open Source Citizen” Olmak

Open Source Citizen olmak için açık kaynak kodlu bir program kullanmak yeterlidir. Bunun bir tık
fazlası ise programı kullanmanın yanında, o programın gelişmesine de katkıda bulunmaktır. Open
source dünyası da kullanıcılara bu imkânı birçok farklı yoldan sağlayabiliyor. Hatta tek bir kod satırını
değiştirmeden bile projeleri daha ileri taşımak mümkün.

Peki iyi bir “Open Source Citizen” olmak için neler yapılabilir?

#### Katılım

Geri bildirim vermek, açık kaynak kodlu projelerin gelişmesi için en temel ögelerden biridir. Bu
yüzden kullanıcılar ilk adım olarak en beğendikleri, favori gördükleri açık kaynak projelerin, mail
listesine, hata izleyicilerine ve/ya diğer topluluklarına katılabilir. Böylece aldıkları hataları, tecrübe
ettikleri deneyimleri, proje hakkındaki yorumlarını paylaşılmış olur. Bu da her yönden hem projeye
hem geliştiriciye hem de open source dünyasının gelişimine katkıda bulunur.

#### Saygı

Öncelikle şu unutulmamalıdır; açık kaynak kodlu bir program, geliştirici ve kullanıcılara yardım etmeyi
amaçlayan, ücretsiz olarak dağıtılan ve basit bile olsa bir emek sonrası ortaya çıkan bir programdır.
Dolayısı ile beğenilse de beğenilmese de ürüne ve geliştirene saygı göstermek gerekir.

Bu saygı çerçevesinde, yorumları yapıcı tutmak, sert eleştirilerden uzak durmak gerekir. Sonuçta open
source dünyası, programların ve geliştiricilerin daha iyi olmasını sağlamak amaçlıdır. Sert ve kırıcı
yorumlar ürünü de geliştiriciyi de daha iyi olmasını sağlamaz. Hatta tam tersi motivasyonu düşürür.
Bu da gerilemeye ve hatta geliştiricinin projeyi bırakmasına bile sebep olabilir.

#### Topluluk Destekçisi Olun

Açık kaynak koldu bir yazılımın uzun zamandır kullanıcısı olanlar, ürünün input ve outputlarına hakim
olanlar, projenin hata izleyicilerinde temel sorunları yanıtlamak için gönüllü olabilirler. Bu o projenin
geliştiricileri için çok önemli bir destektir.

Açık kaynak kodlu bir projeyi sürdürmekteki en zorlanılan konulardan biri de iletişim hacmini
korumaktır. Eğer diğer kullanıcılar bu yükü biraz da olsa alıp onları hafifletirse, proje sahipleri
geliştirmeye çok daha fazla zaman bulabileceklerdir. Dolayısı ile de daha hızlı bir gelişim el birliği ile
sağlanmış olacaktır.


#### Dokümantasyon

Açık kaynak kodlu yazılım projelerin, kullanıcıların kolayca erişebileceği, proje hakkında bilgi (teknik
dahil) veren bir dokümantasyonu mutlaka olması gerekir. Proje sahipleri browser üzerinden
erişilebilen ve yine browser üzerinden güncelleme yapmaya imkân sağlayan “wiki” tarzı
dokümantasyonları tercih edebilirler.

Özellikle proje içinde karmaşık yapıda bir fonksiyon varsa mutlaka bu dokümanlarda belirtilmeli ve
nasıl kullanılması gerektiği açıklanmalıdır.

Hata izleyicilerin de burada şu şekilde bir katkısı olabilir. Diğer kullanıcılardan gelen soruları
cevaplarken, onları ilgili wiki sayfasına yönlendirmektense, direk cevabı açıklayıcı bir şekilde
paylaşmaları kullanıcıları kısa yoldan doğru yola götürmeye yardımcı olacaktır.

#### Blog

Eğer ki açık kaynak kodlu projenin bir wiki olmasa bile, geliştiriciler proje ve fonksiyonları hakkında
blog yazabilir, bu yazılar çeşitli senaryolar içerebilir. Blog yazıları genellikle projeye hakim olmayan,
yeni başlayan kullanıcılar için kılavuz olabilecek en iyi kaynaklardır.

# Open Source Tarihçesi

#### Unix Nedir?

Unix, 1969 yılında ABD’de bulunan AT&T Bell Laboratuvarı’nda çalışan Ken Thompson, Dennis Ritchie,
Brian Kernighan, Douglas McIIroy, Michael Lesk ve Joe Ossanna tarafından geliştirilen bir işletim
sistemidir.

#### Unix Tarihçesi

Unix’in geliştirilesi 1960’ların ortalarında, MIT, Bell Laboratuvarı ve General Electric’in ortak olarak
yürüttükleri **MULTICS** (Multiplexed Operating and Computing System) projesi ile başlamıştır. 60’ların
sonlarına doğru Bell Laboratuvarı projeden bu projeden çekilmiş, Ken Thompson’ın bir dosya yönetim
sistemi kodlamasıyla Unix’in ilk sürümü olan **UNICS** (Uniplexed Operating and Computing) i ortaya
çıkmıştır.

1970’lerin başlarında Dennis Ritchie tarafından C dilinde tekrardan yazılan bu küçük işletim sistemi ile
Unix’i diğer muadillerden ayırmış oldu. O yıllarda işletim sistemlerinin taşınabilme özelliği yoktu.
Sadece yazdıkları donanım türündeki cihazlarda çalışabiliyordu. Unix’i C programlama dilinde yeniden
yazarak, artık pek çok donanım üzerinde çalışabilir hale geldi. Unix’in taşınabilir olması sayesinde
adını hızlıca duyurabildi ve birçok farklı sektördeki kurumların dikkati çekti.

1980’lerin başlarında ise AT&T şirketi Unix’i özel lisanslar altına aldı ve Unix üzerinden para kazanma
modeline geçti. Buna karşı çıkan birçok geliştirici, Richard Stallman öncülüğünde GNU projesine
başladı. Bu projenin amacı Unix’e benzeyen, tamamen ücretsiz ve özgürce dağıtılabilen bir işletim
sistemi yaratmaktı. Böylece **“** Özgür Yazılım Felsefesi **”** ortaya çıkmış oldu.

#### Özgür Yazılım (Free Software)

Stallman, 1984'te başlayarak GNU Projesi'ni başlattı. GNU Projesi herkesçe özgürce geliştirilebilen bir
işletim sistemi oluşturmayı hedeflemişti. Bu hedefte en önemli adımın özgür bir yazılım topluluğu


kurmak olduğuna inanıyordu. Özgür bir yazılım için, ücretsiz bir işletim sistemi olması gerekiyordu ve
çalışmalarını bu hedefe yönlendirmişti.

GNU Projesi, 1990'ların başında Linux ile bir araya geldi. Stallman, yaklaşık on yıl önce öngördüğü
serbest işletim sistemini, nihayetinde iki projenin kombinasyonundan oluşturabildi. Linux (özgür
yazılım topluluğunun dediği gibi “GNU / Linux”) şimdi tüm genel amaçlı işletim sistemlerinin en büyük
kurulu tabanına sahiptir.

#### Linux

Richard Stallman, GNU projesiyle Unix sistemine özgür ve açık kaynak alternatifini yaratmak istiyordu.
Bu proje altında birçok kamu hizmeti veriyor ve programlama üzerinde çok çalışmıştır fakat istediği
işletim sistemini tek başına yaratamamıştır. GNU Projesi’ni Linux ile bir araya getirerek çalışmalarına
devam etmiştir.

Linux, 1991 yılında Helsinki Üniversitesi'nde öğrenci olan Linus Torvalds tarafından kurulmuştur.
Torvalds, Linux'u ağırlıklı olarak akademik ortamlarda kullanılan bir başka Unix klonu olan Minix'e
özgür ve açık kaynak alternatifi olarak kurmuştur. Başlangıçta “Freax” adını vermeyi amaçlamış, ancak
kendi adı (Linus) ve “Unix” kelimesinin bir araya gelmesiyle oluşan “Linux”u tercih etmiştir. GNU
Projesi çalışmalarından bazı araçları kullanarak (GNU Compiler Collection - GCC) Richard Stallman ile
iş birliği sağlamışlardır, güzel bir uyum yakalamışlardır.

Linux dağılımları, GNU Projesi, MIT’nin X-Windows GUI bileşenleri ve bir diğer açık kaynaklı proje olan
BSD lisansı ile hayata geçmiştir.

Linux çekirdeğinin üstüne yazılmış onlarca işletim sistemi bulunmaktadır. En meşhur olanları Ubuntu,
Linux Mint, Debian, Fedora, Red Hat ve bizim işletim sistemimiz olan Pardus’tur.

#### Açık Kaynak (Open Source)

1997 yılında, özgür bir yazılım savunucusu olan Eric Raymond, GNU ve Linux Projesi birleşmeden
önceki geliştirme stillerini karşılaştırarak “The Cathedral and The Bazaar” kitabını yazdı.

Bu iki modeli kısaca şöyle açıklamıştır:

- The Cathedral (GNU Kültürü): Kaynak kodu küçük bir geliştirici grup tarafından geliştirilen ve
    serbestçe dağıtılan.
- The Bazaar (Linux çekirdeği): Kaynak kodu internet üzerinden, kamuya açık olarak geliştirilen.

Raymond’un bu yazısından kısa bir süre sonra, 1998’de **Netscape** bir karar aldı ve Raymond’un “The
Bazaar” yaklaşımından yola çıkarak Netscape Communicator’ın kaynak kodunu açtı.

5 yıl sonra, bir başka açık kaynak kod kullanımı benimseyen **Mozilla Firefox** çıktı. Firefox, 2000’lerin
en popüler tarayıcılarından (browser) olmuştur.


# Açık Kaynak Lisanslama Seçenekleri

İki tür açık kaynak kodlu yazılım lisansı vardır. Bunlar; CopyLeft ve Non-CopyLeft olmak üzere 2ye
ayrılır.

#### CopyLeft

“CopyLeft” terimi daha çok bilinen “CopyRight” yani “Telif Hakkı” teriminden türetilmiştir. Copyleft
yazılım lisansları, dağıtılmış kopyayı, orijinali ile aynı lisans koşulları altında sunabilmeyi sağlar.

Aşağıda ise Copyleft lisansların ortak izin, koşul ve sınırlamaları gösterilmiştir.

### İzinler Koşullar Sınırlamalar

| İzinler | Koşullar | Sınırlamalar |
| -------------|-------------| -----|
| Ticari Kullanım | Açık Kaynak | Sorumluluk |
| Dağıtım | Lisans ve Telif Hakkı Bildirimi | Garanti |
| Değişiklik | Aynı Lisans | |
| Patent Kullanımı | Durum Değişiklikleri | |
| Özel Kullanım | | |

CopyLeft lisans örnekleri;

- GNU GPL v2 and v
- GNU LGPL
- Mozilla Public License
- Eclipse Public License 1.

CopyLeft lisans kullanan yazılım örnekleri;

- Linux Kernel
- Bash
- GIMP
- Ansible
- Quake (id software)

#### Non–CopyLeft

Non-CopyLeft yazılım lisansları, orijinal yazılımın sahiplerinin, dağıtılan kopyalardan hiçbir şekilde
sorumlu tutulmamasına izin verir. Hatta yeniden dağıtılan kopyanın, orijinal yazılımı takip etmesi
zorunlu tutulmaz, isteğe bağlı bırakılmıştır. Bazı non-copyleft lisanslar (Apache 2.0) patent
kullanımına izin verirken bazıları (MIT) izin vermez.

Aşağıda ise Non-Copyleft lisansların ortak izin, koşul ve sınırlamaları gösterilmiştir.

| İzinler | Koşullar | Sınırlamalar |
| -------------|-------------| -----|
| Ticari Kullanım | Açık Kaynak | Sorumluluk |
| Dağıtım | Lisans ve Telif Hakkı Bildirimi | Garanti |
| Değişiklik | | |
| Patent Kullanımı | | |
| Özel Kullanım | | |

Non-CopyLeft lisans örnekleri;

- Apache Software License 2.
- BSD Licenses
- MIT License
- Internet Software Consortium (ISC)
- X11 LIcense
- Free Public License
- The Don’t Ask Me About It License
- Eclipse Public License 2.

Non-CopyLeft lisans kullanan yazılım örnekleri;

- Powershell
- Tensorflow
- ASP.NET
- .NET Framework
- Android (mostly, see: https://source.android.com/setup/start/licenses)
- SimCity
- Atlassian (Bitbucket, JIRA, etc)

## En Çok Kullanılan Lisanslar

#### MIT Lisansı

Sadece telif hakkı ve lisans bildirimlerinin korunmasını gerektiren şartlarla, kısa ve basit bir izin
belgesidir. Lisanslı çalışmalar, değişiklikler ve daha büyük işler farklı şartlar altında ve kaynak kodu
olmadan dağıtılabilir.

![MIT Lisans](/assets/acik-kaynak/dilara-kadakaloglu/1.png)
![MIT Lisans](/assets/acik-kaynak/dilara-kadakaloglu/2.png)

#### GNU General Public License v3.0 (GNU GPLv3)

Türkçe karşılığı “Genel Kamu Lisansı” olan bu lisans, ilk defa açık kaynak kodlu üreticilerin kodlarının kapalı kaynağa dönüştürülmesiyle ortaya çıkmış bir lisans türüdür.

GPL lisansı kullanım şartlarının değiştirilmeden istediğiniz şekilde kullanmanıza izin verir. Lisans şartlarının değiştirilmediği sürece istenilen her şey yapılabilir.

![GNU Lisans](/assets/acik-kaynak/dilara-kadakaloglu/3.png)

#### Apache 2

Apache Lisansı (2.0 sürümünden önce Apache Yazılım Lisansı olarak adlandırılmaktaydı), Apache
Yazılım Vakfı (ASF) tarafından yayımlanan bir özgür yazılım lisansıdır. Tüm sürümleri telif
hakkı koruma ve feragat uyarısı gerektirmektedir. Lisans, özgür ve açık kaynak kodlu
yazılımın geliştirilmesi için kaynak kodlarının kullanımına da izin vermektedir.

ASF tarafından üretilen ya da onun herhangi bir tasarısının ürünü olan tüm yazılımlar, Apache Lisansı
koşullarına göre lisanslanmaktadır. ASF tarafından üretilmeyen yazılımlar da zaman zaman bu lisansı
kullanabilmektedir

![Apache 2 Lisans](/assets/acik-kaynak/dilara-kadakaloglu/4.png)

# Türkiye’de ve Dünyada Open Source

Açık kaynak kodlu yazılımlara ilginin tüm dünyada hızla arttığını görebiliyoruz. Geliştiriciler kadar olmasa da hem dünya ülkelerinin hem de kendi ülkemiz için yavaş yavaş bu alanda çalışmalar yaptığını görebiliyoruz. Geçtiğimiz son 10 yıl içinde, açık kaynak kodlu yazılımları kullanılmasını zorunlu kılan ya da en azından teşvik eden çalışmalar, hükümetlerce yasalaşmaya başladı ve gittikçe de yaygınlaşmaktadır.

Tüm dünya ülkelerinin açık kaynak kodlu yazılım geliştirme ve kullanmada ne durumda olduğunu gösteren bir araştırma yapıldı. Network World tarafından yapılan bu araştırma sayesinde harita üzerinde ülkelerin birbirleriyle olan farkı daha somut ve açık bir şekilde gösterilmiştir.

Bu çalışma, ülkelerin açık kaynak kodlu yazılımlar için aldığı yasal kararlar dikkate alınarak yapılmış ve ülkeleri belirli kategorilerde gruplayarak sınıflandırmıştır.

![Dünyada Open Source](/assets/acik-kaynak/dilara-kadakaloglu/5.png)

Bu çalışmaya göre; Amerika, Çin, Hindistan ve çoğu Avrupa ülkesinin, açık kaynak kodlu yazılımları teşvik eden ama yasal yaptırımı olmayan ülkeler kategorisinde olduğunu görüyoruz. Türkiye ise Rusya ve Brezilya ile aynı kategoride olup, yasal yaptırımın değerlendirme aşamasında olan ülkeler arasındadır.

## Dünyadaki Popüler Open Source Yazılımlar

#### WordPress

![WordPress](/assets/acik-kaynak/dilara-kadakaloglu/6.png)

WordPress, 2003 yılında Mike Little ve Matt Mullenweg tarafından kurulmuştur. Web'deki tüm
sitelerin % 32'sinden fazlası için tercih edilen bu platform, PHP ve MySQL üzerinde yerleşik ve GPLv
altında lisanslıdır.

WordPress ile oluşturulan web sayfaları, kullanıcıların istediği şekilde dönüştürmesini sağlayan bir çok
eklenti ile desteklenir. Her ne kadar da blog platformu olsa da, içerisinde çevrimiçi dergi temaları,
online mağazacılık için e-ticaret, fotoğrafçı ve tasarımcılar için portfolio sergileyebilecekleri galeri
temalarına da sahiptir.

#### Mozilla Firefox

![Mozilla Firefox](/assets/acik-kaynak/dilara-kadakaloglu/7.png)

Mozilla Firefox (veya sadece Firefox), Mozilla Foundation ve onun yan kuruluşu olan Mozilla
Corporation tarafından geliştirilen ücretsiz ve açık kaynaklı bir web tarayıcısıdır. Firefox, Windows,
MacOS, Linux ve Solaris işletim sistemleri için kullanılabilir.

Firefox şu anda web tarayıcılarının kayıtlı kullanım payının% 24.43'ünü karşılıyor ve günden güne de
yükseliş gösteriyor. Çoğu web profesyoneli için tercih edilen bir tarayıcı olan Firefox’un popülaritesi,
kullanıcılara sunduğu kapsamlı third-party eklentiler sayesinde artmaktadır.

#### Apache OpenOffice

![Apache OpenOffice](/assets/acik-kaynak/dilara-kadakaloglu/8.png)

Apache OpenOffice, Microsoft Office’in ücretsiz bir alternatifi olarak, Apache Yazılım Vakfı
önderliğinde özgür yazılım topluluklarınca geliştirilen, özgür ve ücretsiz bir ofis yazılımlarıdır. Kelime
işlemci, hesap tablosu, sunum, çizim, formül ve veritabanı bileşenlerini içerir.

Özgür “Apache Lisansı” ile lisanslanmış olup herkes tarafından (ticari, devlet kurumları, belediyeler ve
eğitim kurumları vb.) kullanılabilir, istenildiği kadar sayıda bilgisayara tamamen ücretsiz olarak
kurulabilir. Microsoft Windows, Linux ve Mac OS X işletim sistemlerini destekler.

#### MySQL

![MySQL](/assets/acik-kaynak/dilara-kadakaloglu/9.png)

MySQL, 6 milyondan fazla sistemde yüklü bulunan multi-threaded, multi-user, hızlı bir veri tabanı
yönetim sistemidir. UNIX, OS/2 ve Windows platformları için ücretsiz dağıtılmakla birlikte
ticari lisans kullanmak isteyenler için de ücretli bir lisans seçeneği de mevcuttur. Linux altında daha
hızlı bir performans sergilemektedir. Kaynak kodu açık olan MySQL'in pek çok platform için
çalıştırılabilir ikilik kod halindeki indirilebilir sürümleri de mevcuttur.

MySQL geliştirme projesi, kaynak kodunu, çeşitli özel anlaşmaların yanı sıra GNU Genel Kamu Lisansı
şartlarına uygun hale getirmiştir.

#### NotePad++

![NotePad++](/assets/acik-kaynak/dilara-kadakaloglu/10.png)

Notepad++, Windows işletim sistemi içerisine gömülü olarak gelen Notepad yazılımına alternatif
olarak kullanılmak üzere C++ ile geliştirilmiş GPL ile dağıtılan açık kaynak kodlu bir kaynak kod
düzenleyicisidir. Scintilla düzenleyicisi temel alınarak geliştirilen Notepad++, birçok yazılım diline ait
kodu görüntüleyip uygun olarak highlight edebilir.

#### Android

![Android](/assets/acik-kaynak/dilara-kadakaloglu/11.png)

Android, Linux çekirdeğinin ve diğer açık kaynak kodlu yazılımların değiştirilmiş bir versiyonuna
dayanan, öncelikle akıllı telefonlar-tabletler gibi dokunmatik ekranlı mobil cihazlar için tasarlanmış
olan ve Google tarafından geliştirilmiş bir mobil işletim sistemidir. Ayrıca Google, televizyonlar için
Android TV, arabalar için Android Auto ve her biri özel bir kullanıcı arayüzüne sahip bilek saatler için
OS'yi geliştirdi.

#### VS Code

![VS Code](/assets/acik-kaynak/dilara-kadakaloglu/12.png)

VS Code, Nisan 2015’te Microsoft’un piyasaya çıkarttığı ve Windows, Linux, macOS işletim
sistemlerinde kullanılabilen, Visual Studio’nun aksine bir IDE değil, programlama odaklı bir text
editördür. Stack Overflow’un 2018 Geliştirici Anketi'nde en popüler geliştirici ortamı seçilmiştir.

![VS Code](/assets/acik-kaynak/dilara-kadakaloglu/13.png)

## Türkiye’deki Open Source Çalışmaları

#### TÜBİTAK Çalışmaları ve Pardus Projesi

Pardus, TÜBİTAK tarafından geliştirilen bir Linux dağıtımı olan ulusal işletim sistemidir. İlk olarak Milli
Savunma Bakanlığı (MSB) tarafından, Türkiye çapında 600 birimde ve 5 binin üzerinde istemcide bu
işletim sistemi kullanılmaya başlanmıştır.

TÜBİTAK Ulakbim tarafından modern ve yerelleştirilmiş bir Linux dağıtımına dönüştürülen Pardus
projesi, Türkiye'de organize bir yapıya ve tam zamanlı katkıcılar ve kamu desteğine sahip olan en
başlıca özgür yazılım projesidir.

TÜBİTAK’ın beraberinde yürüttüğü farklı açık kaynak kodlu projeler de mevcut. Bunları sıralayacak
olursak;

- **Ahtapot – Bütünleşik Siber Güvenlik Sistemi:** Derinlemesine savunma için ihtiyaç duyulan
    siber güvenlik bileşenlerinin entegre edildiği bir sistemdir. İşletim Sistemi Pardus'tur; bu
    sayede siber güvenlik bileşenlerinde de açık kaynak kodlu milli işletim sistemi dağıtımı
    kullanılmaktadır.
    
- **EnGerek – Kimlik yönetim Sistemi** : Web tabanlı geliştirilmiş bir kimlik yönetim sistemidir.
    Java programlama dili ile geliştirilmiştir. Temel hedefi kurum kullanıcılarını ve hesaplarını
    merkezden yönetmektir. Açık kaynaklı olarak geliştirilmiştir. Tomcat uygulama sunucusu
    üzerinde çalışmakta, kimlik deposu olarak MariaDB / MySQL / PostgreSQL veritabanlarını
    desteklemektedir.

- **ETAP – Etkileşimli Tahta Arayüzü Projesi** : Pardus Etkileşimli Tahta Arayüzü eğitim
    kurumlarında kullanılmakta olan etkileşimli tahtalarda kullanılmak üzere özel olarak
    tasarlandı. Tasarım ve eklenen yeni özellikler dokunmatik ekranlı bir cihazın daha kolay ve
    etkili kullanımını sağlaması düşünülerek geliştirildi.

- **LibreOffice – Masaüstü Ofis Paketi** : LibreOffice, özgür ve açık kaynak kodlu bir ofis
    takımıdır. LibreOffice, birçok uygulama içermektedir. Bunlar; Writer kelime işlemci, Calc
    hesap tablosu uygulaması, Impress sunu, Draw çizim ve akış şeması uygulaması, Base
    veritabanı ve Math matematik yazılımı olarak ayrı ayrı uygulamalardır. LibreOffice,
    Microsoft® Word, Excel, PowerPoint ve Publisher gibi birçok belge biçimi ile de
    uyumludur. Ancak LibreOffice, bunların ötesine giderek açık standart olan Açık Belge
    Biçimi – ABB (OpenDocument Format – ODF) kullanımını da sağlamaktadır.

- **LiderAhenk – Merkezi Yönetim Sistemi** : Kurumsal ağ üzerindeki, sınırsız sayıda farklı
    sistemi ve kullanıcılarını tek merkezden yönetebilmeyi, izlemeyi ve denetlemeyi sağlayan,
    TÜBİTAK ULAKBİM tarafından geliştirilen açık kaynaklı bir yazılım sistemidir. Küresel
    dünyada kurumsal bilgi işlem merkezlerinin, sürekli genişleyen ve değişen bilişim araçları
    üzerindeki kurumsal politikalarını, güvenlik gereksinimlerini, etkin, esnek ve düşük
    maliyetlerle karşılamak üzere geliştirilmiştir.
    Lider sunucu ve Ahenk çekirdekleri ile LDAP sunucusunun oluşturduğu benzersiz çözüm
    altyapısı çevresinde kurumsal ihtiyaçlara göre özelleşmiş otuzdan fazla eklenti içerir.

- **ULAKBÜS – Bütünleşik Üniversite Sistemi:** Tübitak Ulakbim tarafından başlatılan ULAKBÜS
    projesi ile üniversitelerin idari ve akademik birimlerinde kullanılmakta olan yazılımların dış
    veri kaynaklarıyla ve birbirleriyle çalışması ve her bir birimin ihtiyaçlarının sağlanması
    hedeflenmektedir. Açık kaynak geliştirme modeli ile üniversitelerin katılım sağlandığı,
    isteyenlerin test edici, geliştirici, belge geliştirici gibi değişik rollerle hem katkı
    sağlayabileceği hem kendilerini geliştirebileceği geniş bir ekosistem hedeflenmektedir.
    Değerli akademik ve idari çalışanları, konuyla ilgili kişi ve kurumları, bu projeye şimdiden
    yardımcı olmaya çağırıyoruz.

#### Türkiye’deki Diğer Açık Oluşumlar

- **LKD – Linux Kullanıcıları Derneği** : Türkiye’de Linux ve özgür yazılıma gönül vermiş kişilerin
    oluşturduğu, bilgi ve deneyim paylaşımı ile ortak hareket etmeyi amaçlayan bir sivil toplum
    örgütüdür. [http://www.lkd.org.tr/](http://www.lkd.org.tr/)

![LKD](/assets/acik-kaynak/dilara-kadakaloglu/14.png)

LKD, Türkiye’de özgür yazılım ve Linux’un gelişmesini ve bu konuda ülkede özgür yazılım
bilincinin oluşmasını, özgür yazılım ile Linux’un ülkeye ve topluma yarar sağlamasını
hedeflemekle birlikte, üyelerinin bilgi ve becerileri ile sosyokültürel gelişimlerine katkıda
bulunmak ve mesleki yarar kazanmalarını sağlamak için faaliyet göstermektedir. Ayrıca, LKD

ülkenin bilişim ve bilgi toplumu politikalarında özgür yazılımın rolü konusunda çalışmalar
yapar; bunları kamuoyu ile paylaşır ve bunların hayata geçmesi için çalışır.

- **Özgür Yazılım ve Linux Günleri** : LKD tarafından her yıl düzenlenen, Türkiye’de özgür yazılım
    ve GNU/Linux ile ilgilenenlerin katıldığı bir etkinliktir. Bu etkinliklerde, her bilgi seviyesine
    uygun tanıtıcı ve teknik seminerler yapılır. İlgili şirket ve organizasyonların stand açıp, ürün ve
    hizmetlerini tanıtabileceği bir platformdur. https://ozguryazilimgunleri.org.tr

![Özgür Yazılım Günleri](/assets/acik-kaynak/dilara-kadakaloglu/15.png)

- **Açık Bilim:** Açık bilim, elde edilen bilimsel ürünlerin, bilimsel makalelerin ya da bilimsel
    yayınların kullanıcılar için ücretsiz, patentsiz bir şekilde ulaşıma açık hale getirilmesi amacını
    güder. Bilimsel ürünlerin özgürce herkes tarafından kullanılması, geliştirilmesi ve bu ürünler
    sayesinde yeni buluşlar yapılması amacı güdülmektedir.

![Açık Bilim](/assets/acik-kaynak/dilara-kadakaloglu/16.png)

# Doğuş Teknoloji ve Open Source

Hem ülkemizin dolayısı ile de Doğuş Teknoloji’nin son dönemlerdeki ekonomik dengesizliklerden
dolayı en çok ihtiyaç duyduğu nitelikler hız, esneklik ve düşük maliyettir. Bu nedenle açık kaynağın
getireceği rekabet avantajından faydalanmak bu ihtiyacı karşılamak için bir fırsattır.

Açık kaynağın şirketlerde maliyeti nasıl düşürdüğünü altı noktada toplarsak;

- Linux Foundation Consulting’den alınan rakama göre ticari çözümlerde yüzde 20 ile 55
    arasında tasarruf sağlar.
- Genelde markalı ürünler, müşterilerin kullanmadığı, ihtiyaç duymadığı hatta istemediği
    özelliklerle birlikte gelirler. Fakat bunlar da ürünün fiyatına dahil olduğu için bu maliyet
    ödenmiş olur. Açık kaynakta bu sorunla karşılaşmazsınız.
- Kapalı sistemlerin hantal kurulumlarıyla karşılaşmazsınız. Açık kaynak pahalı fiyatlama
    yöntemlerinden, ticari satış ve pazarlık sorunlarından kurtulmak demektir.
- Belli bir tedarikçiye bağımlılıktan kurtarır. Açık kaynak sağlayıcıları çeşitli kanallar
    aracılığıyla destek sağlasalar da müşteriler uygulamalarını veya kullandıkları kodu
    değiştirmeden bu sağlayıcıları değiştirme hakkı vardır.
- Markalı çözümlerin danışmanlık masrafından tasarruf sağlar. Açık kaynakta teknolojiye
    ayrıcalıklı bir erişim olmadığı için danışma, eğitim ve desteği de beraberinde sunar.
- Sürekli açık kaynak topluluğunun desteğinden faydalanırsınız. Aktif topluluklar genelde
    ticari destek kurumlarından daha nitelikli destek verir ve bu destek ücretsizdir.

Peki Doğuş Teknoloji özelinde bu açık kaynağın maliyet avantajını nasıl sağlayabiliriz?

Doğuş Teknoloji’nin mevcuttaki kurumsal lisanslı yazılımlarını, açık kaynak kodlu alternatifleri ile
değiştirebiliriz.

Mevcutta Doğuş Teknoloji veri yönetimini, Microsoft ürünü olan “Microsoft SQL Server” üzerinde
yapmaktadır. Microsoft SQL Server’da çoklu veritabanı çalıştırabilmek için lisans satın almak
gerekiyor. Buna karşı, **MySQL** GNU General Public License kullanıyor ve bu sayede kullanımı tamamen
ücretsiz.

Açık kaynak kodlu yazılım kullanmanın en büyük avantajlarından biri de teknik desteğin sadece
geliştirici özelinde kalmamasıdır. (MySQL’in satıcısı ve sahibi Oracle, MS SQL’in satıcısı ve sahibi ise
Microsoft’tur.) MySQL, teknik bir desteğe ihtiyaç duyulduğunda her ne kadar bunu ücretli kılsa da
genellikle buna ihtiyaç duyulmayacaktır. Çünkü MySQL destek topluluğu mutlaka aranılan çözüm için
yardımcı olacaktır. MySQL için destek alınabilecek binlerce topluluk ve forum sitesi mevcuttur. MS
SQL’e göre daha geniş bir topluluğun olduğu tarafta olmak, Doğuş Teknoloji’yi resmi destek isteme
zahmetinden kurtaracaktır. Tek yapılması gereken, çözüm için internette arama yapmak.

Yine mevcutta Doğuş Teknoloji, ofis yazılımları için kullandığı Microsoft ürünü olan Microsoft Office
(Office 365) ürünleri yerine tamamen ücretsiz ve özgür olan **Open Office** ürünlerini kullanmaya
başlayarak, lisanslama bedellerinden kurtulacaktır.

Şirketin diğer operasyonel süreçlerini takip edebileceği uygulamalar için de yine açık kaynak koldu
yazılım alternatifleri vardır.

- CRM uygulamaları (Sugar CRM, Civil CRM, Zurmo, Fat Free CRM vs.)
- HR Uygulamaları (Orange HRM, Waypoint HR, SimpleHRM vs.)
- Muhasebe Uygulamaları (K9ticaripaket, Turquaz vs.)

Open Source ürün kullanmanın Doğuş Teknoloji’ye maliyet ve teknik destek avantajlarını
kazandırmasını yanı sıra, Agile dönüşüm çerçevesinde de destek verebiliyor olması gerekir. Çünkü
Doğuş teknoloji içerisinde 2018 ortalarında başlayan bir çevik dönüşüm süreci başladı. Peki open
source bu dönüşümde nasıl bir katkı sağlayabilir?

Open source dünyasında komite üyelerini müşteri olarak kabul edebiliriz. Her ne tarafta ve/ya şekilde
olursa olsun hem open source hem de agile dünyasında müşterinin isterleri, onlardan gelen geri
bildirimlerle proje devam eder.

Agile prensiplerde “Çalışan yazılım ilerlemenin birincil ölçüsüdür” der. Bu, açık kaynaklı projelerle,
çevik metodolojinin en iyi uyum sağladığı prensiptir. Her iki felsefe de ilerlemenin birincil ölçüsünü
çalışan yazılım olarak görür.

Uyum içerisinde oldukları bir diğer prensip ise; teknik mükemmelliyet ve iyi tasarım üzerindeki özenli
duruştur. Önceki paragraflarda da bahsettiğim gibi kişilerin açık kaynak kod tercih etme sebeplerinde
“kalite” faktörü büyük rol oynar. Aynı prensipte çevik dünyada da kaliteli ürün çıkartma üzerine
ilkeleri vardır.

Agile manifesto ve 12 prensibini, open source felsefesi ile birlikte değerlendirecek olursak, her iki
hareketin de benzer ilkelere dayalı olduğunu görebiliriz. Dolayısı ile çevik dönüşüm devam ederken,
aslında open source proje geliştirme felsefesini de bir yerlerden yakalayabileceğiz.

**İlkim Dilara KADAKALOĞLU**

**d.**

# Referanslar

[http://kod5.org/acik-kaynak-kod-ve-linux-1/](http://kod5.org/acik-kaynak-kod-ve-linux-1/)

[http://kod5.org/acik-kaynak-kod-ve-linux-2/](http://kod5.org/acik-kaynak-kod-ve-linux-2/)

[https://opensource.org/osd-annotated](https://opensource.org/osd-annotated)

[https://en.wikipedia.org/wiki/Open-source_software](https://en.wikipedia.org/wiki/Open-source_software)

[https://opensource.com/resources/what-open-source](https://opensource.com/resources/what-open-source)

[https://www.quora.com/Why-do-people-prefer-using-open-source-software](https://www.quora.com/Why-do-people-prefer-using-open-source-software)

[https://gist.github.com/nolanlawson/d5334678848aaf11ba](https://gist.github.com/nolanlawson/d5334678848aaf11ba)

[https://www.mobomo.com/2011/08/10-tips-for-open-source-citizens/](https://www.mobomo.com/2011/08/10-tips-for-open-source-citizens/)

[https://blogs.vmware.com/opensource/2017/10/12/good-open-source-citizen/](https://blogs.vmware.com/opensource/2017/10/12/good-open-source-citizen/)

[https://opensource.com/resources/linux](https://opensource.com/resources/linux)

[https://opensource.com/article/18/5/differences-between-linux-and-unix](https://opensource.com/article/18/5/differences-between-linux-and-unix)

[https://medium.com/gitcoin/a-brief-history-of-open-source-3928cb](https://medium.com/gitcoin/a-brief-history-of-open-source-3928cb)

[https://www.kynetics.com/docs/2018/open-source-software-and-licensing/](https://www.kynetics.com/docs/2018/open-source-software-and-licensing/)

[https://choosealicense.com/licenses/apache-2.0/](https://choosealicense.com/licenses/apache-2.0/)

[https://choosealicense.com/licenses/gpl-3.0/](https://choosealicense.com/licenses/gpl-3.0/)

[https://choosealicense.com/licenses/mit/](https://choosealicense.com/licenses/mit/)

[https://wordpress.org/about/](https://wordpress.org/about/)

[https://en.wikipedia.org/wiki/Firefox](https://en.wikipedia.org/wiki/Firefox)

[https://www.openoffice.org/tr/why/why_foss.html](https://www.openoffice.org/tr/why/why_foss.html)

[https://en.wikipedia.org/wiki/MySQL](https://en.wikipedia.org/wiki/MySQL)

[https://notepad-plus-plus.org/](https://notepad-plus-plus.org/)

[https://en.wikipedia.org/wiki/AOSP](https://en.wikipedia.org/wiki/AOSP)

[https://www.ihs.com.tr/blog/googlein-en-iyi-10-acik-kaynak-projesi/](https://www.ihs.com.tr/blog/googlein-en-iyi-10-acik-kaynak-projesi/)

[https://insights.stackoverflow.com/survey/2018/](https://insights.stackoverflow.com/survey/2018/)

[http://www.minepla.net/2015/05/visual-studio-code-nedir-ne-degildir/](http://www.minepla.net/2015/05/visual-studio-code-nedir-ne-degildir/)

[https://www.pardus.org.tr/donusum/](https://www.pardus.org.tr/donusum/)

[https://www.pardus.org.tr/projeler/ahtapot/](https://www.pardus.org.tr/projeler/ahtapot/)

[https://www.pardus.org.tr/projeler/engerek/](https://www.pardus.org.tr/projeler/engerek/)

[https://www.pardus.org.tr/projeler/etap/](https://www.pardus.org.tr/projeler/etap/)

[https://www.pardus.org.tr/projeler/libreoffice/](https://www.pardus.org.tr/projeler/libreoffice/)

[https://www.pardus.org.tr/projeler/liderahenk/](https://www.pardus.org.tr/projeler/liderahenk/)

[http://www.ulakbus.org/](http://www.ulakbus.org/)

[http://www.cio.com.tr/haber/acik-kaynak-vermeyen-sirketler-tutunamayacak/](http://www.cio.com.tr/haber/acik-kaynak-vermeyen-sirketler-tutunamayacak/)

[https://agilemanifesto.org/](https://agilemanifesto.org/)

[https://agilemanifesto.org/principles.html](https://agilemanifesto.org/principles.html)
