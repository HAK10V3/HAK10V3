# 🎙️ Hak10 v3 - Gerçek Zamanlı Ses Modülasyon Uygulaması

<p align="center">
  <img src="https://img.shields.io/badge/Version-3.2.0-blue.svg" alt="Version">
  <img src="https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-0078d7.svg" alt="Platform">
  <img src="https://img.shields.io/badge/Python-3.8%2B-brightgreen.svg" alt="Python">
  <img src="https://img.shields.io/badge/Latency-Ultra--Low%20(~3--6ms)-orange.svg" alt="Latency">
  <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License">
</p>

**Hak10 v3**, mikrofonunuzdan gelen ses sinyalini ultra düşük gecikmeyle gerçek zamanlı olarak işleyen, 12 farklı stüdyo kalitesinde DSP ses efektine, modern kullanıcı arayüzüne, donanım kilitli güvenli lisans mimarisine ve GitHub üzerinden otomatik güncelleme desteğine sahip masaüstü ses modülasyon yazılımıdır.

---

## 🌟 Öne Çıkan Özellikler

### 🎛️ 12 Adet Gerçek Zamanlı DSP Ses Efekti
1. 🔊 **Kazanç (Gain Boost)**: 0 - 40 dB aralığında agresif ve temiz ses yükseltme.
2. 🎸 **Bas Güçlendirme (Bass Boost)**: 180 Hz IIR alçak geçiren filtre ile dolgun bas tepkisi.
3. 🔥 **Bozukluk (Distortion)**: Çift tanh tabanlı asimetrik analog doygunluk ve distorsiyon.
4. ⚡ **Kırılma (Clipping)**: Dinamik sinyal eşiği sınırlayıcı sert kırılma efekti.
5. 🛡️ **Limiter (Koruyucu Sınırlayıcı)**: Ses patlamalarını ve ani yükselmeleri engelleyen güvenlik kalkanı.
6. 🔇 **Noise Gate (Gürültü Geçidi)**: RMS tabanlı arka plan dip gürültü kesici.
7. ⏳ **Delay (Yankı)**: Geri besleme ve milisaniye ayarlı halka tampon (ring buffer) eko efekti.
8. 📻 **EQ Telsiz / Walkie-Talkie**: Eski telsiz ve megafon simülasyonu sağlayan bant geçiren filtre.
9. 🎵 **Pitch Shift (Ses Tonu)**: -12 ila +12 yarım ton aralığında anlık ses kalınlaştırma / inceltme.
10. 🏛️ **Reverb (Oda Akustiği)**: 4 adet paralel gecikme hattıyla mekan hacmi simülasyonu.
11. 🌊 **Chorus (Koro)**: LFO modülasyonlu sinyal çoğaltma ve derinlik efekti.
12. 📊 **Compressor (Sıkıştırıcı)**: Dinamik aralık kontrolü sağlayan zarf takipçili stüdyo kompresörü.

---

### 🎨 Arayüz & Profil Özelleştirme
- **5 Hazır Tema**: Aydınlık Panel, Karanlık Panel, Mavi Okyanus, Mor Gece, Matrix.
- **Özel Tema Düzenleyici**: Arayüz renklerini, aksan tonlarını ve yazı tipini dilediğiniz gibi tasarlayıp kaydedebilme.
- **Ses Profilleri**: Canavar, Robot, Telsiz, Megafon, Uzaylı gibi hazır şablonlar ile tek tıkla profil geçişi.
- **Dışa/İçe Aktarma**: Kendi ses profilinizi `.json` olarak dışa aktarıp arkadaşlarınızla paylaşabilme.

### 🔒 Güvenlik & Donanım Kilitli Lisans (HWID)
- Bilgisayarın anakart UUID'sini SHA-256 ile hash'leyerek her cihaza özel benzersiz Donanım Kimliği (HWID) üretir.
- Supabase bulut veritabanı üzerinden lisans anahtarını tekil bilgisayara kilitler (anahtar paylaşımını engeller).
- Çevrimdışı doğrulama için yerel şifreli lisans önbellekleme mekanizması barındırır.

### 🔄 Otomatik Güncelleme (Auto-Updater)
- Uygulama GitHub Releases üzerinden tek tıkla yeni sürümleri kontrol eder ve kullanıcıyı zahmete sokmadan kendini günceller.

---

## 🚀 İndirme & Kurulum

1. En son sürümü indirmek için **[Hak10 v3 Sürümler (Releases)](https://github.com/HAK10V3/HAK10V3/releases)** sayfasına gidin.
2. `Hak10_v3.exe` dosyasını bilgisayarınıza indirin.
3. Çift tıklayarak uygulamayı çalıştırın ve size iletilen lisans anahtarınızı girerek hemen kullanmaya başlayın!

> **💡 Otomatik Güncelleme:** Uygulama açılışta yeni bir sürüm yayınlandığında otomatik olarak sizi bilgilendirecek ve tek tıkla kendini güncelleyebilecektir.

---

## 🎧 Discord, OBS ve Oyunlara Sesi Aktarma

Uygulamadan çıkan efektli sesi oyunlara veya sesli sohbetlere aktarmak için ücretsiz **VB-Audio Virtual Cable** yazılımı önerilir:

1. [VB-Audio Virtual Cable](https://vb-audio.com/Cable/) sürücüsünü kurun ve bilgisayarı yeniden başlatın.
2. **Hak10 v3** Ayarlar menüsünden **Çıkış Aygıtı** olarak `CABLE Input (VB-Audio Virtual Cable)` seçin.
3. Discord, OBS veya oyun içi ses ayarlarında **Mikrofon (Giriş Aygıtı)** olarak `CABLE Output (VB-Audio Virtual Cable)` seçin.
4. Artık sesiniz modüle edilmiş haliyle doğrudan sohbete gidecektir!


---

## 📄 Lisans

Bu proje MIT lisansı ile lisanslanmıştır. Detaylar için `LICENSE` dosyasına bakabilirsiniz.
