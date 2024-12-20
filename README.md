# Türkiye Deprem İzleme Sistemi 🌍
Bu proje, Türkiye'deki deprem aktivitelerini gerçek zamanlı olarak izlemek ve görselleştirmek için geliştirilmiş interaktif bir web uygulamasıdır. Kandilli Rasathanesi'nden alınan veriler ile Türkiye'deki deprem aktivitelerini il bazında gösterir.
## 🌟 Özellikler
- **Gerçek Zamanlı Veri**: Kandilli Rasathanesi'nden anlık deprem verileri
 **İnteraktif Harita**: 3D görünüm ve ısı haritası seçenekleri
 **İl Bazlı Görselleştirme**: Her il için:
 - Toplam deprem sayısı
 - En büyük deprem magnitude'u
 - Son depremler listesi
 **Zaman Filtresi**: Son 24 saat, 48 saat veya 7 günlük deprem verileri
 **Responsive Tasarım**: Mobil cihazlarla uyumlu arayüz
## 🚀 Kurulum
1. Projeyi klonlayın:
```bash
git clone https://github.com/mehmet0404/turkiye-deprem-izleme.git
```
2. Gerekli paketleri yükleyin:
```bash
npm install
```
3. `.env` dosyasını oluşturun:
```env
MAPBOX_TOKEN=your_mapbox_token_here
PORT=3001
```
4. Uygulamayı başlatın:
```bash
npm start
```
5. Tarayıcınızda açın:
```
http://localhost:3001
```
## 🛠️ Teknolojiler
- **Frontend**:
  - MapboxGL JS (3D harita görselleştirme)
  - Chart.js (Veri grafikleri)
  - HTML5/CSS3
  - JavaScript (ES6+)
- **Backend**:
  - Node.js
  - Express.js
  - node-fetch (API istekleri)
  - iconv-lite (Türkçe karakter desteği)
## 📊 Veri Kaynağı
Bu uygulama, Boğaziçi Üniversitesi Kandilli Rasathanesi ve Deprem Araştırma Enstitüsü'nün (KOERI) sağladığı deprem verilerini kullanmaktadır.
## 🎯 Kullanım
1. **3D Görünüm**: "3D Görünüm" butonuna tıklayarak haritayı 3 boyutlu görüntüleyebilirsiniz
2. **Isı Haritası**: "Isı Haritası" butonu ile deprem yoğunluğunu gösteren ısı haritasını açabilirsiniz
3. **Zaman Filtresi**: Üst menüden istediğiniz zaman aralığını seçebilirsiniz
4. **İl Detayları**: Haritadaki il işaretçilerine tıklayarak detaylı deprem bilgilerini görüntüleyebilirsiniz
## 🤝 Katkıda Bulunma
1. Bu projeyi fork edin
2. Yeni bir branch oluşturun (`git checkout -b feature/yeniOzellik`)
3. Değişikliklerinizi commit edin (`git commit -am 'Yeni özellik: Detaylar'`)
4. Branch'inizi push edin (`git push origin feature/yeniOzellik`)
5. Pull Request oluşturun
## 📝 Lisans
Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasına bakınız.
## 📧 İletişim
- Proje Sahibi: [İsim Soyisim]
- E-posta: [E-posta adresi]
- GitHub: [GitHub profil linki]
## 🙏 Teşekkürler
- Boğaziçi Üniversitesi Kandilli Rasathanesi ve Deprem Araştırma Enstitüsü
- Mapbox GL JS ekibi
- Tüm katkıda bulunanlara
---
⭐️ Bu projeyi beğendiyseniz yıldız vermeyi unutmayın!
