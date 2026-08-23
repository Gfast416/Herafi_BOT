
# Herafi_BOT – Optimism Sepolia Automation Bot

Herafi_BOT adalah bot Command-Line Interface (CLI) berbasis Node.js yang dirancang untuk mempermudah interaksi dengan jaringan **Optimism Sepolia**. Bot ini secara otomatis dapat melakukan:

- 💧 Claim faucet
- 🔄 Swap token
- 💼 Add liquidity
- 🗑️ Remove liquidity

Dibangun menggunakan [Ethers.js v6](https://docs.ethers.org/v6/), bot ini sangat berguna untuk pengembang dan penguji DApp di lingkungan testnet.

---

## 📦 Fitur Utama

- 💧 Klaim faucet testnet secara otomatis
- 💱 Swap token antar alamat/token tertentu
- 💼 Tambah likuiditas ke protokol yang didukung
- 🗑️ Hapus likuiditas dari protokol
- 🔐 Dukungan `.env` untuk menjaga keamanan kunci pribadi dan konfigurasi sensitif
- 🧪 Dirancang khusus untuk jaringan **Optimism Sepolia**

---

## 🏗️ Struktur Proyek

```

Herafi\_BOT/
├── LICENSE            # License information
├── .env.example       # Template konfigurasi environment
├── autoBot.js         # Main script
├── package.json       # Metadata dan dependensi npm
└── README.md          # This documentation

````

---

## ⚙️ Instalasi

1. **Clone repositori**
   ```bash
   git clone https://github.com/nolimitool/Herafi_BOT.git
   cd Herafi_BOT


2. **Install dependensi**

   ```bash
   npm install


3. **Siapkan file konfigurasi**
   Salin `.env.example` menjadi `.env` dan isi variabel berikut:

   ```
   PRIVATE_KEY=YourPrivateKeyHere
   RPC_URL=https://sepolia.optimism.io



## 🚀 Menjalankan Bot

Jalankan bot menggunakan:

```bash
npm start
```

---

> Ikuti petunjuk interaktif yang tersedia di terminal. Pastikan saldo wallet cukup untuk membayar gas.

Pastikan `package.json` kamu memiliki bagian berikut:

```json
"scripts": {
  "start": "node index.js"
}
```

---

## 🌐 Persyaratan

* Node.js v18+
* Koneksi internet stabil
* Wallet dengan test ETH di jaringan **Optimism Sepolia**

---

## 📃 Lisensi

Distributed under the MIT License. Lihat `LICENSE` untuk informasi lebih lanjut.

---

## 🙌 Kontribusi

Pull request dan isu sangat diterima! Untuk kontribusi besar, silakan buka *issue* terlebih dahulu untuk mendiskusikan perubahan apa yang ingin Anda buat.

---

## 👤 Pembuat

**0xdyifu**
[GitHub – nolimitool](https://github.com/nolimitool)


> Herafi\_BOT dibuat untuk memudahkan eksplorasi DeFi di lingkungan testnet. Tidak untuk digunakan di mainnet.


