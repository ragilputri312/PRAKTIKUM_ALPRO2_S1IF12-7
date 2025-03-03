# Repositori Pengumpulan Tugas Praktikum Algoritma Pemrograman 2 Kelas S1IF-12-07

## Note
- **Ganti branch dari `main` ke `NIM` masing-masing** jika ingin melihat tugasnya.
- **Link Video Cara Upload Tugas ke Repositori ini:** [Klik di sini]()

---

## 📌 Requirements:
1. **Buat akun GitHub** → [GitHub](https://github.com/)
2. **Download dan install Git** → [Git SCM](https://git-scm.com/)

---

## 📜 Alur Pengumpulan Tugas

### 1️⃣ Fork Repositori
Klik tombol **Fork** di pojok kanan atas repositori ini.

### 2️⃣ Clone Repositori Hasil Fork
```
git clone https://github.com/UsernameGithub/PRAKTIKUM_ALPRO2_S1IF12-7.git
```

### 3️⃣ Buat dan Pindah ke Branch Sesuai NIM
```bash
cd PRAKTIKUM_ALPRO2_S1IF12-7
git branch NIM_ANDA
git checkout NIM_ANDA
```

### 4️⃣ Buat Folder Sesuai NIM dan Masuk ke Dalamnya
```bash
mkdir NIM_ANDA
cd NIM_ANDA
```

### 5️⃣ Buat Folder untuk Setiap Praktikum
```bash
mkdir "Praktikum-n"
cd "Praktikum-n"
```
**(n = Nomor praktikum)**

### 6️⃣ Tambahkan File dan Commit Perubahan
```bash
git add .  # Menambahkan semua file
git commit -m "Menambahkan tugas praktikum n"
```

### 7️⃣ Push Perubahan ke GitHub
```bash
git push origin NIM_ANDA
```

**Jika pertama kali push, akan diminta login GitHub dengan:**
- **Username** → Gunakan username GitHub
- **Password** → Gunakan **personal access token** (bukan password biasa!)

---

## 🎟️ Cara Membuat Personal Access Token
1. Klik **profile** di pojok kanan atas GitHub.
2. Pilih **Settings** → Scroll ke bawah → Klik **Developer Settings**.
3. Pilih **Personal Access Tokens**.
4. Klik **Generate New Token**.
5. Beri nama token sesuai keinginan.
6. Pilih waktu **Expiration** (sesuai keinginan).
7. Pada **Select Scope**, centang **repo**.
8. Klik **Generate Token**.
9. **Salin token** dan simpan dengan baik (hanya bisa dilihat sekali!).

---

## 🏷️ Membuat Pull Request
1. Masuk ke GitHub dan buka repositori hasil fork.
2. Pastikan semua tugas telah di-push.
3. Pilih menu **Pull Request**.
4. Klik **New Pull Request**.
5. Pilih **base repository** → `main`, dan **compare branch** → `NIM_ANDA`.
6. Klik **Create Pull Request**.

---

## ⚠️ Hal-Hal yang Harus Diperhatikan
✔️ Setiap orang memiliki folder **sesuai NIM**.  
✔️ **Satu praktikum, satu folder**.  
✔️ **Program berjalan dengan baik** dan sesuai ketentuan tugas.  

---

Selamat mengerjakan dan semangat belajar! 🚀

