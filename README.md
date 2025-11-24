# PROJECT[2].LATIHAN-2
# LANGKAH[1] Buat folder baru
berikut cara membuat folder baru
Definisi gambar

```
mkdir projectSO_2
```
```
mkdir source_files backup logs
```

# Membuat file menggunakan metode perulangan(Loop)
Berikut cara membuat file menggunakan metode perulangan
Definisi gambar

```
for i in {1..2) do echo " Laporan minggu ke-$i " > laporan$i.txt;done
```
```
for i in {1..2} do echo " catatan evaluasi bulan ke
-$i " > file$i.pdf; done
```
*`Penjelasan`.
* `mkdir` → membuat folder baru.
* `cd` → masuk ke folder.
* `cd ..` → keluar ke folder
* `for` → perintah looping/perulangn
* `echo` → menampilkan teks/variabel
  
# LANGKAH[2] Membuat script
# Buat script backup.sh di dalam direktori project
```
nano backup.sh
```
# ISI SCRIPT
```
```
# Komptesi file menggunakan tar dan gzip
Definisi gambar


# Pemindahan file backup ke direktori khusus dengan timestamp
Definisi gambar


# log file yang mencatat setiap aktifitas backup
Definisi gambar

# Notifikasi sederhana jika backup berhasil atau gagal
Definisi gambar


# Beri hak eksekusi
```
chmod +x backup.sh
```
# Eksekusi script yang telah di buat
```
./backup.sh
```











