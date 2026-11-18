
# Tugas Docker Minggu 9

## Identitas
- Nama: Muudmainah
- NIM: 202557201063
- Program Studi: Sistem Informasi
- Universitas: Universitas Musamus

## Deskripsi
Proyek ini merupakan tugas kontainerisasi halaman profil menggunakan Docker dan Nginx.

## File Proyek
- Dockerfile
- index.html
- README.md

## Cara Build Image
```bash
docker build -t profil-muudmainah:1.0 .
```

## Cara Menjalankan Container
```bash
docker run -d --name profil-muudmainah -p 8082:80 profil-muudmainah:1.0
```

## Membuka Halaman
Buka browser dan akses:
http://localhost:8082

## Menghentikan Container
```bash
docker stop profil-muudmainah
docker rm profil-muudmainah
```
