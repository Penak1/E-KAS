# E-Kas - Smart Personal Finance Assistant
<h1 align="center">💎 E-Kas</h1>
<div align="center">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1000 500" width="100%" height="auto" style="border-radius: 12px; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;">
    <defs>
      <!-- Background Gradients -->
      <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#001850" />
        <stop offset="50%" stop-color="#052880" />
        <stop offset="100%" stop-color="#0b112c" />
      </linearGradient>
      <radialGradient id="glowGrad" cx="10%" cy="20%" r="50%">
        <stop offset="0%" stop-color="#3b82f6" stop-opacity="0.3"/>
        <stop offset="100%" stop-color="#052880" stop-opacity="0"/>
      </radialGradient>
      <radialGradient id="glowGradRight" cx="80%" cy="80%" r="60%">
        <stop offset="0%" stop-color="#7c3aed" stop-opacity="0.25"/>
        <stop offset="100%" stop-color="#052880" stop-opacity="0"/>
      </radialGradient>

      <!-- Diamond/Logo Gradients -->
      <linearGradient id="diamondGrad1" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#38bdf8" />
        <stop offset="100%" stop-color="#0284c7" />
      </linearGradient>
      <linearGradient id="diamondGrad2" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#a78bfa" />
        <stop offset="100%" stop-color="#6d28d9" />
      </linearGradient>
      <linearGradient id="diamondGrad3" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#ffffff" />
        <stop offset="100%" stop-color="#bae6fd" />
      </linearGradient>

      <!-- Card Gradient -->
      <linearGradient id="cardGrad" x1="0%" y1="0%" x2="0%" y2="100%">
        <stop offset="0%" stop-color="#1e293b" stop-opacity="0.8" />
        <stop offset="100%" stop-color="#0f172a" stop-opacity="0.9" />
      </linearGradient>
      
      <!-- Gold Gradient -->
      <linearGradient id="goldGrad" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#fbbf24" />
        <stop offset="100%" stop-color="#d97706" />
      </linearGradient>
    </defs>

    <!-- Background -->
    <rect width="1000" height="500" fill="url(#bgGrad)" />
    <rect width="1000" height="500" fill="url(#glowGrad)" />
    <rect width="1000" height="500" fill="url(#glowGradRight)" />

    <!-- Wave/Abstract Shapes in Background -->
    <path d="M 0 100 Q 250 50 500 200 T 1000 150 L 1000 500 L 0 500 Z" fill="#ffffff" fill-opacity="0.02" />
    <path d="M 0 350 Q 300 250 600 420 T 1000 300 L 1000 500 L 0 500 Z" fill="#00f2fe" fill-opacity="0.03" />

    <!-- Decorative Stars/Glows -->
    <circle cx="450" cy="80" r="1.5" fill="#fff" opacity="0.6" />
    <circle cx="580" cy="180" r="2" fill="#fff" opacity="0.8" />
    <circle cx="150" cy="400" r="1.5" fill="#fff" opacity="0.5" />
    <circle cx="850" cy="90" r="2.5" fill="#fff" opacity="0.7" />
    
    <!-- Large Glowing Star/Cross -->
    <g transform="translate(450, 70) scale(0.6)">
      <path d="M 0,-15 L 3,-3 L 15,0 L 3,3 L 0,15 L -3,3 L -15,0 L -3,-3 Z" fill="#fff" opacity="0.8" />
    </g>
    <g transform="translate(850, 80) scale(0.8)">
      <path d="M 0,-15 L 3,-3 L 15,0 L 3,3 L 0,15 L -3,3 L -15,0 L -3,-3 Z" fill="#fff" opacity="0.9" />
    </g>

    <!-- BRANDING SECTION (Left-Center) -->
    <!-- Logo (Diamond) -->
    <g transform="translate(80, 110)">
      <!-- Left facet -->
      <polygon points="0,35 45,0 45,70" fill="url(#diamondGrad1)" />
      <!-- Center top facet -->
      <polygon points="45,0 90,35 45,35" fill="url(#diamondGrad3)" />
      <!-- Center bottom facet -->
      <polygon points="45,35 90,35 45,70" fill="url(#diamondGrad2)" />
      <!-- Right facet -->
      <polygon points="90,35 135,35 90,70" fill="url(#diamondGrad1)" opacity="0.8" />
      <!-- Top right facet -->
      <polygon points="90,35 135,35 90,0" fill="url(#diamondGrad3)" opacity="0.9" />
      <!-- Sparkle/Glow lines -->
      <line x1="-10" y1="10" x2="0" y2="20" stroke="#fff" stroke-width="1.5" stroke-linecap="round" opacity="0.7"/>
      <line x1="20" y1="-10" x2="30" y2="0" stroke="#fff" stroke-width="1.5" stroke-linecap="round" opacity="0.7"/>
      <circle cx="-5" cy="5" r="2" fill="#fff" />
      <circle cx="25" cy="-15" r="1.5" fill="#fff" />
    </g>

    <!-- Title & Subtitle -->
    <text x="240" y="175" font-size="76" font-weight="900" fill="#ffffff" letter-spacing="1">E-Kas</text>
    <text x="80" y="240" font-size="28" font-weight="700" fill="#ffffff">
      Smart Personal Finance <tspan fill="#60a5fa">Assistant</tspan>
    </text>
    <text x="80" y="280" font-size="18" fill="#cbd5e1" font-weight="400">
      Kelola Keuangan Lebih Cerdas dengan <tspan fill="#38bdf8" font-weight="600">AI</tspan>, <tspan fill="#c084fc" font-weight="600">Suara</tspan>, dan <tspan fill="#34d399" font-weight="600">Analitik Modern</tspan>
    </text>

    <!-- Mockup Phone / Floating Widgets (Right side representation) -->
    <g transform="translate(680, 50)">
      <!-- Main Phone body shadow -->
      <rect x="0" y="0" width="220" height="380" rx="35" fill="#030712" opacity="0.6" filter="blur(10px)" />
      <!-- Main Phone body -->
      <rect x="0" y="0" width="220" height="380" rx="35" fill="#0b1329" stroke="#1e293b" stroke-width="4" />
      <!-- Phone Inner Screen -->
      <rect x="8" y="8" width="204" height="364" rx="28" fill="#080e1e" />
      
      <!-- Phone Camera/Speaker Notch -->
      <rect x="70" y="8" width="80" height="18" rx="9" fill="#030712" />
      
      <!-- Mockup Balance Card -->
      <rect x="20" y="45" width="180" height="90" rx="16" fill="#1e293b" opacity="0.8" />
      <text x="35" y="70" font-size="11" fill="#94a3b8">Total Saldo</text>
      <text x="35" y="95" font-size="18" font-weight="bold" fill="#ffffff">Rp 25.680.000</text>
      
      <!-- Cash Flow small graph indicators -->
      <rect x="35" y="112" width="65" height="15" rx="4" fill="#15803d" fill-opacity="0.2" />
      <text x="42" y="123" font-size="9" fill="#4ade80" font-weight="bold">▲ 12.5%</text>
      
      <rect x="110" y="112" width="65" height="15" rx="4" fill="#b91c1c" fill-opacity="0.2" />
      <text x="117" y="123" font-size="9" fill="#f87171" font-weight="bold">▼ 8.3%</text>

      <!-- Transaction List Mock -->
      <text x="25" y="165" font-size="12" font-weight="bold" fill="#f1f5f9">Transaksi Terbaru</text>
      
      <!-- Item 1 -->
      <rect x="20" y="180" width="180" height="38" rx="10" fill="#0f172a" />
      <circle cx="38" cy="199" r="12" fill="#d97706" />
      <!-- Food icon (simple bowl/fork path) -->
      <path d="M 34 199 L 42 199 M 38 195 L 38 203" stroke="#fff" stroke-width="1.5" stroke-linecap="round" />
      <text x="58" y="197" font-size="10" font-weight="bold" fill="#f1f5f9">Makan Siang</text>
      <text x="58" y="208" font-size="8" fill="#64748b">Hari ini</text>
      <text x="142" y="203" font-size="10" font-weight="bold" fill="#f87171">- Rp 25.000</text>

      <!-- Item 2 -->
      <rect x="20" y="226" width="180" height="38" rx="10" fill="#0f172a" />
      <circle cx="38" cy="245" r="12" fill="#059669" />
      <!-- Salary icon (simple wallet/bill path) -->
      <rect x="32" y="240" width="12" height="9" rx="1" fill="none" stroke="#fff" stroke-width="1.5" />
      <text x="58" y="243" font-size="10" font-weight="bold" fill="#f1f5f9">Gaji Bulanan</text>
      <text x="58" y="254" font-size="8" fill="#64748b">Kemarin</text>
      <text x="138" y="249" font-size="10" font-weight="bold" fill="#4ade80">+ Rp 5.000.000</text>

      <!-- Navigation Bar at Bottom -->
      <rect x="8" y="325" width="204" height="47" rx="0" fill="#060b18" />
      <circle cx="110" cy="340" r="18" fill="#2563eb" />
      <text x="110" y="345" font-size="18" font-weight="bold" fill="#ffffff" text-anchor="middle">+</text>
      <!-- Small dots for other nav items -->
      <circle cx="40" cy="340" r="3" fill="#64748b" />
      <circle cx="75" cy="340" r="3" fill="#64748b" />
      <circle cx="145" cy="340" r="3" fill="#64748b" />
      <circle cx="180" cy="340" r="3" fill="#64748b" />
    </g>

    <!-- Floating Scan Widget (Overlapping Phone) -->
    <g transform="translate(560, 240)">
      <rect x="0" y="0" width="140" height="70" rx="14" fill="#1e293b" stroke="#334155" stroke-width="1.5" opacity="0.95" />
      <text x="15" y="22" font-size="10" font-weight="bold" fill="#38bdf8">Scan Nota AI</text>
      <text x="15" y="42" font-size="14" font-weight="bold" fill="#ffffff">Rp 125.000</text>
      <text x="15" y="56" font-size="8" fill="#34d399">✓ Berhasil dipindai</text>
      <!-- Success check icon -->
      <circle cx="115" cy="40" r="10" fill="#10b981" />
      <path d="M 111 40 L 114 43 L 120 37" fill="none" stroke="#fff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
    </g>

    <!-- FEATURE CARDS SECTION (Bottom 5 columns) -->
    <!-- Card 1: Voice Input -->
    <g transform="translate(80, 315)">
      <rect width="150" height="95" rx="12" fill="url(#cardGrad)" stroke="#1e293b" stroke-width="1" />
      <rect x="12" y="12" width="32" height="32" rx="8" fill="#2563eb" />
      <!-- Mic Icon -->
      <path d="M 28 22 C 28 25 26 27 24 27 C 22 27 20 25 20 22 L 20 18 C 20 15 22 14 24 14 C 26 14 28 15 28 18 Z" fill="none" stroke="#fff" stroke-width="1.5"/>
      <path d="M 17 22 C 17 26 21 29 24 29 C 27 29 31 26 31 22" fill="none" stroke="#fff" stroke-width="1.5"/>
      <line x1="24" y1="29" x2="24" y2="33" stroke="#fff" stroke-width="1.5" />
      
      <text x="12" y="60" font-size="12" font-weight="bold" fill="#ffffff">Voice Input</text>
      <text x="12" y="74" font-size="9" fill="#94a3b8">Catat transaksi</text>
      <text x="12" y="85" font-size="9" fill="#94a3b8">dengan suara</text>
    </g>

    <!-- Card 2: Receipt Scanner -->
    <g transform="translate(242, 315)">
      <rect width="150" height="95" rx="12" fill="url(#cardGrad)" stroke="#1e293b" stroke-width="1" />
      <rect x="12" y="12" width="32" height="32" rx="8" fill="#7c3aed" />
      <!-- Camera/Scanner Icon -->
      <rect x="19" y="21" width="18" height="12" rx="2" fill="none" stroke="#fff" stroke-width="1.5" />
      <path d="M 24 21 L 26 18 L 30 18 L 32 21" fill="none" stroke="#fff" stroke-width="1.5" stroke-linejoin="round" />
      <circle cx="28" cy="27" r="3" fill="none" stroke="#fff" stroke-width="1.5" />
      
      <text x="12" y="60" font-size="12" font-weight="bold" fill="#ffffff">Receipt Scanner</text>
      <text x="12" y="74" font-size="9" fill="#94a3b8">Scan nota otomatis</text>
      <text x="12" y="85" font-size="9" fill="#94a3b8">dengan AI</text>
    </g>

    <!-- Card 3: Smart Analytics -->
    <g transform="translate(404, 315)">
      <rect width="150" height="95" rx="12" fill="url(#cardGrad)" stroke="#1e293b" stroke-width="1" />
      <rect x="12" y="12" width="32" height="32" rx="8" fill="#0891b2" />
      <!-- Chart Icon -->
      <line x1="20" y1="32" x2="36" y2="32" stroke="#fff" stroke-width="1.5" stroke-linecap="round" />
      <rect x="22" y="24" width="3" height="8" fill="#fff" />
      <rect x="27" y="18" width="3" height="14" fill="#fff" />
      <rect x="32" y="21" width="3" height="11" fill="#fff" />
      
      <text x="12" y="60" font-size="12" font-weight="bold" fill="#ffffff">Smart Analytics</text>
      <text x="12" y="74" font-size="9" fill="#94a3b8">Laporan &amp; grafik</text>
      <text x="12" y="85" font-size="9" fill="#94a3b8">yang informatif</text>
    </g>

    <!-- Card 4: Custom Categories -->
    <g transform="translate(566, 315)">
      <rect width="150" height="95" rx="12" fill="url(#cardGrad)" stroke="#1e293b" stroke-width="1" />
      <rect x="12" y="12" width="32" height="32" rx="8" fill="#ea580c" />
      <!-- Folder/Grid Icon -->
      <path d="M 18 18 L 24 18 L 26 21 L 36 21 L 36 32 L 18 32 Z" fill="none" stroke="#fff" stroke-width="1.5" stroke-linejoin="round" />
      
      <text x="12" y="60" font-size="12" font-weight="bold" fill="#ffffff">Custom Categories</text>
      <text x="12" y="74" font-size="9" fill="#94a3b8">Kategori fleksibel</text>
      <text x="12" y="85" font-size="9" fill="#94a3b8">sesuai kebutuhan</text>
    </g>

    <!-- FOOTER DIVIDER LINE -->
    <line x1="80" y1="435" x2="920" y2="435" stroke="#1e293b" stroke-width="1" opacity="0.6" />

    <!-- FOOTER INFO -->
    <!-- Privacy Info -->
    <g transform="translate(80, 448)">
      <!-- Shield Icon -->
      <rect x="0" y="2" width="20" height="20" rx="4" fill="#1e293b" />
      <path d="M 6 8 L 10 6 L 14 8 L 14 12 C 14 15 11 17 10 18 C 9 17 6 15 6 12 Z" fill="none" stroke="#38bdf8" stroke-width="1.2" />
      <text x="28" y="11" font-size="11" font-weight="bold" fill="#ffffff">Privasi Anda, Prioritas Kami</text>
      <text x="28" y="22" font-size="9" fill="#64748b">Data Anda dikelola dengan aman dan lokal</text>
    </g>

    <!-- Premium Design Info -->
    <g transform="translate(420, 448)">
      <!-- Star/Award Icon -->
      <rect x="0" y="2" width="20" height="20" rx="4" fill="#1e293b" />
      <path d="M 10 5 L 11.5 8.5 L 15 9 L 12.5 11.5 L 13 15 L 10 13.5 L 7 15 L 7.5 11.5 L 5 9 L 8.5 8.5 Z" fill="url(#goldGrad)" />
      <text x="28" y="11" font-size="11" font-weight="bold" fill="#ffffff">Desain Premium</text>
      <text x="28" y="22" font-size="9" fill="#64748b">Pengalaman modern dan intuitif</text>
    </g>
  </svg>
</div>

<br/>

<p align="center">
  <b>Smart Personal Finance Assistant</b><br>
  Kelola Keuangan Lebih Cerdas dengan AI, Suara, dan Analitik Modern
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Version-Latest-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Platform-Android-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/AI-Powered-purple?style=for-the-badge">
  <img src="https://img.shields.io/badge/UI-Premium-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge">
</p>

---

## ✨ Tentang E-Kas

**E-Kas** adalah aplikasi pencatatan keuangan modern yang dirancang untuk membantu Anda mengelola pemasukan, pengeluaran, tabungan, hutang, dan aktivitas finansial harian dengan lebih praktis.

Menggabungkan desain premium, teknologi AI, serta pengalaman pengguna yang intuitif untuk menghadirkan cara baru dalam mengelola keuangan pribadi.

---

# 🚀 Fitur Unggulan

## 🎙️ Voice Transaction

Catat transaksi cukup dengan suara.

Ucapkan transaksi secara natural dan sistem akan membantu mengisi data transaksi secara otomatis untuk mempercepat proses pencatatan.

---

## 📸 Smart Receipt Scanner

Scan nota atau struk belanja hanya dalam beberapa detik.

Teknologi AI membantu membaca informasi penting sehingga proses input menjadi lebih cepat dan nyaman.

---

## ⚡ Quick Input

Input transaksi secepat mengirim pesan.

Contoh:

```text
Makan siang 25000
```

Sistem akan membantu mengenali nominal dan deskripsi transaksi secara otomatis.

---

## 📊 Smart Analytics

Pantau kondisi keuangan melalui:

- Grafik pemasukan
- Grafik pengeluaran
- Ringkasan bulanan
- Statistik kategori
- Tren keuangan

Semua disajikan dalam tampilan visual yang mudah dipahami.

---

## 📁 Custom Categories

Buat kategori sesuai kebutuhan:

- Makanan
- Transportasi
- Gaji
- Investasi
- Bisnis
- Tabungan
- Dan kategori lainnya

Lengkap dengan ikon dan warna yang dapat disesuaikan.

---

## 🔒 Secure Access

Lapisan keamanan modern untuk menjaga privasi data dan memberikan pengalaman penggunaan yang lebih nyaman.

---

## 🌙 Premium UI Experience

Nikmati tampilan modern dengan:

- Glassmorphism Design
- Smooth Animation
- Dark Mode
- Material Design
- Responsive Layout

Dirancang agar nyaman digunakan setiap hari.

---

# 💎 Highlights

✅ Voice Transaction

✅ AI Receipt Scanner

✅ Smart Analytics

✅ Quick Input

✅ Custom Categories

✅ Dark Mode

✅ Backup & Restore

✅ Financial Dashboard

✅ Premium UI

✅ Fast Performance

---

# 📱 Cocok Untuk

- Mahasiswa
- Anak Kos
- Karyawan
- Freelancer
- UMKM
- Pebisnis
- Keluarga
- Pengguna yang ingin mengatur keuangan dengan lebih baik

---

# 📸 Preview

<p align="center">
  <img src="assets/screenshots/home.png" width="220">
  <img src="assets/screenshots/report.png" width="220">
  <img src="assets/screenshots/category.png" width="220">
</p>

> Ganti gambar di atas dengan screenshot aplikasi Anda.

---

# 📥 Download

Unduh versi terbaru melalui halaman **Releases**.

```text
GitHub → Releases → Download APK
```

---

# ⭐ Dukungan

Jika aplikasi ini bermanfaat:

- Berikan ⭐ pada repository
- Bagikan kepada teman
- Berikan masukan dan saran

---

<p align="center">
  <b>💎 E-Kas</b><br>
  Smart Personal Finance Assistant
</p>

<p align="center">
  Kelola uang lebih cerdas, lebih mudah, dan lebih terorganisir.
</p>
