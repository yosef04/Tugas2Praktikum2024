# Tugas Pertemuan 2

Fork dan clone repository ini, lalu jalankan perintah 
```
flutter pub get
```
Buatlah tampilan form yang berisi nama, nim, dan tahun lahir pada file `ui/form_data.dart`, lalu buatlah tampilan hasil dari input data tersebut pada file `ui/tampil_data.dart`

JELASKAN PROSES PASSING DATA DARI FORM MENUJU TAMPILAN DENGAN FILE `README.md`

Buat tampilan semenarik mungkin untuk dilihat.


Nama : YOSEF PARLINDUNGAN SIBARANI

NIM : H1D021026

Shift Baru: B

PENJELASAN PROSES PASSING DATA DARI FORM MENUJU TAMPILAN
1. MENGELOLA DATA DAN MEMPROSES LOGIKA DI BAGIAN form_data.dart(CONTROLLER). SETELAH ITU AKAN MEMICU NOTIFIKASI AGAR UI DIPERBARUI.
2. SETELAH form_data.dart(CONTROLLER) MENGIMPLEMENTASIKAN LOGIKA PERUBAHAN DATA DAN MEMASTIKAN SETIAP KALI DATA BERUBAH, tampil_data.dart(VIEW) DIBERITAHU DAN MEMPERBARUI SECARA OTOMATIS.
3. KETIKA DATA DIPERBAHARUI, VIEW AKAN DIRENDER ULANG SECARA OTOMATIS DENGAN DATA TERBARU.

## Screenshot
Contoh :
![Lampiran Form](form.png)
![Lampiran Hasil](hasil.png)
