# 👨‍💻 Temel Yazılım Bilgisi (Fundamentals)

> **"Temeli sağlam olmayan bina en ufak sarsıntıda yıkılır."**  
> Hangi alanı seçerseniz seçin (Frontend, Backend, AI, Mobile), buradaki bilgiler sizin **ortak dilinizdir**.

---

## 🟢 Seviye 1: Başlangıç (Junior)
*Bu kavramları adınız gibi bilmelisiniz.*

### 1. İnternet Nasıl Çalışır?
- [ ] **Internet vs Web**: İnternet altyapıdır, Web (WWW) onun üzerinde çalışan bir servistir.
- [ ] **HTTP/HTTPS**: Tarayıcı ve sunucu nasıl konuşur? (GET, POST nedir?)
- [ ] **DNS (Domain Name System)**: `google.com` yazınca arkada dönen IP adresi eşleşmesi.
- [ ] **Hosting & Domain**: Alan adı tescili ve sunucu kiralama mantığı.
- [ ] **Tarayıcılar (Browsers)**: Chrome, Firefox bir web sayfasını nasıl render eder (çizer)?

### 2. İşletim Sistemleri & Terminal
- [ ] **Terminal Korkusunu Yen**: Siyah ekrandan korkma!
    - `cd`: Klasör değiştir.
    - `ls` (Mac/Linux) / `dir` (Windows): Dosyaları listele.
    - `mkdir`: Klasör oluştur.
    - `touch` / `echo`: Dosya oluştur.
    - `rm`: Sil (Dikkatli ol!).
- [ ] **Linux Temelleri**: Sunucuların %90'ı Linux kullanır. Dosya izinleri (chmod), kullanıcılar.

### 3. Git & Versiyon Kontrol
- [ ] **Neden Git?**: "final_proje_v2_son_gercekten_son.zip" karmaşasından kurtulun.
- [ ] **Temel Komutlar**:
    - `git init`: Projeyi başlat.
    - `git add .`: Dosyaları sahneye al.
    - `git commit -m "mesaj"`: Değişikliği kaydet.
    - `git push`: Buluta (GitHub) gönder.
    - `git pull`: Buluttan çek.
- [ ] **GitHub/GitLab**: Kod barındırma servisleri. Repo oluşturma, Star/Fork mantığı.

---

## 🟡 Seviye 2: Orta (Mid)
*Profesyonel hayatta her gün karşılaşacağınız senaryolar.*

### 1. Veri Yapıları ve Algoritmalar (CS101)
- [ ] **Veri Yapıları**: Array, Linked List, Stack, Queue, Hash Map (Dictionary). Nerede hangisi kullanılır?
- [ ] **Algoritma Mantığı**: Sorting (Sıralama), Searching (Arama).
- [ ] **Big O Notation**: Kodum ne kadar hızlı? O(1) vs O(n) vs O(n^2).

### 2. İleri Git
- [ ] **Branching (Dallanma)**: `main` bozulmasın diye `feature` dalında çalışmak.
- [ ] **Merge & Conflict**: Aynı dosyayı iki kişi değiştirirse ne olur? Çatışma çözme (Conflict Resolution).
- [ ] **Pull Request (PR)**: Kodunu takım arkadaşına inceletme (Code Review).
- [ ] **Gitignore**: Hangi dosyalar (şifreler, node_modules) repoya atılmamalı?

### 3. Ağ (Networking) Derinlik
- [ ] **IP & Port**: 127.0.0.1 (Localhost) nedir? Port 80, 443, 3000 ne işe yarar?
- [ ] **HTTP Status Codes**:
    - `200`: Başarılı.
    - `404`: Bulunamadı.
    - `500`: Sunucu Hatası (Backend patladı).
    - `401/403`: Yetkisiz giriş.
- [ ] **JSON & XML**: Veri taşıma formatları.

---

## 🔴 Seviye 3: İleri (Senior)
*Sistemi tasarlayan ve optimize eden mühendis seviyesi.*

### 1. Performans ve Güvenlik
- [ ] **Character Encoding**: UTF-8, ASCII farkları. Emoji neden bazen bozuk çıkar?
- [ ] **Hashing & Encryption**: Şifreler veritabanında nasıl saklanır? (Asla düz metin saklama!).
- [ ] **SSH**: Sunucuya şifresiz, anahtar dosyası ile bağlanma.

### 2. Mimari Kavramlar (Giriş)
- [ ] **RESTful API**: API tasarım standartları.
- [ ] **Design Patterns (Tasarım Desenleri)**: Singleton, Factory, Observer. (Dil bağımsız).
- [ ] **Clean Code**: Okunabilir, sürdürülebilir kod yazma (SOLID Prensipleri giriş).

---

## 🛠️ Araç Kutusu (Toolkit)
- **Editör**: VS Code (Eklentiler: Prettier, ESLint, GitLens).
- **Terminal**: Windows Terminal (PowerShell) veya iTerm2 (Mac).
- **Tarayıcı**: Chrome DevTools kullanmayı öğrenin.

---

## 📚 Kaynaklar

| Kaynak | Tip | Dil | Seviye |
| :--- | :--- | :--- | :--- |
| **[CS50: Introduction to Computer Science](https://pll.harvard.edu/course/cs50-introduction-computer-science)** | Kurs | İngilizce | Başlangıç |
| **[BTK Akademi - Bilgi Teknolojilerine Giriş](https://www.btkakademi.gov.tr)** | Video | Türkçe | Başlangıç |
| **[Git - The Simple Guide](https://rogerdudler.github.io/git-guide/index.tr.html)** | Web | Türkçe | Başlangıç |
| **[Patika.dev](https://www.patika.dev)** | Bootcamp | Türkçe | Hepsi |
| **[Tech Terms Definitions](https://techterms.com/)** | Sözlük | İngilizce | Orta |

---

## 💡 Proje Fikirleri
Öğrendiklerini pekiştirmek için yap:

1.  **Kişisel Wiki Sayfası**: HTML/CSS kullanarak öğrendiğin terimleri (DNS, HTTP) anlatan basit bir statik site yap.
2.  **Terminal Gezgini**: Sadece terminal kullanarak klasörler arası gez, dosya oluştur, sil ve bir metin dosyasının içine yazı yaz.
3.  **Git Günlüğü**: Bir proje klasörü aç, her gün öğrendiğin bir şeyi text dosyasına yaz, commit at ve GitHub'a pushla. (Green squares doldurma sanatı!).

---

## ❓ Mülakat Soruları (Interview Questions)
- 1. `google.com`'a bastığımda ekrana görüntü gelene kadar geçen sürede arka planda neler olur? (DNS, IP, Handshake, Request/Response).
- 2. Git'te `merge` ve `rebase` arasındaki fark nedir?
- 3. HTTP ve HTTPS arasındaki fark nedir? SSL sertifikası ne işe yarar?
- 4. Stack ve Heap memory farkı nedir?
- 5. ASCII ve Unicode (UTF-8) arasındaki fark nedir?
