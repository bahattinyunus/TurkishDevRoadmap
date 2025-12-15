# 🧠 Backend Roadmap (Arka Uç Geliştirme)

> **"Buzdağının görünmeyen yüzü."**  
> Verinin saklandığı, işlem gördüğü ve güvenliğin sağlandığı makine dairesi.

---

## 🟢 Seviye 1: Başlangıç (Junior)
*Bir sunucu ayağa kaldırıp veri kaydedebilme.*

### 1. Dil Seçimi (Birini Seç ve Ustalaş)
- **Node.js (JavaScript)**: Frontend bilginle backend yazabilirsin. Startup'lar sever.
- **Python**: Yapay zeka'ya yakın, sözdizimi kolay. (Django/FastAPI).
- **Go (Golang)**: Google tarafından geliştirildi. Çok hızlı, concurrency kralı.
- **Java / C#**: Kurumsal şirketlerin vazgeçilmezi. Sağlam, tip güvenli.
- **PHP**: Web'in %70'i hala PHP. Laravel ile çok modern.

### 2. Temel Veritabanı (Database)
- [ ] **İlişkisel (SQL)**: Tablolar ve ilişkilendirme. `SELECT * FROM users`.
    - PostgreSQL (Önerilen) veya MySQL.
- [ ] **NoSQL (Document)**: JSON formatında veri saklama. Esnek.
    - MongoDB.

### 3. API Geliştirme Temelleri
- [ ] **HTTP Methodları**: GET, POST, PUT, DELETE, PATCH.
- [ ] **Status Codes**: 200, 201, 400, 401, 404, 500.
- [ ] **Postman / Insomnia**: API'leri test etme aracı.

---

## 🟡 Seviye 2: Orta (Mid)
*Ölçeklenebilir kod yazma ve mimari.*

### 1. Advanced API & Security
- [ ] **Authentication (Kimlik Doğrulama)**: "Sen kimsin?". JWT (JSON Web Token), OAuth2 (Google ile giriş).
- [ ] **Authorization (Yetkilendirme)**: "Bunu yapmaya iznin var mı?". Role-based Access Control (RBAC).
- [ ] **REST Best Practices**: Doğru URL yapısı (`/users/123/orders`).

### 2. Veritabanı Optimizasyonu
- [ ] **ORM (Object Relational Mapping)**: SQL yazmadan kodla veritabanı yönetimi (Prisma, TypeORM, Entity Framework).
- [ ] **Indexing**: Sorguları hızlandırma sanatı.
- [ ] **Caching**: Veritabanı yorulmasın diye Redis kullanma.

### 3. Deployment & DevOps Giriş
- [ ] **Docker**: Uygulamayı konteyner içine hapsetme ("Benim makinede çalışıyordu" sorununa son).
- [ ] **CI/CD**: GitHub Actions ile otomatik test ve deploy.
- [ ] **Linux Sunucu Yönetimi**: Nginx, Reverse Proxy.

---

## 🔴 Seviye 3: İleri (Senior)
*Milyonlarca kullanıcıya hizmet eden sistemler kurma.*

### 1. Sistem Mimarisi (System Design)
- [ ] **Monolith vs Microservices**: Ne zaman hangisi? (Hype'a kapılma!).
- [ ] **Load Balancing**: Trafiği birden fazla sunucuya dağıtma (Nginx, HAProxy).
- [ ] **Message Queues (Kuyruklar)**: Asenkron işlem yapma. (RabbitMQ, Kafka, Redis Pub/Sub).
- [ ] **Event-Driven Architecture**: Olay tabanlı sistemler.

### 2. Scalability (Ölçeklenebilirlik)
- [ ] **Scaling**:
    - **Vertical (Dikey)**: Daha güçlü RAM/CPU (Pahalı, limitli).
    - **Horizontal (Yatay)**: Daha fazla sunucu (Ucuz, limitsiz).
- [ ] **Sharding/Partitioning**: Veritabanını parçalara bölme.
- [ ] **CAP Teoremi**: Consistency, Availability, Partition Tolerance üçgeni.

### 3. Güvenlik (Advanced Security)
- [ ] **OWASP Top 10**: SQL Injection, XSS, CSRF saldırılarını anlama ve önleme.
- [ ] **Rate Limiting**: API'ye aşırı isteği engelleme.

---

## 🛠️ Araç Kutusu (Toolkit)
- **API Tool**: Postman veya Thunder Client (VS Code Eklentisi).
- **Database GUI**: DBeaver (Her veritabanına bağlanır).
- **Container**: Docker Desktop.

---

## 📚 Kaynaklar

| Kaynak | Tip | Dil | Seviye |
| :--- | :--- | :--- | :--- |
| **[Roadmap.sh Backend](https://roadmap.sh/backend)** | Görsel Harita | İngilizce | Hepsi |
| **[Kodluyoruz Backend Patikası](https://app.patika.dev/paths)** | Bootcamp | Türkçe | Başlangıç |
| **[Node.js Design Patterns](https://www.nodejsdesignpatterns.com/)** | Kitap | İngilizce | İleri |
| **[System Design Primer](https://github.com/donnemartin/system-design-primer)** | GitHub Repo | İngilizce | İleri |

---

## 💡 Proje Fikirleri

1.  **Blog API**: CRUD işlemleri yap. Kullanıcılar üye olsun, yazı yazsın. (Auth + DB).
2.  **Real-time Chat**: Socket.io kullanarak anlık mesajlaşma uygulaması yap. (WebSockets).
3.  **URL Shortener (Link Kısaltıcı)**: `bit.ly` klonu. Redis kullanarak performansı artır.
4.  **E-Ticaret Backend**: Karmaşık veritabanı ilişkileri (Sipariş, Ürün, Kategori, Kullanıcı).

---

## ❓ Mülakat Soruları
- 1. SQL ve NoSQL arasındaki temel farklar nelerdir? Hangisi ne zaman seçilmeli?
- 2. "ACID" prensipleri nelerdir? (Atomicity, Consistency, Isolation, Durability).
- 3. Monolitik mimari ile Mikroservis mimarisi arasındaki farklar nelerdir?
- 4. Bir API'de Authentication (AuthN) ve Authorization (AuthZ) farkı nedir?
- 5. High Cohesion (Yüksek Bağlılık) ve Loose Coupling (Gevşek Bağımlılık) nedir?
