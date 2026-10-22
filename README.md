# BFAliGhostAura 👻

**Friday Night Funkin' V-Slice için hayalet aura görsel efekt modu.**

BFAliGhostAura, karakterler başarılı nota vuruşları gerçekleştirdiğinde geçici, camgöbeği renkli hayalet izleri oluşturur. Oynanışa ekstra görsel geri bildirim ve hareket katar.

## ✨ Özellikler

- **Hayalet Aura:** Başarılı nota vuruşlarında oluşan geçici hayalet izleri.
- **Camgöbeği Görsel Stil:** Moda özgü, dikkat çekici camgöbeği renk paleti.
- **Dinamik Animasyonlar:** Hayalet izleri ölçeklenebilir, süzülebilir, dönebilir ve zamanla kaybolabilir.
- **Karakter Desteği:** Oyuncu ve rakip karakterler için tasarlanmış görsel efektler.
- **Hafif Efektler:** Görsel geri bildirim için geçici sprite'lar kullanır.
- **Platforma Özel Yapılandırma:** Masaüstü ve mobil platformlar için ayrı efekt ayarları.
- **V-Slice Uyumluluğu:** Friday Night Funkin' V-Slice 0.8.6 için geliştirilmiştir.

## 🎮 Gereksinimler

- Friday Night Funkin' V-Slice 0.8.6.
- V-Slice ile uyumlu bir mod kurulumu.
- BFAliGhostAura tarafından kullanılan komut dosyası API'lerini destekleyen bir oyun sürümü.

## 📦 Kurulum

1. Depoyu indirin veya klonlayın.
2. Mod klasörünü V-Slice kurulumunuzdaki uygun dizine yerleştirin.
3. `_polymod_meta.json` dosyasının ve `scripts` klasörünün mevcut olduğundan emin olun.
4. Oyunu başlatın ve modun doğru şekilde yüklendiğini kontrol edin.

*Kurulum dizinleri, oyun sürümünüze ve kullandığınız mod yükleyicisine göre değişebilir.*

## 📁 Proje Yapısı

```text
BFAliGhostAura/
├── _polymod_meta.json
├── LICENSE.md
├── README.md
└── scripts/
    ├── GhostAura.hxc
    └── backend/
        ├── desktop/
        │   └── DesktopConfig.hxc
        └── mobile/
            └── MobileConfig.hxc
```

## ⚙️ Yapılandırma

BFAliGhostAura, platforma göre farklı efekt ayarları kullanabilir.

Yapılandırılabilen başlıca değerler:

- **İz Uzunluğu:** Aynı anda tutulabilecek hayalet izi sayısı.
- **Başlangıç Opaklığı:** Hayalet izlerinin ilk görünürlük seviyesi.
- **Kaybolma Süresi:** Efektlerin ne kadar sürede kaybolacağı.
- **Ölçek Animasyonu:** Hayalet izlerinin büyüyüp küçülmesi.
- **Hareket Efektleri:** İzlerin süzülmesi ve dönmesi.
- **Karışım Modu:** Efektlerin oyun görüntüsüyle nasıl birleşeceği.

### 💻 Masaüstü

`DesktopConfig.hxc`, masaüstü için daha uzun izler ve ek hareket animasyonları gibi efekt ayarlarını içerir.

### 📱 Mobil

`MobileConfig.hxc`, mobil cihazlarda daha hafif bir efekt deneyimi hedefleyen ayrı ayarlar içerir.

## 🛠️ Uyumluluk

BFAliGhostAura, Friday Night Funkin' V-Slice 0.8.6 hedeflenerek geliştirilmiştir.

Diğer sürümlerle uyumluluk garanti edilmez. Oyunun komut dosyası API'lerinde yapılan değişiklikler, modun güncellenmesini gerektirebilir.

## 👥 Katkıda Bulunanlar

- **Lisans Sahibi:** Prism Crew Studio
- **Geliştirici:** BF_AliBerk_BF
- **Geliştirme Desteği:** Prism Crew Studio
- **Lisans:** MIT

## 📄 Lisans

BFAliGhostAura, MIT Lisansı kapsamında dağıtılır.

Telif Hakkı © 2026 Prism Crew Studio.

Lisansın tam metni için `LICENSE.md` dosyasına bakın.

## ⚠️ Sorumluluk Reddi

BFAliGhostAura, topluluk tarafından geliştirilmiş resmî olmayan bir modifikasyondur. Friday Night Funkin' oyununun resmî geliştiricileriyle bağlantısı yoktur ve onlar tarafından desteklenmez veya onaylanmaz.

Friday Night Funkin' ve oyuna ait varlıklar, ilgili hak sahiplerinin mülkiyetindedir.

---

**Vuruşunu yap, izini bırak.** 👻

*BF_AliBerk_BF tarafından, Prism Crew Studio desteğiyle geliştirilmiştir.*