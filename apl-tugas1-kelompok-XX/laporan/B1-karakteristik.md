# B1. Identifikasi dan Klasifikasi Karakteristik

<!-- Penanggung jawab: ZULFAJRIN -->


| Karakteristik Arsitektur | Alasan Pemilihan & Skenario Penerapan pada Layanan Izin dan Sakit |
| :--- | :--- |
| **Keamanan (Security)** | Dokumen yang diunggah berupa surat keterangan sakit dari dokter memuat informasi medis pribadi mahasiswa yang bersifat sensitif. Sistem wajib menerapkan enkripsi data, batasan hak akses (hanya dosen/akademik terkait yang dapat melihat), serta validasi berkas guna mencegah celah keamanan. |
| **Keandalan (Availability & Reliability)** | Layanan harus siap diakses 24/7 terutama menjelang batas waktu (*deadline*) pelaporan presensi mingguan atau masa ujian akhir. Sistem harus mampu menangani proses pengunggahan berkas tanpa error agar data kehadiran mahasiswa tidak berpotensi hangus. |
| **Kemudahan Penggunaan (Usability)** | Antarmuka formulir pengajuan izin harus sederhana dan responsif saat diakses melalui ponsel (*mobile*). Mahasiswa dapat dengan mudah mengunggah foto surat sakit, dan dosen dapat dengan cepat memverifikasi atau menolak pengajuan hanya dalam beberapa klik. |
| **Integritas Data (Data Integrity)** | Setiap kali status perizinan disetujui oleh dosen, sistem harus secara otomatis memperbarui data rekapitulasi presensi utama tanpa adanya manipulasi atau ketidaksesuaian data antara modul perizinan dan modul presensi kelas. |