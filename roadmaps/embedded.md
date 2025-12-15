# 🔌 Embedded Systems Roadmap (Gömülü Sistemler)

> **"Yazılımın metale dokunduğu yer."**  
> Mikrodalgadan uzay mekiğine, donanımı yöneten beyin.

---

## 🟢 Seviye 1: Elektronik ve C Dili (Junior)
*Led yakıp söndürmek ve temel devre mantığı.*

### 1. Elektronik 101
- [ ] **Devre Elemanları**: Direnç, Kapasitör, Transistör, Diyot nedir?
- [ ] **Araçlar**: Multimetre (Ölçü aleti) kullanma, Lehim yapma.
- [ ] **Breadboard**: Devre kurma tahtası.

### 2. C Programlama (Ana Dil)
- [ ] **Pointers**: Bellek adresleri. Gömülücülerin korkulu rüyası ama olmazsa olmaz.
- [ ] **Bitwise Operations**: Bit seviyesinde işlemler (`&`, `|`, `^`, `<<`). (Register yönetimi için şart).
- [ ] **Memory Management**: Stack, Heap ve Static bellek yönetimi.

### 3. Arduino (Giriş Kapısı)
- [ ] **Sensörler**: Sıcaklık, Mesafe, Işık sensörlerini okuma.
- [ ] **Aktüatörler**: Motor sürme (Servo, Step), Röle kontrolü.
- [ ] **Haberleşme**: Serial (UART) haberleşmesi.

---

## 🟡 Seviye 2: Mikrodenetleyiciler ve PCB (Mid)
*Profesyonel kart tasarımı ve STM32.*

### 1. STM32 / ARM Cortex-M
- [ ] **HAL Library vs Register**: Hazır kütüphane mi, doğrudan donanıma yazmak mı?
- [ ] **Interrupts (Kesmeler)**: İşlemciyi durdurmadan iş yapma (Butona basılınca anında tepki).
- [ ] **Timers**: Zamanlayıcılar ve PWM (Sinyal genişlik modülasyonu).
- [ ] **ADC/DAC**: Analog sinyali (Sıcaklık) dijitale çevirme.

### 2. İletişim Protokolleri (Haberleşme)
- [ ] **I2C**: 2 kablo ile sensör okuma.
- [ ] **SPI**: Yüksek hızlı veri aktarımı (SD Kart, Ekran).
- [ ] **UART**: Seri haberleşme (Bluetooth, GPS).

### 3. PCB Tasarımı
- [ ] **KiCad / Altium**: Kendi devre kartını çizme ve ürettirme (Gerber dosyası).

---

## 🔴 Seviye 3: RTOS ve Linux (Senior)
*Gerçek zamanlı ve kompleks sistemler.*

### 1. RTOS (Real Time Operating System)
- [ ] **FreeRTOS**: Görev (Task) yönetimi.
- [ ] **Multitasking**: İşlemciyi verimli bölüştürme.
- [ ] **Semaphore / Mutex**: Aynı kaynağa (RAM) erişen görevlerin çakışmasını önleme.

### 2. Embedded Linux
- [ ] **Raspberry Pi**: Linux tabanlı gömülü geliştirmeler.
- [ ] **Yocto / Buildroot**: Kendi Linux dağıtımını (Image) derleme.
- [ ] **Kernel Drivers**: Linux çekirdeğine sürücü yazma (Çok ileri seviye).

---

## 🛠️ Araç Kutusu (Toolkit)
- **Kartlar**: Arduino Uno, STM32 Blue Pill, Raspberry Pi, ESP32 (Wi-Fi/Bluetooth için).
- **IDE**: Keil uVision, STM32CubeIDE, PlatformIO (VS Code).
- **Donanım**: Lojik Analizör (Sinyal izleme), Osiloskop.

---

## 📚 Kaynaklar

| Kaynak | Tip | Dil | Seviye |
| :--- | :--- | :--- | :--- |
| **[DeepBlue (YouTube)](https://www.youtube.com/@DeepBlueEmbedded)** | Video | İngilizce | Orta |
| **[Coşkun Taşdemir](https://www.youtube.com/c/Co%C5%9FkunTa%C5%9Fdemir)** | YouTube | Türkçe | Hepsi |
| **[Nezih Tınas](https://www.youtube.com/user/nezihtinas)** | YouTube | Türkçe | Başlangıç |
| **[EEVblog](https://www.youtube.com/user/EEVblog)** | Video (Elektronik) | İngilizce | Eğlenceli |

---

## 💡 Proje Fikirleri

1.  **Akıllı Ev (IoT)**: ESP32 kullanarak sıcaklığı telefona gönder, telefondan lambayı yak. (MQTT protokolü).
2.  **Çizgi İzleyen Robot**: Sensörlerle siyah çizgiyi takip eden otonom araç. (PID Kontrol algoritması).
3.  **Hava İstasyonu**: Sıcaklık, nem, basınç verilerini ölçüp OLED ekrana yazdır.

---

## ❓ Mülakat Soruları
- 1. `volatile` anahtar kelimesi C'de ne işe yarar? Gömülü sistemlerde neden kritiktir?
- 2. Polling (Sorgulama) ve Interrupt (Kesme) arasındaki fark nedir?
- 3. Watchdog Timer nedir? Sistemi kilitlenmekten nasıl kurtarır?
- 4. Little Endian ve Big Endian farkı nedir?
- 5. I2C ve SPI arasındaki temel farklar nelerdir? Hangi durumda hangisi seçilir?
