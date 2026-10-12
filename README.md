# Literatür Tarama Web

Türkçe arayüzlü, tarayıcı üzerinden çalışan akademik makale arama aracı. Python veya sunucu kurulumu gerektirmez.

## Özellikler

- OpenAlex API ile makale arama
- En eski yayın yılı filtresi
- Makale başlığı, yazarlar, dergi, DOI, atıf sayısı ve açık erişim PDF bağlantısı
- Tek makale seçildiğinde **İncele** paneli (OpenAlex özeti ve terim bazlı yöntem tespiti)
- Seçili bağlantıları açma, CSV dışa aktarma
- Google Scholar, DergiPark, ScienceDirect, Semantic Scholar ve YÖK için arama sayfası bağlantıları

## Kullanım

1. [GitHub Pages](https://pages.github.com/) adresinde yayımlanan siteyi açın veya `index.html` dosyasını tarayıcıda açın.
2. Anahtar kelimeleri yazın, en eski yılı belirleyin.
3. **Makaleleri Direkt Bul** ile OpenAlex sonuçlarını getirin.
4. Tek makale seçip **İncele** ile mevcut özet bilgilerini görüntüleyin.
5. CSV dışa aktarın veya yayın/PDF bağlantılarını açın.

## GitHub Pages yayımlama

1. GitHub'da herkese açık yeni bir depo açın (ör. `literatur-tarama`).
2. Bu klasördeki `index.html`, `README.md`, `LICENSE` dosyalarını deponun **kök dizinine** yükleyin.
3. **Settings → Pages → Build and deployment → Source: Deploy from a branch** seçin.
4. Branch olarak `main`, klasör olarak `/ (root)` seçip **Save** deyin.
5. Birkaç dakika sonra `https://KULLANICI_ADIN.github.io/DEPO_ADI/` adresini açın.

## Teknik notlar ve sınırlamalar

- OpenAlex API kullanır; arama için internet gerekir. API'nin güncel erişim koşulları, hız limitleri ve anahtar gereksinimleri değişebilir.
- Kişisel API anahtarını HTML kaynak koduna sabit yazmayın veya GitHub'a yüklemeyin. Tarayıcıda girilen anahtar, tarayıcı üzerinden yapılan ağ isteklerinde görünür.
- Diğer akademik kaynaklar için doğrudan makale çekilmez, yalnızca arama bağlantıları üretilir.
- **İncele** yapay zekâ özeti değildir: özet metnini ve özette eşleşen yöntem terimlerini gösterir; sonuçları asıl makaleden doğrulayın.
- Tarayıcı, çok sayıda sekmeyi açmayı engelleyebilir.
- Makale PDF'lerinin telif ve erişim koşulları yayıncıya bağlıdır.

## Lisans

MIT — ayrıntılar için `LICENSE`.
