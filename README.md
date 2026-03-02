# FaceUnlock
<!-- TÜRKÇE / TURKISH -->
<div align="center">
  <h1>🔆 FaceUnlock - Karanlıkta Yüz Tanıma İyileştiricisi</h1>
  <h3>Karanlık ortamlarda yüz tanıma için ekran parlaklığını otomatik artıran Magisk modülü</h3>
  <p><i>KİKYO FLOWER ASH tarafından geliştirilmiştir</i></p>
</div>

<br>

<!-- BADGES / ROZETLER -->
<div align="center">
  <img src="https://img.shields.io/badge/Magisk-v20.0%2B-blue?style=for-the-badge&logo=magisk">
  <img src="https://img.shields.io/badge/Android-9.0%2B-green?style=for-the-badge&logo=android">
  <img src="https://img.shields.io/badge/License-MIT-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Version-v1.0-brightgreen?style=for-the-badge">
</div>

<br>

---

## 📱 Türkçe

### 📋 Açıklama
**FaceUnlock**, karanlık ortamlarda yüz tanımanın çalışmaması sorununa çözüm getiren bir Magisk modülüdür. Ortam ışığı düştüğünde ekran parlaklığını otomatik olarak artırarak yüzünüzün daha iyi aydınlatılmasını sağlar ve böylece yüz tanıma özelliğinin karanlıkta da sorunsuz çalışmasına olanak tanır.

### ✨ Özellikler
- 🌙 **Otomatik Parlaklık Artırma**: Ortam karanlık olduğunda ekran parlaklığını yükseltir
- 🔒 **Kilit Ekranı Desteği**: Sadece kilit ekranı aktifken çalışır
- ⚙️ **Özelleştirilebilir Ayarlar**: Parlaklık seviyesi, bekleme süresi, saat aralığı vb.
- 🔋 **Pil Dostu**: Pil tasarrufu modundayken otomatik devre dışı kalır
- 🌍 **Evrensel Uyumluluk**: Tüm Android cihazlar ve ROM'larla çalışır
- 🎯 **Eylem Butonu Desteği**: Magisk'ten doğrudan ayarları değiştirin

### 🛠️ Gereksinimler
- Magisk v20.0 veya üzeri
- Android 9.0 veya üzeri
- Rootlu cihaz
- Yüz tanıma özelliğine sahip cihaz (veya GApps yüklü)

### 📦 Kurulum
1. Son sürüm ZIP dosyasını [Releases](https://github.com/Harunkaraogl/FaceUnlock/releases) sayfasından indirin
2. Magisk uygulamasını açın
3. "Modüller" sekmesine gidin
4. "Modülü yükle" butonuna tıklayın
5. İndirdiğiniz ZIP dosyasını seçin
6. Kurulum tamamlandıktan sonra cihazınızı yeniden başlatın

### ⚙️ Kullanım
1. Magisk uygulamasında "Modüller" sekmesine gidin
2. FaceUnlock modülünün yanındaki **"Eylemler"** butonuna tıklayın
3. Açılan arayüzden ayarları yapın:
   - **Parlaklık Seviyesi**: Karanlıkta kaç parlaklık kullanılacak (50-255)
   - **Bekleme Süresi**: Parlaklık kaç saniye açık kalacak
   - **Çalışma Saatleri**: Modülün aktif olacağı saat aralığı
   - **Pil Tasarrufu**: Pil tasarrufu modundayken kapat
   - **Sensör Hassasiyeti**: Işık sensörünün hassasiyeti

### 🔄 Güncelleme
- Yeni sürümler çıktığında Magisk'te "Güncelle" butonu aktif olacaktır
- Tek yapmanız gereken butona tıklayıp onaylamak

### 🗑️ Kaldırma
1. Magisk uygulamasında "Modüller" sekmesine gidin
2. FaceUnlock modülünün yanındaki çöp kutusu simgesine tıklayın
3. Veya modülü manuel olarak silin: `/data/adb/modules/FaceUnlock/`
4. Cihazınızı yeniden başlatın

### ❓ Sıkça Sorulan Sorular
**S: Her cihazda çalışır mı?**  
C: Evet, modül tüm cihazlar ve ROM'lar için evrensel olarak tasarlanmıştır.

**S: Pil tüketimi nasıl?**  
C: Minimum düzeydedir. Sadece kilit ekranı açıkken ve karanlık ortamda çalışır.

**S: Otomatik parlaklıkla çakışır mı?**  
C: Hayır, otomatik parlaklığı geçici olarak keser ve işi bittiğinde geri verir.

### 🐛 Hata Bildirimi
Bir hata bulursanız veya öneriniz varsa [Issues](https://github.com/Harunkaraogl/FaceUnlock/issues) sayfasından bildirebilirsiniz.

### 📜 Lisans
Bu proje MIT lisansı ile lisanslanmıştır.

### 👨‍💻 Geliştirici
- **KİKYO FLOWER ASH**
- [GitHub](https://github.com/Harunkaraogl)

---

## 🌍 English

### 📋 Description
**FaceUnlock** is a Magisk module that solves the problem of face unlock not working in dark environments. It automatically increases screen brightness when ambient light is low, better illuminating your face and allowing face recognition to work seamlessly in the dark.

### ✨ Features
- 🌙 **Automatic Brightness Boost**: Increases screen brightness in dark environments
- 🔒 **Lock Screen Support**: Only activates when the lock screen is active
- ⚙️ **Customizable Settings**: Brightness level, duration, time range, etc.
- 🔋 **Battery Friendly**: Automatically disabled during power saving mode
- 🌍 **Universal Compatibility**: Works on all Android devices and ROMs
- 🎯 **Action Button Support**: Change settings directly from Magisk

### 🛠️ Requirements
- Magisk v20.0 or higher
- Android 9.0 or higher
- Rooted device
- Device with face unlock feature (or GApps installed)

### 📦 Installation
1. Download the latest ZIP from the [Releases](https://github.com/Harunkaraogl/FaceUnlock/releases) page
2. Open Magisk app
3. Go to "Modules" tab
4. Click "Install from storage"
5. Select the downloaded ZIP file
6. Reboot your device after installation

### ⚙️ Usage
1. Go to "Modules" tab in Magisk app
2. Click the **"Actions"** button next to FaceUnlock module
3. Configure settings in the interface:
   - **Brightness Level**: Brightness value in dark (50-255)
   - **Duration**: How many seconds the brightness stays on
   - **Active Hours**: Time range when module is active
   - **Power Saving**: Disable during power saving mode
   - **Sensor Sensitivity**: Light sensor sensitivity

### 🔄 Update
- When new versions are released, the "Update" button will appear in Magisk
- Just click and confirm to update

### 🗑️ Uninstallation
1. Go to "Modules" tab in Magisk app
2. Click the trash icon next to FaceUnlock module
3. Or manually delete: `/data/adb/modules/FaceUnlock/`
4. Reboot your device

### ❓ FAQ
**Q: Does it work on all devices?**  
A: Yes, the module is designed to be universal for all devices and ROMs.

**Q: How about battery consumption?**  
A: Minimal. It only works when the lock screen is active and in dark environments.

**Q: Does it conflict with auto-brightness?**  
A: No, it temporarily overrides auto-brightness and restores it when done.

### 🐛 Bug Report
If you find a bug or have a suggestion, please report it on the [Issues](https://github.com/Harunkaraogl/FaceUnlock/issues) page.

### 📜 License
This project is licensed under the MIT License.

### 👨‍💻 Developer
- **KİKYO FLOWER ASH**
- [GitHub](https://github.com/Harunkaraogl)

---

<div align="center">
  <h3>⭐ Bu projeyi beğendiyseniz yıldız vermeyi unutmayın! ⭐</h3>
  <h3>⭐ If you like this project, don't forget to star it! ⭐</h3>
</div>
