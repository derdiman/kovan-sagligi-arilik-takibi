# Kovan Sağlığı ve Arılık Takibi

**Türkçe skill · Sürüm 1.3.0**

Kovan başında arıcının gördüklerini anlamasına, bakım ve takip işlerini belirlemesine ve bütün arılığın tarihli kayıtlarını tutmasına yardımcı olur. Telefon kullanımı ve kısa sesli konuşma düşünülerek hazırlanmıştır.

## Başlama örneği

“Arılıktayım, kovanları kontrol edeceğiz.”

Önce bulunduğun yer ve kovan kimliği öğrenilir. İlk kayıtta ana ırkı ve yılı, takılı ve yoğun arılı çıta sayıları, ahşap/kompozit/strafor gibi gövde malzemesi ve polen tuzağı bilgisi birlikte sorulur. Sonraki kontrollerde kayıtlı bilgiler kullanılır, değişiklikler ve bugünkü bulgular eklenir. Arıcıya kısa bir bakış planı söylenir; uygun havada kontrolünü yapıp gördüklerini anlatır. Fotoğraf çekemiyorsa kısa cevaplarla devam eder. Acil bir durum bildirirse önce gerekli yönlendirme gelir.

## 1.3.0 güncellemesi

Oğul ve bölmede arıcının kabul edeceği yeni numara önerisi, kaynak koloni bağlantısı ve ana kökeni eklendi. İkinci ve sonraki karşılaştırılabilir kontrollerde gelişim, sayı/yüzde/geçen süre ve bakım olaylarıyla birlikte gösterilir. Damızlık ön adaylığı yalnız büyüme sıralamasına dayanmaz; sağlık, davranış, tekrarlanan performans ve üretim amacıyla birlikte değerlendirilir. F1/melez beyanı saf ırk uygunluğundan ayrı tutulur; kesin genetik üstünlük veya sertifikalı damızlık iddiası verilmez. Önceki kayıt, saha ve güvenlik kuralları korunur.

## Neye bakar?

Arılı çıtalar, açık/kapalı yavru, kemer balı ve polen, kovan önü, varroa ölçümleri, yavru/arı sağlığı belirtileri, ana bilgisi, mevsimsel alan ihtiyacı, küf ve örtü ıslaklığı. Sorun varsa ilgili sorular derinleşir; hepsi uzun bir form olarak sorulmaz.

Değerlendirme sade dille verilir. “Bu kovanla işimiz bitti mi?” sorusuna evet denince kayıt tamamlanır ve sonraki kovana geçilir.

Günlük kontroller bitince bakılan ve henüz bakılmayan kovanlar ayrı gösterilir. Ortam dosya oluşturabiliyorsa güncel arılık defteri .txt olarak sunulur; WhatsApp’ta kendine saklama yolu gösterilir. Dosya üretilemiyorsa aynı sohbette kısa kayıt özeti verilir. Bütün aktif koloniler birden çok güne yayılan kontrol turunda ele alındığında, ortam destekliyorsa isteğe bağlı Excel listesi hazırlanabilir.

## Skill olarak kullanım

Paketteki `kovan-sagligi-arilik-takibi` klasörünü, özel skill destekleyen ortamın yükleme yoluyla ekleyin. SKILL.md, references ve templates birlikte kalmalı. Yükleme adımları ortama göre değişir.

## Prompt olarak kullanım

`PromptKullanimi.txt` dosyasındaki metnin tamamı yeni bir sohbette kullanılabilir. Bu dosya ana talimatı, destekleyici yönergeleri ve kayıt şablonunu birlikte içerir.

## Ses, geçmiş ve dosyalar

Sesli konuşma, fotoğraf/video okuma, canlı hava araştırması ve dosya üretimi kullanılan uygulamanın olanaklarına bağlıdır. Skill bunları tek başına açmaz. Gerçekten erişilebilen eski sohbet ve defterlerden devam eder; başka sohbette aynı skill'i kullanmak geçmişe otomatik erişim sağlamaz.

Her arılık için tek defter tutulur. Önceki deftere erişilemediğinde mevcut kovan değerlendirmesi yapılabilir; geçmiş sonradan birleştirilir. Arıcının Excel bilmesi veya şablon doldurması gerekmez.

## Dayanak

Türkiye, Birleşik Krallık, Avustralya, ABD ve Kanada'daki resmi kurum ve üniversite kaynakları ile uygun araştırmalardan yararlanan bir değerlendirme akışı içerir. Hazırlama kaynakları, erişim sınırları ve kullanımda güncelleme gereği [references/kaynaklar.md](references/kaynaklar.md) içinde belirtilmiştir.

Fotoğraf/beyanla yapılan durum değerlendirmesi kesin laboratuvar teşhisi değildir. İlaç/doz reçetesi bu skill'in kapsamına alınmamıştır; hastalık şüphesinde uygun uzman ve kurum yolunu gösterir.

## Paket

- SKILL.md: ana davranış ve saha akışı.
- references/: gerektiğinde okunacak saha, sağlık, bakım, kayıt ve kaynak yönergeleri.
- templates/arilik-defteri.txt: asistanın dolduracağı ortak kayıt yapısı.
- PromptKullanimi.txt: tek parça kullanım metni.

Dosya yapısı ve yönerge tutarlılığı kontrol edilmiştir; gerçek arılıkta veya farklı platformlarda saha başarısı henüz doğrulanmamıştır. Yayım lisansı henüz belirlenmemiştir; bu paketin hazırlanması herhangi bir GitHub deposunda lisans seçimi veya yayımlama işlemi yapmaz.
