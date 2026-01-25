# DREAM OS v13.4.5 - SIF AL-FIKRI EDITION

Sistem Digital Terpadu untuk SIF Al-Fikri dengan fitur keamanan tingkat tinggi dan UX optimal untuk perangkat Samsung A12/A15/A25.

## Fitur Utama
- 🔐 **Secure Authentication**: Password berlapis + Fingerprint Biometric
- 👁️ **Show/Hide Password**: Tombol mata yang responsif
- 🚨 **Auto-Lock**: Sistem terkunci 5 menit setelah 3x gagal login
- 📱 **PWA Ready**: Installable ke home screen HP
- 🌐 **Responsive Design**: Optimized untuk Samsung series
- 💾 **Offline Support**: Tetap berfungsi tanpa internet
- 🏛️ **SIF Branding**: Header spiritual dengan Bismillah & Shalawat

## Cara Deploy ke Cloudflare Pages

1. **Buat repo GitHub baru** (misal: `sif-dreamos`)
2. **Upload semua file** ke repo tersebut
3. **Buka Cloudflare Dashboard** → Pages → Create Project
4. **Konfigurasi build**:
   - Framework preset: `None`
   - Build command: _kosongkan_
   - Build output directory: `/`
5. **Environment Variables** (di Cloudflare):
   - `VITE_SUPABASE_URL`: URL project Supabase
   - `VITE_SUPABASE_KEY`: Anon key Supabase
6. **Klik Deploy!**

## Password Default (Untuk Tim Internal)

| Role | Password | Catatan |
|------|----------|---------|
| **Master M** | `Mr.M_Architect_2025` | Full system control |
| **Admin No.8** | `4dm1n_AF6969@00` | Akses semua modul |
| **Security** | `LHPSsec_AF2025` | Laporan keamanan & patroli |
| **User Umum** | `user_@1234` | Booking ruangan |

> **PERINGATAN**: Ganti password default setelah deploy! Simpan Master Key di tempat aman.

بِسْمِ اللَّهِ بِإِذْنِ اللَّهِ — Dibangun dengan Shalawat & Kecintaan pada Amal Digital Al-Fikri
