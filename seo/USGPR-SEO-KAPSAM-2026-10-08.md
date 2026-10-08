# USGPR 81 il / ilçe SEO kapsam ve uygulama planı

Tarih: 8 Ekim 2026. Durum: kaynak denetimi tamamlandı; GPR URL’leri öneridir, yayına alınmış sayfalar değildir.

## 1. Kanıt ve kapsam sınırı

İncelenen depo: https://github.com/dilekesmeryildiz/teknous
Denetim tabanı: `a104882ccdfefc971a6d4d9c7726b966355c5999` (bu belge eklenmeden önceki main).
`SITE-DIZINI.md`, 65 şehir dosyasının içerikleri, README ve depo dosya envanteri incelendi. İl eşlemesi alan adı tahmininden değil, dosyaların H1 il adlarından üretildi; Afyon alan adı Afyonkarahisar’a eşlendi. Bölge sütunu planlama gruplamasıdır; parsel jeolojisi değildir.

- Dizin: 70 benzersiz alan adı; 65 şehir + 5 marka kaynağı. 70 göreli bağlantının tamamı mevcut dosyalara karşılık geliyor.
- Şehir kapsamı: 48/81 il (%59,3); eksik 33 il (%40,7). 17 ilde ikişer kaynak var; 31 ilde birer kaynak var. Çoklu alan adı ek il kapsamı oluşturmaz.
- Mevcut metinler metal dedektörü seçimi, zemin ayarı ve saha hazırlığı odaklıdır. Ortak kontrol listesi ve sınırlar bölümü tekrar eder; ikili domainlerde yerel odak paragrafı da aynıdır. Bu, canlı sitelerin birebir kopya olduğunun kanıtı değildir.
- README’de ekipli saha çalışması, ölçüm, analiz ve raporlama modeli 8 Ekim’de zaten netleştirilmiş; yeniden yazılmasına gerek yok.
- Depo envanterinde usgpr.com.tr yayın kodu bulunmadı. Canlı domainler, FTP paketi, Search Console, trafik, arama hacmi ve saha kanıtları denetlenmedi. “Kaynak yok” yalnızca bu depodaki şehir kaynağının yokluğudur.
- GPR için 81 ilin tamamı planlama kapsamındadır; hiçbir il için mevcut usgpr.com.tr URL durumu bu denetimle doğrulanmış değildir.

## 2. 81 il kapsam matrisi

P0: Ankara pilotu. P1: özellikle belirtilen diğer eksik iller. P2: kalan eksik iller. P3: dedektör kaynağı bulunan iller. Bu sıra kaynak boşluğunu kapatma önerisidir; ölçülmüş ticari talep sıralaması değildir. Yayın önceliği her zaman içerik kanıtı ve operasyon teyidine bağlıdır. “GPR aday URL” sütununun tamamı taslaktır.

| Plaka | İl | Bölge profili | Dedektör kaynak sayısı | Mevcut kaynaklar | Kaynak durumu | Öncelik | GPR aday URL |
|---|---|---|---:|---|---|---|---|
| 01 | Adana | Akdeniz | 1 | [adanadedektor.com.tr](../sehir-kaynaklari/adanadedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/adana/` |
| 02 | Adıyaman | Güneydoğu Anadolu | 1 | [adiyamandedektor.com.tr](../sehir-kaynaklari/adiyamandedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/adiyaman/` |
| 03 | Afyonkarahisar | Ege | 1 | [afyondedektor.com.tr](../sehir-kaynaklari/afyondedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/afyonkarahisar/` |
| 04 | Ağrı | Doğu Anadolu | 0 | — | Eksik | P2 | `/bolgeler/agri/` |
| 05 | Amasya | Karadeniz | 1 | [amasyadedektor.com](../sehir-kaynaklari/amasyadedektor.com.md) | Mevcut | P3 | `/bolgeler/amasya/` |
| 06 | Ankara | İç Anadolu | 0 | — | Eksik | P0 | `/bolgeler/ankara/` |
| 07 | Antalya | Akdeniz | 1 | [antalyametaldedektor.com](../sehir-kaynaklari/antalyametaldedektor.com.md) | Mevcut | P3 | `/bolgeler/antalya/` |
| 08 | Artvin | Karadeniz | 1 | [artvindedektor.com](../sehir-kaynaklari/artvindedektor.com.md) | Mevcut | P3 | `/bolgeler/artvin/` |
| 09 | Aydın | Ege | 0 | — | Eksik | P2 | `/bolgeler/aydin/` |
| 10 | Balıkesir | Marmara | 1 | [balikesirdedektor.com.tr](../sehir-kaynaklari/balikesirdedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/balikesir/` |
| 11 | Bilecik | Marmara | 0 | — | Eksik | P2 | `/bolgeler/bilecik/` |
| 12 | Bingöl | Doğu Anadolu | 0 | — | Eksik | P2 | `/bolgeler/bingol/` |
| 13 | Bitlis | Doğu Anadolu | 0 | — | Eksik | P2 | `/bolgeler/bitlis/` |
| 14 | Bolu | Karadeniz | 0 | — | Eksik | P2 | `/bolgeler/bolu/` |
| 15 | Burdur | Akdeniz | 0 | — | Eksik | P2 | `/bolgeler/burdur/` |
| 16 | Bursa | Marmara | 1 | [bursametaldedektor.com](../sehir-kaynaklari/bursametaldedektor.com.md) | Mevcut | P3 | `/bolgeler/bursa/` |
| 17 | Çanakkale | Marmara | 1 | [canakkalededektor.com.tr](../sehir-kaynaklari/canakkalededektor.com.tr.md) | Mevcut | P3 | `/bolgeler/canakkale/` |
| 18 | Çankırı | İç Anadolu | 1 | [cankiridedektor.com](../sehir-kaynaklari/cankiridedektor.com.md) | Mevcut | P3 | `/bolgeler/cankiri/` |
| 19 | Çorum | Karadeniz | 1 | [corumdedektor.com](../sehir-kaynaklari/corumdedektor.com.md) | Mevcut | P3 | `/bolgeler/corum/` |
| 20 | Denizli | Ege | 1 | [denizlidedektor.com.tr](../sehir-kaynaklari/denizlidedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/denizli/` |
| 21 | Diyarbakır | Güneydoğu Anadolu | 0 | — | Eksik | P1 | `/bolgeler/diyarbakir/` |
| 22 | Edirne | Marmara | 1 | [edirnededektor.com.tr](../sehir-kaynaklari/edirnededektor.com.tr.md) | Mevcut | P3 | `/bolgeler/edirne/` |
| 23 | Elazığ | Doğu Anadolu | 0 | — | Eksik | P2 | `/bolgeler/elazig/` |
| 24 | Erzincan | Doğu Anadolu | 1 | [erzincandedektor.com.tr](../sehir-kaynaklari/erzincandedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/erzincan/` |
| 25 | Erzurum | Doğu Anadolu | 1 | [erzurumdedektor.com.tr](../sehir-kaynaklari/erzurumdedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/erzurum/` |
| 26 | Eskişehir | İç Anadolu | 1 | [eskisehirdedektor.com.tr](../sehir-kaynaklari/eskisehirdedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/eskisehir/` |
| 27 | Gaziantep | Güneydoğu Anadolu | 1 | [gaziantepdedektor.com](../sehir-kaynaklari/gaziantepdedektor.com.md) | Mevcut | P3 | `/bolgeler/gaziantep/` |
| 28 | Giresun | Karadeniz | 1 | [giresundedektor.com.tr](../sehir-kaynaklari/giresundedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/giresun/` |
| 29 | Gümüşhane | Karadeniz | 0 | — | Eksik | P2 | `/bolgeler/gumushane/` |
| 30 | Hakkâri | Doğu Anadolu | 0 | — | Eksik | P2 | `/bolgeler/hakkari/` |
| 31 | Hatay | Akdeniz | 0 | — | Eksik | P1 | `/bolgeler/hatay/` |
| 32 | Isparta | Akdeniz | 0 | — | Eksik | P2 | `/bolgeler/isparta/` |
| 33 | Mersin | Akdeniz | 1 | [mersindedektor.com.tr](../sehir-kaynaklari/mersindedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/mersin/` |
| 34 | İstanbul | Marmara | 2 | [istanbulmetaldedektor.com](../sehir-kaynaklari/istanbulmetaldedektor.com.md)<br>[istanbulmetaldedektor.com.tr](../sehir-kaynaklari/istanbulmetaldedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/istanbul/` |
| 35 | İzmir | Ege | 2 | [izmirdedektor.com](../sehir-kaynaklari/izmirdedektor.com.md)<br>[izmirdedektor.com.tr](../sehir-kaynaklari/izmirdedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/izmir/` |
| 36 | Kars | Doğu Anadolu | 0 | — | Eksik | P2 | `/bolgeler/kars/` |
| 37 | Kastamonu | Karadeniz | 1 | [kastamonudedektor.com.tr](../sehir-kaynaklari/kastamonudedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/kastamonu/` |
| 38 | Kayseri | İç Anadolu | 2 | [kayserimetaldedektor.com](../sehir-kaynaklari/kayserimetaldedektor.com.md)<br>[kayserimetaldedektor.com.tr](../sehir-kaynaklari/kayserimetaldedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/kayseri/` |
| 39 | Kırklareli | Marmara | 0 | — | Eksik | P2 | `/bolgeler/kirklareli/` |
| 40 | Kırşehir | İç Anadolu | 2 | [kirsehirdedektor.com](../sehir-kaynaklari/kirsehirdedektor.com.md)<br>[kirsehirdedektor.com.tr](../sehir-kaynaklari/kirsehirdedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/kirsehir/` |
| 41 | Kocaeli | Marmara | 0 | — | Eksik | P1 | `/bolgeler/kocaeli/` |
| 42 | Konya | İç Anadolu | 2 | [konyadedektor.com](../sehir-kaynaklari/konyadedektor.com.md)<br>[konyadedektor.com.tr](../sehir-kaynaklari/konyadedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/konya/` |
| 43 | Kütahya | Ege | 1 | [kutahyadedektor.com.tr](../sehir-kaynaklari/kutahyadedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/kutahya/` |
| 44 | Malatya | Doğu Anadolu | 1 | [malatyadedektor.com.tr](../sehir-kaynaklari/malatyadedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/malatya/` |
| 45 | Manisa | Ege | 1 | [manisadedektor.com.tr](../sehir-kaynaklari/manisadedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/manisa/` |
| 46 | Kahramanmaraş | Akdeniz | 0 | — | Eksik | P2 | `/bolgeler/kahramanmaras/` |
| 47 | Mardin | Güneydoğu Anadolu | 0 | — | Eksik | P2 | `/bolgeler/mardin/` |
| 48 | Muğla | Ege | 2 | [mugladedektor.com](../sehir-kaynaklari/mugladedektor.com.md)<br>[mugladedektor.com.tr](../sehir-kaynaklari/mugladedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/mugla/` |
| 49 | Muş | Doğu Anadolu | 0 | — | Eksik | P2 | `/bolgeler/mus/` |
| 50 | Nevşehir | İç Anadolu | 2 | [nevsehirdedektor.com](../sehir-kaynaklari/nevsehirdedektor.com.md)<br>[nevsehirdedektor.com.tr](../sehir-kaynaklari/nevsehirdedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/nevsehir/` |
| 51 | Niğde | İç Anadolu | 2 | [nigdededektor.com](../sehir-kaynaklari/nigdededektor.com.md)<br>[nigdededektor.com.tr](../sehir-kaynaklari/nigdededektor.com.tr.md) | Mevcut | P3 | `/bolgeler/nigde/` |
| 52 | Ordu | Karadeniz | 2 | [ordumetaldedektor.com](../sehir-kaynaklari/ordumetaldedektor.com.md)<br>[ordumetaldedektor.com.tr](../sehir-kaynaklari/ordumetaldedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/ordu/` |
| 53 | Rize | Karadeniz | 2 | [rizededektor.com](../sehir-kaynaklari/rizededektor.com.md)<br>[rizededektor.com.tr](../sehir-kaynaklari/rizededektor.com.tr.md) | Mevcut | P3 | `/bolgeler/rize/` |
| 54 | Sakarya | Marmara | 0 | — | Eksik | P2 | `/bolgeler/sakarya/` |
| 55 | Samsun | Karadeniz | 1 | [samsundedektor.com](../sehir-kaynaklari/samsundedektor.com.md) | Mevcut | P3 | `/bolgeler/samsun/` |
| 56 | Siirt | Güneydoğu Anadolu | 0 | — | Eksik | P2 | `/bolgeler/siirt/` |
| 57 | Sinop | Karadeniz | 2 | [sinopdedektor.com](../sehir-kaynaklari/sinopdedektor.com.md)<br>[sinopdedektor.com.tr](../sehir-kaynaklari/sinopdedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/sinop/` |
| 58 | Sivas | İç Anadolu | 2 | [sivasdedektor.com](../sehir-kaynaklari/sivasdedektor.com.md)<br>[sivasdedektor.com.tr](../sehir-kaynaklari/sivasdedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/sivas/` |
| 59 | Tekirdağ | Marmara | 1 | [tekirdagdedektor.com](../sehir-kaynaklari/tekirdagdedektor.com.md) | Mevcut | P3 | `/bolgeler/tekirdag/` |
| 60 | Tokat | Karadeniz | 1 | [tokatdedektor.com](../sehir-kaynaklari/tokatdedektor.com.md) | Mevcut | P3 | `/bolgeler/tokat/` |
| 61 | Trabzon | Karadeniz | 2 | [trabzonmetaldedektor.com](../sehir-kaynaklari/trabzonmetaldedektor.com.md)<br>[trabzonmetaldedektor.com.tr](../sehir-kaynaklari/trabzonmetaldedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/trabzon/` |
| 62 | Tunceli | Doğu Anadolu | 0 | — | Eksik | P2 | `/bolgeler/tunceli/` |
| 63 | Şanlıurfa | Güneydoğu Anadolu | 0 | — | Eksik | P2 | `/bolgeler/sanliurfa/` |
| 64 | Uşak | Ege | 0 | — | Eksik | P2 | `/bolgeler/usak/` |
| 65 | Van | Doğu Anadolu | 0 | — | Eksik | P1 | `/bolgeler/van/` |
| 66 | Yozgat | İç Anadolu | 2 | [yozgatdedektor.com](../sehir-kaynaklari/yozgatdedektor.com.md)<br>[yozgatdedektor.com.tr](../sehir-kaynaklari/yozgatdedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/yozgat/` |
| 67 | Zonguldak | Karadeniz | 1 | [zonguldakdedektor.com.tr](../sehir-kaynaklari/zonguldakdedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/zonguldak/` |
| 68 | Aksaray | İç Anadolu | 1 | [aksaraydedektor.com.tr](../sehir-kaynaklari/aksaraydedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/aksaray/` |
| 69 | Bayburt | Karadeniz | 0 | — | Eksik | P2 | `/bolgeler/bayburt/` |
| 70 | Karaman | İç Anadolu | 2 | [karamandedektor.com](../sehir-kaynaklari/karamandedektor.com.md)<br>[karamandedektor.com.tr](../sehir-kaynaklari/karamandedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/karaman/` |
| 71 | Kırıkkale | İç Anadolu | 2 | [kirikkalededektor.com](../sehir-kaynaklari/kirikkalededektor.com.md)<br>[kirikkalededektor.com.tr](../sehir-kaynaklari/kirikkalededektor.com.tr.md) | Mevcut | P3 | `/bolgeler/kirikkale/` |
| 72 | Batman | Güneydoğu Anadolu | 0 | — | Eksik | P2 | `/bolgeler/batman/` |
| 73 | Şırnak | Güneydoğu Anadolu | 0 | — | Eksik | P2 | `/bolgeler/sirnak/` |
| 74 | Bartın | Karadeniz | 1 | [bartindedektor.com](../sehir-kaynaklari/bartindedektor.com.md) | Mevcut | P3 | `/bolgeler/bartin/` |
| 75 | Ardahan | Doğu Anadolu | 0 | — | Eksik | P2 | `/bolgeler/ardahan/` |
| 76 | Iğdır | Doğu Anadolu | 0 | — | Eksik | P2 | `/bolgeler/igdir/` |
| 77 | Yalova | Marmara | 2 | [yalovadedektor.com](../sehir-kaynaklari/yalovadedektor.com.md)<br>[yalovadedektor.com.tr](../sehir-kaynaklari/yalovadedektor.com.tr.md) | Mevcut | P3 | `/bolgeler/yalova/` |
| 78 | Karabük | Karadeniz | 1 | [karabukdedektor.com](../sehir-kaynaklari/karabukdedektor.com.md) | Mevcut | P3 | `/bolgeler/karabuk/` |
| 79 | Kilis | Güneydoğu Anadolu | 0 | — | Eksik | P1 | `/bolgeler/kilis/` |
| 80 | Osmaniye | Akdeniz | 0 | — | Eksik | P2 | `/bolgeler/osmaniye/` |
| 81 | Düzce | Karadeniz | 1 | [duzcededektor.com.tr](../sehir-kaynaklari/duzcededektor.com.tr.md) | Mevcut | P3 | `/bolgeler/duzce/` |

Eksik iller: **Ağrı, Ankara, Aydın, Bilecik, Bingöl, Bitlis, Bolu, Burdur, Diyarbakır, Elazığ, Gümüşhane, Hakkâri, Hatay, Isparta, Kars, Kırklareli, Kocaeli, Kahramanmaraş, Mardin, Muş, Sakarya, Siirt, Tunceli, Şanlıurfa, Uşak, Van, Bayburt, Batman, Şırnak, Ardahan, Iğdır, Kilis, Osmaniye**.

## 3. Dedektör ve GPR kapsamlarını ayırma

Dedektör kaynakları `sehir-kaynaklari/` ve `marka-kaynaklari/` altında kalır. GPR planı `seo/` altında tutulur; GPR yayın kodu bulunduğunda onun gerçek içerik modeline uygulanır. Yeni domain icat edilmez; eksik ili kapatmak için domain satın alma önerilmez. Marka kaynakları: deepdedektor.com, garrettdedektor.com.tr, minelabdedektor.com.tr, usdedektor.com.tr, xpdedektor.com.tr. Bunlar 81 il kapsamına dahil değildir ve GPR hizmet kanıtı olarak kullanılmaz.

Dedektör kullanıcı sinyali, metal türü ve mineralizasyon anlatımını radar sonucuna çevirmeyin. Depodaki Çanakkale haberinin varlığı bir içerik kaydıdır; ölçüm dosyası ve yayın izni doğrulanmadan usgpr.com.tr’de yeni vaka kanıtı olarak çoğaltmayın. Domain ağı üzerinden site geneli anahtar kelimeli bağlantı veya otomatik yönlendirme kurmayın. Gerçekten ilgili içerik varsa bağlam içinde sınırlı bağlantı verin; farklı ürün/hizmet sayfalarını sırf SEO için GPR ana sayfasına 301 yönlendirmeyin.

## 4. URL ve arama niyeti mimarisi

| Sayfa | Önerilen URL | Niyet ve içerik görevi | Açılma koşulu |
|---|---|---|---|
| Ulusal GPR hizmeti | `/hizmetler/gpr-radar/` | Yöntem, uygunluk, veri toplama, analiz, teslim kapsamı | Gerçek hizmet kapsamı teknik ekipçe teyitli |
| Altyapı inceleme | `/hizmetler/altyapi-inceleme/` | Hat/tesisat inceleme talebi; ölçüm sınırları ve doğrulama ihtiyacı | Kullanılan yöntem ve teslim çıktıları teyitli |
| Boşluk/anomali inceleme | `/hizmetler/bosluk-anomali-inceleme/` | Olası boşluk/dolgu farkı araştırması; kesin sınıflandırma vaadi yok | Teknik kapsam ve yöntem teyitli |
| Bölge dizini | `/bolgeler/` | İl seçimi, operasyonun nasıl planlandığı | Yalnızca hazır sayfalara link; kapsam hedefi ile aktif hizmet ayrımı |
| İl merkezi | `/bolgeler/{il}/` | “{il} jeoradar / GPR radar / ekipli yeraltı görüntüleme” | Yerel fayda ve operasyon bilgisi tamam |
| İlçe | `/bolgeler/{il}/{ilce}/` | “{ilçe} GPR ölçüm / ekipli saha hizmeti” | İl sayfasından farklı, karar verdiren yerel içerik |
| Bilgi rehberi | `/rehber/gpr-olcum-oncesi-hazirlik/` | Bilgi araması, teklif için gerekli saha verileri | Teknik inceleme tamam |
| Teklif | `/teklif/` | Alan, hedef, konum ve teslim beklentisi toplama | Çalışan form ve gerçek iletişim bilgileri |

“Jeoradar kiralama” niyetini il sayfasındaki açıklama ve SSS ile karşılayın: cihaz bağımsız teslim edilmez; ekipli ölçüm, analiz ve raporlama teklifi değerlendirilir. Aynı il için radar/jeoradar/yeraltı görüntüleme/kiralama eşanlamlılarının her birine ayrı kopya sayfa açmayın. “Zemin etüdü” ifadesini kapsamı teyit edilmeden tam zemin etüdü hizmeti gibi sunmayın; GPR incelemesiyle eşitlemeyin. Cihaz satış niyeti doğrulanırsa ayrı ürün mimarisi kurun; saha hizmetine karıştırmayın.

## 5. İl ve ilçe içerik şablonu

İl Title: `{İl} GPR Radar ve Ekipli Yeraltı İnceleme | USGPR`. H1: `{İl} için GPR radar saha inceleme planlaması`. Bunlar editoryal taslaktır; hizmet uygunluğu teyit edilmeden yayınlanmaz.

Sıra: (1) müşteri ihtiyacı ve kapsam; (2) bu il için doğrulanmış planlama bilgisi; (3) alan/yüzey/hedefe göre yöntem uygunluğunun nasıl değerlendirildiği; (4) ekipli ölçüm → analiz → raporlama; (5) gerçek teslim listesi; (6) ilçelere erişim; (7) yerel sorular ve belirsizlikler; (8) teklif formu.

İlçede H1 ve Title ilçe + il adı içerir. Genel yöntem açıklaması kısa tutulup ana hizmete bağlanır. İlçe sayfasının özgün çekirdeği: doğrulanmış erişim/çalışma kısıtları, talep türüne özel ön hazırlık, teyitli planlama koşulları ve varsa izinli gerçek proje verisi. Tarihi/turistik paragraf veya ilçe adını değiştirmek yeterli değildir. İlçede ayrı içerik yoksa il sayfasında bölüm olarak karşılayın; URL üretmeyin.

Her sayfa için editörün dolduracağı özgün veri alanları:

| Alan | Gerekli kanıt | Eksikse davranış |
|---|---|---|
| Operasyon uygunluğu | Ekip teyidi, tarih, kapsam | Taslakta tut; aynı gün/24 saat hizmet yazma |
| Yerel çalışma kısıtları | İlgili alan belgesi veya müşteri/ekip teyidi | Genel kontrol sorusu yaz; yerel gerçeği icat etme |
| Yüzey/zemin bilgisi | Projeye ait gözlem veya kaynaklı yerel veri | Tüm ile tek zemin türü atama |
| Teslim çıktısı | Onaylı örnek rapor/iş kapsamı | Kesit, 3D, koordinat, CAD/PDF teslimini varsayma |
| Fiyat/termin | Geçerli fiyatlandırma ve operasyon teyidi | Alan, yüzey, hedef ve ulaşım bilgisiyle teklif iste |
| Vaka/fotoğraf | Ölçüm kaydı, tarih, izin ve yöntem | Vaka bölümü çıkar; temsili görseli saha fotoğrafı diye sunma |
| Yerel SSS | Gerçek müşteri sorusu veya açıkça editoryal soru | Yanıtı teknik ekip teyit etsin |

Parsel hakkında olmayan bölgesel jeoloji bilgisi ölçüm sonucu yerine geçmez. Performans, derinlik, hedef/malzeme teşhisi ve başarı oranı uydurulmaz; rapor bulgusu ile yorum ve belirsizlik ayrılır.

## 6. Yedi bölge için içerik geliştirme profili

Aşağıdaki niyetler araştırma hipotezidir; talep hacmi veya gerçekleşmiş hizmet değildir. Her il satırı matristeki bölge profiliyle bu gereksinimleri devralır; yerel teyit sonucu değiştirilir.

| Bölge | Araştırılacak niyet ve sayfa bölümü | Özgün veri gereksinimi | İç bağlantı | Tekrar riski ve çözüm |
|---|---|---|---|---|
| Marmara | Altyapı, tesis/şantiye inceleme; erişim ve çalışma alanı bölümü | Gerçek alan kısıtları, yüzey ve çalışma penceresi | İl → ilgili altyapı hizmeti; hazır ilçeler → il | Her ile aynı “sanayi” paragrafı yazma; gerçek proje ihtiyacıyla ayır |
| Ege | Altyapı/yeraltı anomali talebi; saha hazırlığı bölümü | Alan yüzeyi ve varsa kaynaklı yerel koşullar | İl → hazırlık rehberi ve uygun hizmet | Kıyı/tuz metnini tüm ilçelere kopyalama |
| Akdeniz | Yapı/altyapı inceleme; hedef ve yöntem uygunluğu | Sahaya özgü yüzey, erişim ve teknik değerlendirme | İl → GPR yöntemi ve ilgili hizmet | Karst/boşluk/depreme ilişkin yerel teşhis üretme |
| İç Anadolu | Ekipli ölçüm ve teklif; mobilizasyon bölümü | Gerçek ekip planı, ulaşım ve teslim koşulları | Ankara pilotu → hizmet/teklif; ilçe → il | “Ankara’dan her yere aynı gün” varsayımı yapma |
| Karadeniz | Saha erişimi ve veri toplama planı | Gerçek yüzey, erişim, ölçüm zamanı koşulları | İl → hazırlık rehberi; yalnız hazır ilçe | Her ilçeyi ıslak/killi sayma; veri yoksa soru formatı kullan |
| Doğu Anadolu | Proje uygunluğu ve ekip organizasyonu | Teyitli ulaşım, zamanlama ve saha bilgisi | İl → yöntem, teklif, ilçe | İklimden cihaz performansı veya hizmet süresi çıkarmama |
| Güneydoğu Anadolu | Altyapı/şantiye inceleme ve rapor talebi | Hedef, erişim, ekip planı, teyitli çıktı | İl → ilgili hizmet/rapor açıklaması | Bütün illere aynı şantiye/vaka anlatımı yazma |

## 7. Eksik iller ve ilçe yayın sırası

1. **P0 Ankara:** İlk il sayfasını hazırlayın. Çankaya, Yenimahalle, Keçiören, Etimesgut ve Sincan içerik araştırması için ilk adaylardır; talep ve operasyon verisi görülmeden en yüksek hacimli ilçeler olarak sunulmaz. Diğer Ankara ilçeleri aynı veri modeline kaydedilir.
2. **P1 Kocaeli, Diyarbakır, Hatay, Van, Kilis:** İl sayfalarının veri kartlarını hazırlayın. İlk ilçe araştırma adayları sırasıyla İzmit/Gebze; Kayapınar/Bağlar; Antakya/İskenderun; İpekyolu/Tuşba; Merkez/Elbeyli. İlçe listeleri yayın öncesinde güncel resmî idari kaynaktan doğrulanır. Bunlar hizmet gerçekleşmişliği veya talep sıralaması değildir.
3. **P2 diğer 27 eksik il:** Matriste P2 olan her il için veri kartı; teyitli talep ve içerik hazır olma durumuna göre yayın. Kaynak boşluğu ilçe sayfalarını otomatik yayımlama nedeni değildir.
4. **P3 mevcut 48 il:** Dedektör kaynaklarını GPR sayfası kabul etmeyin. GPR veri kartlarını ayrı hazırlayın; gerçek talep/kanıt varsa P2’den önce yayınlanabilir.

81 il ve tüm ilçeler veri kapsamı hedefidir, otomatik indexlenebilir sayfa sayısı hedefi değildir. Güncel resmî il/ilçe envanteri edinilmeden toplam ilçe sayısı sabitlenmez veya tam liste uydurulmaz. Envanterde her ilçe draft/ready/published/merged durumuyla izlenir; içeriksiz ilçeler il sayfasına bağlı kayıt olarak kalır.

## 8. Geliştirici için veri ve yayın kapısı

Yayın kodunun gerçek deposu belirlenince örnek kayıt bu şemaya uyarlanır:

```json
{
  "province_code": "06",
  "province": "Ankara",
  "province_slug": "ankara",
  "district": null,
  "district_slug": null,
  "existing_detector_sources": [],
  "gpr_url": "/bolgeler/ankara/",
  "status": "draft",
  "operation_confirmed": false,
  "operation_checked_at": null,
  "intent_hypothesis": "ekipli GPR saha inceleme",
  "local_content": null,
  "evidence": [],
  "approved_deliverables": [],
  "reviewer": null,
  "reviewed_at": null
}
```

Kanıt kaydı: id, tür, kaynak URL/belge, doğrulama tarihi, kapsam, yayın izni. Özel müşteri bilgileri bu kamuya açık depoya konmaz; izinli özet veya kurum içi referans kullanılır.

Yayın kuralı: geçerli idari eşleme + operasyon teyidi + karar verdiren özgün yerel içerik + teknik editör onayı + çalışan teklif akışı. Eksikse public URL oluşturma. Önizleme gerekiyorsa erişimi sınırla; herkese açık taslağa noindex uygula ve sitemap’e alma. robots.txt ile engellenen bir URL’nin noindex etiketi tarayıcı tarafından görülemeyebilir.

Tekrarlılık kontrolü: şablon başlık/footer ve ortak süreç metni ayrılarak ana içerik karşılaştırılır. Kelime 5-gram Jaccard benzerliği ≥0,80 editör inceleme işareti olarak kullanılabilir; bu bir Google eşiği değildir. Yer adlarını çıkardıktan sonra aynı kalan içerik manuel kontrol edilir. Eşanlamlı değişimi çözüm değildir; yeni yerel bilgi ekle veya sayfayı birleştir.

## 9. İç bağlantı ve teknik SEO

- Ana menüden ulusal hizmete ve `/bolgeler/` dizinine; dizinden hazır illere; ilden hazır ilçelere; ilçeden üst il ve gerçekten ilgili hizmete bağlantı. Breadcrumb: Ana sayfa → Bölgeler → İl → İlçe.
- 81 il × tüm ilçeler bağlantısını her sayfanın footer’ına ekleme. Yayınlanmamış URL’lere link verme. İller arası link yalnız kullanıcıya anlamlı ilişki varsa verilir.
- Her özgün yayımlanmış sayfa 200 ve self-canonical; HTTPS/host/trailing slash tek biçim; eski eşdeğer URL varsa birebir 301. Aynı isimli ilçeler il slug’ıyla ayrılır. Türkçe karakter dönüşümü ve URL çakışmaları kontrol edilir.
- İlçe kopyaysa canonical ile kalite sorununu gizleme. İçeriği il bölümüne birleştir; mevcut eşdeğer ilçe URL’si varsa ilgili il/bölüme uygun yönlendirme planla. Boş URL’leri soft-404 üretmeden kaldır.
- Sitemap yalnız canonical, indexlenebilir 200 URL’leri içerir; `lastmod` gerçek içerik değişimidir. İl ve ilçe sitemap’leri gerektiğinde ayrılır; taslak, noindex ve redirect URL bulunmaz.
- Sunucuda üretilmiş/statik HTML, taranabilir `a href`, mobil okunabilirlik, optimize görsel boyutları. Gerçek ölçümle LCP/INP/CLS takip edilir; “0 ms” yüklenme veya hızdan sıralama garantisi yazılmaz.
- `Organization`, doğrulanmış `Service` ve `BreadcrumbList` verileri görünen içerikle uyumlu tutulur. İl/ilçe sayfasına sahte şube, adres, LocalBusiness, puan veya yorum eklenmez. İlçe için hreflang kullanılmaz; bu plan tek dilde Türkiye şehir sayfaları içindir.

## 10. Uygulama işleri ve kabul ölçütleri

| Sıra | İş | Sorumlu rol | Çıktı / kabul |
|---|---|---|---|
| 1 | usgpr.com.tr gerçek yayın deposu/CMS, mevcut URL ve yönlendirmeleri belirle | Geliştirici | URL envanteri; çakışmayan rota planı |
| 2 | Güncel resmî ilçe envanteri ve kaynak tarihini kaydet | İçerik/veri editörü | 81 il eşlemesi; her ilçe benzersiz il+ilçe kimliği |
| 3 | Ankara ve P1 veri kartlarını doldur | Operasyon + teknik ekip | Operasyon, özgün yerel bilgi ve çıktı teyidi |
| 4 | Ulusal hizmet, bölge dizini ve Ankara pilotunu uygula | İçerik + geliştirici | Taslak onayı; kırık link ve uydurma iddia yok |
| 5 | İçerik kapısından geçen ilçeleri ekle | Editör | Her ilçede farklı karar verdiren içerik |
| 6 | Kanıt ve talebe göre kalan il/ilçe kayıtlarını sıraya koy | SEO + operasyon | P2/P3 backlog; indekslenebilirlik ayrı izlenir |
| 7 | Search Console ve teklif dönüşüm ölçümünü kur/incele | SEO + geliştirici | Sorgu/sayfa ve nitelikli talep verisi |

Kontrol: matris 81 benzersiz il; kaynak sayısı 65; mevcut il 48; eksik 33; 5 marka ayrı; domain ve link eşleşmesi tam. Yayın öncesi: mobil kontrol, doğru title/H1/canonical, HTTP ve redirect kontrolü, sitemap, şema doğruluğu, form testi ve teknik iddia incelemesi.

İlk 28 günlük ölçüm baz çizgisini kaydedin; sonraki dönemi aynı uzunlukla karşılaştırın. İl/ilçe ve niyet bazında gösterim, tıklama, CTR, indeks durumu, nitelikli teklif ve iş dönüşümünü izleyin. Sıralama tek başarı ölçütü değildir; birinci sıra garantisi yoktur. Benzer sayfalar aynı sorguda yarışıyorsa niyetleri birleştirin; içeriksiz yayını artırmayın. Arama hacmi ve gerçek teklif verisi geldikten sonra backlog önceliğini güncelleyin.

## 11. Bu depoda yapılacak değişiklikler

Bu belge `seo/USGPR-SEO-KAPSAM-2026-10-08.md` olarak eklenir. Dedektör kaynakları ve SITE-DIZINI’nin 70 alan adı listesi değiştirilmez; GPR URL adayları domain listesine karıştırılmaz. İsteğe bağlı sonraki dokümantasyon işi: SITE-DIZINI’ye “65 şehir kaynağı 48 ili temsil eder; canlı yayın durumu bu dizinle doğrulanmaz” notu ve bu plana bağlantı eklemek. Bu belge bir yayın kodu veya canlı site değişikliği değildir.

## 12. Referanslar

- Depo kaynak dizini: https://github.com/dilekesmeryildiz/teknous/blob/a104882ccdfefc971a6d4d9c7726b966355c5999/SITE-DIZINI.md
- Şehir kaynakları: https://github.com/dilekesmeryildiz/teknous/tree/a104882ccdfefc971a6d4d9c7726b966355c5999/sehir-kaynaklari
- Hizmet modeli: https://github.com/dilekesmeryildiz/teknous/blob/a104882ccdfefc971a6d4d9c7726b966355c5999/README.md
- Google spam politikaları (doorway ve scaled content): https://developers.google.com/search/docs/essentials/spam-policies
- Canonical açıklaması: https://developers.google.com/search/docs/crawling-indexing/canonicalization

Google politikalarından çıkarılan uygulama kararı: yalnız şehir adını değiştirerek çok sayıda benzer giriş sayfası üretmek yerine faydalı, gezilebilir hiyerarşi ve özgün yerel içerik kapısı kullanmak. Canonical, Google’a tercihi bildirir; farklı özgün sayfaların veya zayıf içeriğin yerine geçmez.
