# 🔥 Fullstack Roadmap (Tam Yığın Geliştirme)

> **"Tek kişilik ordu."**  
> Hem Frontend hem Backend dünyasına hakim, bir projeyi A'dan Z'ye tek başına hayata geçirebilen geliştirici.

---

## 🟢 Seviye 1: Başlangıç (Stack Seçimi)
*İki tarafı birleştirip basit bir uygulama çıkarma.*

### 1. Stack Seçimi (Birini Seç)
Tüm dilleri öğrenmeye çalışma, uyumlu ikilileri seç.

- **MERN Stack** (En Popüler): MongoDB, Express, React, Node.js.
- **T3 Stack** (Modern & Type-Safe): Next.js, TypeScript, Tailwind, Prisma, tRPC.
- **Java Spring + Angular**: Kurumsal şirketlerin tercihi.
- **Django (Python) + Vue/React**: Hızlı prototipleme.

### 2. Entegrasyon (Frontend <-> Backend)
- [ ] **API Tüketimi**: Frontend'den Backend'e `fetch` veya `axios` ile istek atma.
- [ ] **CORS Hatası**: "Neden veri gelmiyor?" sorusunun cevabı. Cross-Origin Resource Sharing mantığı.
- [ ] **Environment Variables**: API anahtarlarını `.env` dosyasında saklama. Frontend'e sızdırmama!

---

## 🟡 Seviye 2: Orta (Mid)
*Profesyonel proje geliştirme standartları.*

### 1. Authentication (Tam Entegrasyon)
- [ ] **Session vs JWT**: Kullanıcı girişini frontend ve backend'de senkronize tutma.
- [ ] **Cookie Yönetimi**: `HttpOnly` cookie nedir? Güvenli saklama.
- [ ] **Protected Routes**: Giriş yapmamış kullanıcıyı `/dashboard` sayfasına sokmama.

### 2. State Senkronizasyonu
- [ ] **Server State**: Backend verisini Frontend'de yönetme (TanStack Query / SWR).
- [ ] **Optimistic UI**: Beğeni butonuna basınca sunucudan cevap gelmeden rengi değiştirme hilesi.
- [ ] **Form Handling**: React Hook Form + Zod ile hem client hem server tarafında veri doğrulama.

### 3. Deployment (Bütünleşik Dağıtım)
- [ ] **Monorepo**: Frontend ve Backend kodunu tek repoda tutma (Nx, Turborepo).
- [ ] **Vercel / Netlify**: Next.js projelerini tek tıkla deploy etme.
- [ ] **Docker Compose**: Veritabanı, Backend ve Frontend'i tek komutla ayağa kaldırma.

---

## 🔴 Seviye 3: İleri (Senior)
*Büyük ölçekli sistem tasarımı.*

### 1. İleri Mimari
- [ ] **Backend-for-Frontend (BFF)**: Mobil ve Web için ayrı backend katmanları oluşturma.
- [ ] **Micro-frontends**: Frontend'i parçalara bölüp ayrı ekiplere dağıtma.
- [ ] **Serverless Functions**: AWS Lambda veya Vercel Functions ile sunucusuz backend.

### 2. Performans ve SEO
- [ ] **Edge Computing**: Kodu kullanıcıya en yakın sunucuda çalıştırma.
- [ ] **Image Optimization**: Görselleri CDN üzerinden optimize ederek sunma.
- [ ] **Database Replication**: Okuma (Read) ve Yazma (Write) işlemlerini farklı veritabanlarına yönlendirme.

---

## 🛠️ Araç Kutusu (Toolkit)
- **Monorepo Tools**: Turborepo, Nx.
- **Fullstack Frameworks**: Next.js, Remix, Nuxt.
- **Database ORM**: Prisma (Type-safe veritabanı erişimi).

---

## 📚 Kaynaklar

| Kaynak | Tip | Dil | Seviye |
| :--- | :--- | :--- | :--- |
| **[The Odin Project](https://www.theodinproject.com)** | Web | İngilizce | Hepsi |
| **[FullStackOpen](https://fullstackopen.com/en/)** | Web Course | İngilizce | İleri |
| **[CodeWithAntonio (YouTube)](https://www.youtube.com/@CodeWithAntonio)** | Video | İngilizce | Proje |
| **[Create T3 App](https://create.t3.gg/)** | CLI | İngilizce | Orta |

---

## 💡 Proje Fikirleri

1.  **SaaS (Software as a Service) Platformu**:
    - Kullanıcı üye olur, aylık abonelik satın alır (Stripe/Iyzico).
    - Dashboard'unda verilerini görür.
    - Tech: Next.js + Stripe + Prisma + Supabase.
2.  **Sosyal Medya Klonu**:
    - Tweet atma, beğenme, yorum yapma.
    - Real-time bildirimler (Pusher/Socket.io).
    - Tech: T3 Stack.
3.  **Booking Uygulaması (Airbnb Klonu)**:
    - Takvim seçimi, rezervasyon yapma, ödeme alma.
    - Harita integrasyonu.

---

## ❓ Mülakat Soruları
- 1. "Race Condition" nedir? Frontend ve Backend arasında nasıl sorunlara yol açar?
- 2. GraphQL kullanmanın REST'e göre avantajı ve dezavantajı nedir? Hangi senaryoda hangisi seçilmeli?
- 3. SSR (Server Side Rendering) uygulamasında Authentication nasıl yönetilir? (Cookie vs Header).
- 4. Bir form gönderildiğinde "Double Submit" sorununu nasıl engellersin?
- 5. Cross-Site Scripting (XSS) ve Cross-Site Request Forgery (CSRF) nedir? Nasıl korunulur?
