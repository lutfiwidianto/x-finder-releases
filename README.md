<div align="center">

# ⚡ X-Finder (Android & OpenWrt Multi-Tool Suite)

[![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20OpenWrt%20%7C%20Linux-blue?style=for-the-badge&logo=android)](https://github.com/lutfiwidianto/x-finder-releases)
[![Security](https://img.shields.io/badge/Security-DRM%20Widevine%20Hardware%20TEE-green?style=for-the-badge&logo=shield)](https://github.com/lutfiwidianto/x-finder-releases)
[![Telegram Auth](https://img.shields.io/badge/Auth-Telegram%20Deep--Link-0088cc?style=for-the-badge&logo=telegram)](https://t.me/xfinder_auth_bot)
[![License](https://img.shields.io/badge/Status-Active%20Release-success?style=for-the-badge)](https://github.com/lutfiwidianto/x-finder-releases)

**Aplikasi All-in-One Network Utility, Multi-Protocol Xray/SSH-WS Scanner, CDN Bug Hunter, dan Pengelola Router OpenWrt.**

[📥 Download APK Terbaru](x-finder.apk) • [📖 Panduan Penggunaan](#-panduan-penggunaan--aktivasi-lisensi) • [💬 Hubungi Pengembang](https://t.me/widianto_lutfi)

</div>

---

## 📱 Apa Sebenarnya Aplikasi X-Finder Ini?

**X-Finder** adalah perangkat lunak jaringan serbaguna (*network engineering & diagnostics tool*) yang dirancang khusus untuk mempermudah:

1. **Mencari & Menguji Bug Host CDN / Proxy (Bug Hunting)**: Menguji secara cepat respon HTTP, status code (101 Switching Protocols, 200 OK, 301/302 Redirection), latency (ping/ms), dan ketersediaan IP address atau domain CDN (Cloudflare, Cloudfront, Akamai, Fastly, dll).
2. **Multi-Protocol Xray & SSH-Websocket Scanner**: Memvalidasi kesiapan protokol Vless, Vmess, Trojan, dan SSH Websocket melalui berbagai teknik penetrasi host (Address Scan, Wildcard Scan, SNI Handshake Scan, dan Onering Scan).
3. **Reconnaissance Jaringan & Subdomain Hunter**: Melakukan pencarian subdomain target secara otomatis, pemindaian status live, pencarian reverse IP tetangga satu server, hingga pencarian kata kunci DNS.
4. **Sinkronisasi Langsung ke Router OpenWrt / VPS**: Mengirimkan dan menerapkan hasil temuan bug host atau konfigurasi langsung ke router OpenWrt (`luci-app-xwan`) atau Linux server tanpa perlu mengedit file konfigurasi manual.

---

## 🎯 Untuk Siapa Aplikasi Ini Dibuat?

- **Pengguna Router OpenWrt & Libernet / Xray / Passwall**: Membutuhkan tool cepat di HP untuk mencari bug host aktif lalu menerapkannya ke router rumah/kantor.
- **Network Engineer & Sysadmin**: Menguji latency TLS Handshake SNI, header Websocket, dan responsivitas CDN edge node.
- **Pegiat Tunneling & Jaringan**: Ingin tool pemindai yang ringan, cepat, modern, dan tidak membebani kuota atau memori HP.

---

## 🖼️ Tampilan Aplikasi (Preview & Demo)

<div align="center">
  <img src="assets/demo_activation.png" width="30%" alt="Menu Multi-Tool" />
  &nbsp;&nbsp;
  <img src="assets/demo_drawer.png" width="30%" alt="Navigasi Drawer & Modul" />
  &nbsp;&nbsp;
  <img src="assets/demo_locked_activation.png" width="30%" alt="Sistem Keamanan & Aktivasi" />
</div>

---

## ✨ Fitur-Fitur Unggulan

### 1. 🚀 Xray Multi-Mode Scanner
- **Address Scan**: Memindai kandidat IP address atau proxy server pada port tertentu.
- **Wildcard Scan**: Menguji responsivitas wildcard subdomain (*.domain.com) pada CDN host.
- **SNI Scan**: Menguji jabat tangan (*handshake*) TLS SNI server name langsung ke server tujuan.
- **Onering Scan**: Pengujian format multi-layer tunnel `onering:domain:target`.
- **Auto All Modes (Fitur Unggulan)**: Menggabungkan seluruh metode pemindaian secara paralel dan otomatis menentukan konfigurasi terbaik dengan latency terendah.

### 2. 🔍 Subdomain & Recon Suite
- **Subdomain Scanner**: Menggali puluhan hingga ratusan subdomain target secara otomatis.
- **Live Status Checker**: Memfilter subdomain mana yang aktif menghasilkan respon HTTP/HTTPS valid.
- **Reverse IP Lookup**: Melihat domain lain apa saja yang berada di dalam satu blok IP server target.

### 3. 🛡️ Keamanan Tingkat Tinggi (Hardware TEE DRM Silicon)
- **Bukan Berbasis IMEI / Android ID Biasa**: Device ID dihasilkan langsung dari enkripsi hardware silicon **MediaDrm Widevine TrustZone**.
- **Anti-Spoofing & Anti-Clone**: Tidak dapat dipalsukan oleh Custom ROM, Magisk Device Spoofer, ataupun aplikasi *clone*.
- **Offline-Safe Smart Lease**: Berkat sistem *Smart Leased Cache*, aplikasi tetap berjalan super cepat (0 ms) tanpa membebani internet setiap kali membuka fitur.

---

## 🚀 Panduan Penggunaan & Aktivasi Lisensi

Aktivasi lisensi X-Finder dibuat sangat mudah dan **100% aman** tanpa perlu mengetik manual username atau kode acak:

```
[Buka X-Finder] ➡️ [Klik 'Minta Izin Aktivasi via Telegram'] ➡️ [Tekan START di Bot] ➡️ [Admin Setujui] ➡️ [Tekan 'Cek Status' di Aplikasi]
```

### Langkah-langkah Detail:
1. **Unduh & Pasang APK**:
   Download file [x-finder.apk](x-finder.apk) lalu pasang di perangkat Android Anda.
2. **Buka Aplikasi**:
   Pilih fitur **Auto All Modes Scanner** atau menu lain yang memerlukan lisensi.
3. **Minta Izin Aktivasi**:
   - Layar akan menampilkan kartu **Akses Fitur Premium Terkunci** beserta **Device ID** perangkat Anda.
   - Klik tombol biru **"Minta Izin Aktivasi via Telegram"**.
4. **Konfirmasi di Bot Telegram**:
   - Aplikasi akan otomatis membuka Telegram ke bot resmi [`@xfinder_auth_bot`](https://t.me/xfinder_auth_bot).
   - Tekan tombol **START** di bot. Akun Telegram dan Device ID Anda akan otomatis terkirim secara aman ke antrian Admin.
5. **Aktivasi Selesai**:
   - Setelah Admin menyetujui permohonan Anda di bot, kembali ke aplikasi X-Finder dan tekan tombol **"Cek Status"**.
   - Fitur langsung terbuka seketika!

---

## ❓ Tanya Jawab Umum (FAQ)

<details>
<summary><b>1. Apakah aplikasi ini membutuhkan root?</b></summary>
Tidak. X-Finder dapat berjalan sempurna di semua perangkat Android (Android 7.0 hingga Android 15+) baik yang sudah di-root maupun non-root.
</details>

<details>
<summary><b>2. Mengapa aplikasi tetap bisa dipakai saat offline?</b></summary>
X-Finder menggunakan sistem HMAC-signed smart lease lokal yang aman. Begitu status lisensi Anda terverifikasi, aplikasi menyimpan sertifikat tanda tangan digital lokal sehingga tidak perlu terus-menerus menghubungi internet.
</details>

<details>
<summary><b>3. Apa yang terjadi jika Admin mencabut lisensi perangkat saya?</b></summary>
Perangkat Anda akan kembali ke status terkunci. Anda dapat mengajukan permohonan izin baru kapan saja melalui tombol yang sama.
</details>

<details>
<summary><b>4. Apakah saya bisa menggunakan aplikasi ini bersamaan dengan Router OpenWrt?</b></summary>
Bisa. Hasil pemindaian dari X-Finder dapat disalin atau diexport langsung untuk digunakan pada router OpenWrt (Passwall, OpenClash, v2rayA, atau plugin Xwan).
</details>

---

## 👨‍💻 Kontak & Dukungan

Jika Anda memiliki pertanyaan seputar perizinan, bug report, atau saran pengembangan fitur:

- **Telegram Pengembang**: [@widianto_lutfi](https://t.me/widianto_lutfi)
- **Bot Lisensi**: [@xfinder_auth_bot](https://t.me/xfinder_auth_bot)

<div align="center">
<sub>© 2026 X-Finder Project • Dibuat dengan performa tinggi & keamanan hardware modern.</sub>
</div>
