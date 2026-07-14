# Sertler Soğutma - Yeni 7 Blog Yazısı Ekleme Uygulama Planı

Bu plan, `C:\Users\tugce\Downloads\al` klasöründeki 7 adet yeni klima servisi blog yazısının `.docx` dosyalarından HTML'e dönüştürülerek web sitesine entegre edilmesini içerir.

## 1. Amaç
Sitenin mevcut tasarım şablonuna (`blog/tarsus-beyaz-esya-servisi.html`) sadık kalınarak 7 yeni klima servis rehberinin sisteme eklenmesi, sitemap.xml güncellenmesi ve blog listesinde listelenmesi.

## 2. Yapılacak Değişiklikler ve Adımlar (7 Adım)
Dönüşüm işlemleri sırasıyla şu adımlarla yapılacaktır:
1. **1. Adım:** `Tarsus Midea Klima Servisi.docx`
2. **2. Adım:** `Tarsus Mitsubishi Klima Servisi.docx`
3. **3. Adım:** `Tarsus Regal Klima Servisi.docx`
4. **4. Adım:** `Tarsus Toshiba Klima Servisi.docx`
5. **5. Adım:** `Tarsus Vestel Klima Servisi.docx`
6. **6. Adım:** `Tarsus Viessmann Klima Servisi.docx`
7. **7. Adım:** `Tarsus York Klima Servisi.docx`

## 3. Görsel Entegrasyonu Planı
Yeni eklenecek 7 makale için mevcut premium görseller weBP formatında ilgili isimlerle kopyalanarak entegre edilecektir:
* **Midea, Mitsubishi, Regal:** `tarsus-altus-klima-servisi-1.webp` (klima temizlik ve bakım görseli) kopyalanarak kullanılacaktır.
* **Toshiba, Vestel:** `tarsus-baymak-klima-servisi-1.webp` (klima onarım ve kart arıza tespiti görseli) kopyalanarak kullanılacaktır.
* **Viessmann, York:** `tarsus-daylux-klima-servisi-1.webp` (klima dış ünite kontrolü görseli) kopyalanarak kullanılacaktır.

## 4. Uygulama Adımları
* Her adımda belirtilen dosya `python convert_docx_to_html.py "[Dosya_Adi].docx"` komutuyla dönüştürülecektir.
* Her adımdan sonra `blog/index.html` sayfasındaki durum sayacı (yayındaki yazı sayısı) 26'dan 33'e doğru kademeli olarak güncellenecektir.
* Adımlar arasında sizden onay alınarak ilerlenecektir.
