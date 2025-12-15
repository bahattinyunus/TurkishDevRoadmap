# 🌐 Frontend Roadmap (Arayüz Geliştirme)

> **"Kullanıcının gördüğü her şey."**  
> Tasarımı koda döken, performans ve estetiği birleştiren mühendislik sanatı.

---

## 🟢 Seviye 1: Başlangıç (Junior)
*Bir web sitesini sıfırdan yapabilme yeteneği.*

### 1. HTML5 (İskelet)
- [ ] **Semantic Elements**: `<header>`, `<main>`, `<section>`, `<article>`. Div çorbası yapma!
- [ ] **SEO Basics**: Meta tag'ler, Open Graph (OG) tag'leri.
- [ ] **Forms**: Validation, Input types.
- [ ] **Accessibility (A11y)**: `aria-label`, `alt` text.

### 2. CSS3 (Makyaj)
- [ ] **Box Model**: Margin, Padding, Border, Content. Bunu anlamadan ilerleyemezsin.
- [ ] **Layouts**:
    - **Flexbox**: Tek boyutlu dizilim (Row/Column).
    - **Grid**: İki boyutlu dizilim (Layout iskeleti).
- [ ] **Responsive Design**: `@media queries` ile mobilde düzgün görünen siteler.
- [ ] **Modern CSS**: Variables (var(--color)), `calc()`, Pseudo-classes (`:hover`, `:nth-child`).

### 3. JavaScript (Beyin)
- [ ] **DOM Manipulation**: `document.getElementById`, `querySelector`, `addEventListener`.
- [ ] **ES6+ Özellikleri**:
    - Arrow Functions `() => {}`.
    - Template Literals `` `Hello ${name}` ``.
    - Destructuring `const { name } = user`.
    - Spread/Rest Operator `...data`.
- [ ] **Fetch API**: Sunucudan veri çekme.

---

## 🟡 Seviye 2: Orta (Mid)
*Frameworkler ve Modern Ekosistem.*

### 1. Modern Frameworkler (Birini Seç)
- [ ] **React** (Sektör Standartı):
    - JSX mantığı.
    - **Hooks**: `useState`, `useEffect`, `useMemo`, `useCallback`.
    - **Context API**: State yönetimi.
- [ ] **Vue.js**: Daha kolay öğrenim eğrisi.
- [ ] **Angular**: TypeScript tabanlı, her şey dahil (batteries-included) yapı.

### 2. CSS Frameworks & Preprocessors
- [ ] **Tailwind CSS**: Utility-first yaklaşım (Sektörde çok popüler).
- [ ] **Sass/SCSS**: CSS'i programlama dili gibi yazmak (Variables, Nesting).
- [ ] **UI Libraries**: Material UI, Ant Design, Shadcn/UI (Copy-paste componentler).

### 3. Paket Yönetimi & Tooling
- [ ] **NPM / Yarn / PNPM**: Paket yükleme ve `package.json` yönetimi.
- [ ] **Vite**: Webpack yerine kullanılan, çok hızlı build tool.

---

## 🔴 Seviye 3: İleri (Senior)
*Performans, Mimari ve Ölçeklenebilirlik.*

### 1. Advanced React & Meta-Frameworks
- [ ] **Next.js**:
    - **SSR (Server Side Rendering)**: SEO için sunucuda render.
    - **SSG (Static Site Generation)**: Işık hızında bloglar.
    - **Server Actions**: API yazmadan veri tabanına erişim.
- [ ] **State Management**: Redux Toolkit, Zustand, TanStack Query (Server State).

### 2. Performans (Web Vitals)
- [ ] **LCP/CLS/FID**: Google'ın hız kriterleri.
- [ ] **Lazy Loading**: Görselleri ve komponentleri sadece gerektiğinde yükle.
- [ ] **Bundle Analysis**: Büyük kütüphaneleri tespit et ve küçült.

### 3. Testing & Type Safety
- [ ] **TypeScript**: JavaScript'e tip güvenliği getirir. `interface`, `type`, `generics`.
- [ ] **Testing**:
    - **Unit**: Jest / Vitest.
    - **E2E (End-to-End)**: Cypress / Playwright.

---

## 🛠️ Araç Kutusu (Toolkit)
- **Browser**: Chrome React Developer Tools.
- **Design**: Figma (Tasarımcıdan gelen çizimi koda dökme).
- **Linter**: ESLint & Prettier (Kod formatı).

---

## 📚 Kaynaklar

| Kaynak | Tip | Dil | Seviye |
| :--- | :--- | :--- | :--- |
| **[MDN Web Docs](https://developer.mozilla.org)** | Doküman | İngilizce | Hepsi |
| **[Sadık Turan - Komple Uygulamalı Web Geliştirme](https://www.udemy.com/course/komple-uygulamali-web-gelistirme-egitimi/)** | Kurs | Türkçe | Başlangıç |
| **[React Resmi Dokümanları (Beta)](https://react.dev)** | Doküman | İngilizce | Orta |
| **[Protürk - Tayfun Erbilen](https://prototurk.com/)** | Web | Türkçe | Orta |
| **[Frontend Masters](https://frontendmasters.com)** | Kurs | İngilizce | İleri |

---

## 💡 Proje Fikirleri

1.  **To-Do List**: Klasik ama öğretici. Ekle, Sil, Düzenle, LocalStorage'da sakla.
2.  **Hava Durumu Uygulaması**: API'den veri çek, asenkron işlemleri (Async/Await) öğren.
3.  **E-Ticaret Sepeti**: Ürün ekle, fiyat topla, global state (Context/Redux) kullan.
4.  **Netflix Klonu**: API ile film verilerini çek, slider yap, Next.js kullan.

---

## ❓ Mülakat Soruları
- 1. `var`, `let` ve `const` farkı nedir? Scope kavramını açıkla.
- 2. React'te `Virtual DOM` nedir, nasıl çalışır ve neden hızlıdır?
- 3. `Block` element ile `Inline` element farkı nedir?
- 4. "Callback Hell" nedir ve Promise/Async-Await ile nasıl çözülür?
- 5. SSR (Server Side Rendering) ve CSR (Client Side Rendering) farkları nelerdir?
