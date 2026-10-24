# Bahasa Kita Menjadi Bahasa Mesin - Tugas Individu

Aplikasi model CyberChef mini, karya mandiri:
tulis bahasa kita, susun operasi (recipe), baca hasil bahasa mesinnya.
Dibuat oleh Ahmad Muqarrobin (Robin), NIM 242502040003, Kelas 3TI01.

## Isi folder
- `index.html` - versi web (buka di browser, atau lewat GitHub Pages)
- `bahasa_mesin.py` - versi Python (aplikasi desktop Tkinter, tanpa library luar)
- `bahasa_mesin.pyc` - bahasa_mesin.py yang sudah di-compile (bytecode),
  bisa dijalankan dengan: `python bahasa_mesin.pyc`
- `build_exe.bat` - pembuat file .exe di Windows (lihat bawah)

## Operasi yang tersedia
Bahasa kita jadi bahasa mesin: Ke Biner, Ke Desimal ASCII, Ke Heksadesimal,
Ke Oktal, Ke Base64. Sebaliknya: Dari Biner, Dari Desimal ASCII,
Dari Heksadesimal, Dari Base64. Olah teks: Balik Teks, Huruf Besar, Huruf Kecil.
Operasi bisa dirangkai berurutan, misalnya teks -> Ke Biner -> Dari Biner
kembali jadi teks. Tabel ASCII menampilkan tiap huruf beserta nomor desimal,
biner 8 bit, dan heksanya.

## Cara menjalankan versi Python
```
python bahasa_mesin.py
```

## Cara membuat file .exe (Windows)
1. Pastikan Python 3 terpasang (centang "Add Python to PATH" saat install).
2. Klik dua kali `build_exe.bat`.
3. Hasilnya: `dist\BahasaMesin.exe` - file ini yang bisa dikumpulkan
   sebagai "file Python yang sudah di-compile" beserta `bahasa_mesin.py`.

## Cara publish versi web ke GitHub Pages
1. Buat repository baru di GitHub, nama: `bahasa-mesin`
2. Upload `index.html` ke repository itu
3. Settings - Pages - Source "Deploy from a branch", Branch `main`, folder `/ (root)`, Save
4. Tunggu 1-2 menit, webnya online di: `https://<username-github>.github.io/bahasa-mesin/`

## Catatan UTS
Soal UTS nanti bentuknya sama, hanya judulnya ditentukan Ibu Aliyah.
Judul aplikasi ini cukup diganti satu baris saja:
di `index.html` (komentar JUDUL_APLIKASI di atas) dan di `bahasa_mesin.py`
(baris JUDUL_APLIKASI), tidak perlu mengubah logika apa pun.
