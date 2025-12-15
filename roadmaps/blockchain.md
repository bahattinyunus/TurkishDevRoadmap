# ⛓️ Blockchain Roadmap (Blokzincir)

> **"Web 1.0 (Oku), Web 2.0 (Oku-Yaz), Web 3.0 (Oku-Yaz-Sahiplen)."**  
> Merkeziyetsiz sistemlerin ve finansın geleceği.

---

## 🟢 Seviye 1: Temel Kavramlar (Junior)
*Bitcoin nedir, nasıl çalışır?*

### 1. Blokzincir Teorisi
- [ ] **Decentralization**: Merkeziyetsizlik nedir? Neden bankaya ihtiyaç duyulmaz?
- [ ] **Consensus Mechanisms**: PoW (Proof of Work - Madencilik) vs PoS (Proof of Stake).
- [ ] **Wallet (Cüzdan)**: MetaMask nedir? Public Key (IBAN) ve Private Key (Şifre) farkı.

### 2. Akıllı Sözleşmeler (Smart Contracts)
- [ ] **Ethereum**: Kod çalıştırabilen ilk blokzincir.
- [ ] **Gas Fee**: İşlem ücretleri neden ödenir?

---

## 🟡 Seviye 2: Geliştirme (Mid)
*Kendi token'ını ve dApp'ini geliştirmek.*

### 1. Solidity (Dillerin Kralı)
- [ ] **Syntax**: JavaScript'e benzer ama tiplidir.
- [ ] **Data Types**: `address`, `mapping`, `uint256`.
- [ ] **ERC Standards**:
    - **ERC-20**: Kendi token'ını (Coin) yarat.
    - **ERC-721**: Kendi NFT koleksiyonunu yarat.

### 2. Geliştirme Araçları
- [ ] **Remix IDE**: Tarayıcı üzerinden kod yazıp deploy etme (Kurulum gerekmez).
- [ ] **Hardhat / Foundry**: Profesyonel geliştirme ortamı, test yazma.

### 3. Frontend Entegrasyonu (Web3.js / Ethers.js)
- [ ] **Connect Wallet**: React sitesine "Cüzdan Bağla" butonu ekleme.
- [ ] **Contract Interaction**: Sitedeki butona basınca blokzincirdeki fonksiyonu çağırma.

---

## 🔴 Seviye 3: İleri Uzmanlık (Senior)
*Güvenlik ve İleri Mimari.*

### 1. Smart Contract Security (Çok Kritik!)
- [ ] **Reentrancy Attack**: DAO'ların çökmesine sebep olan meşhur açık.
- [ ] **Integer Overflow**: Sayı sınırlarını aşma.
- [ ] **Auditing**: Yazılan kodu güvenlik taramasından geçirme.

### 2. DeFi (Decentralized Finance)
- [ ] **AMM (Automated Market Maker)**: Uniswap nasıl çalışır? Havuz (Pool) mantığı.
- [ ] **Lending/Borrowing**: Aave, Compound protokolleri.
- [ ] **Flash Loans**: Teminatsız kredi çekip aynı blokta geri ödeme.

### 3. Layer 2 & Scaling
- [ ] **Rollups**: Arbitrum, Optimism.
- [ ] **Zero Knowledge (ZK) Proofs**: Gizlilik odaklı ölçekleme.

---

## 🛠️ Araç Kutusu (Toolkit)
- **Wallet**: MetaMask.
- **Explorer**: Etherscan (İşlemleri takip etme).
- **Oracle**: Chainlink (Dış dünyadan hava durumu, fiyat verisi çekme).
- **Node**: Alchemy veya Infura.

---

## 📚 Kaynaklar

| Kaynak | Tip | Dil | Seviye |
| :--- | :--- | :--- | :--- |
| **[CryptoZombies](https://cryptozombies.io/tr/)** | İnteraktif Oyun | Türkçe | Başlangıç |
| **[Solidity by Example](https://solidity-by-example.org/)** | Doküman | İngilizce | Orta |
| **[Ethereum.org](https://ethereum.org/en/developers/)** | Resmi Doküman | İngilizce | Hepsi |
| **[Patrick Collins (YouTube)](https://www.youtube.com/@PatrickAlphaC)** | Efsane Kurs | İngilizce | Hepsi |

---

## 💡 Proje Fikirleri

1.  **Kendi Coin'ini Bas**: ERC-20 standardında "BahattinCoin" üret ve test ağında (Sepolia) arkadaşına gönder.
2.  **Basit Oylama (Voting) dApp**: Herkesin cüzdanıyla oy kullandığı, sonuçların değiştirilemediği bir seçim uygulaması.
3.  **NFT Pazaryeri**: Basit bir Opensea klonu. Resim yükle, NFT yap (Mint) ve satışa koy.

---

## ❓ Mülakat Soruları
- 1. `msg.sender` ve `tx.origin` arasındaki fark ne kadar tehlikeli olabilir?
- 2. "Private Key"imi kaybedersem coinlerime ne olur? Kurtarılabilir mi?
- 3. Ethereum'da bir işlem (Transaction) geri alınabilir mi? Neden?
- 4. Solidity'de `payable` anahtar kelimesi ne işe yarar?
- 5. Proof of Work ve Proof of Stake arasındaki enerji tüketimi ve güvenlik farkı nedir?
