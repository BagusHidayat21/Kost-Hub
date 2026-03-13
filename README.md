# KostHub - Platform Manajemen Kost/Kontrakan

KostHub adalah platform SaaS multitenant yang membantu pemilik kost/kontrakan mengelola properti mereka secara digital, mulai dari manajemen kamar, penyewa, pembayaran, hingga pelaporan keuangan.

## 🚀 Fitur Utama (MVP)

- **Multi-Tenancy**: Isolasi data antar pemilik kost dengan tenant_id.
- **Manajemen Properti & Kamar**: Kelola unit properti dan detail kamar secara terstruktur.
- **Manajemen Penyewa**: Pantau data penyewa, riwayat sewa, dan integrasi foto KTP.
- **Manajemen Pembayaran**: Auto-generate invoice bulanan dan pencatatan pembayaran manual (tunai/transfer).
- **Dashboard & Laporan**: Monitoring occupancy rate, revenue, dan tunggakan secara real-time.

## 🛠️ Tech Stack

### Frontend
- **Next.js 16**: React framework terbaru dengan App Router.
- **React 19**: Versi terbaru React untuk performa optimal.
- **Tailwind CSS 4**: Modern styling dengan CSS-first approach.
- **TypeScript**: Type-safety untuk pengembangan yang lebih handal.

### Backend
- **Express.js 5**: Web framework cepat dan minimalis untuk Node.js.
- **Prisma ORM**: Type-safe database queries.
- **PostgreSQL**: Relational database untuk penyimpanan data yang robust.

## 📂 Struktur Proyek

```bash
KostHub/
├── frontend/    # Next.js Application
└── backend/     # Express.js API
```

## ⚙️ Persiapan Pengembangan

### Prerequisites
- Node.js (v18+)
- PostgreSQL
- npm atau yarn

### Instalasi Backend

1. Masuk ke direktori backend:
   ```bash
   cd backend
   ```
2. Instal dependensi:
   ```bash
   npm install
   ```
3. Copy file `.env.example` ke `.env` dan sesuaikan konfigurasinya:
   ```bash
   DATABASE_URL="postgresql://user:password@localhost:5432/kosthub"
   JWT_SECRET="your-secret-key"
   ```

### Instalasi Frontend

1. Masuk ke direktori frontend:
   ```bash
   cd frontend
   ```
2. Instal dependensi:
   ```bash
   npm install
   ```
3. Jalankan development server:
   ```bash
   npm run dev
   ```

## 🗺️ Roadmap Pasca-MVP

- **v1.1**: Integrasi Payment Gateway (Midtrans/Xendit) & Auto-reconciliation.
- **v1.2**: Sistem komplain, tracking maintenance, dan support multi-bahasa.
- **v1.3**: Sistem booking untuk calon penyewa dan Virtual Tour.
- **v2.0**: Mobile App (iOS/Android), IoT Smart Locks, dan Marketplace Kost.

## 📝 Lisensi

Proyek ini dikembangkan untuk kebutuhan internal. Hak cipta © 2026 KostHub.
