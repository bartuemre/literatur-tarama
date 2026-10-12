# Geliştirme ve katkıda bulunma

Bu dosya son kullanıcıdan ziyade projeye katkıda bulunmak veya kendi kopyasını yayımlamak isteyen geliştiriciler içindir.

## Yerel çalıştırma

`index.html` dosyasını Chrome veya Edge ile açın. Uygulama saf HTML/CSS/JavaScript kullanır; Python ve paket kurulumu gerekmez. API araması için internet erişimi gerekir.

## Değişiklik önerme

1. Depoyu fork'layın ve yeni bir branch oluşturun.
2. Değişiklikleri `index.html` üzerinde yapın.
3. Arama, yıl filtresi, İncele, CSV ve bağlantı açma işlevlerini tarayıcıda kontrol edin.
4. Pull request açıp değişikliğin amacını ve test adımlarını açıklayın.

## GitHub Pages ile kendi kopyanızı yayımlama

1. GitHub'da herkese açık bir depo oluşturun.
2. `index.html`, `README.md`, `LICENSE` ve isteğe bağlı diğer proje dosyalarını depo köküne yükleyin.
3. **Settings → Pages → Build and deployment** altında **Deploy from a branch** seçin.
4. Branch olarak `main`, klasör olarak `/ (root)` seçin ve kaydedin.
5. Yayım tamamlandığında `https://KULLANICI_ADI.github.io/DEPO_ADI/` adresini ziyaret edin.

Kendi deponuza kopyalarsanız README içindeki canlı demo bağlantısını da değiştirin.

## Ekran görüntüsü ekleme

Gerçek uygulama ekranının görüntüsünü alın; kişisel API anahtarlarını ve hassas bilgileri gizleyin. Görseli `assets/uygulama-ekrani.png` olarak ekleyin. README'deki uygulama görünümü bölümüne şu satırı yerleştirin:

```markdown
![Uygulama ekran görüntüsü](assets/uygulama-ekrani.png)
```

## Güvenlik ve API

API anahtarlarını koda, commit'lere veya ekran görüntülerine koymayın. Tarayıcıda girilen anahtarların istemci tarafında görülebileceğini unutmayın. OpenAlex ve diğer kaynakların erişim koşullarına uyun.
