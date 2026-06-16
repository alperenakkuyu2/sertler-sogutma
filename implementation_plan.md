# Sertler Soğutma - 12 Adımlı Blog Entegrasyon Planı

Bu plan kapsamında `C:\Users\tugce\Downloads\blog1` klasöründeki 12 adet klima servisi konulu `.docx` dosyası, sırasıyla ve onaylı adımlarla blog yazılarına dönüştürülecektir.

## 1. Amaç
Her bir adımda 1 adet `.docx` dosyası okunarak HTML şablonuna göre üretilecek, `sitemap.xml` ve `blog/index.html` dosyalarına kaydedilecektir. Adımlar arasında kullanıcı onayı alınarak ilerlenecektir.

## 2. Dönüştürülecek Dosyalar (12 Adım)
1. **1. Adım:** `Tarsus Altus Klima Servisi.docx`
2. **2. Adım:** `Tarsus Arçelik Klima Servisi.docx`
3. **3. Adım:** `Tarsus Baymak Klima Servisi.docx`
4. **4. Adım:** `Tarsus Beko Klima Servisi.docx`
5. **5. Adım:** `Tarsus Bosch Klima Servisi.docx`
6. **6. Adım:** `Tarsus Daikin Klima Servisi.docx`
7. **7. Adım:** `Tarsus Daylux Klima Servisi.docx`
8. **8. Adım:** `Tarsus Demirdöküm Klima Servisi.docx`
9. **9. Adım:** `Tarsus Fujitsu Klima Servisi.docx`
10. **10. Adım:** `Tarsus General Electric Klima Servisi.docx`
11. **11. Adım:** `Tarsus Gree Klima Servisi.docx`
12. **12. Adım:** `Tarsus Hitachi Klima Servisi.docx`

## 3. Süreç
* Her adımda belirtilen dosya `python convert_docx_to_html.py "[Dosya_Adi].docx"` komutuyla dönüştürülecektir.
* Dönüşüm sonrasında üretilen HTML dosyasının yapısı ve içeriği kontrol edilip kullanıcıya sunulacaktır.
* Kullanıcı onay verdiğinde bir sonraki adıma geçilecektir.

---
*Gerekli Python altyapısı ve otomatik şablon güncelleyici script ([convert_docx_to_html.py](file:///c:/Users/tugce/Desktop/sertler-sogutma-main/convert_docx_to_html.py)) hazır durumdadır.*
