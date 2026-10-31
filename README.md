# 📚 Literatür Tarama Web

**Akademik makaleleri keşfetmek, karşılaştırmak ve ön inceleme yapmak için ücretsiz, açık kaynaklı bir web uygulaması.**

[![Uygulamayı Aç](https://img.shields.io/badge/🌐_Uygulamayı_Aç-GitHub_Pages-2563eb?style=for-the-badge)](https://bartuemre.github.io/literatur-tarama/)
![Lisans: MIT](https://img.shields.io/badge/Lisans-MIT-green)
![Teknoloji](https://img.shields.io/badge/HTML-CSS-JavaScript-orange)

**🔗 Canlı uygulama:** https://bartuemre.github.io/literatur-tarama/

Python, VS Code veya başka bir program yüklemeden, doğrudan tarayıcıda çalışır.

## ✨ Özellikler

- **Doğrudan makale arama:** OpenAlex üzerinden akademik yayınları listeleme
- **Yıl filtresi:** Seçtiğiniz yıldan önceki yayınları hariç tutma
- **Yayın bilgileri:** Makale başlığı, dergi/yayın yeri, atıf sayısı ve DOI
- **Açık erişim:** Mevcutsa PDF bağlantısını görüntüleme
- **🔎 İncele:** Tek makale seçildiğinde yazarları, kurumları, mevcut özeti ve özette tespit edilen yöntem terimlerini gösterme
- **Toplu işlemler:** Makale bağlantılarını açma veya kopyalama
- **CSV dışa aktarma:** Sonuçları tablo olarak kaydetme
- **Ek kaynak bağlantıları:** Google Scholar, DergiPark, ScienceDirect, Semantic Scholar ve YÖK Tez Merkezi için arama URL'leri
- **Mobil görünüm:** Sonuçlar dar ekranlarda kart olarak gösterilir; filtreleme sırasında seçili kayıtlar korunur

## 🖥️ Uygulama görünümü

Uygulamanın güncel arayüzünü [canlı demodan](https://bartuemre.github.io/literatur-tarama/) görebilirsiniz.

> Projeye gerçek bir ekran görüntüsü eklemek için `assets/uygulama-ekrani.png` dosyasını yükleyip bu bölüme `![Uygulama ekran görüntüsü](assets/uygulama-ekrani.png)` satırını ekleyebilirsiniz.

## 🚀 Nasıl kullanılır?

1. **[Uygulamayı açın](https://bartuemre.github.io/literatur-tarama/).**
2. Anahtar kelimeleri her satıra bir sorgu gelecek şekilde girin.
3. **En eski yıl** ve **sorgu başına makale sayısını** belirleyin.
4. **Makaleleri Direkt Bul** butonuna basın.
5. Başlık, dergi, yıl, atıf, DOI ve varsa PDF bağlantılarını inceleyin.
6. Bir makaleyi işaretleyip **🔎 İncele** ile ön bilgilerini görüntüleyin.
7. İsterseniz sonuçları **CSV İndir** ile kaydedin.

## 🔎 İncele özelliği hakkında

İncele paneli, OpenAlex'te bulunan metadata ve özet verisini kullanır. Kullanılan teknikler özetteki belirli terimlerin eşleşmesiyle tespit edilir. **Yapay zekâ ile tam metin analizi yapmaz**; makalenin yöntemini, problemini veya araştırmanın gerçekleştirildiği ülkeyi kesin olarak doğrulamaz. Akademik çalışmalarda asıl makaleyi kontrol edin.

## 🛠️ Teknoloji ve veri kaynağı

- **Ön yüz:** HTML, CSS, JavaScript
- **Akademik veri:** [OpenAlex API](https://docs.openalex.org/)
- **Yayımlama:** GitHub Pages
- **Lisans:** [MIT](LICENSE)

Arama internet bağlantısı ve OpenAlex API erişimi gerektirir. API erişim koşulları, anahtar gereksinimi ve kullanım sınırları zamanla değişebilir. Kişisel API anahtarlarını GitHub'a veya herkese açık HTML kaynak koduna eklemeyin.

Bazı yayınlarda PDF bulunmayabilir; toplu sekme açma işlemleri tarayıcı tarafından engellenebilir. Diğer akademik platformlarda uygulama doğrudan makale çekmek yerine arama bağlantıları oluşturur.

## 🤝 Katkıda bulunma

Hata bildirimi ve geliştirme önerileri için GitHub Issues kullanabilirsiniz. Yerel geliştirme, değişiklik gönderme ve GitHub Pages yönergeleri için [CONTRIBUTING.md](CONTRIBUTING.md) dosyasına bakın.

## 📄 Lisans

Bu proje [MIT lisansı](LICENSE) ile sunulmaktadır.
