# 🎫 Tiket Teknisi

Aplikasi work-order teknisi lapangan, mobile-first: buat tiket, pantau status, share ke WhatsApp, export CSV. Data tersimpan offline di `localStorage` HP — tanpa server/database.

![Status](https://img.shields.io/badge/mobile_first-blue?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)

## Fitur

- ➕ Buat tiket: judul, lokasi, prioritas, teknisi, catatan
- ▶ Status berjenjang: Baru → Dikerjakan → Selesai
- 🔍 Filter status + statistik count
- 💬 Share 1 tiket ke WhatsApp (format rapi)
- ⬇ Export CSV (buka di Excel) + bersihkan tiket selesai
- 📴 100% offline — cocok untuk area sinyal lemah

## Teknologi

Astro static + vanilla JS. Satu file `src/pages/index.astro` (±200 baris).

## Kustomisasi

- Nomor WA tujuan: konstanta `WA_NUMBER` di atas file.
- Daftar teknisi: `<select id="fTeknisi">` di form.

## Run

```bash
npm install
npm run dev
```

Live: https://dulkemot.github.io/tiket-teknisi/

MIT — dulkemot 2026
