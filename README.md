# ROOMZERO di iPhone — panduan langkah demi langkah

Survival horror · 1–4 pemain · iPhone & iPad (iOS 14 ke atas).

ROOMZERO **tidak ada di App Store**. Game ini dipasang gratis lewat aplikasi **SideStore**, memakai **Apple ID milikmu sendiri** (Apple ID biasa, tidak perlu akun developer berbayar).

> **Ringkasnya:** pasang SideStore sekali pakai laptop (±15 menit) → setelah itu ROOMZERO dipasang, di-update, dan diperpanjang langsung dari iPhone, tanpa laptop lagi.

Halaman pemasangan (buka di **Safari** di iPhone): **https://pinc3ng.github.io/roomzero-ios/**

---

## Yang kamu butuhkan

- iPhone / iPad dengan **iOS 14 atau lebih baru**, ruang kosong ±1 GB.
- **Apple ID** (yang dipakai di App Store juga boleh) — sebaiknya sudah pakai verifikasi dua langkah.
- **Sekali saja:** laptop/PC (Windows, Mac, atau Linux) + **kabel USB** iPhone.
- Internet (Wi-Fi lebih baik; file game ±210 MB).

---

## Bagian A — Pasang SideStore (sekali saja, pakai laptop)

> Langkah resmi bisa berubah mengikuti versi iOS terbaru. Kalau ada yang berbeda dari yang tertulis di sini, ikuti **https://docs.sidestore.io** (panduan resmi SideStore).

1. **Di laptop**, buka https://docs.sidestore.io → bagian *Installation*. Unduh aplikasi pemasang yang disarankan di sana (saat panduan ini ditulis: **iloader**).
   - **Windows:** pasang juga **Apple Devices** (dari Microsoft Store) atau **iTunes**, supaya laptop bisa "melihat" iPhone lewat kabel.
2. **Colokkan iPhone** ke laptop pakai kabel. Di iPhone muncul *"Percayai Komputer Ini?"* → ketuk **Percayai** dan masukkan kode sandi iPhone.
3. **Buka iloader** di laptop → login dengan **Apple ID-mu** → pilih iPhone-mu → pilih **SideStore** → **Install**. Tunggu sampai selesai. (Langkah ini juga memasang *pairing file* yang dibutuhkan SideStore agar nanti bisa bekerja tanpa laptop.)
4. **Di iPhone**, buka **Pengaturan → Umum → VPN & Manajemen Perangkat** → ketuk Apple ID-mu → **Percayai**.
5. **iOS 16 ke atas:** buka **Pengaturan → Privasi & Keamanan → Mode Pengembang** → nyalakan → iPhone restart → setelah menyala, ketuk **Nyalakan** sekali lagi.
6. **Pasang aplikasi VPN lokal** yang diminta SideStore dari App Store (gratis; namanya tertulis di docs.sidestore.io — saat ini **LocalDevVPN**). Buka sekali dan izinkan menambahkan konfigurasi VPN. *VPN ini hanya berjalan di dalam iPhone-mu sendiri* — SideStore memakainya untuk memasang dan memperpanjang aplikasi tanpa laptop.
7. **Buka SideStore** → login dengan Apple ID yang sama.
8. Laptop sudah **tidak dibutuhkan lagi**. Cabut kabelnya.

---

## Bagian B — Pasang ROOMZERO (dari iPhone, tanpa laptop)

1. Di iPhone, buka **Safari** → **https://pinc3ng.github.io/roomzero-ios/**
2. Ketuk **"Tambahkan ROOMZERO ke SideStore"** → SideStore terbuka → **Tambahkan / Add**.
   - Kalau tombol itu tidak membuka SideStore: ketuk **"Salin link source"**, lalu di SideStore buka **Sources → + →** tempel link ini:
     ```
     https://pinc3ng.github.io/roomzero-ios/apps.json
     ```
3. Di SideStore buka **Browse** → **ROOMZERO** → **Get / Install**. Tunggu unduhan (±210 MB) dan pemasangan selesai (pastikan VPN lokal menyala).
4. Ikon **ROOMZERO** muncul di layar utama. Selesai — main!

**Update:** kalau ada versi baru, SideStore menampilkannya di **My Apps** / **Updates** → ketuk **Update**. Data game tetap tersimpan.

---

## Bagian C — Supaya tidak kedaluwarsa (sekali setup)

Aplikasi dari Apple ID gratis **berlaku 7 hari** (aturan Apple, tidak bisa dihilangkan). Buat iPhone memperpanjangnya sendiri setiap hari:

1. **SideStore → Settings** → nyalakan **Background Refresh** (kalau ada di versimu).
2. Buka app **Pintasan (Shortcuts)** → tab **Otomatisasi** → **+** → **Waktu** → pilih jam (misalnya **21.00**), **Setiap Hari** → pilih **Jalankan Segera** → **Berikutnya**.
3. **Otomatisasi Kosong Baru** → **Tambah Tindakan** → cari **SideStore** → pilih **Refresh All Apps** (Segarkan Semua App) → **Selesai**.
4. Biarkan **VPN lokal** SideStore tetap terpasang dan izinkan tersambung saat diminta.
5. Cek sesekali: **SideStore → My Apps** → sisa hari ROOMZERO harus kembali ke **7** setelah jam otomatisasi lewat.

Kalau sempat kedaluwarsa (ROOMZERO tidak mau terbuka): nyalakan VPN lokal → buka SideStore → **My Apps** → **Refresh**. **Data game tidak hilang.**

---

## Bagian D — Cara main

- **Gerak:** joystick di kiri bawah. **Lihat sekeliling:** geser jari di sisi kanan layar.
- **Tombol kanan:** tangan = interaksi (tahan untuk aksi panjang), lari, jongkok, senter, kamera malam (night vision).
- **Atas:** pause, **peta** (atau ketuk minimap di kiri atas). Ikon **buku** = notebook: langkah berikutnya, dokumen dan tape yang sudah dibaca.
- **Kiri atas:** minimap + bar **nyawa**. Cari kotak P3K (palang merah) di dinding kalau terluka.
- **Sembunyi** di loker kalau makhluknya mengejar.

### Main bareng (co-op online, 2–4 pemain, beda HP/PC boleh)

1. **Host:** menu utama **Multiplayer** → **Buat room** → bagikan **kode room** (6 huruf/angka) ke teman.
2. **Teman:** menu utama **Multiplayer** → ketik kode di kotak **Kode room** → **Gabung**.
3. Isi **Namamu**, pilih **survivor** (satu survivor hanya untuk satu pemain), host memilih peta → **Mulai misi**.
4. **Semua pemain harus memakai versi game yang sama** (lihat tulisan *Versi* di bawah menu utama). iPhone, Android, dan PC bisa satu room asal versinya sama.

---

## Masalah yang sering terjadi

| Masalah | Solusi |
|---|---|
| "Tidak dapat memverifikasi aplikasi" / "Untrusted Developer" | Pengaturan → Umum → VPN & Manajemen Perangkat → Apple ID-mu → **Percayai**. |
| "Batas aplikasi tercapai" / *maximum number of apps* | Apple ID gratis hanya boleh **3** aplikasi sideload aktif (SideStore dihitung satu). Hapus satu aplikasi sideload lain. |
| SideStore gagal memasang / refresh | Pastikan **VPN lokal menyala** dan ada internet, lalu coba lagi. |
| ROOMZERO tidak mau terbuka setelah seminggu | Sudah kedaluwarsa → SideStore → My Apps → **Refresh** (lihat Bagian C supaya otomatis). |
| Tidak bisa masuk room teman | Cek **versi game sama**, kode room benar, dan host masih di layar room (belum mulai main). |
| Mode Pengembang tidak muncul | Muncul setelah SideStore terpasang lewat laptop (Bagian A langkah 3). |

---

## Untuk pengurus repo

- `apps.json` — source SideStore / AltStore (daftar versi ROOMZERO).
- File `.ipa` ada di [Releases](https://github.com/Pinc3ng/roomzero-ios/releases). File ini **belum ditandatangani**; SideStore menandatanganinya dengan Apple ID pemain saat dipasang.
- Versi baru: build `.ipa` (GitHub Actions di repo game) → buat Release `vX.Y.Z` berisi `ROOMZERO-X.Y.Z.ipa` → tambahkan entri baru **di paling atas** daftar `versions` di `apps.json` (+ perbarui `version`, `downloadURL`, `size` di level aplikasi).

Kredit aset (suara, model, tekstur, font) ada di menu **Kredit** di dalam game.
