# 📱 Mobile Roadmap (Mobil Uygulama Geliştirme)

> **"Herkesin cebine gir."**  
> Telefon ve tabletler için uygulama geliştirmek.

---

## 🟢 Seviye 1: Yol Ayrımı ve Başlangıç (Junior)
*Mobil dünyaya ilk adım.*

### 1. Hangi Yolu Seçmeliyim? (Cross vs Native)
- **Cross-Platform (Önerilen)**: Tek kodla hem iOS hem Android.
    - **Flutter (Dart)**: Google arkasında. Performansı çok iyi, UI çizimi çok esnek.
    - **React Native (JS/TS)**: Web bilgin varsa çok hızlı öğrenirsin. Instagram, Discord bunu kullanır.
- **Native (Yerel)**: En yüksek performans ve platforma özel özellikler.
    - **iOS (Swift)**: Sadece Apple ürünleri için. Mac bilgisayar şart.
    - **Android (Kotlin)**: Sadece Android cihazlar için.

### 2. Temel UI (Arayüz)
- [ ] **Component/Widget Yapısı**: Butonlar, Listeler, Yazı alanları.
- [ ] **Layout**:
    - Flutter: Row, Column, Stack, ListView.
    - React Native: Flexbox.
- [ ] **Navigation**: Sayfalar arası geçiş (Push/Pop).

---

## 🟡 Seviye 2: Orta (Mid)
*Profesyonel uygulama geliştirme.*

### 1. State Management (Veri Yönetimi)
- [ ] **Flutter**: Provider, Riverpod, Bloc.
- [ ] **React Native**: Redux Toolkit, Zustand, Context API.
- Ufak uygulamada `setState`, büyüyünce `Bloc` veya `Redux` şart.

### 2. Veri ve API
- [ ] **Local Storage**: Küçük verileri telefonda saklama (Shared Preferences / AsyncStorage).
- [ ] **Local DB**: SQLite, Hive, Realm (Büyük veriler ve offline mod için).
- [ ] **API Entegrasyonu**: Sunucudan veri çekme (Dio / Axios). JSON parse etme.

### 3. Cihaz Özelliklerini Kullanma
- [ ] **Kamera & Galeri**: Fotoğraf çekme, yükleme.
- [ ] **GPS & Haritalar**: Konum alma, Google Maps gösterme.
- [ ] **Push Notification**: Bildirim gönderme (Firebase FCM).

---

## 🔴 Seviye 3: İleri (Senior)
*Store'a çıkmaya hazır, optimize edilmiş uygulamalar.*

### 1. Architecture & Clean Code
- [ ] **Design Patterns**: MVVM (Model-View-ViewModel), MVC.
- [ ] **Clean Architecture**: Katmanlı mimari (Data, Domain, Presentation). Kodun test edilebilir olsun.

### 2. Store Süreçleri (Dağıtım)
- [ ] **App Store (iOS)**: Apple Developer Program ($99/yıl). TestFlight ile test, Review süreci.
- [ ] **Google Play (Android)**: Google Play Console ($25 tek seferlik). Release trackler (Alpha, Beta).
- [ ] **CI/CD**: Fastlane ile otomatik build alma ve markete yükleme.

### 3. Native Modules (Köprüler)
- [ ] Bazen Flutter/RN yetmez. Swift veya Kotlin yazarak "Native Module" oluşturup JS/Dart tarafından onu çağırmayı öğren.

---

## 🛠️ Araç Kutusu (Toolkit)
- **IDE**: VS Code (Flutter/RN), Xcode (iOS), Android Studio (Android).
- **Emülatör**: Bilgisayarında sanal telefon çalıştırma (Android Emulator / iOS Simulator).
- **Backend (Mobile için)**: Firebase (Auth, Database, Analytics tek pakette).

---

## 📚 Kaynaklar

| Kaynak | Tip | Dil | Seviye |
| :--- | :--- | :--- | :--- |
| **[Flutter Resmi Dokümanları](https://docs.flutter.dev/)** | Doküman | İngilizce | Hepsi |
| **[React Native Express](https://www.reactnative.express/)** | Web | İngilizce | Başlangıç |
| **[Veli Bacık - Flutter Eğitimi](https://www.youtube.com/c/VeliBacik)** | YouTube | Türkçe | Orta/İleri |
| **[Atıl Samancıoğlu - Mobile Bootcamp](https://www.udemy.com/user/atilsamancioglu/)** | Kurs | Türkçe | Başlangıç |

---

## 💡 Proje Fikirleri

1.  **Haber Uygulaması**: API'den haberleri çek, listele, detaya git.
2.  **Fitness Takipçisi**: Adım sayar (Pedometer), kalori hesabı, günlük su takibi (Local DB kullan).
3.  **Sohbet Uygulaması**: Firebase kullanarak gerçek zamanlı mesajlaşma. Fotoğraf gönderme eklenebilir.
4.  **Duvar Kağıdı (Wallpaper) App**: Yüksek çözünürlüklü resimler, indir butonu, favorilere ekleme.

---

## ❓ Mülakat Soruları
- 1. Flutter'da `StatelessWidget` ve `StatefulWidget` farkı nedir?
- 2. React Native'de "Bridge" (Köprü) mantığı nasıl çalışır?
- 3. iOS ve Android'de uygulama yaşam döngüsü (App Lifecycle) nasıl işler? (Background, Foreground).
- 4. "Offline First" ne demektir? Bir uygulama internet yokken nasıl çalışır?
- 5. Uygulama boyutunu (APK/IPA size) küçültmek için neler yapılabilir?
