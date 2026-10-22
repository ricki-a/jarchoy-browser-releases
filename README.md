# JarChoy Agent Browser

Browser Android buatan sendiri — ringan, TANPA IKLAN, dengan VPN bawaan (SSH / SSH+SSL / WebSocket / VLESS / Trojan), password manager, dan dua bahasa (Indonesia / English).

Download APK versi terbaru di bagian **Releases** repo ini.

## Fiturnya

### Browser
- Tab banyak + preview
- Bookmark, riwayat, dan pengelola unduhan
- Mode privat (ikon ninja di bilah alamat)
- Ad-block bawaan
- Scanner QR / Barcode / QRIS
- Dua bahasa: Indonesia dan English
- DNS custom + DNS-over-HTTPS bawaan
- Laci menu gaya iPhone: grup Peramban / VPN & Keamanan / Tampilan

### VPN (pakai akun sendiri — SSH / VLESS / Trojan)
- **SSH** — paling stabil, sudah terbukti jalan
- **SSH over WebSocket** — tembus di port 80/443
- **SSH + SSL (TLS) dengan SNI** — untuk akun port 443 yang diam saja kalau dibuka pakai SSH biasa
- **Payload dengan token** — [host], [port], [crlf], [cr], [lf], [crlf*2] otomatis diterjemahkan, 
- **Proxy HTTP berantai** — format host:port atau user:pass@host:port, berlaku di semua jalur koneksi
- **VLESS & Trojan** — protokol kekinian (TCP / WS / TLS)
- Tinggal paste link `vless://` atau `trojan://` di Host / IP, otomatis terpasang
- Indikator VPN di bilah alamat saat terhubung; koneksi yang mati diam-diam terdeteksi dan dibersihkan otomatis

### Password Manager
- Otomatis menawarkan simpan password
- Autofill sekali tap
- Rapi per domain

### Tema
- **Midnight Metal** — hitam + merah untuk mode gelap
- Mode terang juga ada
- Semua dialog gaya iPhone
- Ganti tema tidak mematikan koneksi VPN

## Cara Install
1. Download file `.apk` dari **Releases** yang paling baru
2. Di HP, buka **Pengaturan** → **Keamanan** → nyalakan **"Sumber tidak dikenal"**
3. Buka file APK-nya → **Install**
4. Jadi!

> **Catatan:** Belum ada di Play Store. Install manual dulu.

## Butuh Apa
- Android 8.0 ke atas
- Ukuran APK hanya ±1,6 MB
- Internet
- Akun SSH / VLESS / Trojan milik sendiri untuk fitur VPN

## Masih Beta!
Masih tahap pengembangan, jadi mungkin ada bug. Nemu bug? Bikin **Issue** di repo ini ya, biar dibenerin!

## Update
Cek **Releases** buat liat versi terbaru. Versi saat ini: **b96**.

---
Cheers,
Ricki + JarChoy 🙏
