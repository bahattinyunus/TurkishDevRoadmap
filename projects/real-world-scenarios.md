# 🌍 Gerçek Hayat Senaryoları (Real World Scenarios)

> **"To-Do List yapmaktan sıkılanlara..."**  
> Sektörde gerçekten istenecek, CV'nizi parlatacak kompleks proje fikirleri.

---

## 1. E-Ticaret Platformu (Fullstack)
*Basit bir sepet uygulamasının ötesinde.*

### Gereksinimler
- **Roller**: Admin (Ürün ekler, Sipariş yönetir), Müşteri (Alışveriş yapar).
- **Özellikler**:
    - **Filtreleme**: Fiyat aralığı, markaya göre filtreleme (Backend tarafında yapılmalı, Front-end'de değil).
    - **Stok Yönetimi**: Aynı anda iki kişi son 1 kalan ürünü almaya çalışırsa? (Concurrency Handling).
    - **Ödeme**: Iyzico veya Stripe test entegrasyonu.
    - **Sipariş Takibi**: "Hazırlanıyor", "Kargoda" durum güncellemeleri.

### Teknoloji Önerisi
- Next.js (Frontend & Backend) + PostgreSQL (DB) + Prisma (ORM) + Stripe.

---

## 2. SaaS (Software as a Service) Abonelik Sistemi
*Aylık ödeme alan bir yazılım.*

### Senaryo
Kullanıcıların notlarını yapay zeka ile özetleyen bir uygulama (Notes AI).

### Gereksinimler
- **Auth**: Google ile giriş.
- **Abonelik**:
    - **Free Plan**: Ayda 5 not özeti.
    - **Pro Plan**: Sınırsız not özeti ($9/ay).
- **Limit Kontrolü**: Ücretsiz kullanıcı 6. notu atmaya çalışırsa engelle (Middleware).
- **Webhook**: Kullanıcı ödemeyi iptal ederse sistemden yetkisini otomatik al.

### Teknoloji Önerisi
- T3 Stack (Next.js, tRPC, Tailwind) + Stripe Billing + OpenAI API.

---

## 3. Real-Time Chat & Collaboration
*Slack veya Discord'un minik versiyonu.*

### Gereksinimler
- **Anlık Mesajlaşma**: Sayfa yenilemeden mesaj gelsin (WebSockets).
- **Kanallar**: Kullanıcılar kendi odalarını kurabilsin.
- **Online/Offline**: Kim çevrimiçi göster.
- **Yazıyor...**: Karşı taraf yazarken "Yazıyor..." ibaresi çıksın.

### Teknoloji Önerisi
- Node.js (Socket.io) veya Pusher + React + Redis (Hızlı veri için).

---

## 4. Rezervasyon Sistemi (Booking)
*Otel veya Kuaför randevusu.*

### Gereksinimler
- **Takvim**: Dolu günleri engelle.
- **Çakışma Kontrolü**: Aynı saatte iki kişi randevu alamasın.
- **E-posta Bildirimi**: Randevu alınca onay maili gitsin (Nodemailer / Resend).
- **Admin Paneli**: İş yeri sahibi takvimi yönetsin.

---

## 5. IoT Dashboard (Veri Görselleştirme)
*Sensör verilerini izleme.*

### Gereksinimler
- **Veri Akışı**: Simüle edilmiş 1000 cihazdan her saniye sıcaklık verisi aksın.
- **Grafik**: Canlı akan grafikte (Line Chart) veriyi göster.
- **Alarm**: Sıcaklık 50 dereceyi geçerse Dashboard kıpkırmızı olsun.

### Teknoloji Önerisi
- Go (Backend - Hız için) + React (Recharts kütüphanesi).

---

> 🚀 **Tavsiye**: Bu projelerden **birini** tam anlamıyla bitirip, canlıya alıp (Vercel/Railroad vb.), GitHub'a temiz kodla koyarsan, Junior pozisyonlarının %90'ına kabul alırsın. Hepsini yarım yapma, birini tam yap.
