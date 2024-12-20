---
# 🌍 Türkiye Deprem İzleme Sistemi

Bu proje, Türkiye'deki deprem aktivitelerini gerçek zamanlı olarak izlemek ve görselleştirmek amacıyla geliştirilmiş bir web uygulamasıdır. Kandilli Rasathanesi'nden alınan veriler sayesinde deprem bilgilerini il bazında detaylı bir şekilde sunar.
---

## 🌟 Özellikler

- **Gerçek Zamanlı Veri:** Kandilli Rasathanesi'nden alınan anlık deprem verileri.
- **İnteraktif Harita:** 3D harita görünümü ve ısı haritası seçenekleri.
- **İl Bazlı Görselleştirme:**
  - Toplam deprem sayısı.
  - En büyük deprem magnitude'u.
  - Son depremler listesi.
- **Zaman Filtresi:**
  - Son 24 saat, 48 saat veya 7 günlük deprem verilerini görüntüleyin.
- **Responsive Tasarım:** Mobil cihazlar ve farklı ekran boyutlarıyla uyumlu arayüz.

---

## 🚀 Kurulum

### 1. Projeyi Klonlayın

```bash
git clone https://github.com/mehmet0404/turkiye-deprem-izleme.git
```

### 2. Gerekli Paketleri Yükleyin

```bash
npm install
```

### 3. Çevre Değişkenlerini Ayarlayın

Proje kök dizininde `.env` dosyası oluşturun ve aşağıdaki bilgileri ekleyin:

```env
MAPBOX_TOKEN=your_mapbox_token_here
PORT=3001
```

### 4. Uygulamayı Başlatın

```bash
npm start
```

### 5. Tarayıcınızda Açın

```
http://localhost:3001
```

---

## 🛠️ Teknolojiler

- **Frontend:**

  - Mapbox GL JS (3D harita görselleştirme).
  - Chart.js (Veri grafikleri).
  - HTML5/CSS3.
  - JavaScript (ES6+).

- **Backend:**
  - Node.js.
  - Express.js.
  - `node-fetch` (API istekleri).
  - `iconv-lite` (Türkçe karakter desteği).

---

## 📊 Veri Kaynağı

Bu uygulama, **Boğaziçi Üniversitesi Kandilli Rasathanesi ve Deprem Araştırma Enstitüsü**'nden (KOERI) sağlanan verileri kullanmaktadır.

---

## 🎯 Kullanım

1. **3D Görünüm:**

   - Haritayı 3 boyutlu görmek için "3D Görünüm" butonuna tıklayın.

2. **Isı Haritası:**

   - Deprem yoğunluklarını incelemek için "Isı Haritası" seçeneğini açın.

3. **Zaman Filtresi:**

   - Üst menüden istediğiniz zaman aralığını seçin (24 saat, 48 saat veya 7 gün).

4. **İl Detayları:**
   - Haritada bir il işaretçisine tıklayarak detaylı deprem bilgilerini görüntüleyin.

---

## 🤝 Katkıda Bulunma

1. Projeyi fork edin.
2. Yeni bir branch oluşturun:
   ```bash
   git checkout -b feature/yeniOzellik
   ```
3. Değişikliklerinizi commit edin:
   ```bash
   git commit -am 'Yeni özellik: Detaylar'
   ```
4. Branch'i push edin:
   ```bash
   git push origin feature/yeniOzellik
   ```
5. Pull Request oluşturun.

---

## 📝 Lisans

Bu proje, [MIT Lisansı](LICENSE) altında lisanslanmıştır. Detaylar için `LICENSE` dosyasına göz atabilirsiniz.

## 🙏 Teşekkürler

- **Boğaziçi Üniversitesi Kandilli Rasathanesi ve Deprem Araştırma Enstitüsü**.
- **Mapbox GL JS Ekibi**.
