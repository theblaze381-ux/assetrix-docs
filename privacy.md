# Assetrix Gizlilik Politikası

**Son güncelleme:** 23 Mayıs 2026
**Geçerlilik tarihi:** Uygulama yayımlandığı tarih

---

## 1. Genel Bilgiler

Assetrix uygulamasını ("**Uygulama**", "**Assetrix**") **NUKAI LABS FZ-LLC** ("**Şirket**", "**biz**", "**bize**") işletmektedir. Bu Gizlilik Politikası, Uygulamayı kullanırken hangi kişisel verilerinizi topladığımızı, neden işlediğimizi, kimlerle paylaştığımızı ve haklarınızı açıklar.

**Veri Sorumlusu**
- Şirket Adı: NUKAI LABS FZ-LLC
- Tür: Free Zone Limited Liability Company (Birleşik Arap Emirlikleri)
- İletişim e-posta: **assetrixtr@gmail.com**

Bu politika **6698 sayılı Kişisel Verilerin Korunması Kanunu (KVKK)** kapsamında, Türkiye Cumhuriyeti'nde ikamet eden kullanıcılarımız için hazırlanmıştır.

---

## 2. Topladığımız Veriler

Uygulamayı kullandığınızda aşağıdaki kategorilerde veri işliyoruz:

### 2.1 Anonim Kimlik Bilgisi (Tüm Kullanıcılar)
- Anonim kullanıcı tanımlayıcısı (UID — sizi şahsen tanımlamaz)
- Cihaz dili, tema tercihi, para birimi tercihi
- Uygulama versiyonu

### 2.2 Hesap Bilgileri (Yalnızca Google ile Giriş Yaparsanız — İsteğe Bağlı)
- E-posta adresi
- Ad-soyad
- Google profil fotoğrafı URL'si

Google ile giriş yapmadığınız sürece Uygulama tamamen anonim çalışır.

### 2.3 Finansal İçerik (Sizin Girdiğiniz Veri)
Aşağıdaki verileri Uygulamaya **siz girersiniz**:
- Portföy bilgileri: hisse senedi, kripto para, döviz, emtia pozisyonları
- Banka hesabı ve nakit bakiyeleri
- Vadeli mevduat bilgileri
- Borç ve alacak kayıtları
- Mal varlığı bilgileri
- İşlem geçmişiniz ve net varlık değişimi

Bu veriler **hassas finansal bilgilerdir**. Sizinle ilişkilendirilmiş olarak güvenli sunucularımızda saklanır.

### 2.4 Yapay Zeka Sorgu Verisi
AI özelliğini kullandığınızda:
- Portföyünüzün anlık görüntüsü (snapshot)
- Sorduğunuz soru metni
- AI'nın cevabı (yalnızca size dönmek için, kayıt edilmez)

AI sorgularınız **kalıcı olarak saklanmaz**. Yalnızca işleme süresince geçici olarak Cloudflare Worker üzerinden Google Gemini API'sine iletilir, cevap döner döner silinir.

### 2.5 Abonelik ve Kullanım Verisi
- Aylık AI sorgu sayısı (rate limit için)
- Abonelik durumu (Premium / Trial)
- Satın alma token'ı (RevenueCat üzerinden)

### 2.6 Toplamadığımız Veriler
Aşağıdakileri **kesinlikle toplamıyoruz**:
- Konum bilgisi (GPS)
- Reklam tanımlayıcıları (ADID/IDFA)
- Telefon rehberi
- Fotoğraf galerisi
- Mikrofon, kamera, sensör verisi
- Cihaz IMEI veya seri numarası
- Üçüncü taraf analitik verisi (Mixpanel, Amplitude, vb. **kullanmıyoruz**)
- Kullanım analizi / heatmap

---

## 3. Verilerin Kullanım Amaçları

Verilerinizi yalnızca aşağıdaki amaçlar için işliyoruz:

1. **Hizmet sunumu**: Portföy hesaplama, görüntüleme, raporlama
2. **Cihazlar arası senkronizasyon**: Birden fazla cihazda aynı veriyi görmeniz
3. **Yapay zeka analizi**: Portföyünüze ilişkin AI yorumları sunma
4. **Abonelik yönetimi**: Premium üyeliğin doğrulanması ve takibi
5. **Güvenlik**: Kötüye kullanım tespiti, rate limiting
6. **Yasal yükümlülükler**: Vergi, ticari kayıt yükümlülükleri

Verilerinizi **hiçbir koşulda reklam amacıyla kullanmaz, üçüncü taraflara satmaz veya kiralamayız**.

---

## 4. Hukuki Dayanak (KVKK Madde 5)

| Veri Türü | Hukuki Sebep |
|---|---|
| Anonim kimlik + temel ayarlar | Sözleşmenin ifası |
| Google hesap bilgisi | Açık rıza |
| Finansal veri | Sözleşmenin ifası |
| AI sorgu içeriği | Sözleşmenin ifası |
| Abonelik verisi | Sözleşmenin ifası, hukuki yükümlülük |

---

## 5. Üçüncü Taraf Hizmet Sağlayıcılar

Hizmetimizi sunmak için aşağıdaki **veri işleyicilerle** çalışırız:

| Hizmet Sağlayıcı | Amaç | Verinin Türü | Sunucu Konumu |
|---|---|---|---|
| **Google Firebase** | Kimlik doğrulama + veri senkronizasyonu | UID, e-posta (opsiyonel), tüm portföy verisi | İrlanda (europe-west3) |
| **Cloudflare** | API trafiği, rate limiting | Anonim UID, AI sorgu metni | Küresel edge ağı |
| **Google Gemini API** | Yapay zeka analizi | Portföy anlık görüntüsü, soru metni | ABD / AB |
| **RevenueCat** | Abonelik yönetimi | Anonim UID, satın alma token'ı | ABD |
| **Google Play Billing** | Ödeme işlemi | Ödeme bilgisi (bize iletilmez) | Küresel |

Her hizmet sağlayıcı, kendi gizlilik politikalarına ve veri güvenlik standartlarına tabidir.

---

## 6. Yurtdışı Veri Aktarımı (KVKK Madde 9)

Verileriniz hizmet sağlayıcılarımız aracılığıyla **Türkiye dışına aktarılmaktadır**:

- **AB (İrlanda)**: Firebase europe-west3 bölgesi
- **ABD**: Gemini API, RevenueCat
- **Küresel edge**: Cloudflare

Bu aktarımlar **Uygulamanın çalışması için zorunludur**. Aktarımlarda:
- Standart sözleşme hükümleri (SCC) uygulanır
- Hizmet sağlayıcılar uluslararası güvenlik standartlarına (ISO 27001, SOC 2) uyumludur
- Tüm veri iletimi HTTPS/TLS ile şifrelenir

Uygulamayı kullanmaya başlamanızla bu aktarımlara **açık rıza** vermiş sayılırsınız. Rızanızı her zaman geri çekebilirsiniz; bu durumda hesabınız silinir ve Uygulamayı kullanmaya devam edemezsiniz.

---

## 7. Saklama Süreleri

| Veri Türü | Saklama Süresi |
|---|---|
| Anonim kullanıcı verisi | Hesap silinene kadar veya 2 yıl atıl kalma sonrası |
| Google ile bağlanan hesap bilgisi | Hesap silinene kadar |
| Finansal portföy verisi | Hesap silinene kadar |
| Abonelik ve ödeme kayıtları | Vergi mevzuatı gereği **10 yıl** |
| AI sorgu metinleri | **Saklanmaz** (anlık işlenir) |
| Rate limit sayaçları | 30 gün |

Saklama süresi sona erdiğinde veriler kalıcı olarak silinir veya anonimleştirilir.

---

## 8. Haklarınız (KVKK Madde 11)

**6698 sayılı Kanun'un 11. maddesi** uyarınca aşağıdaki haklara sahipsiniz:

1. Kişisel verilerinizin işlenip işlenmediğini öğrenme
2. İşlenmişse buna ilişkin bilgi talep etme
3. İşlenme amacını ve uygun kullanılıp kullanılmadığını öğrenme
4. Yurtiçinde/yurtdışında aktarıldığı üçüncü kişileri öğrenme
5. Eksik veya yanlış işlenmişse düzeltilmesini isteme
6. KVKK Madde 7 uyarınca silinmesini veya yok edilmesini isteme
7. Düzeltme/silme işleminin üçüncü kişilere bildirilmesini isteme
8. Otomatik sistemlerle analiz sonucu aleyhinize doğan sonuca itiraz etme
9. Hukuka aykırı işleme sebebiyle zarara uğramanız halinde zararın giderilmesini talep etme

**Hak talepleriniz için**: assetrixtr@gmail.com

Talepleriniz **30 gün içinde** ücretsiz olarak yanıtlanır.

---

## 9. Güvenlik Önlemleri

Verilerinizin güvenliği için aldığımız teknik ve idari tedbirler:

- **Tüm trafik HTTPS/TLS şifrelemesi** ile iletilir
- **Firestore Security Rules**: `/users/{uid}/` yoluna yalnızca kendi UID'sine sahip kullanıcı erişebilir
- **API anahtarları sunucu tarafında** (Cloudflare Worker secret olarak şifrelenmiş) saklanır, asla uygulamaya gömülmez
- **App Lock** özelliği ile uygulama düzeyinde Face ID/Parmak İzi/PIN koruması
- **Rate limiting**: kötüye kullanımın önlenmesi için sorgu limiti uygulanır
- **Düzenli güvenlik incelemeleri** ve güncelleme yamaları

---

## 10. Çocukların Gizliliği

Bu Uygulama **18 yaş altı kullanıcılara yönelik değildir**.

Bilerek 18 yaş altı kullanıcılardan veri toplamayız. 18 yaş altı bir kullanıcının verilerini topladığımızı tespit edersek, hesabı derhal kapatır ve verileri sileriz. Bu durumu fark eden ebeveynler bize ulaşabilir: assetrixtr@gmail.com.

---

## 11. Çerez ve Takip Teknolojileri

Assetrix bir mobil uygulamadır:
- **Web çerezi kullanmıyoruz**
- **Reklam tanımlayıcısı (ADID/IDFA) toplamıyoruz**
- **Üçüncü taraf takip pikseli yok**
- Yalnızca uygulamanın çalışması için zorunlu olan yerel depolama (AsyncStorage) kullanılır

---

## 12. Hesap Silme ve Veri Kaldırma

Hesabınızı ve tüm verilerinizi silmek için iki yol:

1. **Uygulama içinden**: Ayarlar → Hesap → Hesabımı Sil
2. **E-posta ile**: assetrixtr@gmail.com adresine "Hesap silme talebi" konulu e-posta göndererek

Hesap silme talebi **7 iş günü içinde** işleme alınır. Yasal saklama yükümlülüğü olan veriler (abonelik kayıtları gibi) ilgili yasal süreler sonunda silinir; diğer tüm veriler derhal kalıcı olarak silinir.

---

## 13. Politika Değişiklikleri

Bu Gizlilik Politikası zaman zaman güncellenebilir:
- Önemli değişiklikler uygulama içi bildirim ile duyurulur
- Bu sayfanın üst kısmındaki **"Son güncelleme"** tarihi yenilenir
- Esaslı değişikliklerde gerekirse yeniden açık rıza istenir

---

## 14. Şikayet ve Başvuru

Veri işleme faaliyetlerimizden memnun değilseniz veya KVKK haklarınızdan birini kullanmak istiyorsanız:

**1. Adım**: Bize doğrudan ulaşın → **assetrixtr@gmail.com** (30 gün içinde yanıt)

**2. Adım**: Çözüm bulunamazsa Türkiye Cumhuriyeti **Kişisel Verileri Koruma Kurulu**'na başvurabilirsiniz:
- Web: [www.kvkk.gov.tr](https://www.kvkk.gov.tr)
- KEP: kvkk@hs01.kep.tr

---

## 15. İletişim

Bu Gizlilik Politikası ile ilgili her türlü soru, talep veya geribildiriminiz için:

**NUKAI LABS FZ-LLC**
E-posta: **assetrixtr@gmail.com**

Talebinizin daha hızlı işleme alınması için e-posta konusuna "**KVKK Talebi - [konu]**" yazmanızı rica ederiz.

---

*Bu Gizlilik Politikası, 6698 sayılı Kişisel Verilerin Korunması Kanunu (KVKK) ve ilgili ikincil mevzuat hükümlerine uygun olarak hazırlanmıştır.*
