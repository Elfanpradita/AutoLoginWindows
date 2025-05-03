# 🚀 Auto Login Windows via Registry Editor

Panduan singkat untuk mengatur Windows agar login otomatis tanpa perlu memasukkan password setiap kali menyala.

## ⚠️ Peringatan
- Gunakan hanya di komputer pribadi, **bukan** komputer publik.
- Password akan tersimpan dalam bentuk teks biasa di Registry, jadi **risiko keamanan** harus kamu pahami.

---

## 🛠️ Langkah-langkah

1. Tekan `Windows + R`, ketik `regedit`, lalu tekan **Enter**.
2. Arahkan ke folder berikut:
3. Tambahkan atau ubah nilai berikut (klik kanan > New > String Value jika belum ada):

| Nama String        | Nilai yang Diisi                         |
|--------------------|------------------------------------------|
| `DefaultUserName`  | Email akun Microsoft kamu                |
| `DefaultPassword`  | Password akun Microsoft kamu             |
| `AutoAdminLogon`   | `1`                                      |

4. Tutup Registry Editor dan restart komputer.

---

## ✅ Hasil
Komputer akan otomatis login ke akun Microsoft kamu saat dinyalakan.

---

## 🔒 Tips Keamanan
- Jangan gunakan fitur ini jika kamu berbagi komputer dengan orang lain.
- Selalu kunci layar (`Windows + L`) saat meninggalkan perangkat.

---

## 📌 Catatan
Jika menggunakan akun domain atau organisasi, fitur ini bisa dinonaktifkan oleh administrator IT.

