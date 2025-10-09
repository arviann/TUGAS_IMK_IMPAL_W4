# 📋 Laporan Audit

## 🧠 INFORMASI UMUM
**Nama Proyek:** Website Pengajuan Cuti  
**Platform Desain:** Figma  
**Tanggal Audit:** 9 Oktober 2025  
**Auditor:** Arkanzi Suharjanto  
**Repository:** TUGAS_IMK_IMPAL_W4  

---

## 👥 INFORMASI KELOMPOK
**Nama Kelompok:** *Damiungkee*  
**CM:** Muhammad Rafif Taufiq Ramadhan  
**Auditor:** Arkanzi Suharjanto  
**Designer:** Nabila Putri Aulia & Jeany Ferliza Nayla  
**Customer/Client:** Arfian Ghifari Mahya  

---

## 🎯 Tujuan Audit
Audit ini dilakukan untuk menilai **kualitas tampilan, kesesuaian fungsi, dan kelengkapan elemen form** pada halaman *Form Pengajuan Cuti* dan *Halaman Utama (Dashboard/Menu)*.  
Audit juga mencakup **konsistensi desain**, **feedback sistem**, dan **tampilan status cuti** agar pengalaman pengguna lebih intuitif.

---

## 🔍 Objek Audit

| No | Halaman             | Komponen yang Diperiksa | Fokus Pemeriksaan                                    |
| -- | ------------------- | ----------------------- | ---------------------------------------------------- |
| 1  | Form Pengajuan Cuti | Form Input Data         | Kelengkapan field, keterbacaan label, validasi input |
| 2  | Form Pengajuan Cuti | Tombol “Ajukan”         | Fungsi submit, posisi tombol, dan respons            |
| 3  | Dashboard / Menu    | Navigasi Menu           | Kemudahan akses ke halaman pengajuan dan approval    |
| 4  | Header              | Identitas Pengguna      | Informasi akun dan ID tampil jelas                   |
| 5  | Desain UI           | Layout & Warna          | Kesesuaian warna dengan tema dan kontras             |

---

## 📊 Hasil Audit

| No | Komponen                 | Deskripsi                                                                     | Temuan / Analisis                                                                                                                                                                                | Rekomendasi                                                                                          | Status                    |
| -- | ------------------------ | ----------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------- | ------------------------- |
| 1  | **Form Pengajuan Cuti**  | Halaman untuk pengisian data cuti pegawai.                                    | Tampilan form rapi dan terstruktur. Label dan urutan input sudah logis. Namun belum terlihat validasi input (contoh: tanggal mulai tidak boleh > tanggal selesai).                               | Tambahkan validasi otomatis dan notifikasi sukses setelah klik “Ajukan”.                             | Perlu penyempurnaan minor |
| 2  | **Status Cuti**          | Menampilkan daftar pengajuan dengan status Approved, Rejected, dan Requested. | Warna status sudah jelas (hijau, merah, kuning). Layout bersih dan profesional. Namun urutan status masih acak dan tombol “Rejected/Approved” di kartu Requested belum jelas apakah bisa diklik. | Urutkan status dari Requested → Approved → Rejected. Beri efek hover/tooltip jika tombol interaktif. | Sudah layak               |
| 3  | **Approval Cuti**        | Halaman bagi atasan/HR untuk menyetujui atau menolak cuti.                    | Status sudah jelas, tombol aksi “Setujui” dan “Tolak” mudah diakses. Namun layout tabel agak padat.                                                                                              | Tambahkan jarak antar elemen untuk keterbacaan lebih baik.                                           | Sudah layak               |
| 4  | **Rekap Pengajuan Cuti** | Menampilkan rekap data cuti dan sisa cuti pegawai.                            | Informasi utama tampil lengkap (nama, ID, tanggal, status, sisa cuti). Penggunaan badge status sudah baik.                                                                                       | Saran tambahan: tambahkan filter rekap per bulan/tahun dan ekspor data (PDF/Excel).                  | Sudah sesuai              |
| 5  | **Konsistensi Desain**   | Konsistensi warna, font, dan layout antarhalaman.                             | Warna merah sebagai identitas utama sudah konsisten. Layout antarhalaman seragam.                                                                                                                | Pertahankan skema warna dan tipografi agar branding kuat.                                            | Sesuai                    |
| 6  | **Feedback Pengguna**    | Respons sistem setelah aksi penting.                                          | Belum terlihat notifikasi langsung setelah pengajuan atau approval.                                                                                                                              | Tambahkan notifikasi (popup/toast) “Pengajuan berhasil dikirim” atau “Status berhasil diperbarui”.   | Perlu penyempurnaan minor |

---

## 🧾 Kesimpulan
Website pengajuan cuti ini telah memenuhi sebagian besar **kriteria audit UI/UX**, dengan tampilan profesional dan navigasi yang mudah dipahami.  
Namun, dari hasil audit ditemukan beberapa poin yang perlu disempurnakan agar pengalaman pengguna lebih optimal.

### Ringkasan:
- ✅ Tampilan sudah rapi, informatif, dan konsisten.  
- ⚠️ Perlu ditambahkan validasi input dan feedback interaktif.  
- 🟢 Sistem sudah layak untuk tahap uji coba dan presentasi.  
