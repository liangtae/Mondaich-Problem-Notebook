# Mondaich-Problem-Notebook

# 問題帳 Mondaichō — Catatan Pemecahan Masalah

> Notebook masalah bergaya Jepang untuk membedah setiap masalah dengan metode **5W + 1H** (Apa, Siapa, Kapan, Dimana, Mengapa, Bagaimana) — ringan, cantik, dan 100% berjalan di browser tanpa backend.

**Deskripsi singkat untuk GitHub (About):**
> Catatan digital bergaya Jepang untuk membedah masalah dengan metode 5W+1H — tag, prioritas bintang, pin, pencarian, dark mode, backup/restore JSON, dan pagination — murni HTML/CSS/JS, data tersimpan di localStorage.

**Topik/tags yang disarankan:** `problem-solving` `5w1h` `vanilla-js` `single-file-app` `localstorage` `productivity` `japanese-design` `no-backend`

---

## ✨ Fitur

- **Metode 5W + 1H** — setiap masalah dicatat lengkap: Apa (何), Siapa (誰), Kapan (いつ), Dimana (どこ), Mengapa (なぜ), Bagaimana (どう).
- **Prioritas & status** — tandai tingkat kesulitan dengan bintang (1–5), tandai selesai/berjalan, dan sematkan (pin) masalah penting di atas.
- **Tag & pencarian** — beri tag bebas, filter berdasarkan tag/status, cari di judul/isi/tag, serta urutkan (terbaru, terlama, A–Z, kesulitan).
- **Pagination lengkap dengan range** — bilah pagination menampilkan rentang data aktif (`Menampilkan 16–30 dari 42 masalah`), navigasi first/prev/next/last, nomor halaman bercelah (`…`) di sekitar halaman aktif, kotak **lompat ke halaman**, serta pilihan **jumlah item per halaman** (10/15/25/50/Semua) yang tersimpan otomatis.
- **Backup & restore** — ekspor seluruh data ke file JSON dan impor kembali kapan saja; ada juga opsi reset total.
- **Mode gelap/terang** — beralih tema dengan satu klik, tersimpan di perangkat.
- **Kutipan inspiratif** — 250+ kutipan seputar problem solving & motivasi yang berganti secara acak.
- **Sepenuhnya offline & privat** — semua data disimpan di `localStorage` browser Anda sendiri, tidak ada server atau tracking.

## 🖥️ Demo

Cukup buka `mondaicho.html` di browser apa pun (Chrome, Edge, Firefox, Safari) — tidak perlu instalasi, server, atau koneksi internet (kecuali untuk memuat font Google Fonts).

## 🚀 Cara Menjalankan

1. Clone atau unduh repository ini.
2. Buka file `mondaicho.html` langsung di browser (double-click), **atau** jalankan lewat local server ringan:
   ```bash
   npx serve .
   # atau
   python3 -m http.server 8080
   ```
3. Mulai catat masalahmu dengan tombol **"＋ Masalah baru"**.

## 🧩 Cara Pakai

1. Klik **"＋ Masalah baru"**, isi judul dan jawab elemen 5W+1H selengkap mungkin.
2. Tambahkan tag (dipisah koma) dan atur tingkat kesulitan dengan bintang.
3. Gunakan kotak pencarian, filter tag/status, dan pengurutan untuk menavigasi daftar masalah.
4. Klik judul kartu untuk membuka/menutup detail 5W+1H.
5. Gunakan bilah di bawah daftar untuk **berpindah halaman**, **melompat ke halaman tertentu**, atau **mengubah jumlah item per halaman**.
6. Tandai selesai ketika masalah terpecahkan — akan muncul animasi stempel 解決 dan taburan sakura 🌸.
7. Backup data secara berkala lewat tombol **"⬇ Backup data"**.

## 🛠️ Teknologi

- HTML5, CSS3 (custom properties untuk tema terang/gelap), JavaScript (vanilla, tanpa dependency/framework).
- Font: [Shippori Mincho](https://fonts.google.com/specimen/Shippori+Mincho) & [Zen Kaku Gothic New](https://fonts.google.com/specimen/Zen+Kaku+Gothic+New) via Google Fonts.
- Penyimpanan: `localStorage` browser (tidak ada backend/database).

## 📁 Struktur Proyek

```
.
├── mondaicho.html   # Aplikasi single-file (HTML + CSS + JS)
└── README.md        # Dokumentasi ini
```

## 🗺️ Roadmap (opsional ke depan)

- [ ] Ekspor per-masalah ke PDF/Markdown
- [ ] Sinkronisasi lintas perangkat (opsional, via cloud storage)
- [ ] Statistik/dashboard (jumlah selesai per minggu, distribusi tag)

## 🤝 Kontribusi

Pull request dan saran sangat diterima. Silakan fork repo ini, buat branch baru, dan ajukan PR.

## 📄 Lisensi

Proyek ini dirilis di bawah [Lisensi MIT](LICENSE) — bebas digunakan, dimodifikasi, dan didistribusikan.

---

一期一会 — *setiap masalah adalah kesempatan untuk memahami lebih dalam.*
