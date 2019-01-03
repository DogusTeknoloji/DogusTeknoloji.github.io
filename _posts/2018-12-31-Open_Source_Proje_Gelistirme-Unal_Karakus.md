---
layout: post
title:  "Open Source Proje Geliştirme - Ünal Karakuş"
categories: ["Açık Kaynak"]
tags: ["Açık Kaynak", unalkarakus]
permalink: acik_kaynak_unal_karakus
---

[Bu yazının PDF versiyonu için tıklayınız.](/assets/acik-kaynak/unal-karakus/Open_Source_Proje_Gelistirme_Unal_Karakus.pdf)

**NEDİR BU AÇIK KAYNAK?**
=====================

Diyelim ki bir metin dosyasının içindeki yazıları okumaya ihtiyacınız
var. Bunun için bir programlama dilinde küçük bir konsol uygulaması
(herhangi bir grafik arabirimi olmayan uygulama) yazıyorsunuz,
elinizdeki tüm metin dosyalarınızı bu programı kullanarak okutuyor ve
ihtiyacınızı karşılıyorsunuz. Bir gün sohbet arasında bir arkadaşınız
bir “metin dosya okuma programı” ihtiyacı olduğunu dile getiriyor. Siz
de böyle bir uygulamayı daha önce yazdığınızı ve isterse onunla
paylaşabileceğinizi söylüyorsunuz. Arkadaşınız da memnuniyetle kabul
ediyor ve uygulamayı kullanmaya başlıyor. Hatta arkadaşınızın yaptığı
işte bu uygulama için bir grafik arayüzü ihtiyacı doğuyor ve arkadaşınız
sizin uygulamanız üstünde bu geliştirmeyi yaparak uygulamanıza katkı
sağlıyor.

Tam bu noktada sizde bir ışık yanıyor ve kendinize diyorsunuz ki “e ben
bunu başkalarıyla paylaşırsam hem uygulamam gelişir hem de onların metin
dosyası okuma ihtiyacını karşılayabilirim.” İşte tam bu noktada açık
kaynak modeli devreye giriyor. Modele hizmet eden servisler üzerinde
yazdığınız kodu paylaştığınız ve uygun bir lisans modeliyle
lisansladığınız takdirde yazdığınız uygulama hem sürekli gelişebilir hem
de dünyada başka ihtiyaç sahipleri tarafından kullanılabilir oluyor.

Tüm bu hikâye sonrasında aslında açık kaynak için *“iş birliğine dayalı,
belirli lisans modelleri çerçevesinde özgürce kullanılabilen ve
merkezileştirilmemiş yazılım geliştirme modelidir*” tanımını kullanmamız
yanlış olmayacaktır.

**PEKİ YA AÇIK KAYNAĞIN TARİHİ?**
=============================

Her ne kadar açık kaynak kavramı yazılım ile anılıyor olsa da teknik
becerilerin ve bilgilerin paylaşımı bilgisayarlardan önceye dayanır.
*Otomobillerin gelişiminin ilk zamanlarında George B. Selden 2 zamanlı
benzinli motor için bir patente sahipti ve bu patent Ford gibi büyük
markaların ve endüstrinin gelişiminde büyük engel teşkil ediyordu. 1911
yılında Henry Ford, bu patente karşı açılan hukuk savaşında galip geldi
ve bu galibiyet Selden’ın patentini değersizleştirdi. Akabinde kurulan
Motorlu Taşıt Üreticileri Derneği, otomobil üreticilerinin yaptıkları
çalışmaları çapraz kullanabileceği bir lisans modeli geliştirdi. Bu
anlaşma sayesinde her firma birçok teknoloji ve patent geliştirmesine
rağmen birbiriyle paylaşıp gelişimlerine katkıda bulunabildi. Birinci
dünya savaşı sırasında 92’si Ford’a ait toplamda 607 patenti herhangi
bir bedel ödemeden otomobil firmaları arasında paylaşılabilir
durumdaydı.*

Yazılım kaynak kodlarının ilk paylaşımları **1950-60’lı** yıllarda
**IBM** tarafından başlatıldı. İşletim sistemleri ve bu sistemler
üzerinden çalışan yazılımlar küçük bir kullanıcı grubu **(SHARE)**
arasında paylaşıldı. 1960’lı yıllarda ARPANET üyeleri tarafından network
protokollerini test etmek amacıyla **NWG** (Network Working Group) ağı
kuruldu ve **RFC** (Request For Comments) adı verilen geri bildirim
sürecini işletildi ve bu da erken internetin doğmasını destekleyici
oldu. 1980’li yıllara gelindiğinde ise **USENET** (User Network) adı
verilen Unix sunuculardan oluşan bir ağda ve dünya çapında oluşturulmuş,
geliştiricilerin bilgi paylaşımlarını yapabileceği ve etkileşimde
bulunabileceği paylaşım platformu oluşturuldu.

**1980**’lerin ortalarına doğru ise gerçekten **özgür yazılım**
kavramının doğuşu başlıyordu. Çalıştığı ortamda (MIT) değişiklik yapmak
adına bir kaynak kodu isteyen **Richard Stallman** (RMS olarak tanınır)
adındaki genç bir yazılımcı, kaynak kodu “gizli” olduğu için kendisiyle
paylaşmayan arkadaşları karşısında şaşkınlığa uğramıştı. Bu şaşkınlığını
ilerleyen zaman içerisinde MIT’den ayrılan araştırmacıların kendi
şirketlerini kurarak, kurumsal şirketler için özel yazılımlar yapmaya
başlamaları da destekledi.

RMS bu duruma tepki olarak, tüm geliştirmecilerin kaynak kodlarını
inceleyebileceği ve katkıda bulunabileceği **GNU** işletim sistemi
projesini oluşturmaya karar verdi ve böylece **Özgür Yazılım Hareketi**
başlamış oldu. 1984’te MIT’den ayrılarak GNU’un geliştirmelerine
başladı. **GCC (GNU Compiler Collection)** ve **GSD (GNU Symbolic
Debugger)** modülleri ve **GPL(GNU Public Licence)** bu sistemin başlıca
çıktılarıdır.

**1991**’de **Linus Torvalds**, GNU sistemini temel alan Minix adını
verdiği kendi çekirdeğini oluşturmaya kararını verdi. Ve bu adımla
birlikte GNU projesinin son parçası da tamamlanmış oldu. GNU projesi
artık milyonları etkileyecek bir hal aldı ve **GNU/Linux** işletim
sistemi doğdu. GNU/Linux işletim sistemi bugün neredeyse her cihazda yer
alıyor; sunucular, modemler, network cihazları, cep telefonları vb…

**1993** yılında Linux çekirdeğini baz alan ve bugün de kurumsal
seviyede birçok sistemde kullanılan **RedHat** doğdu. RedHat bizlere
özgür olan bir yazılımın aslında ne kadar kârlı olduğunun bir kanıtıdır
ve doğuşundan beri açık kaynak dünyasının gelişimine önemli katkılar
sağlamıştır.

**1996**’ya gelindiğinde **Apache HTTP Server** doğdu. NSCA HTTPd
çözümünü temel olan bu açık kaynak yazılım bugünün en popüler ve en çok
kullanılan internet sunucu yazılımlarından biridir.

**1998** yılı hem açık kaynak hem de internet tarayıcıları için dönüm
noktası oldu. **NetScape**, piyasada bulunan diğer internet
tarayıcılarından çok daha iyi bir konuma gelmek adına kaynak kodunu
açacağını ve **Mozilla** grubunu oluşturacağını duyurdu. Böylece
tarayıcının gelişmesi adına hem geribildirimler alabilecek hem de kaynak
koda müdahaleler kabul edebilecekti. Yıllar boyunca bu destekle birlikte
gelişen NetScape’in yerini alan **Firefox**, bugünün en bilinen ve en
güçlü web tarayıcılarından biridir.

**AÇIK KAYNAK YAYGINLAŞACAK GÜCÜ NEREDEN BULUYOR?**
===============================================

Açık kaynak, yazılım dünyasında adından oldukça bahsettiren ve gittikçe
popülerleşen bir kavram. Son zamanlarda özellikle Microsoft, Google gibi
dünya firmaların da bu alanda yaptığı yatırımlar açık kaynağa olan
güveni de oldukça artırıyor.

Hiç şüphesiz ki hem firma yatırımlarının hem de bu derece yaygınlaşmanın
ardında birtakım sebepler mevcut. Bunlardan maddeler halinde bahsedelim;

1)  **Topluluk:** Yaptığınız işleri milyonlarla paylaşıyorsunuz. Düşünce
    alanınızın bir birim olduğunu varsayarsak, milyon birimden oluşan
    bir düşünce alanının işlerinize olan katkısını tahmin bile
    edemezsiniz. Aynı zamanda siz de bu topluluğun bir parçası
    olacağınızdan farklı bir iş için inanılmaz bir katkı
    sağlayabilirsiniz.

2)  **Bilgi alışverişi ve iş birliği:** Bilgi paylaştıkça büyür. Önemli
    bir problemin çözümü için toplulukta bulunan kişi ya da kişilerle
    bilgi paylaşımında bulunabilir ve onlardan fikirler alabilirsiniz.
    Paylaşım ve iş birliğiniz sayesinde çözüme kolayca ulaşabilirsiniz.

3)  **İyi olan kazansın:** Açık kaynakta iyi olan kazanır. Aynı amaca
    hizmet eden birçok projenin paylaşıldığı bir ortamda topluluk en iyi
    olanı destekleyecektir. Eğer projeniz yeterince iyiyse siz de
    yıldızları toplayabilirsiniz. Hatta projelerinizden start-up
    şirketler kurabilir, kurumsal hizmetler satabilir, büyük firmalardan
    projeleriniz için yatırım alabilir hatta kurduğunuz şirketi iyi
    paralara diğer şirketlere satabilirsiniz.

4)  **Güvenilirlik ve sağlamlık:** Açık kaynak olan popüler bir yazılımı
    kullanıyorsunuz ve bir hata ile karşılaştınız. Yeterince
    yetkinliğiniz varsa bu açık kaynak yazılımının hatasını bulup katkı
    sağlayabilir veya talepte bulunarak ilgili topluluktan destek
    isteyebilirsiniz. Muhakkak ki birileri bu çağrınızı görecektir ve
    hatanın çözümü için size destek olacaktır, çünkü hiç kimse tüm
    dünyayla paylaştığı yazılımının gözden düşmesini istemez.

5)  **Maliyet avantajı:** Özellikle kurumsal alanda kullanılan lisanslı
    ve kapalı yazılımlar, şirketler için büyük gider kalemi
    oluştururlar. Günümüzde neredeyse her kurumsal yazılımın bir açık
    kaynak örneği bulunmaktadır. Kapalı yazılımlarınızın bir kısmını ya
    da bir parçasını açık kaynak ile değiştirdiğinizde ciddi anlamda
    maliyet avantajı sağlayabilir ve hizmet verdiğiniz müşterilerinizde
    memnuniyet yaratabilirsiniz.

**NASIL İYİ BİR AÇIK KAYNAK VATANDAŞI OLURUM?**
===========================================

İyi bir geliştirici olmak için araştırmak, denemek ve uygulamak gerekir.
Lakin iyi bir geliştiricinin iyi bir açık kaynak destekçisi olmasını
beklemek doğru olmaz. Nasıl ki iyi bir vatandaşın ülkesi için bazı
sorumlulukları varsa açık kaynak gönüllüsünün de aynı şekilde
sorumlulukları vardır. Peki nedir bu sorumluluklar, hızlıca inceleyelim.

1)  **Araştırmacı olmak:** Çözüme ulaşmak için birden fazla yol
    olabileceğini unutmamalısınız. Bunun için katkıda bulunulacak
    projelerde ya da etkinliklerde odaklanılan konuların geniş çaplı
    araştırmasını ve kod incelemesini yapmak gerekir.

2)  **Katılımcı olmak:** Açık kaynağın yaygınlaşmasının en önemli
    nedenlerinden biri katılımcılarının oldukça fazla olmasıdır.
    Katılımlar sayesinde problem hızlıca çözümlenir, yeni çözüm yolları
    edinilebilir. İyi bir açık kaynak gönüllüsünün açık kaynak
    platformlarında yer alan projelerde boy göstermesi önemlidir.

3)  **Katkıda bulunmak:** Açık kaynak platformlarına projeler
    ekleyebilir veya var olan projelerde düzenleme yapmak
    isteyebilirsiniz. Her ikisi de önemli katkı yöntemleridir.

4)  **Saygılı olmak:** Projelerinizde ya da katkıda bulunduğunuz
    projelerde pek de saygı içermeyen ithamlarla karşılaşabilirsiniz. Bu
    durumlarda saygıyı elden bırakmadan durumu yönetmek önem arz
    etmektedir.

5)  **Olumlu geri bildirim vermek:** Her türlü katkıya olumlu geri
    bildirim vermeniz hem sizi hem de katkıda bulunan kişi ya da
    kişileri iyi hissettirecektir ve katkıda bulunmak isteklerini
    artıracaktır. Aynı durum sizin için de geçerlidir.

6)  **Sözünde durmak:** Yaptığınız projeyle ilgili size bir talep ya da
    bulgu geldiğinde “Bunu akşam çözerim” veya “Hafta sonu bu özelliği
    eklemeyi düşünüyorum.” Diyorsanız bunu belirttiğiniz zaman sınırları
    içerisinde yapmanız size olan güvenin artmasına yardımcı olacaktır.

7)  **Denetçi olmak:** Paylaştığınız projelerin branch’lerini koruma
    altına almanız önemlidir. Bu yöntem, herhangi bir gönüllü projenize
    katkıda bulunmak için size pull request gönderdiğinde sizin bu
    değişikliği gözden geçirmenize olanak sağlayacaktır. Aynı durum
    sizin başka bir projeye katkı sağlamak istediğinizde de geçerli
    olacaktır. Bu yöntem hem etkileşimi hem de kaliteyi artıracaktır.

**AÇIK KAYNAK LİSANSLANIR MI, NASIL?**
==================================

Sorunun cevabı evet, açık kaynak lisanslanır. Açık kaynak projelerinizin
paylaşımının dağıtımını ve sorumluluklarını kontrol altına almak ve
paylaşımcının hakkını korumak amacıyla açık kaynak lisansları devreye
girer.

İki türlü lisanslama yöntemi vardır;

1)  **Permissive lisanslama**: Bu lisanslama modeli aslında bir
    “hoşgörülü” lisanslama modelidir, yani açık kaynak projeye
    istediğinizi yapabilirsiniz diyebiliriz. Sadece projenin dağıtımı
    yapanlar karşılaşabileceğiniz durumlardan sorumlu değillerdir. Bir
    kaynakta **“kodla ne yaparsan yap ama beni dava etme”** cümlesi bu
    lisans için en güzel tanım olacaktır. Ek olarak lisans dahilinde
    kullanımda ilk yayıncının tanınması sağlamak da kullananın
    sorumluluğundadır.

    Lisans örnekleri ise şu şekildedir;

    a.  **Apache 2.0**

    b.  **MIT**

    c.  **BSD**

    d.  **ISC**

2)  **Copyleft Lisanslama:** Permissive lisans modeline ek bazı
    kısıtlamalar getirir. Kaynak kod yeniden dağıtılıyorsa bu kod lisans
    sahibine de açık olmalıdır. Bununla beraber yeniden dağıtım
    aşamasında baz alınan lisans modeli üstünde değişiklik yapamazsanız.

    Bu lisans modelinin konseptini geliştiren kişi, daha önce adından
    sıkça bahsettiğimiz Richard Stallman’dır. Kendisi copyleft lisans
    için **“Değiştir, yeniden dağıt ama bu özgürlüğü ortadan kaldırma”**
    demiş ve avukatlarla birlikte ilk implementasyonu olan **General
    Public Licence (GPL)** lisansını oluşturmuştur.

Lisans örnekleri ise şu şekildedir;

a.  **GNU AGPLv3**

b.  **GNU GPLv3**

c.  **GNU LGPLv3**

d.  **Mozilla Public Licence (MPL)**

e.  **Eclipse Public Licence (EPL)**

**AÇIK KAYNAK İÇİN HİZMET VEREN SERVİSLER NELER?**
==============================================

Açık kaynak için dünya çapında hizmet veren önemli servisler vardır. Bu
servisler üstünde açık kaynak lisansı altında paylaşımlar yapabilir,
diğer açık kaynak gönüllüleriyle hatta tüm dünya ile projelerinizi
paylaşabilirsiniz.

**GITHUB:** Belki de açık kaynak diyince akla gelen ilk servistir
GitHub. Tüm açık kaynak servisleri gibi GitHub da bir web arayüzü
bulunan dünyadaki en popüler ve en sık kullanılan kaynak kod deposudur.
Eğer bir probleme çözüm sağlayan iyi bir açık kaynak proje arıyorsanız
GitHub yıldızlarına bakarak kıyaslamasını yapabilirsiniz. Yakın zamanda
Microsoft tarafından satın alınması sonrası bir miktar kullanıcısını
GitLab’a kaptırmış olsa bile açık kaynak servisi olarak popülerliğini
artırmaya devam etmektedir.

**GITLAB:** GitHub, Bitbucket gibi açık kaynak projeler için kod deposu
sağlayan bir diğer servistir. Diğer servislerden farklı olarak özellikle
ücretli versiyonlarında güvenlik, izleme, raporlama, yedekleme, on-prem
sunucu gibi çok ciddi özellikleri de beraberinde getirmektedir. Bu
özellikler nedeniyle büyük firmaların özel kod depoları için tercih
ettikleri bir servis olmuştur.

**BITBUCKET:** Atlassian ürünleriyle oldukça entegre çalışan bir kod
deposu olan Bitbucket, diğer servislerle aynı özelliklere sahiptir. Eğer
JIRA ve Bitbucket kullanıyorsanız yazılım geliştirme süreçlerinizi
başarılı bir şekilde yönetebilirsiniz.

**AZURE DEVOPS:** Bir zamanlar açık kaynakla savaş açmış olan
Microsoft’un açık kaynak alanında yaptığı önemli açılımlardan biri de bu
servistir. Kod deponuzu ve yazılım geliştirme süreçlerini
yönetebileceğiniz ücretsiz hizmet veren servislerden biri olarak tercih
sebebi olabilir.

Tüm bu servislere ek olarak aslında tüm dünya tarafından kullanılan bazı
açık kaynak platformları da mevcut. DT olarak gündemimizde olan
platformlara da kısaca değinmek isterim.

- **OpenStack**: Sanallaştırma platformlarının sağladığı maliyet avantajı tartışılmaz. Geçtiğimiz yıllarda birçok firma fiziksel sunucularını sanallaştırarak ciddi avantajlar sağladı. Tabi bu dönüşüm sanallaştırma yazılımlarında da (VMware, Hyper-V) kullanım artışı nedeniyle aynı oranda bir fiyat artışına yol açtı. OpenStack ise tam bu noktada sanallaştırma platformlarını farklı modüller çerçevesinde oluşturmanızı sağlayan açık kaynak bir çözüm olarak karşımıza çıkıyor. 

 - **PostgreSQL**: İlişkisel veritabanı yönetimi için kendini kanıtlamış, ücretli çözümlerden neredeyse hiç farkı olmayan bir veri tabanı platformu olarak PostgreSQL, SQL Server ve Oracle gibi ücretli alternatifleri yerine tercih edilir bir ürün olarak karşımıza çıkıyor.

 - **Docker ve Kubernetes**: Docker ile uygulamalarınızı ücretsiz sanallaştırarak platform bağımsız olarak kullanabilirsiniz. Kubernetes ile sanallaştırdığınız uygulamalarınızın orkestrasyonunu yine ücretsiz olarak yapabilirsiniz. 

 - **Tensorflow**: Google desteğiyle açık kaynak olarak geliştirilen, makine öğrenmesi ve derin öğrenme için kullanılan fonksiyonlarının tamamını barındıran bir altyapıdır. Hızı ve kolaylığı ile yapay zeka çözümlerinde tercih edilmektedir.

 - **ELK (Elasticsearch LogStash Kibana) Stack**: Uygulamalarınızın loglama sürecini kurgulayabileceğiniz, aktardığınız logları izleyip raporlar çıkartabileceğiniz pratik ve güzel bir çözümdür.

**TÜRKİYE'NİN AÇIK KAYNAK YAKLAŞIMI**
=================================

Tüm dünya ile birlikte aynı hızda olmasa bile Türkiye’de de bazı açık
kaynak yatırımları yapılıyor ve bu yatırımlar gittikçe artıyor.
Maddelendirilmiş örnekler üstünden gitmek, yorumlamak daha açıklayıcı
olacaktır;

-   **TÜBİTAK** tarafından geliştirilen ve bir zamanlar popüler olarak
    dağıtımı yapılan **Pardus** işletim sistemi, Linux çekirdeğini
    kullanıyor ve yine aynı lisans altında ücretsiz olarak dağıtılıyor.
    Yeterli mi, tartışılır. Pardus bu alanda ilk adım olarak
    değerlendirilebilir lakin bu örneklerin çoğaltılması için hem ulusal
    hem de uluslararası üniversite destekli çalışmaların yapılması
    alanda bilinirliğimiz artıracaktır.

-   **Pardus** projesi kapsamında **EnGerek** (Kimlik Yönetim Sistemi),
    **Ahtapot** (Birleşik Siber Güvenlik Sistemi), **ETAP** (İnteraktif
    Tahta Arayüzü), **LibreOffice** (Ofis programları süiti),
    **LiderAhenk** (Merkezi Yönetim Sistemi), **ULAKBÜS** (Bütünleşik
    Üniversite Sistemi) alt projeleri de geliştirilmiş ve **GitHub**
    üstünde diğer projelerle birlikte açık kaynak lisansıyla topluluğa
    sunulmuştur.

-   Çok yakın bir tarihte, Sanayi ve Teknoloji Bakanlığı yönetiminde,
    özel sektör ve kamu iş birliği ile **Türkiye Açık Kaynak Platformu**
    kurulmuştur. Sanayi Bakanı, bu platformu dışa bağımlılıktan
    kurtulmak, yazılımcı ekosistemi oluşturmak ve ekonomik katkı
    sağlamak amacıyla kurduklarını dile getirmiştir. Tam olarak nasıl
    bir kapsamda olacağı ve neleri içinde barındıracağı ilerleyen
    günlerde netleşecektir.

-   Doğuş Teknoloji’nin de içinde bulunduğu birçok teknoloji firması hem
    açık kaynak çözümler geliştirmeye hem de geliştirdikleri çözümleri
    ilgili servisler üzerinden paylaşmaya başlamışlardır. GitHub’a
    girdiğinizde birçok Türk firmasının proje paylaşımlarını
    görebilirsiniz. Ayrıca yine şirketimizde örneğini görebileceğiniz
    açık kaynak projelere katkı sağlama isteği de şirketler için önemli
    bir değer aline gelmeye başlamıştır.

-   Üniversitelerde bulunan akademisyen, yüksek lisans ve doktora
    öğrencileri, yaptıkları çalışmaları yine GitHub üstünden
    paylaşmaktadırlar. Bu paylaşımlar sayesinde ülke olarak önemli
    kazanımlar edinebilir durumdayız. Özellikle üniversitelerin
    bünyesinde bulunan öğrenci ve çalışanlarını bu konuda teşvik etmesi
    dünya çapında tanınırlığımız açısından önemlidir.

Dünya ile Türkiye’yi kıyasladığımızda elbette aynı seviyelerde
olmadığımızı görebiliyoruz. Lakin bunu bir motivasyon kaybı değil, bir
şans olarak değerlendirmemizin doğru olacağı kanaatindeyim. Özellikle
dünyadaki açık kaynak çözümlere ülke olarak katkı sağlamak hem şahıs hem
kurum bilinirliğimizi artıracak niteliktedir. Ayrıca ülkemizin tanıtımı
açısından da bu alanda yer almak, yapılan lokalize çözümleri dünya ile
paylaşmak Türkiye’yi teknoloji alanında tercih edilen ülkelerden olma
yolunda ve belki de son yıllarda artan beyin göçünün azalmasında
destekleyici olabilir.

**DOĞUŞ TEKNOLOJİ VE AÇIK KAYNAK**
==================================

Ülkemizde yaşanan ekonomik değişimlerin tüm şirketler üstünde etkileri
olmaktadır ve bizler Doğuş Teknoloji çalışanları olarak şirketimizde ve
hizmet verdiğimiz şirketlerde etkilerini bunu yakından hissetmekteyiz.
Ülkedeki önemli teknoloji şirketlerden biri olarak da bu durumu yönetmek
için bazı açılımları desteklememiz ve açık kaynak alanına yatırım
yapmamız gerektiğinin de farkındayız.

İlk olarak şirket içinde iyi bir açık kaynak vatandaşı (gönüllüsü)
yetiştirme programı başlatabiliriz. Bu program kapsamında Doğuş
Teknoloji GitHub reposunda yaptığımız bazı çalışmaları gerekli
standartlara uygun bir şekilde paylaşabiliriz. **BatMap** bu
paylaşımların güzel bir örneğidir. Bununla birlikte bazı önemli
projeleri çatallandırıp yeni özellikler ekleyebilir ve bunun PR olarak
göndererek katkıda bulunabiliriz. Yine **Swagger** için yazılmış olan
axios provider yapılan katkı bunun iyi bir örneğidir.

Halihazırda kullandığımız RDBMS sistemleri için de dönüşüm süreci
çalışmalarımıza başladık. Eski geliştirdiğimiz uygulamalarda
**PostgreSQL**, **MySQL** dönüşümlerini yapmaya başlamamız
müşterilerimize sağlayacağımız maliyet avantajı için önemli bir adım
olacaktır. Benzer şekilde altyapı sanallaştırma sistemlerimizi
**OpenStack** ile dönüştürmemiz aynı faydayı sağlayacak,
müşterilerimizde maliyet avantajı nedeniyle, iş arkadaşlarımızda da açık
kaynak kullandığı ve gelişime katkıda bulunduğu için memnuniyet
yaratacaktır.

Teknoloji şirketi olarak yazılım geliştirme süreçlerimizde kullandığımız
ürünleri ve kodlama standartlarımızı açık kaynak toplulukları tarafından
kabul gören ve tercih edilen ürün ve standartlarla değiştirmemiz bizler
adına hem iyi bir imaj oluşturacak hem de ürettiğimiz projelerdeki
kalitemizi artıracaktır. Bu gelişme aynı zamanda şirket genelindeki
yazılımcılar için ortak akıl ve kurallar bütünü oluşmasına ve yapılan
her işte aynı kaliteye ulaşılması katkı sağlayacaktır.

İşe alım süreçlerimizde şirketimize başvuran adayların açık kaynak
katkılarını incelememiz ve seçimlerimize buna göre yapmamız insan
kaynağı kalitesi açısından da fayda sağlayacaktır. Tam tersini
düşündüğümüzde ise, şirket olarak yaptığımız açık kaynak paylaşımlar da
kaliteli insan kaynağının bizi tercih etmesinde destekleyici unsur
olacaktır. Facebook, Google, Amazon, Microsoft gibi firmalar yaptıkları
anketlerle bunun önemini gözler önüne sermişlerdir.

Tüm bunların yanında Doğuş Teknoloji için bence en çok önem arz eden ve
dünyada birçok firmanın gelir kaynağı olarak kabul gören bir diğer konu
ise geleceği olan açık kaynak projeleri tespit etmek ve bu projelere
maddi katkı sağlamaktır. Katkı sağlanan projeler ilerleyen zamanlarda
iyi startup çıkışları yapabilir ve değerlerini iyi seviyelere
ulaştırabilirlerse eğer şirket olarak ciddi kazançlar elde edebiliriz.

Tüm bu süreçte bizlere düşen en önemli görev ise açık kaynak dünyasını
yakından takip etmek, bu dünyadaki fırsatları görebilmek, üretilen açık
kaynak çözümleri desteklemek ve tüm bu akışı yazılım sürecimizin bir
parçası haline getirmek olmalıdır. Bu şekilde hem açık kaynak dünyasına
Doğuş Teknoloji ve bireysel kimliğimizle önemli bir fayda sağlamış hem
de şirketimize, ülkemize ve kendimize iyi bir yatırım yapmış oluruz.


**KAYNAKÇA**
===========

<https://hackernoon.com/being-a-good-open-source-citizen-9060d0ab9732>

<https://opensource.org/licenses>

<https://choosealicense.com/licenses/>

<https://www.gnu.org/licenses/license-list.html>

<https://medium.com/gitcoin/a-brief-history-of-open-source-3928cb451767>

<https://royal.pingdom.com/2010/01/15/the-9-most-important-events-in-open-source-history/>

<https://blog.lizardwrangler.com/2008/01/22/january-22-1998-the-beginning-of-mozilla/>

<https://techcrunch.com/2016/02/09/the-money-in-open-source-software/>

<http://theconversation.com/how-the-internet-was-born-from-the-arpanet-to-the-internet-68072>

<https://stallman.org/biographies.html>

<https://economictimes.indiatimes.com/small-biz/startups/newsbuzz/why-is-open-source-software-so-popular/articleshow/62689785.cms>

<https://eksisozluk.com/richard-stallman--43270?p=10>

<https://techcrunch.com/2017/04/07/tracking-the-explosive-growth-of-open-source-software/>

<https://mozanunal.com/2016/09/ack-kaynak-yazlm-lisans-turleri-ve/>

<https://dev.to/bekka/wrap-it-up-being-a-good-citizen-of-open-source-by-devdiscuss-8je>
