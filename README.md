# Interpretasi SIBI
Penerapan pendeteksian objek menggunakan <a href="https://arxiv.org/abs/1512.02325">Single Shot Multibox Detector</a> dengan _backbone_ <a href="https://arxiv.org/abs/1905.02244">MobileNet V3</a> pada panggilan video berbasis Windows Desktop.

## Deskripsi
Project ini adalah hasil tugas akhir dari Jurusan Informatika, Universitas Jenderal Soedirman tahun 2024. Aplikasi ini dapat mendeteksi 29 kelas (26 abjad dan 3 gestur tambahan), yang dapat dilihat <a href="#kamus-gestur-yang-dapat-digunakan">di sini</a>. Khusus untuk abjad J dan Z, tidak sesuai dengan <a href="https://pmpk.kemdikbud.go.id/sibi/kosakata">referensi kamus SIBI</a> karena kedua gestur tersebut memiliki sifat dinamis. Oleh karena itu, digantikan dengan gestur pengganti. 

<a href="https://pmpk.kemdikbud.go.id/sibi/SIBI/katadasar/J.webm">Gestur J</a> digantikan dengan <a href="https://pmpk.kemdikbud.go.id/sibi/SIBI/angka/01.webm">gestur 3</a>, dan <a href="https://pmpk.kemdikbud.go.id/sibi/SIBI/katadasar/Z.webm">gestur Z</a> digantikan dengan <a href="https://pmpk.kemdikbud.go.id/sibi/SIBI/angka/07.webm">gestur 7</a>, sesuai dengan angka pada SIBI. Selain itu, digunakan juga gestur tambahan yang diambil dari gestur angka. <a href="https://pmpk.kemdikbud.go.id/sibi/SIBI/angka/04.webm">Gestur 4</a> digunakan sebagai "SPASI", <a href="https://pmpk.kemdikbud.go.id/sibi/SIBI/angka/05.webm">gestur 5</a> digunakan sebagai "BERSIHKAN", dan <a href="https://pmpk.kemdikbud.go.id/sibi/SIBI/angka/08.webm">gestur 8</a> digunakan sebagai "HAPUS".

## _Download_ Aplikasi
Aplikasi dapat di-_download_ melalui <a href="https://bit.ly/InterpretasiSIBI">link Google Drive ini</a>.

## Demo Aplikasi
Demo penggunaan aplikasi dapat dilihat pada <a href="https://youtu.be/rg8tsOqkxQQ"> video ini</a>.

## _Compatibility_
Sudah diuji dan dapat digunakan pada OS Windows 10 dan 11.

## _Prerequisites_
Aplikasi ini memerlukan <a href="https://obsproject.com/">OBS Studio</a> untuk berjalan dengan lancar karena memanfaatkan virtual camera dari OBS untuk menampilkan hasil interpretasi bahasa isyarat SIBI.

## Petunjuk Penggunaan Aplikasi
1. Jalankan "Interpretasi SIBI.exe" (bila terjadi error, dapat mengunjungi <a href="#frequently-asked-questions-faq">FAQ</a>)
2. Pilih _webcam_ yang ingin digunakan
3. Tekan tombol "Start" untuk memulai kamera virtual
4. Buka _platform_ panggilan video yang diinginkan (e.g. Zoom, Google Meet, dll.)
5. Ubah kamera menjadi "OBS Virtual Camera"
6. Selamat menggunakan!

### Catatan
> Tekan tombol "Stop" untuk menghentikan kamera virtual.

> Tekan tombol "Refresh" untuk mengganti kamera saat kamera virtual sudah berjalan.

> Ketika program di-_close_, kamera virtual otomatis berhenti.

## Kamus Gestur Yang Dapat Digunakan
Di bawah terdapat tabel berisi kelas dan gestur yang terdaftar pada aplikasi interpretasi SIBI ini.

| Kelas  | Gestur |
| ------------- | ------------- |
| A  | <img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/A.jpg" alt="Gestur A" height="200" width="200">  |
| B  | <img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/B.jpg" alt="Gestur B" height="200" width="200">  |
| C  | <img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/C.jpg" alt="Gestur C" height="200" width="200">  |
| D  | <img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/D.jpg" alt="Gestur D" height="200" width="200">  |
| E  | <img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/E.jpg" alt="Gestur E" height="200" width="200">  |
| F  | <img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/F.jpg" alt="Gestur F" height="200" width="200">  |
| G  | <img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/G.jpg" alt="Gestur G" height="200" width="200">  |
| H  | <img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/H.jpg" alt="Gestur H" height="200" width="200">  |
| I  | <img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/I.jpg" alt="Gestur I" height="200" width="200">  |
| J  | <img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/J.jpg" alt="Gestur J" height="200" width="200">  |
| K  | <img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/K.jpg" alt="Gestur K" height="200" width="200">  |
| L  | <img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/L.jpg" alt="Gestur L" height="200" width="200">  |
| M  | <img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/M.jpg" alt="Gestur M" height="200" width="200">  |
| N  | <img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/N.jpg" alt="Gestur N" height="200" width="200">  |
| O  | <img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/O.jpg" alt="Gestur O" height="200" width="200">  |
| P  | <img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/P.jpg" alt="Gestur P" height="200" width="200">  |
| Q  | <img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/Q.jpg" alt="Gestur Q" height="200" width="200">  |
| R  | <img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/R.jpg" alt="Gestur R" height="200" width="200">  |
| S  | <img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/S.jpg" alt="Gestur S" height="200" width="200">  |
| T  | <img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/T.jpg" alt="Gestur T" height="200" width="200">  |
| U  | <img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/U.jpg" alt="Gestur U" height="200" width="200">  |
| V  | <img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/V.jpg" alt="Gestur V" height="200" width="200">  |
| W  | <img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/W.jpg" alt="Gestur W" height="200" width="200">  |
| X  | <img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/X.jpg" alt="Gestur X" height="200" width="200">  |
| Y  | <img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/Y.jpg" alt="Gestur Y" height="200" width="200">  |
| Z  | <img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/Z.jpg" alt="Gestur Z" height="200" width="200">  |
| SPASI  | <img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/SPASI.jpg" alt="Gestur SPASI" height="200" width="200">  |
| HAPUS  | <img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/HAPUS.jpg" alt="Gestur HAPUS" height="200" width="200">  |
| BERSIHKAN  | <img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/BERSIHKAN.jpg" alt="Gestur BERSIHKAN" height="200" width="200">  |

## Frequently Asked Questions (FAQ)
### 1. Aplikasi terdeteksi sebagai virus, bagaimana cara menjalankannya?
<img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/error2.jpg" alt="Virus Detection" height="200">
Aplikasi Interpretasi SIBI dapat salah terdeteksi sebagai virus oleh antivirus yang digunakan pada komputer. Untuk menjalankannya, atur pada software antivirus untuk memperbolehkan aplikasi untuk tetap diperbolehkan pada komputer. Contohnya seperti gambar berikut, pada notifikasi rav antivirus dapat menekan tombol "Remain Exposed."
<img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/error1.jpg" alt="Virus Detection" height="200">

### 2. Terjadi error "Unhandled exception in script" ketika memulai aplikasi. Bagaimana cara mengatasinya?
<img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/error3.jpg" alt="Virus Detection" height="200">
Error ini terjadi ketika <a href="https://obsproject.com/">OBS Studio</a> belum terinstal, silakan instal terlebih dahulu.

### 3. Muncul _warning_ "Windows protected your PC" ketika memulai aplikasi. Bagaimana cara mengatasinya?
<img src="https://raw.githubusercontent.com/muflihabdurrafi/interpretasi-sibi/main/images/error4.jpg" alt="Virus Detection" height="200">
Mirip seperti <a href="#1-aplikasi-terdeteksi-sebagai-virus-bagaimana-cara-menjalankannya">FAQ 1</a>, aplikasi terdeteksi berbahaya. Namun dapat tetap dijalankan dengan menekan tombol "More info" dan tekan "Run anyway."

# Terima kasih, semoga bermanfaat 🙏
