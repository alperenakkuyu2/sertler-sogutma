# Sertler Soğutma - Dofollow Link Entegrasyonu Walkthrough

## 1. Başlangıç ve İhtiyaç Analizi
Bu projede kullanıcı tarafından verilen **dofollow_plan.md** dosyasındaki yönergeler baz alınarak, 12 farklı blog yazısına doğal bir şekilde SEO amaçlı dış linkler (backlink) eklenmesi talep edilmiştir. Öncelikle daha önceki konuşmalarda hangi dosyaların işlendiği ve eksik kalanların hangileri olduğu tespit edilmiştir. 

Önceki işlemler incelendiğinde, beyaz eşya ile ilgili ilk 8 linkin zaten ilgili sayfalara yerleştirilmiş olduğu, ancak son 4 linkin (Klima servislerine yönelik) henüz eklenmemiş olduğu tespit edildi.

## 2. Eksik Dosyaların Tespit Edilmesi ve İncelenmesi
İlgili son 4 link şunlardı:
1. `tarsus-klima-servisi.html` -> `klima servisi` anahtar kelimesi ile `akbeytekniksogutma.com` domainine
2. `tarsus-klima-tamircisi.html` -> `klima tamircisi` anahtar kelimesi ile `akbeytekniksogutma.com` domainine
3. `tarsus-klima-montaj.html` -> `klima montaj` anahtar kelimesi ile `akbeytekniksogutma.com` domainine
4. `tarsus-klima-bakim.html` -> `klima bakım` anahtar kelimesi ile `yildizlarteknikservis.com.tr` domainine

Bu anahtar kelimelerin sayfa içerisinde nerede ve nasıl geçtiğini görmek için dosyalar teker teker incelendi (`view_file` ve `run_command` araçlarıyla tarandı).

## 3. Linklerin Doğal Bir Şekilde Metne Yerleştirilmesi
Arama motoru optimizasyonu (SEO) kuralları gereği dış linklerin **doğal (doğrudan düz metin üzerinden)** verilmesi önem taşır. Dosyalarda yapılan incelemeler sonucunda, bu anahtar kelimelerin genellikle kalınlaştırılarak (`<strong>` etiketi içerisinde) ve baş harfleri büyük şekilde kullanıldığı görüldü. 

Bu sebeple, okuma akışını bozmayacak şekilde küçük gramer/kelime uyarlamaları yapıldı:
- **`tarsus-klima-servisi.html`** içerisinde "Klima Servisi" şeklinde geçen bir kelime bulunup `<a>` etiketi ile sarıldı.
- **`tarsus-klima-tamircisi.html`** içerisinde "klima tamir ustası" öbeği "klima tamircisi" şeklinde değiştirilip link verildi.
- **`tarsus-klima-montaj.html`** içerisinde "Yanlış yapılan bir montaj" ibaresi "Uzman olmayan kişilerce yapılan bir klima montaj işlemi" olarak güncellendi ve linklendi.
- **`tarsus-klima-bakim.html`** içerisinde "kliması bozulana kadar servis çağırmayı ihmal eder" cümlesi "cihazında bir arıza meydana gelene kadar klima bakım hizmeti almayı ihmal eder" olarak revize edildi ve bağlantı uygulandı.

## 4. Son Kontroller ve Tamamlama
Tüm metin değişiklikleri `multi_replace_file_content` aracı ile tek bir işlemde doğru satırlara uygulandı. Yapılan değişiklikler neticesinde 12 linkin tamamı, SEO dofollow kurallarına, metnin bütünlüğüne ve HTML formatına uygun bir şekilde ilgili sayfalara başarıyla işlenmiş oldu.
