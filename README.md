# 🛵 ShopeeFood Driver - Mobile Map & Argo Simulator

Aplikasi web mobile interaktif khusus mitra driver **ShopeeFood** untuk simulasi rute peta jalan raya asli Google Maps, penentuan titik ambil (Resto) & antar (Pemesan), perhitungan argo bersih driver (setelah potongan komisi 20%), navigasi turn-by-turn langsung ke Google Maps, serta pelacak target poin dan bonus harian.

![Preview](https://raw.githubusercontent.com/asit044/shopeefood-driver-maps/main/preview.png)

---

## ✨ Fitur Utama

- 📱 **Mobile-First Driver UI**: Antarmuka responsif menyerupai aplikasi driver resmi (Shopee Driver) dengan bottom navigation thumb-friendly.
- 🗺️ **Peta Google Maps Asli**: Pilihan tampilan Google Maps Jalan Raya, Live Traffic, dan Satelit asli tanpa blokir CORS.
- 📍 **Kelola Titik 1 & 2 Fleksibel**:
  - **Titik 1**: Tempat Ambil Makanan (Restoran / Merchant).
  - **Titik 2**: Alamat Pengantaran (Pemesan / Konsumen).
  - Pencarian alamat / nama resto mandiri dengan autocomplete.
  - Tombol **`🛰️ GPS Saya`** untuk mendeteksi posisi akurat driver saat ini.
  - Tombol **`⇅ Tukar Titik: 1 (Ambil) ⇄ 2 (Antar)`** secara instan.
- 🛣️ **Rute Jalan Raya Akurat (OSRM)**: Menghitung jarak tempuh aktual di jalan raya dengan multi-server fallback.
- 🚀 **Buka di Google Maps Navigasi**: Tombol sekali klik untuk langsung membuka navigasi belokan (*turn-by-turn navigation*) di aplikasi Google Maps resmi.
- 💰 **Kalkulator Argo ShopeeFood Transparan**:
  - Skema **Reguler** vs **Hub / Shift**.
  - Jumlah order gabungan: Single (1), Double (2), Triple (3).
  - Tip pelanggan (100% milik driver).
  - Perhitungan bersih diterima driver setelah potongan komisi 20%.
- 🎯 **Target Poin & Bonus Insentif Harian**:
  - Pelacak progres poin harian (Tier 1: 800p = +Rp20rb, Tier 2: 1.200p = +Rp35rb, Tier 3: 1.600p = +Rp55rb).
  - Ringkasan total uang masuk dompet hari ini (Argo Bersih + Bonus Poin).

---

## 🚀 Menjalankan Secara Lokal

1. Clone repositori:
   ```bash
   git clone https://github.com/asit044/shopeefood-driver-maps.git
   cd shopeefood-driver-maps
   ```
2. Buka `index.html` langsung di browser, atau jalankan menggunakan live server / Laragon / Vercel.

---

## 🌐 Deploy di Vercel

Proyek ini telah dikonfigurasi untuk langsung di-deploy di Vercel:
```bash
npx vercel
```
Atau hubungkan repositori GitHub ini melalui [Vercel Dashboard](https://vercel.com/new).

---

Dibuat untuk kebutuhan operasional harian mitra driver ShopeeFood.
