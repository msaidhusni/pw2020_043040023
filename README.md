# Akari Ease

Akari Ease adalah sebuah website toko online untuk menjual produk-produk seperti sayuran dan kebutuhan rumah lainnya. Website ini dibangun menggunakan teknologi terbaru untuk memberikan pengalaman pengguna yang interaktif dan performa yang optimal.

## Tech Stack

- **Next.js**: Framework React yang digunakan untuk membangun aplikasi web dengan kemampuan server-side rendering (SSR) untuk meningkatkan SEO.
- **TypeScript**: Superset dari JavaScript yang memberikan tipe statis dan alat pengembangan yang lebih baik.
- **Prisma**: ORM yang digunakan untuk mengelola dan menghubungkan aplikasi dengan database.
- **Redux Toolkit**: Digunakan untuk state management yang efisien dan terstruktur.

## Fitur

- **Server-Side Rendering (SSR)**: Meningkatkan SEO dan waktu muat halaman dengan merender halaman di server.
- **State Management**: Menggunakan Redux Toolkit untuk mengelola state aplikasi dengan cara yang lebih baik dan efisien.
- **Database Management**: Menggunakan Prisma untuk pengelolaan database yang lebih mudah dan terstruktur.
- **Responsive Design**: Desain yang responsif untuk tampilan yang optimal di berbagai perangkat.

## Instalasi

1. Clone repository ini:

   ```bash
   git clone https://github.com/username/akari-ease.git
   cd akari-ease
   ```

2. Instal dependensi:

   ```bash
   npm install
   ```

3. Konfigurasi database dengan Prisma:

   Buat file `.env` di root project dan tambahkan konfigurasi database Anda:

   ```env
   DATABASE_URL="your-database-url"
   ```

   Generate client Prisma:

   ```bash
   npx prisma generate
   ```

   Jalankan migrasi database:

   ```bash
   npx prisma migrate dev --name init
   ```

4. Jalankan aplikasi:

   ```bash
   npm run dev
   ```

   Aplikasi akan berjalan di `http://localhost:3000`.

Jika ada informasi tambahan atau spesifik yang ingin ditambahkan, silakan beritahu saya!
