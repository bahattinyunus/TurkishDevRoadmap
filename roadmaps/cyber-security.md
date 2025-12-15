# 🔐 Cyber Security Roadmap (Siber Güvenlik)

> **"Sistemi kuran değil, koruyan ol."**  
> Milyon dolarlık sistemlerin açığını bulmak veya onları savunmak.

---

## 🟢 Seviye 1: Temel Bilgiler (Junior)
*Sistemin nasıl çalıştığını bilmeden hackleyemezsin.*

### 1. Ağ (Network) Temelleri
- [ ] **IP & MAC**: Adresleme mantığı.
- [ ] **Ports & Protocols**: TCP, UDP, FTP (21), SSH (22), HTTP (80).
- [ ] **OSI Modeli**: 7 katmanın ne işe yaradığını ezberleme, öğren.
- [ ] **Subnetting**: Bir ağı alt ağlara bölme.

### 2. İşletim Sistemleri
- [ ] **Linux (Kali/Parrot)**: Hacker'ların ana vatanı. Komut satırına hakim ol.
- [ ] **Windows**: Active Directory yapısını öğren (Kurumsal hack için şart).

### 3. Programlama (Temeller)
- [ ] **Python**: Script yazmak, otomasyon (Socket programming).
- [ ] **Bash**: Linux toollarını birbirine bağlamak.

---

## 🟡 Seviye 2: Alan Seçimi (Mid)
*Saldırıyor muyuz (Red), savunuyor muyuz (Blue)?*

### 1. Web Uygulama Güvenliği (Web Sec)
- [ ] **OWASP Top 10**: En kritik 10 web açığı (SQLi, XSS, CSRF, IDOR).
- [ ] **Burp Suite**: HTTP isteklerini yakalayıp değiştirme aracı (Proxy).
- [ ] **Fuzzing**: Sisteme rastgele veri gönderip çökertmeye çalışma.

### 2. Ağ Güvenliği (Net Sec)
- [ ] **Nmap**: Ağ haritalama ve port tarama.
- [ ] **Wireshark**: Ağ paketlerini dinleme (Sniffing).
- [ ] **Firewall & IDS/IPS**: Saldırı tespit ve engelleme sistemleri.

### 3. Kriptografi (Şifreleme)
- [ ] **Hashing**: MD5, SHA-256 (Geri döndürülemez).
- [ ] **Encryption**: AES, RSA (Anahtarla geri döndürülebilir).
- [ ] **OpenSSL**: Sertifika işlemleri.

---

## 🔴 Seviye 3: İleri Uzmanlık (Senior)
*Sistemlerin derinlikleri ve kurumsal savunma.*

### 1. Red Team (Offensive)
- [ ] **Exploit Development**: Buffer Overflow zafiyetleri için exploit yazma (C/Assembly).
- [ ] **Metasploit Framework**: Hazır exploitleri kullanma ve payload oluşturma.
- [ ] **Social Engineering**: İnsanları kandırarak şifre alma (Phishing).

### 2. Blue Team (Defensive)
- [ ] **SIEM (Security Information and Event Management)**: Splunk, ELK. Log analizi.
- [ ] **Incident Response**: Saldırı anında ne yapılmalı? Kanıt toplama (Forensics).
- [ ] **Malware Analysis**: Virüslerin nasıl çalıştığını tersine mühendislik (Reverse Engineering) ile çözme (Ghidra, IDA Pro).

---

## 🛠️ Araç Kutusu (Toolkit)
- **OS**: Kali Linux veya Parrot OS.
- **Scanner**: Nmap, Nessus.
- **Web**: Burp Suite (Community / Pro).
- **Forensics**: Autopsy.

---

## 📚 Kaynaklar

| Kaynak | Tip | Dil | Seviye |
| :--- | :--- | :--- | :--- |
| **[TryHackMe](https://tryhackme.com/)** | İnteraktif Lab | İngilizce | Başlangıç |
| **[Hack The Box](https://www.hackthebox.com/)** | Lab & CTF | İngilizce | Orta/İleri |
| **[PortSwigger Academy](https://portswigger.net/web-security)** | Eğitim (Web) | İngilizce | Hepsi |
| **[Can Değer (YouTube)](https://www.youtube.com/c/CanDeger)** | Video | Türkçe | Başlangıç |

---

## 💡 Proje Fikirleri

1.  **Keylogger Yaz**: Python ile basılan tuşları kaydedip maile atan basit bir script (Kendi bilgisayarında dene!).
2.  **Kendi Laboratuvarını Kur**: VirtualBox ile zafiyetli makineler (Metasploitable, DVWA) kur ve hacklemeye çalış.
3.  **Port Scanner**: Nmap'in basit bir versiyonunu Python ile yaz.

---

## ❓ Mülakat Soruları
- 1. Symmetric ve Asymmetric şifreleme farkı nedir?
- 2. Bir sistemde "Ping" (ICMP) kapalıysa o makinenin açık olduğunu nasıl anlarsın?
- 3. "Salting" nedir ve parolaları saklarken neden kullanılır?
- 4. XSS (Cross Site Scripting) açığı olan bir sayfadan nasıl cookie çalınır?
- 5. Man-in-the-Middle (Ortadaki Adam) saldırısı nasıl çalışır?
