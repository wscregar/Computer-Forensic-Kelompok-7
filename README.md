# Computer Forensics - Kelompok 7

- **Operating System:** Windows 11 
- **Disk Image Format:** Virtual Hard Disk (.vhd)
- **Image Name:** Kelompok 7.vhd
- **Virtual Disk Capacity:** 256 MB
- **Link:** https://drive.google.com/file/d/1DvnV1g7lUBlPdOi4aiTJeFDMWyewRwp6/view?usp=sharing

## Anggota Kelompok 7
| No | Nama | NRP |
|:--:|:-----|:----|
| 1  | Wira Samudra Siregar | 5027231041 |
| 2  | Zein Muhammad Hasan | 5027241035 |
| 3  | M. Hildan Adiwena | 5027231077 |

## Deskripsi Kasus: 

### Corporate Financial Manipulation

Seorang staf dari departemen keuangan bernama `staff_akuntan` melaporkan adanya kejanggalan pada laporan pengadaan barang bulan Oktober. Terduga pelaku, `staff_admin`, dicurigai menggunakan aksesnya untuk menggelapkan dana. 

`staff_admin` diduga memanipulasi laporan anggaran dengan melakukan *mark-up*, memalsukan struk transaksi pengadaan barang (bekerja sama dengan vendor lain untuk memanipulasi harga), menyembunyikan catatan transaksi asli, dan menghapus dokumen laporan awal untuk menghilangkan jejak.

## Target Investigasi
1. Menemukan file `laporan_anggaran_oktober.xlsx` yang telah dihapus.
2. Menemukan file tersembunyi `log_transaksi.csv` yang berisi catatan transaksi asli.
3. Menemukan jejak perubahan pada `laporan_anggaran_final.xlsx` (identifikasi nilai anggaran yang di-*mark up*, serta manipulasi vendor A menjadi vendor B).
4. Mengidentifikasi `username` yang melakukan perubahan tersebut, waktu kejadian (*timestamp* file), dan bukti pendukung lainnya.

---
