# Sertler Soğutma - 12 Adımlı Blog Entegrasyon Walkthrough

Bu belge, 12 adımlı blog entegrasyonu sürecindeki ilerlemeyi ve yapılan işlemleri takip eder.

## Yapılan Hazırlıklar
* **Özel Parser ve Dönüştürücü Geliştirildi:** Kullanıcının Word dosyalarının formatına uygun (ilk satır H1, SSS soruları tek satırda birleşik) çalışan özel bir [convert_docx_to_html.py](file:///c:/Users/tugce/Desktop/sertler-sogutma-main/convert_docx_to_html.py) scripti geliştirildi.
* **Tekil Çalıştırma Modu Eklendi:** Scriptin her adımda yalnızca istenen dosyayı dönüştürebilmesi için parametrik çalıştırılma özelliği (`python convert_docx_to_html.py "dosya-adi.docx"`) eklendi.
* **Kart Başlıkları ve Açıklamaları Sadeleştirildi:** Blog ana sayfasındaki kartlarda upuzun H1 başlıkları yerine sade dosya isimleri (`Tarsus Altus Klima Servisi` vb.) kullanıldı. Paragraf açıklamaları markalara özel ve vurucu olacak şekilde `MARKALAR_DESCRIPTIONS` haritası ile güncellendi.
* **Şık ve Profesyonel Kart Tasarımı:** Blog kartlarının başlıklarına şık ve profesyonel bir lacivert/mavi tonu (`#1e3a8a`) tanımlandı; hover durumunda yumuşak bir transition ile buz mavisine dönmesi sağlandı.
* **Hesaplama Araçları Ayrı Bölüme Taşındı:** İnteraktif araçlar (BTU hesaplama ve Elektrik Tasarruf Simülatörü), diğer blog yazılarından görsel olarak ayrılması ve her zaman en üstte sabit kalması için bağımsız bir "Hesaplama Araçları" grid alanına taşındı.
* **WebP Görsel Varlıkları Üretildi ve Entegre Edildi:** Yeni eklenen 12 blog yazısı için klima servisi, montajı, bakımı ve kart onarımı konseptlerinde 4 adet premium görsel AI ile üretildi. Bu görseller Pillow kütüphanesi yardımıyla `.webp` formatına dönüştürülerek 12 marka yazısı için ayrı ayrı `images/blog/` klasörü altına yerleştirildi.
* **Uygulama Planı Güncellendi:** [implementation_plan.md](file:///c:/Users/tugce/Desktop/sertler-sogutma-main/implementation_plan.md) belgesi 12 adımda ilerleyecek şekilde yeniden yapılandırıldı.

## Adım Takibi
- [x] 1. Adım: Tarsus Altus Klima Servisi (Tamamlandı - 16 Haziran 2026)
- [x] 2. Adım: Tarsus Arçelik Klima Servisi (Tamamlandı - 16 Haziran 2026)
- [x] 3. Adım: Tarsus Baymak Klima Servisi (Tamamlandı - 16 Haziran 2026)
- [x] 4. Adım: Tarsus Beko Klima Servisi (Tamamlandı - 16 Haziran 2026)
- [x] 5. Adım: Tarsus Bosch Klima Servisi (Tamamlandı - 16 Haziran 2026)
- [x] 6. Adım: Tarsus Daikin Klima Servisi (Tamamlandı - 16 Haziran 2026)
- [x] 7. Adım: Tarsus Daylux Klima Servisi (Tamamlandı - 16 Haziran 2026)
- [x] 8. Adım: Tarsus Demirdöküm Klima Servisi (Tamamlandı - 16 Haziran 2026)
- [x] 9. Adım: Tarsus Fujitsu Klima Servisi (Tamamlandı - 16 Haziran 2026)
- [x] 10. Adım: Tarsus General Electric Klima Servisi (Tamamlandı - 16 Haziran 2026)
- [x] 11. Adım: Tarsus Gree Klima Servisi (Tamamlandı - 16 Haziran 2026)
- [x] 12. Adım: Tarsus Hitachi Klima Servisi (Tamamlandı - 16 Haziran 2026)
