# Branchline Gizlilik Bildirimi

Version: 2026-09-08.1

## Bilgilerinizden kim sorumlu

Türkiye'de Kylindravia markasıyla çalışan bireysel geliştirici Ahmet Kılıç, Branchline davet, lisans ve özel destek kayıtlarının veri sorumlusudur. Konuya “Branchline privacy” yazarak [kylindravia@gmail.com](mailto:kylindravia@gmail.com) adresine ulaşabilirsiniz. Bu bildirim veri işlemeyi açıklar; genel bir açık rıza talebi değildir.

## Repolar ve isteğe bağlı yardım

Branchline, Mac'inizdeki repolarla çalışır. Git ağ işlemleri, yapılandırdığınız Git sunucularıyla ve ayarladığınız kimlik bilgileriyle gerçekleşir. Repo yolları, kaynak kod, remote adresleri ve Git kimlik bilgileri lisans hizmetine gönderilmez.

İsteğe bağlı commit mesajı yardımını yapılandırırsanız uygulama, Send seçiminizden önce hedefi ve gönderilecek isteği gösterir. İstek, seçili staged dosyaların yollarını ve diff içeriklerini barındırabilir. Seçtiğiniz uç nokta bu isteği alır; yerel bir komut isteği standart girdiden alır ve kendisi dış hizmetlerle iletişim kurabilir. Seçtiğiniz sağlayıcının veri işleme uygulamaları geçerlidir. Aktivasyon, yardım isteklerini etkinleştirmez veya bunlara izin vermez.

## Aktivasyon ve yerel kayıt

Aktivasyon, süre uzatımı kontrolü ve deaktivasyon; aktivasyon kodunu ve rastgele bir kurulum kimliğini Branchline lisans hizmetine gönderir. Hizmet; lisans kimliği, kodun anahtarlı özeti, mevcut kurulum kimliği, oluşturma/güncelleme/ilk aktivasyon tarihleri, bitiş tarihi, devre dışı durumu ve revizyonu saklar. Lisans veritabanında kodun kendisi veya e-posta adresi saklanmaz. Deaktivasyon kurulum alanını temizler; cihaz geçmişi tablosu yoktur.

İstekte donanım seri numarası, iletişim e-postası, uygulama parolası, repo verisi veya uygulama sürümü bulunmaz. IP adresi dahil olağan bağlantı bilgileri barındırma sağlayıcısına ulaşır. Hizmet, aşırı istekleri sınırlamak için IP adresinin geçici anahtarlı özetini kullanır. Worker uygulama günlüğü kapalıdır; hizmet IP adresini veya özetini lisans veritabanına kaydetmez.

Mac'inizde eşitlenmeyen Anahtar Zinciri kayıtları; kodu, imzalı lisans kaydını, rastgele kurulum kimliğini, deaktivasyon durumunu ve son kaydedilen lisans kontrol zamanını tutar. Kişisel Kullanım Koşullarını kabul ettiğinizde bildirim sürümü, uygulamadaki metinlerin içerik özeti ve kabul zamanı da bu yerel kayda eklenir. Bu kabul kaydı sunucuya gönderilmez. Uygulamayı kaldırmak Anahtar Zinciri kayıtlarını kendiliğinden silmez.

## Davetler, destek ve tanılama

Geliştirici, davet ve özel destek için Kylindravia Gmail hesabını; davet iletişim bilgisi ile lisans kimliğini eşleştirmek için özel yerel bir kaydı kullanır. Bu kayıt GitHub'a veya paylaşılan bir bulut tablosuna konmaz. Davetler ve e-posta yazışmaları kişisel kodu içerebilir; bunları gizli tutun.

Destek, göndermeyi seçtiğiniz iletişim bilgilerini, mesajları ve ekleri alır. Branchline tanılama raporu yerel olarak hazırlanır ve önizlenir; kaydetmek raporu yüklemez. Uygulama geliştiriciye otomatik tanılama veya çökme raporu göndermez. macOS'in kendi tanılama paylaşım ayarları ayrıdır.

Gönderdiğiniz GitHub issue'ları ve ekleri herkese açıktır. Aktivasyon kodlarını, Git kimlik bilgilerini, özel kaynak kodunu veya gözden geçirilmemiş günlükleri eklemeyin. Özel raporlar izniniz olmadan yayımlanmaz. Davet iletişim bilgileri reklam için kullanılmaz veya pazarlama listesine eklenmez.

## Sağlayıcılar ve ağ istekleri

Cloudflare, lisans hizmetini ve veritabanını barındırır. GitHub; indirmeleri, imzalı güncelleme kanalını, herkese açık belgeleri ve issue'ları barındırır. Google, geliştiricinin Gmail posta kutusunu sağlar. Bu sağlayıcılar ilgili hizmetler için gereken bilgileri alır; alt hizmet sağlayıcıları dahil Türkiye dışında işleyebilir. Veritabanı için Avrupa konumu seçilmesi, bütün işlemenin Avrupa'da kalacağı anlamına gelmez.

Güncelleme kontrolü GitHub'dan herkese açık kanalı, güncelleme indirmesi ise uygulama arşivini ister. Otomatik kontroller isteğe bağlı olarak açılır; sistem profili raporlaması kapalıdır. Bu istekler bağlantı bilgilerini ve güncelleyicinin kullanıcı aracısı bilgisini içerir; aktivasyon kodu, lisans kaydı veya repo içeriği içermez. Bu bildirimi Branchline içinde okumak ağ isteği oluşturmaz. Web veya e-posta bağlantısı açmak, seçtiğiniz harici uygulamayı ve onun hizmetlerini kullanır.

Sağlayıcı bilgileri: [Cloudflare gizlilik](https://www.cloudflare.com/privacypolicy/), [Cloudflare veri işleme koşulları](https://www.cloudflare.com/cloudflare-customer-dpa/), [GitHub gizlilik](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement) ve [Google gizlilik](https://policies.google.com/privacy). Sağlayıcıların ayrı ağ/güvenlik kayıtları ve saklama süreleri kendi geçerli politikalarına tabidir. Yerel bir kaydın silinmesinin tüm sağlayıcı kayıtlarını anında sileceği taahhüt edilmez.

Bu ücretsiz lisans Lemon Squeezy satın alımı gerektirmez ve aktivasyon isteklerini Lemon Squeezy'ye göndermez. Ücretli satış başlamadan önce gerçek satın alma verisi işlemeyi açıklayan ayrı bildirim hazırlanacaktır.

## Amaçlar ve toplamanın hukuki sebebi

Davet gönderimi, aktivasyon, tek cihaz hakkı, süre uzatımı ve talep edilen lisans desteği için lisans sözleşmesinin kurulması veya ifasıyla doğrudan ilgili ve gerekli bilgiler kullanılır (KVKK madde 5/2-c). Sınırlı güvenlik/istek sınırlama ve yönetim kayıtları, temel haklarınızı gözeterek lisans hizmetini koruma meşru menfaatine dayanır (madde 5/2-f). Belirli bir hukuki yükümlülük veya bir hakkın tesisi, kullanılması ya da korunması için gereken veriler ilgili hukuki sebebe dayanarak tutulabilir (madde 5/2-ç veya e).

Bilgiler; aktivasyon isteklerinizden, seçerek gönderdiğiniz mesaj ve başvurulardan, geliştiricinin davet yönetiminden elektronik olarak toplanır. Özel nitelikli kişisel veri istenmez. Olağan destek için kimlik belgesi, banka bilgisi veya parola göndermeyin. Koşullar kutusu; pazarlamaya, isteğe bağlı yardıma veya yurt dışına aktarıma açık rıza değildir.

## Kayıtların saklama süresi

Hizmetin günlük temizliği, süresi dolan lisansları 90 gün sonra; hiç aktive edilmemiş davetleri oluşturulduktan 366 gün sonra kaldırır. Sınırlı yönetim işlem kayıtları 90 gün sonra silinir. Veritabanının yakın geçmişteki durumları Cloudflare D1 kurtarma geçmişinde yedi güne kadar kalabilir. Lisans veritabanı için ek bir düzenli dışa aktarım şu anda yapılandırılmamıştır.

Geliştiricideki davet/iletişim eşleştirmesi, erişim süresi dolduktan veya katılım sona erdikten sonraki 90 gün içinde kaldırılır; kullanılmayan davet ve eşleştirmeleri en geç 366. günde kaldırılır. Kapanan destek yazışmaları ve yerel kopyaları, kapanıştan sonraki 90 gün içinde kaldırılır. Gerekmeyen hassas ekler daha erken silinir. Belirli bir uyuşmazlık veya hukuki yükümlülük, sınırlı bir kaydın daha uzun tutulmasını gerektirebilir; ilgili bir başvuruya yanıt verirken sebep ve kapsam açıklanır. Herkese açık issue içeriği GitHub'ın kontrollerine tabidir; sağlayıcı güvenlik ve yedek kayıtlarının saklama süreleri farklı olabilir.

Kendi Mac'inizdeki kayıtlar sizin kontrolünüzdedir. Deaktivasyon sunucudaki cihaz hakkını serbest bırakır; yerel geçmiş ve kurtarma erişimini korur, bütün verileri silme talebi sayılmaz. Cihaz hakkını serbest bırakmanız veya kurtarmanız gerekiyorsa lisans kayıtlarını kaldırmadan önce desteğe başvurun.

## Başvurular ve haklarınız

Verilerinizin işlenip işlenmediğini öğrenmek, amaç ve alıcı bilgisi istemek, uygulanabilir koşullarda düzeltme veya silme ve bunun alıcılara bildirilmesini talep etmek, yalnızca otomatik analizle aleyhinize doğan sonuçlara itiraz etmek veya hukuka aykırı işleme nedeniyle başvuru yollarınızı kullanmak için yukarıdaki özel iletişim adresine yazın. Aktivasyon kısıtlamalarının bir kişi tarafından incelenmesini de isteyebilirsiniz.

Mümkünse davet e-posta adresinizi kullanın ve talebinizi belirtin; başlangıçta tam aktivasyon kodu veya kimlik belgesi göndermeyin. Gerekiyorsa yalnızca ölçülü doğrulama bilgisi istenir. Talepler mümkün olan en kısa sürede, KVKK kapsamındaki talepler en geç 30 gün içinde yanıtlanır. Geçerli şikâyet ve diğer hukuki başvuru yollarınız saklıdır.

Değişiklikler yeni bildirim sürümüyle belirtilir. Metin değiştiğinde geçmiş kabul kayıtları yeniden yazılmaz. Yeni bir isteğe bağlı özelliği kullanmadan önce sonraki sürümle gelen bildirimi inceleyin.
