# 🎮 Game Development Roadmap (Oyun Geliştirme)

> **"Hayal gücünün sınırlarını zorla."**  
> Kodlama, sanat, matematik ve fiziğin birleştiği nokta.

---

## 🟢 Seviye 1: Motor Seçimi ve Temeller (Junior)
*Karakteri hareket ettirip ekrana "Hello World" yazdırmak.*

### 1. Oyun Motoru (Hangisini Seçmeli?)
- **Unity (C#)**: Mobil ve Indie oyunların kralı. Kaynak çok, öğrenmesi orta zorlukta.
- **Unreal Engine (C++ / Blueprint)**: AAA (Büyük bütçeli) ve gerçekçi 3D oyunlar için. Görsel programlama (Blueprint) var.
- **Godot (GDScript)**: Açık kaynak, tamamen ücretsiz ve çok hafif. 2D için harika.

### 2. Temel Kavramlar
- [ ] **Game Loop**: Oyun döngüsü (`Update()`) nasıl çalışır? FPS (Frame Per Second) mantığı.
- [ ] **Coordinate System**: X, Y, Z eksenleri. 2D ve 3D uzayda konum (Position), Dönme (Rotation), Büyüklük (Scale).
- [ ] **Input Handling**: Klavye, Mouse veya Dokunmatik girişleri okuma.
- [ ] **Physics (Fizik)**:
    - **Collider**: Çarpışma kutusu.
    - **Rigidbody**: Yerçekimi ve fizik kurallarını objeye uygulama.

---

## 🟡 Seviye 2: Oyun Mekanikleri ve Matematik (Mid)
*Oynanabilir, keyifli bir oyun döngüsü kurmak.*

### 1. Oyun Matematiği (Korkma!)
- [ ] **Vectors**: Hız ve yön hesaplama. İki nokta arası mesafe.
- [ ] **Quaternions**: 3D uzayda dönme işlemleri (Gimbal lock sorununu çözmek için).
- [ ] **Raycasting**: "Silahın namlusundan çıkan görünmez çizgi düşmana çarptı mı?" kontrolü.

### 2. UI ve Ses
- [ ] **Canvas/UI**: Can barı, skor tablosu, menü tasarımı.
- [ ] **Audio**: Arkaplan müziği (Loop) vs Efekt sesleri (One-shot). 3D ses (sesin sağdan/soldan gelmesi).

### 3. Animasyon
- [ ] **Animator Controller**: Koşma animasyonundan zıplamaya geçiş (State Machine).
- [ ] **Tweening**: Kod ile yumuşak hareketler yaptırma (DOTween kütüphanesi).

---

## 🔴 Seviye 3: İleri (Senior)
*Performans canavarı, online ve görsel şölen sunan oyunlar.*

### 1. Graphics & Shaders (Görsel Programlama)
- [ ] **Shader Graph / HLSL**: Işığın objeye nasıl vurduğunu, su efektini, çizgi film (Toon) efektini kodlama.
- [ ] **Post-Processing**: Bloom (Parlama), Color Grading (Renk tonu), Blur efektleri.
- [ ] **Lighting**: Real-time vs Baked lighting (Işıkları önceden hesaplayıp performansı artırma).

### 2. Multiplayer (Çok Oyunculu)
- [ ] **Network Architecture**: Server-Client yapısı. Hile koruması (Anti-cheat) için mantık sunucuda çalışmalı.
- [ ] **Synchronization**: Oyuncu A hareket ettiğinde Oyuncu B'nin bunu gecikmesiz (Lag compensation) görmesi.
- [ ] **Solutions**: Photon, Mirror, Netcode for GameObjects.

### 3. Optimizasyon
- [ ] **Object Pooling**: Mermileri sürekli yaratıp yok etme (Memory şişer), onları havuza atıp geri kullan.
- [ ] **Profiler**: Oyunu kasan (FPS düşüren) kodu bulma.
- [ ] **Draw Calls**: CPU'nun GPU'ya "çiz" emrini optimize etme.

---

## 🛠️ Araç Kutusu (Toolkit)
- **Engine**: Unity Hub veya Epic Games Launcher.
- **Model**: Blender (3D modelleme).
- **Art**: Aseprite (Pixel art) veya Photoshop.
- **VCS**: Git (Ama büyük dosyalar için Git LFS - Large File Storage kullanmayı unutma!).

---

## 📚 Kaynaklar

| Kaynak | Tip | Dil | Seviye |
| :--- | :--- | :--- | :--- |
| **[Brackeys (Efsane)](https://www.youtube.com/user/Brackeys)** | YouTube | İngilizce | Hepsi |
| **[SebLague (Coding Adventures)](https://www.youtube.com/c/SebastianLague)** | YouTube | İngilizce | İleri |
| **[Unity Learn](https://learn.unity.com/)** | Resmi Kurs | İngilizce | Başlangıç |
| **[Unreal Engine Documentation](https://docs.unrealengine.com/)** | Doküman | İngilizce | Hepsi |

---

## 💡 Proje Fikirleri

1.  **Hyper-Casual Oyun**: Tek parmakla oynanan, sonsuz koşu (Endless Runner) oyunu. (Mobil için).
2.  **Platform Oyunu (2D)**: Mario benzeri. Zıplama fizikleri, düşman yapay zekası (sağa sola gitme), bölüm tasarımı.
3.  **FPS (3D)**: Basit bir haritada düşmanları vurma. Raycasting ve 3D hareket mantığı.

---

## ❓ Mülakat Soruları
- 1. `Update`, `FixedUpdate` ve `LateUpdate` arasındaki fark nedir? Hangisi fizikte kullanılır?
- 2. "Object Pooling" nedir ve neden önemlidir?
- 3. Bir objenin diğerine çarpıp çarpmadığını nasıl anlarsın? (Collision Detection).
- 4. "DeltaTime" nedir? Neden hareket kodlarında hız ile çarparız?
- 5. Garbage Collection (GC) oyunlarda neden performans sorununa yol açar? Nasıl azaltılır?
