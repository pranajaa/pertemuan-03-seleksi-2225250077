# Pertemuan 03 Seleksi Python

Nama: Hitana Rifa Pranaja

NIM: 222525077

Kelas: 3A

## Tujuan

Menulis program seleksi if, if-else, kondisi majemuk, dan nested if.

## Cara Menjalankan
### Latihan
python3 latihan/01_ganjil_genap.py

python3 latihan/02_bandingkan_dua_bilangan.py

python3 latihan/03_kelulusan_bersyarat.py

python3 latihan/04_jenis_segitiga.py

### Tugas
python3 tugas/analisis_persamaan_kuadrat.py

## Algoritma Tugas

1. Memasukkan nilai koefisien a, b, dan c.
2. Memeriksa apakah nilai a sama dengan 0.
3. Jika a = 0, tampilkan bahwa input bukan persamaan kuadrat.
4. Jika a ≠ 0, hitung nilai diskriminan dengan rumus:
   D = b² - 4ac.
5. Jika D > 0, hitung dan tampilkan dua akar real yang berbeda.
6. Jika D = 0, hitung dan tampilkan satu akar real kembar.
7. Jika D < 0, tampilkan bahwa tidak terdapat akar real.
8. Tampilkan nilai numerik dengan dua angka di belakang koma.

## Hasil Pengujian

| No | Input (a, b, c) | D | Hasil yang Diharapkan | Keluaran Aktual | Status |
|---|---|---:|---|---|---|
| 1 | (1, -5, 6) | 1 | Dua akar real: 3 dan 2 | Dua akar real: 3.00 dan 2.00 | Berhasil |
| 2 | (1, 2, 1) | 0 | Akar kembar: -1 | Akar kembar: -1.00 | Berhasil |
| 3 | (1, 0, 1) | -4 | Tidak ada akar real | Tidak ada akar real | Berhasil |
| 4 | (0, 2, 3) | - | Bukan persamaan kuadrat | Bukan persamaan kuadrat | Berhasil |

## Refleksi

Kesalahan logika yang ditemukan adalah perhitungan akar
dilakukan sebelum memeriksa nilai diskriminan. Hal tersebut
dapat menyebabkan kesalahan ketika D bernilai negatif karena
akar dari bilangan negatif tidak termasuk akar real.

## Sumber dan Alat bantu
- Menulis program seleksi if, if-else, kondisi majemuk, dan nested if.
- ChatGPT ai
Perbaikannya adalah memeriksa kondisi diskriminan terlebih
dahulu menggunakan nested if. Perhitungan akar hanya dilakukan
jika D > 0 atau D = 0.
