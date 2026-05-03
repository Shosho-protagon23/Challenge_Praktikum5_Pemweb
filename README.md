# Praktikum 5 — Pemrograman Web

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Status-Complete-00C851?style=for-the-badge"/>
</p>

---

## Deskripsi Tugas

Praktikum 5 mata kuliah Pemrograman Web berfokus pada pengenalan **JavaScript DOM (Document Object Model)**.
Materi ini merupakan lanjutan dari Praktikum 3, di mana form pendaftaran yang sudah dibuat
sebelumnya mulai dihubungkan dengan JavaScript untuk mengakses dan memanipulasi elemen HTML
secara dinamis menggunakan `document.getElementById()`.

---

## Dokumentasi

### 📄 index.html — Form Pendaftaran

Form pendaftaran yang sama dari Praktikum 3, digunakan sebagai struktur HTML
yang akan dimanipulasi oleh JavaScript.

| Field | Tipe Elemen |
|---|---|
| Nama lengkap | `<input type="text">` |
| Email | `<input type="email">` |
| Password | `<input type="password">` |
| Jenis Kelamin | `<input type="radio">` — Pria / Wanita |
| Hobi | `<input type="checkbox">` — Olahraga, Seni, Sains, Bahasa |
| Kota | `<select>` — Lampung, Banyumas, Aceh, Bandung, Semarang, Purbalingga |
| Pesan | `<textarea>` |
| Aksi | Tombol **Daftar** (submit) & **Reset** |

---

### 📄 script.js — JavaScript DOM Selection

File JavaScript yang berisi deklarasi variabel untuk mengakses elemen form menggunakan DOM.

| Variabel | Method | Target Elemen |
|---|---|---|
| `namaLengkap` | `getElementById("namaLengkap")` | Input nama lengkap |
| `email` | `getElementById("email")` | Input email |
| `jK` | `getElementById("jk")` | Input jenis kelamin |
| `kota` | `getElementById("kota")` | Dropdown kota |

**Konsep yang dipelajari:**
| Konsep | Keterangan |
|---|---|
| `document.getElementById()` | Mengakses elemen HTML berdasarkan atribut `id` |
| DOM Variable Declaration | Menyimpan referensi elemen ke dalam variabel JS |
| `var` keyword | Deklarasi variabel dengan scope function/global |

---

## Struktur File

```
Praktikum5_Pemweb/
├── index.html
├── script.js
└── README.md
```

---

## Author

<p>
  <a href="https://github.com/Shosho-protagon23">
    <img src="https://img.shields.io/badge/GitHub-Shosho--protagon23-00ff41?style=for-the-badge&logo=github&logoColor=black&labelColor=0d0d0d"/>
  </a>
</p>
