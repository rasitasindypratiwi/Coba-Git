Rasita Sindy Pratiwi
24/533797/PA/22615

# 📝 Laporan Tugas 1 - Praktikum Metkom
Acara 3: Pengenalan GitHub

---
## Langkah-langkah membuat file markdown di new repository
## 1. Membuat Repository di GitHub
- Buka GitHub, klik tanda **plus (+)** di kanan atas → pilih **New Repository**.  
- Isi nama repository: **Coba-Git**.  
- Tambahkan deskripsi: *Praktikum Metkom*.  
- Klik tombol **Create Repository**.  
- Repository berhasil dibuat di GitHub.  

## 2. Clone Repository ke Lokal & Setup Git
- Setelah repository berhasil dibuat, dibuka **Anaconda Prompt**.  
- Cek lokasi folder dengan perintah `dir`, lalu pindah ke folder `miniconda3` menggunakan `cd miniconda3`.  
- Lakukan *clone* repository dengan perintah `git clone` menggunakan URL repository GitHub.  
- Setelah proses clone selesai, masuk ke folder `Coba-Git` dengan perintah `cd Coba-Git`.  
- Lakukan konfigurasi Git dengan mengatur email dan username (hanya perlu sekali di awal).  
- Terakhir, jalankan perintah `git init` untuk memastikan folder sudah dikenali sebagai repository Git.  

## 3. Membuat & Mengedit File Markdown
- Buka **VSCode**, lalu pilih **Open Folder** → arahkan ke folder `Coba-Git`.  
- Edit file `README.md`, isi dengan profil singkat (Nama, NIM, dsb).  
- Tambahkan file baru bernama `tugas1.md` untuk laporan ini.  
- Simpan semua perubahan.  

## 4. Push Perubahan ke GitHub
- Kembali ke **Anaconda Prompt**, lalu jalankan `git add .` untuk menambahkan semua perubahan.  
- Gunakan `git commit -m "Menambahkan README dan tugas1.md"` untuk menyimpan perubahan.  
- Jalankan `git push` untuk mengirim perubahan ke GitHub.  
- Setelah itu buka GitHub dan lakukan refresh.  
- File `README.md` dan `tugas1.md` sudah muncul di repository.  

---
## Catatan
- Sudah dipelajari: cara membuat repository, clone, edit markdown, commit, dan push ke GitHub.  
- Kebingungan:
  - Kadang muncul error/fatal setelah masuk folder `Coba-Git` di Anaconda Prompt.
  - Sering lupa urutan langkah (misalnya harus `git add` dulu sebelum `git commit`, atau `git commit` sebelum `git push`).  

## Fitur 