# 📖 Panduan Penggunaan Lengkap - v2.0.0 Premium

## 🎯 Jadual Kandungan

1. [Memulai](#memulai)
2. [Kad Mencatat Waktu](#kad-mencatat-waktu)
3. [Log Perjalanan Kenderaan](#log-perjalanan-kenderaan)
4. [Muatan Naik Fail](#muatan-naik-fail)
5. [Laporan & Data](#laporan--data)
6. [Tetapan](#tetapan)
7. [Tips & Trik](#tips--trik)

---

## 🚀 Memulai

### Persyaratan Sistem Minimum
- Browser web terkini (Chrome, Firefox, Safari, Edge)
- RAM: 2 GB
- Storage: 100 MB (untuk penyimpanan data)
- Sambungan Internet: Tidak diperlukan (bekerja offline)

### Instalasi
1. Muat turun atau klon repositori
2. Ekstrak fail `index.html`
3. Buka dengan browser yang disokong
4. Mulai gunakan!

### Penetapan Awal
1. Klik tab **Tetapan** di sebelah kanan
2. Isi borang profil:
   - Nama Pengguna
   - Jabatan/Cawangan
   - Bahagian/Seksyen
   - Emel Hubungan
3. Klik **Simpan Tetapan**
4. Data akan disimpan secara otomatis

### Menukar Bahasa
- Klik butang **EN / MS** di penjuru kanan bawah
- Antara muka akan berubah serta-merta
- Pilihan disimpan untuk sesi seterusnya

---

## 📋 Kad Mencatat Waktu

### Langkah Demi Langkah

#### Muka A (Hari 1-15)

**Langkah 1: Isi Maklumat Peribadi**
```
Nama: Ahmad bin Ali
Cawangan/Jabatan: Cawangan Kuala Lumpur
Bahagian/Seksyen: Operasi
Bulan: Mei 2026
```

**Langkah 2: Jana Jadual**
- Klik butang **Jana Jadual (Muka A)**
- Sistem akan menjana 15 baris untuk hari 1-15
- Setiap baris boleh diedit

**Langkah 3: Isi Waktu**
Untuk setiap hari, isi:
- **Masuk 1**: Waktu tiba pagi (cth: 08:00)
- **Keluar 1**: Waktu keluar untuk rehat (cth: 12:00)
- **Masuk 2**: Waktu masuk selepas rehat (cth: 13:00)
- **Keluar 2**: Waktu keluar akhir (cth: 17:00)
- **Kenyataan**: Catatan (cth: Normal, Cuti, MC)

**Langkah 4: Semakan OT**
Sistem auto-deteksi:
- ⚠️ **Merah**: Masuk selepas 09:00 (Lewat)
- 🟡 **Emas**: Sebelum 07:00 atau selepas 18:00 (OT)
- ✅ **Hijau**: Normal (07:30-16:30)

#### Muka B (Hari 16-31)
Ulangi proses yang sama untuk hari 16-31

### Aksi Pada Kad Mencatat Waktu

**Cetak (Print)**
```
1. Klik butang "Cetak (Muka A)" atau "Cetak (Muka B)"
2. Preview akan muncul
3. Pilih printer
4. Klik "Cetak"
```

**Eksport CSV**
```
1. Klik butang "Eksport CSV"
2. Fail akan dimuat turun sebagai CSV
3. Boleh dibuka dengan Excel atau aplikasi spreadsheet lain
```

### Petua Penggunaan
- Gunakan format 24-jam (08:00, 17:30, etc.)
- Simpan secara teratur (auto-save setiap 10 saat)
- Semak OT sebelum cetak
- Catatan penting di kolum "Kenyataan"

---

## 🚗 Log Perjalanan Kenderaan

### Maklumat Kenderaan

**Isi Sekali untuk Setiap Bulan:**
```
Bulan Rekod: Mei 2026
No. Pendaftaran: WLU 123 (Plat Nombor)
Model Kereta: Perodua Myvi 1.3
Odo Permulaan: 50,000 KM
Bahagian/Unit: Operasi
```

### Tambah Rekod Perjalanan

**Langkah 1: Isi Maklumat Asas**
```
Tarikh: 01-05-2026
Masa Pergi: 08:30
Masa Balik: 10:15
```

**Langkah 2: Maklumat Perjalanan**
```
Pemandu: Ahmad bin Ali
Tujuan & Lokasi Penuh: Ziarah ke Bandar Baru, KL Sentral
Pelulus: Encik Ibrahim (Manager)
Pengguna: Siti Fatimah (Pemohon)
```

**Langkah 3: Odometer & Jarak**
```
Odo Awal: 50,000 KM
Odo Akhir: 50,050 KM
Jarak: 50 KM (AUTO-KIRA)
```

**Langkah 4: Kos & Resit**
```
Kos & Resit: 50.00 RM
No. Resit: RCP-2026-001
Liter Bahan Api: 5.0 Liter
```

**Langkah 5: Nota**
```
Nota: Perjalanan biasa. Tidak ada gangguan.
```

### Pengiraan Otomatis

Sistem akan auto-kira:
- **Jarak**: Odo Akhir - Odo Awal
- **Jumlah Jarak**: Semua jarak dalam jadual
- **Jumlah Bahan Api**: Semua liter dalam jadual
- **Jumlah Kos**: Semua kos dalam jadual
- **Jumlah Akhir**: Jumlah keseluruhan untuk bulan

### Ringkasan Ringkas

Di bawah jadual, akan muncul:
```
📊 Ringkasan Perjalanan
- Jumlah Jarak: 500 KM
- Jumlah Bahan Api: 50.0 Liter
- Jumlah Keseluruhan Kos: RM 500.00
- Jumlah Akhir (RM): RM 500.00
```

### Export Log Perjalanan

**Export ke CSV**
```
1. Klik "Eksport CSV"
2. Fail akan dimuat turun
3. Boleh dibuka dalam Excel
```

**Export ke Excel (Akan Datang)**
```
- Fitur akan tersedia dalam v2.1.0
- Sokongan format .xlsx penuh
```

**Export ke Access DB (Akan Datang)**
```
- Fitur akan tersedia dalam v2.1.0
- Sokongan format .mdb penuh
```

---

## 📤 Muatan Naik Fail

### Jenis Fail yang Disokong

#### 1. Resit Minyak (Fuel Receipt)
- Format: JPG, PNG, PDF
- Maksimum Saiz: 5 MB per fail
- Penerangan: Resit dari stesen minyak

#### 2. Resit TNG/Tol (Toll Receipt)
- Format: JPG, PNG, PDF
- Maksimum Saiz: 5 MB per fail
- Penerangan: Resit pembayaran tol

#### 3. Gambar Odometer (Odometer Images)
- Format: JPG, PNG
- Maksimum Saiz: 5 MB per fail
- Penerangan: Foto bacaan odometer

### Proses Muatan Naik

**Kaedah 1: Drag & Drop**
```
1. Buka seksyen "Muatan Naik"
2. Seret dan lepaskan fail ke kawasan
3. Sistem akan memproses fail
4. Akan muncul pesan berjaya
```

**Kaedah 2: Klik Untuk Pilih**
```
1. Klik di kawasan muatan naik
2. Dialog pemilihan fail akan muncul
3. Pilih fail yang dikehendaki
4. Klik "Buka"
5. Sistem akan memproses
```

### Lihat Fail Muatan Naik

- Semua fail akan dipaparkan dalam gallery
- Klik fail untuk lihat preview
- Klik tombol "X" untuk hapus fail
- Semua fail disimpan secara lokal dalam browser

---

## 📊 Laporan & Data

### Seksyen Laporan

**1. Data Kad Mencatat Waktu**
- Papar semua rekod kad mencatat waktu
- Jadual ringkas dengan nama, jabatan, bulan
- Butang aksi untuk cetak atau lihat detail

**2. Data Log Perjalanan**
- Papar semua rekod log perjalanan
- Jadual ringkas dengan tarikh, no. pendaftaran, tujuan, jarak, kos
- Butang aksi untuk lihat detail atau cetak

**3. Data Muatan Naik**
- Papar statistik file yang dimuat naik
- Jumlah fail per kategori
- Tarikh muatan terakhir

### Fungsi Laporan

- **Print**: Cetak laporan untuk kertas
- **View**: Lihat detail lengkap
- **Download**: Muat turun sebagai CSV/Excel

---

## ⚙️ Tetapan

### Tetapan Profil

**Isi Maklumat Profil:**
```
Nama Pengguna: Ahmad bin Ali
Jabatan/Cawangan: Cawangan KL
Bahagian/Seksyen: Operasi
Emel: ahmad.ali@gov.my
```

**Simpan Tetapan:**
- Klik "Simpan Tetapan"
- Data akan disimpan secara lokal
- Widget profil akan menunjukkan data terbaru

### Tetapan Sistem

**Maklumat Sistem:**
- Versi: v2.0.0 Premium
- Tarikh Rilis: 1 Mei 2026
- Bahasa: Bahasa Melayu & Inggeris Amerika
- Kompatibiliti: Windows, macOS, Linux, iOS, Android

### Bersihkan Data

**⚠️ AMARAN: Aksi ini tidak boleh dibuat asal!**

```
1. Klik "Kosongkan Semua Data"
2. Dialog pengesahan akan muncul
3. Klik "OK" untuk sahkan
4. Semua data akan dihapus
5. Halaman akan dimuat semula
```

---

## 💡 Tips & Trik

### Penjimatan Data
1. **Backup Manual**
   - Eksport semua data sebagai CSV
   - Simpan di folder yang selamat
   - Buat salinan setiap bulan

2. **Export Berkala**
   - Export data setiap akhir bulan
   - Simpan di cloud storage (OneDrive, Google Drive)
   - Gunakan untuk backup

### Cetak Berkualiti Tinggi
1. Gunakan browser Chrome atau Firefox
2. Tetapkan margin minimal (0.5 inci)
3. Aktifkan "Print Background Graphics"
4. Pilih kertas A4
5. Tetapkan skala 100%

### Ketik Cepat
1. Tab key untuk pindah antara field
2. Shift+Tab untuk ke belakang
3. Enter untuk simpan/hantar
4. Escape untuk batal

### Autohide Profile
- Widget profil akan tersembunyi selepas 10 saat inaktiviti
- Klik untuk menunjukkan semula
- Gerak mouse untuk "bangunkan"

### Jam Realtime
- Jam digital update setiap saat
- Format 12 jam AM/PM (Bahasa Melayu)
- Tarikh hari seminggu dalam Bahasa Melayu

---

## 🔍 Semakan Sebelum Cetak

**Senarai Semakan Kad Mencatat Waktu:**
- ☐ Nama lengkap
- ☐ Cawangan/Jabatan betul
- ☐ Bulan dan tahun betul
- ☐ Semua waktu diisi
- ☐ Tiada kesilapan OT
- ☐ Kenyataan jelas

**Senarai Semakan Log Perjalanan:**
- ☐ No. pendaftaran benar
- ☐ Model kereta benar
- ☐ Odo awal betul
- ☐ Semua rekod lengkap
- ☐ Jarak auto-kira betul
- ☐ Kos semua terisi
- ☐ No. resit lengkap

---

## 🆘 Penyelesaian Masalah Umum

### Data Hilang Selepas Tutup Browser
**Masalah**: Data tidak disimpan
**Solusi**: 
- Aktifkan LocalStorage (Chrome: Settings → Cookies)
- Refresh halaman
- Export data secara berkala

### Gambar Muatan Naik Tidak Muncul
**Masalah**: Gambar tidak dipaparkan
**Solusi**:
- Semula browser (Ctrl+Shift+Del)
- Kosongkan cache
- Klik F5 untuk refresh

### Export CSV Tidak Berfungsi
**Masalah**: CSV tidak muat turun
**Solusi**:
- Gunakan browser terbaru
- Periksa popup blocker
- Cubalagi selepas beberapa saat

### Antara Muka Tidak Responsif
**Masalah**: Halaman tidak berubah saiz
**Solusi**:
- Tekan Ctrl+Shift+I (Buka DevTools)
- Tekan Ctrl+Shift+M (Responsive Mode)
- Tutup DevTools

---

## 📞 Hubungi Kami

**Untuk Soalan atau Masalah:**
- Email: support@example.gov.my
- GitHub Issues: [ttv4u1/srr](https://github.com/ttv4u1/srr)
- Waktu Operasi: Isnin - Jumaat, 08:00 - 17:00

---

**Semoga panduan ini membantu! Terima kasih! 🇲🇾**
