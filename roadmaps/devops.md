# ☁️ DevOps Roadmap

> **"Code -> Build -> Test -> Deploy -> Monitor"**  
> Yazılım geliştirme (Dev) ve operasyon (Ops) süreçlerini birleştirip otomatize etme kültürü.

---

## 🟢 Seviye 1: Sistem Yöneticiliği (Junior)
*Bir sunucuyu yönetebilme ve sorun çözebilme.*

### 1. Linux & Terminal (Olmazsa Olmaz)
- [ ] **Komut Satırı**: `grep`, `awk`, `sed`, `lsof`, `curl`, `systemctl`.
- [ ] **Shell Scripting**: Bash script ile rutin işleri otomatiğe bağlama (Örn: Logları yedekle).
- [ ] **Network**: DNS, Firewall (iptables/ufw), SSH yönetimi.

### 2. Versiyon Kontrol
- [ ] **Git**: Sadece kod için değil, konfigürasyon dosyaları için de Git.

### 3. Web Server Yönetimi
- [ ] **Nginx / Apache**: Reverse Proxy ayarları, SSL (Let's Encrypt) kurulumu, Load Balancing.

---

## 🟡 Seviye 2: Modern DevOps Araçları (Mid)
*Süreci otomatize etme ve konteynerizasyon.*

### 1. Containerization (Konteyner)
- [ ] **Docker**:
    - `Dockerfile` yazma.
    - `docker-compose` ile çoklu servis yönetimi.
    - Image optimizasyonu (Alpine linux kullanımı).

### 2. CI/CD (Sürekli Entegrasyon/Dağıtım)
- [ ] **Pipeline Mantığı**: "Kod pushlandığında testleri çalıştır, geçerse sunucuya at."
- [ ] **Araçlar**:
    - **GitHub Actions** (En popüler ve modern).
    - **GitLab CI**.
    - **Jenkins** (Eski ama sektörde çok yaygın).

### 3. Cloud (Bulut) Temelleri
- [ ] **AWS (Amazon Web Services)**: EC2 (Sanal Sunucu), S3 (Depolama), RDS (Veritabanı).
- [ ] **Azure / GCP**: Alternatifleri tanı.

---

## 🔴 Seviye 3: Cloud Native & SRE (Senior)
*Altyapıyı kod olarak yönetme ve ölçekleme.*

### 1. IaC (Infrastructure as Code)
- [ ] **Terraform**: Sunucuları, ağları elle değil, kod yazarak kurma (`main.tf`). Cloud bağımsız.
- [ ] **Ansible**: 100 sunucuya aynı anda güncelleme yapma (Configuration Management).

### 2. Container Orchestration
- [ ] **Kubernetes (K8s)**: Docker konteynerlerini yöneten orkestra şefi.
    - Pod, Service, Ingress, ConfigMap kavramları.
    - **Helm**: K8s paket yöneticisi (Kubernetes'in npm'i).

### 3. Monitoring & Logging (Gözlemleme)
- [ ] **Prometheus**: Metrik toplama (CPU, RAM kullanımı).
- [ ] **Grafana**: Verileri görselleştirme (Dashboard).
- [ ] **ELK Stack (Elasticsearch, Logstash, Kibana)**: Log analizi. "Sistem neden çöktü?" sorusunun cevabı.

---

## 🛠️ Araç Kutusu (Toolkit)
- **Terminal**: Oh My Zsh.
- **Editor**: VS Code veya Vim (Sunucuda lazım olur).
- **Tool**: Docker Desktop, Postman.

---

## 📚 Kaynaklar

| Kaynak | Tip | Dil | Seviye |
| :--- | :--- | :--- | :--- |
| **[DevOps Roadmap](https://roadmap.sh/devops)** | Görsel Harita | İngilizce | Hepsi |
| **[Nana Janashia (TechWorld with Nana)](https://www.youtube.com/c/TechWorldwithNana)** | YouTube | İngilizce | Hepsi |
| **[Özgür Yazılım Derneği - Linux Dersleri](https://oyd.org.tr/)** | Doküman | Türkçe | Başlangıç |
| **[DevOpsDays Türkiye](https://devopsdays.org/)** | Konferans | Türkçe | İleri |

---

## 💡 Proje Fikirleri

1.  **Kendi VPN Sunucunu Kur**: DigitalOcean/AWS üzerinde 5$'lık sunucuya OpenVPN veya WireGuard kur.
2.  **Otomatik Deploy (CI/CD)**: Basit bir HTML sayfasını GitHub'a atınca otomatik olarak sunucunda güncellensin (GitHub Actions + SSH).
3.  **Dockerize Et**: Eski bir PHP/Node.js projesini Docker kapsayıcısı haline getir ve tek komutla çalıştır.
4.  **Monitoring**: Sunucunun CPU kullanımını takip eden ve %80'i geçerse sana Telegram'dan mesaj atan bir bot yaz.

---

## ❓ Mülakat Soruları
- 1. Docker ve Sanal Makine (VM) arasındaki fark nedir?
- 2. "Blue-Green Deployment" ve "Canary Release" nedir?
- 3. `git merge` ve `git rebase` farkı nedir?
- 4. CI/CD Pipeline'ı neden patlar? Nasıl debug edersin?
- 5. Kubernetes'te "Pod" nedir? Neden direkt Container kullanmıyoruz?
