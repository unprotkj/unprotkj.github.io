# Dokumentasi Website Unpro TKJ Hotspot
### Versi Bahasa Indonesia — Mudah Dipahami
**Versi:** 1.0
**Terakhir diperbarui:** Mei 2026
**File utama:** `index.html`

---

## Apa Itu Website Ini?

Website **Unpro TKJ Hotspot** adalah toko online sederhana untuk membeli
voucher internet sekolah. Siswa cukup buka website ini, pilih paket yang
diinginkan, bayar, dan langsung dapat kode voucher untuk internetan di
sekolah — tanpa perlu datang ke ruang TKJ atau mencari admin jaringan.

Ibarat membeli pulsa online, tapi ini untuk internet WiFi di sekolah.

---

## Bagian 1 — Apa Saja yang Ada di Website Ini?

Website ini terdiri dari **6 bagian** yang tersusun dari atas ke bawah:

---

### Bagian 1.1 — Bar Atas (Navbar)

Ini adalah bagian paling atas yang selalu kelihatan meskipun kita
scroll ke bawah. Isinya:

- **Logo dan nama "Unpro TKJ"** di sebelah kiri
- **Indikator status MikroTik** di sebelah kanan:
  - Titik **hijau** = MikroTik **ONLINE** (jaringan aktif)
  - Titik **merah** = MikroTik **OFFLINE** (jaringan mati)

---

### Bagian 1.2 — Bagian Selamat Datang (Hero)

Ini bagian pertama yang dilihat pengunjung. Warnanya hijau gelap,
ada tulisan judul besar, keterangan singkat, dan tombol
**"Lihat Paket Sekarang"** yang kalau diklik akan langsung
melompat ke bagian daftar paket.

---

### Bagian 1.3 — Status Jaringan MikroTik

Bagian ini menampilkan apakah jaringan sekolah sedang aktif atau tidak.

- Kalau **ONLINE** → tampilannya kotak hijau bertuliskan "ONLINE"
- Kalau **OFFLINE** → tampilannya kotak merah bertuliskan "OFFLINE"
- Ada keterangan "Heartbeat terakhir: X menit yang lalu"
  (artinya: MikroTik terakhir kali memberi kabar X menit lalu)
- Ada tombol **"Periksa ulang"** untuk cek ulang secara manual
- Website mengecek status otomatis setiap **2 menit sekali**

> **Kenapa perlu tahu status ini?**
> Supaya siswa tidak beli voucher saat jaringan sedang mati.

---

### Bagian 1.4 — Daftar Paket Voucher

Ini bagian inti website. Ada **3 kartu paket** yang bisa dipilih:

| No | Nama Paket | Harga | Keterangan |
|----|------------|-------|------------|
| 1 | Voucher 1 Hari | Rp 2.000 | Internet aktif selama 24 jam |
| 2 | Voucher 2 Hari | Rp 3.000 | Internet aktif selama 48 jam ⭐ Paling populer |
| 3 | Voucher 3 Hari | Rp 5.000 | Internet aktif selama 72 jam |

Setiap kartu berisi:
- Ikon
- Nama paket
- Keterangan singkat
- Daftar fitur
- Harga
- Tombol **"Beli / Aktifkan"**

Kalau tombol diklik, akan muncul jendela konfirmasi dulu sebelum
diarahkan ke halaman pembayaran.

---

### Bagian 1.5 — Cara Beli (Alur Pembelian)

Bagian ini menjelaskan 5 langkah proses pembelian secara visual:

```
Langkah 1 → Buka website dan lihat paket yang tersedia
Langkah 2 → Pilih paket dan lakukan pembayaran (saldo / QRIS)
Langkah 3 → Kode voucher dikirim otomatis oleh sistem
Langkah 4 → Masukkan kode voucher di halaman login hotspot sekolah
Langkah 5 → Internet langsung aktif, siap digunakan!
```

---

### Bagian 1.6 — Video Tutorial

Bagian ini menampilkan video YouTube yang memandu cara membeli
voucher secara lengkap. Video ditampilkan dalam format **tegak (portrait)**
karena direkam menggunakan HP.

Di samping video ada daftar ringkasan langkah-langkah pembelian,
dan tombol merah **"Tonton di YouTube"** untuk membuka video
di aplikasi YouTube secara langsung.

> Kalau link YouTube belum diisi, bagian ini akan menampilkan
> kotak abu-abu dengan tulisan "Video tutorial belum tersedia."

---

### Bagian 1.7 — Footer (Bagian Paling Bawah)

Bagian paling bawah website. Isinya:
- Logo dan nama Unpro TKJ
- Tulisan hak cipta (copyright)
- Keterangan untuk menghubungi pengelola jaringan

---

## Bagian 2 — Bagaimana Alur Pembelian Voucher Secara Lengkap?

Ini alur lengkap dari awal sampai akhir, dari sudut pandang siswa:

```
┌─────────────────────────────────────────────────────────┐
│                                                         │
│  [1] Siswa buka website Unpro TKJ di HP atau laptop     │
│                        │                               │
│                        ▼                               │
│  [2] Siswa pilih paket (1 hari / 2 hari / 3 hari)      │
│                        │                               │
│                        ▼                               │
│  [3] Klik "Beli / Aktifkan"                             │
│      → Muncul konfirmasi nama paket + harga             │
│                        │                               │
│                        ▼                               │
│  [4] Klik "Lanjutkan Pembayaran"                        │
│      → Browser membuka tab baru ke beliwifi.com         │
│                        │                               │
│                        ▼                               │
│  [5] Siswa memilih cara bayar:                          │
│      ├── Pakai saldo di sistem (kalau ada)              │
│      └── Scan QRIS (bayar pakai dompet digital / m-banking) │
│                        │                               │
│                        ▼                               │
│  [6] Sistem beliwifi.com memproses pembayaran           │
│                        │                               │
│                        ▼                               │
│  [7] Kode voucher MikroTik dikirim OTOMATIS ke siswa    │
│                        │                               │
│                        ▼                               │
│  [8] Siswa sambungkan HP/laptop ke WiFi sekolah         │
│                        │                               │
│                        ▼                               │
│  [9] Buka browser → masukkan kode voucher               │
│      di halaman login hotspot                           │
│                        │                               │
│                        ▼                               │
│  [10] ✓ Internet aktif! Siap digunakan                  │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

---

## Bagian 3 — Bagaimana Cara Kerja Status MikroTik?

Ini penjelasan sederhana cara kerja indikator ONLINE/OFFLINE:

```
Bayangkan MikroTik seperti seseorang yang sedang piket jaga.
Setiap 10 menit sekali, si penjaga piket ini "melapor" ke
papan pengumuman di internet (Cloudflare).

Website kita membaca papan pengumuman itu setiap 2 menit.

  Kalau laporan terakhir kurang dari 20 menit yang lalu
  → berarti si penjaga masih ada → ONLINE ✓

  Kalau sudah lebih dari 20 menit tidak ada laporan
  → berarti si penjaga sudah tidak ada / listrik mati → OFFLINE ✗
```

### Alurnya seperti ini:

```
MikroTik (tiap 10 menit)
    │
    │  kirim laporan (POST)
    ▼
Cloudflare Workers
    │  simpan waktu laporan terakhir
    │
    ▼  (dibaca website tiap 2 menit)
Website GitHub Pages
    │
    ├─ Laporan < 20 menit lalu? → Tampilkan ONLINE (hijau)
    └─ Laporan > 20 menit lalu? → Tampilkan OFFLINE (merah)
```

**Kenapa pakai Cloudflare dan bukan ping langsung?**

Karena GitHub Pages hanya bisa menampilkan file HTML — ia tidak bisa
"mendengarkan" ping dari luar. Cloudflare Workers berperan sebagai
perantara yang bisa menerima laporan dari MikroTik dan menyimpannya,
lalu website tinggal membaca hasilnya.

---

## Bagian 4 — Cara Mengubah Isi Website

Semua pengaturan penting ada di dalam file `index.html`,
di bagian `<script>` (kode JavaScript). Cukup buka file dengan
Notepad atau editor teks apa saja.

---

### 4.1 Cara Mengisi Link Video YouTube

Cari baris ini:
```javascript
const YOUTUBE_URL = "";
```

Ganti tanda kutip kosong dengan link YouTube kamu:
```javascript
const YOUTUBE_URL = "https://www.youtube.com/watch?v=XXXXXXXXXX";
```

Setelah disimpan dan di-upload ulang, video akan langsung muncul
di website menggantikan kotak abu-abu.

---

### 4.2 Cara Mengganti Link Pembayaran Paket

Cari bagian `const PACKAGES = [...]`, lalu ganti nilai `link`
di masing-masing paket:

```javascript
{
  id: "1hari",
  link: "https://beliwifi.com/H698aae6293847/pay"  // ← ganti ini
},
{
  id: "2hari",
  link: "https://beliwifi.com/H698aaeace892b/pay"  // ← ganti ini
},
{
  id: "3hari",
  link: "https://beliwifi.com/H698aaf3c54cce/pay"  // ← ganti ini
}
```

---

### 4.3 Cara Mengganti Harga Paket

Masih di bagian `PACKAGES`, cari dan ubah nilai `price`
dan `priceFormatted`:

```javascript
price: 2000,             // angka harga (tanpa titik)
priceFormatted: "Rp 2.000",  // tulisan harga yang tampil di website
```

---

### 4.4 Cara Mengganti URL Cloudflare Worker

Cari baris ini:
```javascript
const CLOUDFLARE_ENDPOINT = "GANTI_DENGAN_URL_WORKER_CLOUDFLARE";
```

Ganti dengan URL Worker milikmu:
```javascript
const CLOUDFLARE_ENDPOINT = "https://nama-worker.username.workers.dev";
```

---

### 4.5 Cara Mengganti Logo Brand

Cari bagian `<div class="brand-icon">` lalu ganti isi SVG-nya dengan:
```html
<img src="logounprotkj.png" alt="Unpro TKJ"
     style="width:24px;height:24px;object-fit:contain;">
```

Pastikan file `logounprotkj.png` ikut di-upload ke repositori GitHub
di folder yang sama dengan `index.html`.

---

## Bagian 5 — File Apa Saja yang Perlu Di-upload ke GitHub?

Cukup **satu file saja**:

```
repository GitHub Pages kamu/
└── index.html   ← ini satu-satunya file yang perlu ada
```

Tidak perlu upload file JSON, file konfigurasi, folder tambahan,
atau apapun yang lain. Semuanya sudah ada di dalam `index.html`.

Layanan-layanan lain (Cloudflare, beliwifi.com, YouTube) berjalan
di server masing-masing — bukan di GitHub kita.

---

## Bagian 6 — Layanan yang Digunakan Website Ini

| Layanan | Fungsinya untuk apa? | Berbayar? | Batas pemakaian |
|---------|----------------------|-----------|-----------------|
| **GitHub Pages** | Tempat hosting website | Gratis | Tidak terbatas |
| **Cloudflare Workers** | Menerima laporan MikroTik | Gratis | 100.000 request/hari, reset tiap hari |
| **Cloudflare KV** | Menyimpan waktu laporan terakhir | Gratis | 1.000 tulis + 100.000 baca per hari |
| **beliwifi.com** | Proses pembayaran & kirim voucher | Berbayar | Sesuai paket langganan |
| **Google Fonts** | Huruf/font yang dipakai website | Gratis | Tidak terbatas |
| **YouTube** | Tempat upload video tutorial | Gratis | Tidak terbatas |

---

## Bagian 7 — Seberapa Banyak "Kuota" Cloudflare yang Dipakai?

Cloudflare gratis memberikan **100.000 request per hari** (reset tiap hari).
Ini estimasi pemakaian kita:

```
MikroTik kirim laporan (tiap 10 menit)
  = 6 kali/jam × 24 jam = 144 kali/hari
  → Menggunakan 14% dari batas 1.000 tulis/hari ✓

Website baca status (perkiraan 50 kunjungan/hari)
  = sekitar 150 baca/hari
  → Menggunakan 0,15% dari batas 100.000 baca/hari ✓

Total keseluruhan: ~294 request/hari
  → Sangat jauh di bawah batas 100.000/hari ✓
```

Kesimpulan: **pemakaian kita sangat kecil**, Cloudflare gratis
lebih dari cukup untuk bertahun-tahun ke depan.

---

## Bagian 8 — Langkah-Langkah Pasang Website (Ringkasan)

Kalau kamu ingin memasang website ini dari awal, urutannya adalah:

```
Langkah 1 → Buat akun Cloudflare (gratis, tanpa kartu kredit)
Langkah 2 → Buat KV Namespace bernama "HEARTBEAT_KV"
Langkah 3 → Buat Worker baru, paste isi cloudflare-worker.js
Langkah 4 → Hubungkan KV ke Worker (Bindings)
Langkah 5 → Isi CLOUDFLARE_ENDPOINT di index.html
Langkah 6 → Upload index.html ke GitHub (nama filenya harus index.html!)
Langkah 7 → Aktifkan GitHub Pages di Settings → Pages
Langkah 8 → Buat Scheduler di MikroTik (Winbox → System → Scheduler)
Langkah 9 → Upload video tutorial ke YouTube, isi YOUTUBE_URL di kode
```

> **Perhatian penting di Langkah 6:**
> Nama filenya **harus** `index.html` (huruf kecil semua).
> Kalau namanya beda (misal `hotspot-sekolah.html`), website tidak
> akan terbuka dengan benar di GitHub Pages.

---

## Bagian 9 — Masalah Umum dan Cara Mengatasinya

| Masalah yang terjadi | Kemungkinan penyebabnya | Cara mengatasinya |
|----------------------|------------------------|-------------------|
| Status selalu OFFLINE | MikroTik tidak kirim laporan | Cek Scheduler di Winbox, coba jalankan manual |
| Video tidak muncul | YOUTUBE_URL masih kosong atau formatnya salah | Isi dengan link YouTube yang benar |
| Tombol beli tidak jalan | Link paket belum diganti | Ganti nilai `link` di array PACKAGES |
| Website 404 (tidak ditemukan) | Nama file bukan `index.html` | Rename file sebelum upload ke GitHub |
| Tulisan "Belum dikonfigurasi" | CLOUDFLARE_ENDPOINT masih placeholder | Isi URL Cloudflare Worker di kode |
| Website tampil aneh / rusak | Cache browser lama | Tekan Ctrl+Shift+R untuk refresh paksa |

---

## Ringkasan Singkat

> Website ini = **toko voucher internet sekolah**.
> Siswa buka → pilih paket → bayar QRIS/saldo → dapat voucher otomatis → internetan.
>
> Satu file HTML saja sudah cukup.
> Gratis untuk di-hosting.
> Status MikroTik ditampilkan secara otomatis.
> Video tutorial bisa ditambahkan kapan saja.

---

*Dokumentasi ini dibuat untuk pengelola jaringan sekolah Unpro TKJ.*
*Versi 1.0 — Mei 2026*
