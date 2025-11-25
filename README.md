# Desain Lo-Fi: MAMASA COFFEE & CULTURE HUB
## Spesifikasi Wireframe Aplikasi Mobile

---

## 1. Struktur Aplikasi (Sitemap)

```
MAMASA COFFEE & CULTURE HUB
│
├── Splash Screen
│
├── Home Screen
│   ├── Search Bar
│   ├── Kategori (4 pilihan)
│   ├── Banner Promosi
│   ├── Rekomendasi Destinasi
│   └── Produk Unggulan
│
├── Wisata Budaya
│   ├── Daftar Destinasi
│   └── Detail Destinasi
│
├── Wisata Kopi
│   ├── Daftar Paket Wisata Kopi
│   └── Detail Paket Wisata
│
├── Homestay
│   ├── Daftar Homestay
│   └── Detail Homestay
│
├── E-Commerce Kopi
│   ├── Daftar Produk Kopi
│   ├── Filter & Sort
│   ├── Detail Produk
│   └── Keranjang Belanja
│
├── Checkout & Pembayaran
│
├── Reservasi Saya
│   ├── Reservasi Aktif
│   └── Riwayat Reservasi
│
└── Akun
    ├── Profil Pengguna
    ├── Pengaturan
    ├── Bantuan & FAQ
    └── Logout
```

---

## 2. Wireframe Detil: Home Screen

### Layout Struktur

```
┌─────────────────────────────────────┐
│  [Logo]  MAMASA HUB  [🔔 Notifikasi]│
├─────────────────────────────────────┤
│                                     │
│  ┌───────────────────────────────┐  │
│  │ 🔍 Cari Kopi, Destinasi...    │  │
│  └───────────────────────────────┘  │
│                                     │
│  ┌──────┬──────┬──────┬──────┐     │
│  │ 🏛️   │ ☕   │ 🏠   │ 🛒   │     │
│  │Budaya│ Kopi │Homestay│E-Com│     │
│  └──────┴──────┴──────┴──────┘     │
│                                     │
│  ┌─────────────────────────────────┐│
│  │ ◀ [Promo Banner 1] ▶           ││
│  │ "Diskon Paket Wisata 20%"       ││
│  └─────────────────────────────────┘│
│                                     │
│  Jelajahi Mamasa                    │
│  ┌──────────────┐ ┌──────────────┐ │
│  │ [Foto]       │ │ [Foto]       │ │
│  │ Tondok Bakaru│ │ Puncak Mambul│ │
│  │ ★★★★★ (4.8) │ │ ★★★★☆ (4.5) │ │
│  │ 12 km        │ │ 25 km        │ │
│  └──────────────┘ └──────────────┘ │
│                                     │
│  Kopi Arabika Pilihan              │
│  ┌──────────────┐ ┌──────────────┐ │
│  │ [Foto Kopi]  │ │ [Foto Kopi]  │ │
│  │ Arabika      │ │ Arabika      │ │
│  │ Medium Roast │ │ Dark Roast   │ │
│  │ Rp 85.000    │ │ Rp 95.000    │ │
│  │ [+ Keranjang]│ │ [+ Keranjang]│ │
│  └──────────────┘ └──────────────┘ │
│                                     │
├─────────────────────────────────────┤
│ [🏠 Home] [📋 Reservasi] [☕ E-Com] [👤 Akun] │
└─────────────────────────────────────┘
```

### Elemen Detail

| Elemen | Ukuran | Deskripsi |
| :--- | :--- | :--- |
| **Header** | Full Width | Logo, Title, Notification Icon |
| **Search Bar** | Full Width - 20px margin | Placeholder: "Cari Kopi, Destinasi, atau Homestay..." |
| **Kategori Icons** | 4 x Equal Width | Grid 2x2 atau 1x4 dengan icon dan label |
| **Banner Promosi** | Full Width | Carousel horizontal dengan swipe gesture |
| **Rekomendasi Cards** | 2 kolom | Horizontal scroll atau vertical list |
| **Bottom Navigation** | Full Width | 4 tab: Home, Reservasi, E-Commerce, Akun |

---

## 3. Wireframe Detil: Detail Paket Wisata

### Layout Struktur

```
┌─────────────────────────────────────┐
│ [◀] Paket Wisata Kopi & Budaya [↗] │
├─────────────────────────────────────┤
│                                     │
│  ┌─────────────────────────────────┐│
│  │                                 ││
│  │  [Carousel Foto Kebun Kopi]     ││
│  │  ◀ [Foto 1/5] ▶                 ││
│  │                                 ││
│  └─────────────────────────────────┘│
│                                     │
│  Paket Wisata Kopi & Budaya 3H2M   │
│  ★★★★★ (4.9) | 156 ulasan         │
│  📍 Mamasa, Sulawesi Barat         │
│                                     │
│  Deskripsi Paket:                  │
│  Nikmati pengalaman wisata kopi    │
│  dari kebun hingga cangkir, dibalut │
│  dengan kekayaan budaya Mamasa...  │
│  [Baca Selengkapnya ▼]             │
│                                     │
│  Itinerary (3 Hari 2 Malam):       │
│  ▼ Hari 1: Tiba dan Coffee Farm    │
│    - Penjemputan di bandara        │
│    - Check-in homestay            │
│    - Kunjungan kebun kopi         │
│    - Malam: Cena tradisional      │
│                                     │
│  ▼ Hari 2: Coffee Processing      │
│    - Pelatihan barista            │
│    - Coffee tasting               │
│    - Kunjungan rumah adat        │
│                                     │
│  ▼ Hari 3: Budaya & Pulang        │
│    - Upacara adat (jika ada)      │
│    - Belanja suvenir              │
│    - Checkout dan pulang          │
│                                     │
│  Harga & Durasi:                   │
│  Rp 2.500.000 / orang              │
│  3 Hari 2 Malam                    │
│  (Termasuk: Homestay, Meals, Guide)│
│                                     │
│  Fasilitas:                        │
│  ✓ Homestay dengan WiFi           │
│  ✓ Pemandu wisata berbahasa Inggris│
│  ✓ Asuransi perjalanan            │
│  ✓ Sertifikat peserta             │
│                                     │
│  ┌─────────────────────────────────┐│
│  │ [PESAN SEKARANG]                ││
│  └─────────────────────────────────┘│
│                                     │
│  ┌─────────────────────────────────┐│
│  │ [HUBUNGI PEMANDU WISATA]        ││
│  └─────────────────────────────────┘│
│                                     │
└─────────────────────────────────────┘
```

### Elemen Detail

| Elemen | Ukuran | Deskripsi |
| :--- | :--- | :--- |
| **Header** | Full Width | Back Button, Title, Share Button |
| **Media Gallery** | Full Width | Carousel foto/video dengan indicator |
| **Judul & Rating** | Full Width | Nama paket, bintang rating, jumlah review |
| **Lokasi** | Full Width | Icon lokasi + nama lokasi |
| **Deskripsi** | Full Width | Teks deskripsi dengan "Baca Selengkapnya" |
| **Itinerary** | Full Width | Expandable sections per hari |
| **Harga & Durasi** | Full Width | Harga besar, durasi, apa yang termasuk |
| **Fasilitas** | Full Width | List dengan checkmark |
| **CTA Buttons** | Full Width | 2 tombol: Pesan Sekarang, Hubungi Pemandu |

---

## 4. Wireframe Detil: E-Commerce Kopi

### Layout Struktur

```
┌─────────────────────────────────────┐
│ [◀] Toko Kopi Mamasa [🛒 (3)]      │
├─────────────────────────────────────┤
│                                     │
│  ┌──────────────┬──────────────┐   │
│  │ [Filter ▼]   │ [Sort: Harga] │   │
│  └──────────────┴──────────────┘   │
│                                     │
│  ┌──────────────┐ ┌──────────────┐ │
│  │ [Foto Kopi]  │ │ [Foto Kopi]  │ │
│  │ Arabika      │ │ Arabika      │ │
│  │ Medium Roast │ │ Dark Roast   │ │
│  │ Rp 85.000    │ │ Rp 95.000    │ │
│  │ [+ Keranjang]│ │ [+ Keranjang]│ │
│  └──────────────┘ └──────────────┘ │
│                                     │
│  ┌──────────────┐ ┌──────────────┐ │
│  │ [Foto Kopi]  │ │ [Foto Kopi]  │ │
│  │ Arabika      │ │ Arabika      │ │
│  │ Light Roast  │ │ Specialty    │ │
│  │ Rp 75.000    │ │ Rp 120.000   │ │
│  │ [+ Keranjang]│ │ [+ Keranjang]│ │
│  └──────────────┘ └──────────────┘ │
│                                     │
│  ┌──────────────┐ ┌──────────────┐ │
│  │ [Foto Kopi]  │ │ [Foto Kopi]  │ │
│  │ Arabika      │ │ Arabika      │ │
│  │ Instant      │ │ Ground       │ │
│  │ Rp 45.000    │ │ Rp 65.000    │ │
│  │ [+ Keranjang]│ │ [+ Keranjang]│ │
│  └──────────────┘ └──────────────┘ │
│                                     │
├─────────────────────────────────────┤
│ Total: 3 item | [LANJUT KE CHECKOUT]│
└─────────────────────────────────────┘
```

### Elemen Detail

| Elemen | Ukuran | Deskripsi |
| :--- | :--- | :--- |
| **Header** | Full Width | Back Button, Title, Cart Icon dengan badge |
| **Filter/Sort** | Full Width | Buttons untuk filter jenis, roast level, harga |
| **Product Grid** | 2 Kolom | Card dengan gambar, nama, harga, tombol |
| **Product Card** | Equal Width | Gambar (square), nama, harga, tombol add |
| **Footer** | Full Width | Total item dan tombol checkout |

---

## 5. Filter & Sort Options

### Filter Jenis Kopi
- Arabika
- Robusta
- Blend

### Filter Roast Level
- Light Roast
- Medium Roast
- Dark Roast
- Extra Dark Roast

### Filter Harga
- Rp 0 - Rp 50.000
- Rp 50.000 - Rp 100.000
- Rp 100.000 - Rp 150.000
- Rp 150.000+

### Sort Options
- Terlaris
- Rating Tertinggi
- Harga Terendah
- Harga Tertinggi
- Terbaru

---

## 6. Desain Visual (Hi-Fi Considerations)

### Color Palette
- **Primary:** #2C5F2D (Deep Forest Green) - Background utama
- **Secondary:** #8B4513 (Coffee Brown) - Accent dan borders
- **Accent 1:** #D4A574 (Golden Harvest) - Highlights dan CTA
- **Text Primary:** #F4E8D0 (Warm Cream) - Headings
- **Text Secondary:** #E8DCC4 (Light Tan) - Body text

### Typography
- **Headlines:** Playfair Display, 24-28px, Bold
- **Subheadings:** Open Sans, 16-18px, Semi-bold
- **Body Text:** Open Sans, 14px, Regular
- **Labels:** Open Sans, 12px, Medium

### Icons & Graphics
- Gunakan icon set yang konsisten (Font Awesome atau Material Icons)
- Gambar produk kopi dengan background putih atau transparan
- Foto destinasi dengan kualitas tinggi (minimal 1200x800px)
- Ikon kategori yang intuitif dan mudah dikenali

---

## 7. User Flow & Interactions

### Flow Pemesanan Paket Wisata
1. User membuka Home Screen
2. Klik kategori "Wisata Kopi"
3. Lihat daftar paket wisata
4. Klik detail paket yang diminati
5. Scroll dan baca deskripsi lengkap
6. Klik "Pesan Sekarang"
7. Masuk ke halaman checkout
8. Isi data pribadi
9. Pilih metode pembayaran
10. Konfirmasi pemesanan

### Flow Pembelian Kopi
1. User membuka Home Screen
2. Klik kategori "E-Commerce"
3. Lihat daftar produk kopi
4. Gunakan filter/sort jika perlu
5. Klik produk untuk detail
6. Klik "+ Keranjang"
7. Lanjutkan belanja atau ke checkout
8. Review keranjang
9. Isi data pengiriman
10. Pilih metode pembayaran
11. Konfirmasi pembelian

---

## 8. Responsive Design Notes

- **Mobile First Approach:** Desain untuk mobile 375x667px (iPhone SE) sebagai baseline
- **Tablet Support:** Responsive hingga 768px dengan grid 2 kolom
- **Desktop Web:** Versi web dengan layout 3-4 kolom untuk browsing yang lebih luas
- **Touch Targets:** Minimal 48x48px untuk semua interactive elements
- **Spacing:** Konsisten dengan 8px grid system

---

## 9. Performance Considerations

- **Image Optimization:** Compress semua gambar untuk loading cepat
- **Lazy Loading:** Load gambar hanya saat diperlukan
- **Caching:** Cache data produk dan destinasi untuk offline access
- **API Integration:** Integrasi dengan backend untuk real-time inventory dan pricing

---

**Catatan:** Desain Lo-Fi ini adalah blueprint untuk fase Hi-Fi development. Setiap elemen dapat disesuaikan berdasarkan feedback pengguna dan best practices UX/UI terkini.
