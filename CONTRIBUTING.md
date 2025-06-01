# 🛠 Panduan Kontribusi

Terima kasih telah tertarik untuk berkontribusi di KelasFullstack GitHub Organization!

Kami percaya bahwa kontribusi kecil dapat memberi dampak besar—baik bagi kariermu maupun komunitas ini. 💪

---

## 🧾 Syarat Umum

- Memiliki akun GitHub aktif
- Memahami dasar penggunaan Git (clone, commit, push, pull request)
- Proyek yang dikirimkan adalah milik sendiri atau proyek publik yang legal untuk dibagikan

---

## 🔁 Alur Kontribusi

1. **Fork** repositori yang ingin kamu kontribusikan (misalnya `kelasfullstack-latihan`)
2. **Clone** repositori hasil fork ke lokal:
   ```bash
   git clone https://github.com/username-kamu/nama-repo
   ```
3. Buat branch baru (opsional tapi direkomendasikan):
   ```bash
   git checkout -b tambah-proyek-portfolio
   ```
4. Tambahkan proyekmu di folder yang sesuai
5. Commit & push:
   ```bash
   git add .
   git commit -m "Menambahkan proyek portfolio React"
   git push origin tambah-proyek-portfolio
   ```
6. Buat **Pull Request** ke repo asal
7. Tim kami akan mereview dan merge jika sesuai

---

## 🧩 Format Struktur Proyek

Setiap proyek sebaiknya diletakkan di dalam folder dengan struktur berikut:

```
nama-proyek/
├── README.md
├── public/
├── src/
├── package.json
└── ...
```

Minimal harus ada:
- `README.md` berisi deskripsi proyek, teknologi yang digunakan, dan cara menjalankan
- Struktur file yang rapi

---

## 📋 Tips Kontribusi Berkualitas

- Tulis README yang jelas dan mudah dipahami
- Gunakan bahasa pemrograman yang umum (JavaScript, Python, Go, dsb)
- Pastikan tidak menyertakan informasi rahasia (API key, token, dsb)
- Hindari file `.env` dan `node_modules`

---

Selamat berkontribusi! 🎉

Jika butuh bantuan, silakan buka issue atau hubungi tim KelasFullstack.

Salam kolaborasi,  
Tim KelasFullstack 🚀
