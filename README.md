# Laporan Keuangan Harian  
Aplikasi berbasis web untuk mencatat pemasukan dan pengeluaran harian dengan fitur ekspor laporan ke PDF.  

## Fitur  
 Menambahkan transaksi pemasukan dan pengeluaran  
 Menghapus satu atau semua transaksi  
 Menghitung total pemasukan, pengeluaran, dan saldo akhir secara otomatis  
 Menyimpan laporan keuangan sebagai file PDF  
 
## Teknologi yang Digunakan  
- **HTML5** → Struktur halaman  
- **CSS (Bootstrap 5.3)** → Tampilan yang responsif  
- **JavaScript** → Logika aplikasi  
- **jsPDF** → Menghasilkan laporan dalam format PDF  

## Instalasi dan Penggunaan  
1. **Clone repository ini**  
   ```sh
   git clone https://github.com/username/laporan-keuangan-harian.git
   cd laporan-keuangan-harian
   ```
2. **Buka `index.html` di browser** atau gunakan ekstensi Live Server di VS Code.  

## Struktur Proyek  
```
📂 laporan-keuangan-harian  
 ├── 📄 index.html   # Halaman utama aplikasi  
 ├── 📄 style.css    # Gaya tampilan (Menggunakan Bootstrap CDN)  
 ├── 📄 script.js    # Logika aplikasi  
 ├── 📂 assets       # Folder untuk ikon atau gambar  
 ├── 📄 README.md    # Dokumentasi proyek  
```

## Cara Penggunaan  
1. **Menambahkan Transaksi**  
   - Pilih tanggal transaksi  
   - Isi keterangan transaksi  
   - Pilih tipe transaksi (pemasukan atau pengeluaran)  
   - Masukkan jumlah uang dan klik **Tambah Transaksi**  

2. **Menghapus Data**  
   - **Hapus Baris Terakhir**: Menghapus transaksi terakhir yang ditambahkan  
   - **Hapus Semua Data**: Menghapus seluruh data transaksi  

3. **Menyimpan sebagai PDF**  
   - Klik tombol **Simpan PDF** untuk mengekspor laporan keuangan  

## Fungsi dalam script.js  
- **`tambahTransaksi()`** → Menambahkan transaksi ke dalam tabel dan memperbarui saldo  
- **`updateSaldo()`** → Menghitung total pemasukan, pengeluaran, dan saldo akhir  
- **`hapusSemuaData()`** → Menghapus semua transaksi dalam tabel  
- **`hapusBarisTerakhir()`** → Menghapus transaksi terakhir yang dimasukkan  
- **`simpanPDF()`** → Mengekspor laporan keuangan ke dalam format PDF menggunakan jsPDF  

## Kontribusi  
Jika ingin berkontribusi:  
1. Fork repository ini  
2. Buat branch baru (`feature-nama-fitur`)  
3. Commit perubahan dan buat pull request  
  
## Kontak  
Jika ada pertanyaan atau saran, silakan hubungi:  
✉ Email: kennanh2710gmail.com
