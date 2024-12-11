## 1. MENGINSTALL GIT
[https://git-scm.com/downloads/win](https://git-scm.com/downloads/win)

## 2. MEMBUAT AKUN GITHUB
Buat akun github
[https://github.com/signup](https://github.com/signup)

Jika sudah punya akun silakan Sign In / Log In:
[https://github.com/login](https://github.com/login)

## 3. DOWNLOAD/CLONE
Clone repository dengan membuka folder kosong menggunakan VS Code lalu buka terminal pada VS Code dan ketikkan perintah berikut:
```
git clone https://github.com/bangabudesign/party-invitation.git .
```
Lalu ubah remote url repository sesuai dengan repository github yg sudah Anda buat
```
git remote set-url origin masukkan_repository_url
```
Melakukan konfigurasi
```
git config --global user.name "Nama Anda"
```
```
git config --global user.email "emailanda@email.com"
```

## 3. UPLOAD KE GITHUB
Tutorial untuk upload project ke github
```
git add .
```
```
git commit -m "catatan commit anda"
```
```
git push --set-upstream origin master
```
```
git push
```

## 4. MEMBUAT AKUN VERCEL
Vercel adalah platform cloud yang menyediakan alat, alur kerja, dan infrastruktur untuk membangun dan menyebarkan aplikasi web. Vercel menawarkan berbagai fitur, seperti: CDN global, Domain kustom, HTTPS otomatis, Fitur rendering untuk membuat halaman dinamis, API Vercel untuk membuat halaman dinamis yang disesuaikan.

Buat akun Vercel melalui situs resminya\
[www.vercel.com](https://vercel.com)

## 5. DEPLOY KE VERCEL
1. Kirim kode Anda ke repositori git Anda (GitHub, GitLab, BitBucket).
2. Impor proyek Anda ke Vercel.
3. Vercel akan mendeteksi project Anda dan akan mengaktifkan pengaturan yang benar untuk penerapan Anda.
4. Aplikasi Anda sudah di-deploy! 
