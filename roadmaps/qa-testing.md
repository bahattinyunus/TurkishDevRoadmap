# 🧪 QA & Testing Roadmap (Yazılım Test & Kalite)

> **"Kalite asla tesadüf değildir."**  
> Hataları (Bug) canlıya çıkmadan yakalama sanatı.

---

## 🟢 Seviye 1: Manuel Test (Junior)
*Bir kullanıcı gibi siteyi gezmek ve hataları raporlamak.*

### 1. Test Temelleri
- [ ] **SDLC & STLC**: Yazılım Geliştirme ve Test Yaşam Döngüsü.
- [ ] **Bug Report**: İyi bir hata raporu nasıl yazılır? (Adımlar, Beklenen/Gerçekleşen Sonuç, Ekran Görüntüsü).
- [ ] **Jira / Trello**: Hata takibi (Bug Tracking) araçları.

### 2. Test Türleri
- [ ] **Black Box vs White Box**: Kodu görmeden test etme vs Kodu görerek test etme.
- [ ] **Regression Test**: Yeni eklenen özellik eskiyi bozdu mu?
- [ ] **Smoke Test**: "Duman çıkıyor mu?" En temel fonksiyonlar çalışıyor mu kontrolü.

---

## 🟡 Seviye 2: Otomasyon (Automation) - Mid
*Tekrar eden işleri robota yaptırmak.*

### 1. Programlama Dili (Birini Seç)
- **Java**: Selenium ile çok yaygın (Kurumsal).
- **Python**: En kolayı, yapay zeka entegrasyonu var.
- **JavaScript/TypeScript**: Modern web testleri için. (Cypress/Playwright).

### 2. UI Test Otomasyonu
- [ ] **Selenium WebDriver**: Eski kral. Mantığını öğrenmek için iyi.
- [ ] **Cypress**: Hızlı, modern, tarayıcı içinde çalışan popüler araç.
- [ ] **Playwright**: Microsoft tarafından geliştirilen, çok hızlı yeni nesil araç.

### 3. API Otomasyonu
- [ ] **Rest Assured (Java)** veya **Requests (Python)**.
- [ ] **Postman**: Koleksiyon oluşturup test senaryoları (Tests tab) yazma ve otomatiğe bağlama.

---

## 🔴 Seviye 3: Performans ve Mobil (Senior)
*Sistem ne kadar yük kaldırır?*

### 1. Performans Testi (Load Testing)
- [ ] **JMeter**: Klasik yük testi aracı. "Siteye 10.000 kişi aynı anda girerse ne olur?".
- [ ] **k6**: Modern, JavaScript ile test yazılan performans aracı.

### 2. Mobil Test
- [ ] **Appium**: Hem iOS hem Android otomasyonu için standart.

### 3. CI/CD Entegrasyonu
- [ ] Yazılan testleri Jenkins veya GitHub Actions pipeline'ına bağlamak. "Test geçmezse deploy durdurulsun."

---

## 🛠️ Araç Kutusu (Toolkit)
- **Test**: Jira, Xray.
- **Automation**: VS Code, IntelliJ IDEA.
- **API**: Postman.
- **Performance**: JMeter.

---

## 📚 Kaynaklar

| Kaynak | Tip | Dil | Seviye |
| :--- | :--- | :--- | :--- |
| **[Ministry of Testing](https://www.ministryoftesting.com/)** | Topluluk | İngilizce | Hepsi |
| **[Selenium Documentation](https://www.selenium.dev/documentation/)** | Doküman | İngilizce | Orta |
| **[Software Testing Help](https://www.softwaretestinghelp.com/)** | Web | İngilizce | Başlangıç |
| **[Cypress Real World App](https://github.com/cypress-io/cypress-realworld-app)** | Proje | İngilizce | Orta |

---

## 💡 Proje Fikirleri

1.  **E-Ticaret Test Senaryosu**: Amazon'da ürün arama, sepete ekleme ve satın alma adımlarını **Selenium/Playwright** ile otomatize et.
2.  **API Test Projesi**: `jsonplaceholder.typicode.com` API'sine kullanıcı ekleyen, silen testleri **Postman** ile yaz.
3.  **Yük Testi**: Kendi blog sitene 500 sanal kullanıcı ile saldırı yap (dikkatli ol, sunucuyu çökertme!) ve rapor al.

---

## ❓ Mülakat Soruları
- 1. Test Piramidi (Test Pyramid) nedir?
- 2. "Positive Testing" ve "Negative Testing" farkı nedir?
- 3. Explicit Wait, Implicit Wait ve Fluent Wait arasındaki farklar nelerdir?
- 4. Bir Bug bulduğunda Developer "Bende çalışıyor (It works on my machine)" derse ne yaparsın?
- 5. Manuel test ile Otomasyon testi arasındaki ROI (Return on Investment) dengesi nasıl kurulur?
