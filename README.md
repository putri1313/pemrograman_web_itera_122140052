Personal Dashboard

Aplikasi dashboard pribadi untuk mahasiswa yang membantu mengatur tugas dan melihat waktu secara real-time.

🎯 Fitur Aplikasi

- ⏰ Jam Indonesia Real-Time: Menampilkan jam, hari, dan tanggal secara otomatis dan akurat.
- ✅ Daftar Tugas:
  - Menambahkan tugas dan deadline.
  - Menampilkan daftar tugas yang sudah ditambahkan.
  - Menandai tugas yang telah selesai (checklist).
- 💾 Penyimpanan Lokal: Semua data disimpan menggunakan `localStorage`, sehingga data tetap ada meskipun halaman direfresh.

🧠 Fitur ES6+ yang Diimplementasikan

- Penggunaan `let` dan `const` untuk deklarasi variabel.
- Template literals untuk menampilkan data secara dinamis.
- Minimal 3 Arrow functions (`updateClock`, `getTasks`, `saveTasks`, dll).
- Destructuring dan spread/rest operator digunakan di modul data.
- Default parameter di beberapa fungsi.
- Pembuatan dan penggunaan `Class` (jika ditambahkan untuk fitur lanjutan).
- Enhanced object literals.
- Modularisasi kode dengan `import/export` ES6 module.
- Array methods: `forEach`, `map`, dll.
- Asynchronous function menggunakan `setInterval()` dan waktu `Asia/Jakarta`.
- DOM Manipulation modern dengan querySelector dan event listener.
- Fetch API (dapat ditambahkan jika ingin ambil data cuaca).

 📁 Struktur Folder

```
project-js-nextgen/
│
├── index.html
├── css/
│   └── style.css      
├── js/
│   ├── main.js
│   ├── app.js
│   └── modules/
│       ├── utils.js
│       └── data.js


📸 Screenshot
![Screenshot 2025-04-15 010429](https://github.com/user-attachments/assets/21c580e5-87cf-43b3-a8e0-1bd777b05987)


 🚀 Cara Menjalankan

1. Buka file `index.html` di browser.
2. Tambahkan daftar tugas dan lihat waktu saat ini secara langsung.
3. Semua data akan otomatis tersimpan di browser menggunakan localStorage.

---

✨ Dibuat untuk memenuhi tugas praktikum Pemrograman Web dengan fokus pada fitur ES6+, interaktivitas, dan manajemen data lokal.

