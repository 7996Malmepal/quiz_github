# Git Knowledge Challenge

## Tujuan

Latihan ini mengenalkan alur kerja GitHub secara berkelompok, mulai dari menyalin repository hingga mengambil hasil akhir yang sudah digabungkan.

## Pembagian kelompok

| Kelompok | Tugas |
|---|---|
| Kelompok 1 | Menjawab soal nomor 1–3 |
| Kelompok 2 | Menjawab soal nomor 4–6 |
| Kelompok 3 | Menjawab soal nomor 7–9 |

## Langkah pengerjaan

1. **Clone repository** ke komputer masing-masing kelompok.
2. Buka file Excel yang tersedia di repository.
3. Isi jawaban hanya pada soal yang menjadi bagian kelompok.
4. Simpan perubahan pada file Excel.
5. Buat commit dengan pesan yang menjelaskan perubahan, misalnya:
   ```text
   Kelompok 1 mengisi jawaban soal 1-3
   ```
6. Ajukan **pull request** ke branch utama repository.
7. Setelah semua pull request diperiksa dan digabungkan, setiap peserta mengambil versi terbaru dengan perintah `git pull`.
8. Buka kembali file Excel dan pastikan seluruh jawaban kelompok sudah tergabung.

## Perintah Git

Jalankan perintah berikut dari folder repository. Ganti pesan commit sesuai nomor kelompok dan soal yang dikerjakan.

```bash
git add .
git commit -m "Kelompok 1 mengisi jawaban soal 1-3"
git push
```

Setelah `git push`, ajukan pull request melalui GitHub.

Untuk mengambil hasil akhir setelah semua perubahan digabungkan:

```bash
git pull
```

## Aturan

- Setiap kelompok hanya mengisi bagian soal yang ditugaskan.
- Jangan menghapus atau mengubah jawaban kelompok lain.
- Pastikan file sudah disimpan sebelum membuat commit.
- Semua peserta melakukan `git pull` setelah fasilitator menggabungkan seluruh pull request.
