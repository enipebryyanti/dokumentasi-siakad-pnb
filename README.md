# Sistem Informasi Akademik

## Deskripsi
Repository ini berisi dokumentasi Sistem Informasi Akademik (SIAKAD), dengan fokus pada data mahasiswa, dosen, mata kuliah, Kartu Rencana Studi (KRS), dan nilai.

## Tujuan
- Mendokumentasikan kebutuhan dan rancangan SIAKAD.
- Menjelaskan struktur lima tabel basis data.
- Menyimpan diagram relasi tabel dan laporan tugas.
- Memudahkan peninjauan serta pelacakan perubahan dokumentasi.

## Pengguna Sistem
- Mahasiswa: melihat data akademik, KRS, jadwal, dan nilai.
- Dosen: melihat data kelas dan mahasiswa serta mengelola nilai.

## Tabel Basis Data
1. Mahasiswa — kunci utama: NIM.
2. Dosen — kunci utama: NIDN.
3. Mata Kuliah — kunci utama: Kode_MK.
4. KRS — kunci utama: ID_KRS.
5. Nilai — kunci utama: ID_Nilai.

## Struktur Repository
- `README.md` — gambaran umum sistem dan repository.
- `dokumen/analisis-kebutuhan/` — dokumentasi kebutuhan sistem.
- `dokumen/perancangan-basis-data/` — rancangan tabel dan keterangannya.
- `dokumen/diagram/` — diagram relasi tabel.
- `laporan/` — laporan tugas.

## Catatan
Repository ini digunakan untuk dokumentasi tugas. Repository ini bukan pengganti basis data akademik operasional.
