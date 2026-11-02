# Tugas Hands-On 3: Pandas Lanjutan

**Nama:** Sofia Risa Aulia
**NIM:** 23552011299

## Kasus yang dipilih
Case 8 - Student Performance (EdTech). Tujuannya memprediksi status kelulusan siswa (klasifikasi biner). Dataset berisi 800 siswa dan 19 kolom.

## Ringkasan temuan
1. Jam belajar adalah pembeda paling kuat: siswa yang belajar 11 jam per minggu atau kurang hanya lulus 3,6%, sedangkan yang belajar lebih dari 21 jam lulus lebih dari 95%.
2. Kehadiran di bawah 60% hanya menghasilkan kelulusan 46,4%, sedangkan kehadiran di atas 90% mencapai 77,5%.
3. Siswa dengan les privat (67,4%) dan akses internet (63,6%) lulus lebih tinggi daripada yang tidak.

Catatan: kolom nilai mapel dan nilai rata-rata tidak dipakai sebagai fitur karena kelulusan ditentukan langsung oleh rata-rata nilai >= 65 (bocoran target).

## Cara menjalankan
1. Install library: `pip install pandas numpy matplotlib seaborn scikit-learn`
2. Buka `notebook.ipynb` di Google Colab atau Jupyter Notebook.
3. Unggah file `data/case9_student_performance.csv` saat diminta.
4. Jalankan semua sel (Runtime, Run all).

## Isi folder
- `notebook.ipynb`: notebook utama
- `data/`: dataset asli
- `output/data_bersih.csv`: data setelah dibersihkan
- `output/kamus_data.csv`: kamus data (kolom, tipe, missing, nilai unik)
- `laporan_kualitas.csv`: perbandingan kualitas sebelum dan sesudah pembersihan
