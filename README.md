# Menyelesaikan Permasalahan Perusahaan Edutech

## Business Understanding

Jaya Jaya Maju, perusahaan multinasional dengan lebih dari 1000 karyawan, menghadapi tantangan dalam mengelola sumber daya manusia, terutama tingginya attrition rate yang mencapai lebih dari 10%. Kondisi ini dapat mengganggu stabilitas operasional dan meningkatkan biaya perekrutan serta pelatihan karyawan baru.Untuk mengatasi masalah ini, departemen HR perlu memahami faktor-faktor penyebab tingginya attrition rate dan membutuhkan business dashboard untuk memantau indikator terkait secara real-time. Dengan analisis yang tepat, perusahaan diharapkan dapat meningkatkan retensi karyawan dan menurunkan attrition rate secara signifikan.

### Permasalahan Bisnis

1. Bagaimana data mengenai tingkat keja dan work-life balance yang dirasakan karyawan?
2. Apa karakteristik karyawan yang memiliki kecenderungan lebih tinggi untuk keluar? (misalnya JobSatisfaction, gender,atau lama bekerja)
3. Apakah attrition rate lebih tinggi pada departemen tertentu dibandingkan dengan yang lain?


### Cakupan Proyek

1. Analisis Data Attrition
- Mengumpulkan dan menganalisis data historis terkait karyawan, seperti demografi, lama bekerja, performa, gaji, dan gender.
- Mengidentifikasi pola dan tren attrition berdasarkan departemen, lokasi, atau jabatan.
- Menggali penyebab utama attrition menggunakan teknik statistik dan machine learning.

2. Pengembangan Business Dashboard
Membuat dashboard interaktif yang menyajikan informasi terkait faktor-faktor attrition, seperti:
- Tingkat attrition per departemen, lokasi, dan periode waktu tertentu.
- Indikator demografi karyawan yang berisiko tinggi untuk keluar.

3. Rekomendasi Strategis
- Memberikan rekomendasi berbasis data untuk menurunkan attrition rate, seperti program retensi, pelatihan, atau penyesuaian kebijakan.
- Menyusun prioritas tindakan berdasarkan faktor yang paling berpengaruh.

### Persiapan

Sumber data: (https://raw.githubusercontent.com/dicodingacademy/dicoding_dataset/refs/heads/main/employee/employee_data.csv)

Setup environment:

```
pip install -r requirements.txt
```


## Business Dashboard

Dalam Businnes Dashboard ini kita bisa mendapatkan insight yang menarik diantaranya Jumlah total karyawan, Rata-rata umur karyawan yang bekerja serta jarak rata-rata dari rumah ke tempat bekerja.
- Diagram pie Attrition menunjukkan persentase karyawan yang keluar (attrition) dan yang masih bekerja.
- Distribusi Work-Life Balance berdasarkan Job Level (Bar Chart)
Sumbu X: Job Level (1-5)
Sumbu Y: Jumlah Karyawan
Warna pada grafik mewakili kategori work-life balance (1 = Low, 4 = Outstanding).
Mayoritas karyawan berada di Job Level 2 dan 3, dengan tingkat work-life balance yang bervariasi.
- Monthly Rate dan Job Level (Line Chart)
Hubungan antara Monthly Rate (Gaji Bulanan) dan Job Level
Sumbu X: Rentang Monthly Rate
Sumbu Y: Jumlah Karyawan
Warna menunjukkan Job Level karyawan.
Menunjukkan pola bagaimana distribusi gaji bulanan terhadap tingkat jabatan.
- Attrition dan Job Satisfaction (Bar Chart)
Menunjukkan hubungan antara tingkat kepuasan kerja (Job Satisfaction) dan tingkat attrition.
Semakin tinggi tingkat kepuasan kerja (4-5), semakin kecil tingkat attrition.
Attrition (warna merah) tampak lebih tinggi pada karyawan dengan tingkat kepuasan rendah (1-2).
- Attrition dan Years at Company (Grafik Bar - Kanan Atas)
Menampilkan jumlah karyawan berdasarkan lama bekerja dan tingkat attrition.
Mayoritas karyawan yang keluar (attrition) memiliki pengalaman kerja 0-5 tahun.
Semakin lama bekerja (>15 tahun), tingkat attrition tampak jauh lebih rendah.
Ini bisa menjadi indikator bahwa karyawan baru lebih rentan keluar dari perusahaan.
- Attrition dan Gender (Donut Chart - Kiri Bawah)
Menampilkan distribusi karyawan berdasarkan gender dan tingkat attrition.
87.8% masih bekerja (biru), 12.2% mengalami attrition (merah).
Terlihat bahwa laki-laki dan perempuan memiliki distribusi attrition yang cukup seimbang, tanpa perbedaan signifikan.
- Attrition dan Department (Grafik Bar - Kanan Bawah)
Memvisualisasikan attrition berdasarkan departemen.
Departemen Research & Development memiliki jumlah karyawan terbanyak, namun juga memiliki tingkat attrition yang lebih tinggi dibandingkan HR.
Sales memiliki tingkat attrition yang cukup tinggi dibandingkan departemen lain.
Departemen HR memiliki jumlah karyawan paling sedikit dengan attrition yang rendah.

Link : (http://localhost:3000/public/dashboard/26dd00a6-23b6-4c84-8024-64ead00b5c06)

## Conclusion
- Tingkat Attrition sebesar 12.2%, menunjukkan bahwa sebagian kecil karyawan keluar dari perusahaan.
- Mayoritas karyawan berada di Job Level 2 & 3, dengan variasi work-life balance yang cukup besar.
- Jarak rata-rata rumah ke kantor sekitar 9.19 km, yang dapat menjadi faktor kepuasan atau attrition.
- Distribusi gaji bulanan berdasarkan job level dapat membantu strategi kompensasi dan promosi.
- Karyawan dengan kepuasan kerja rendah lebih rentan mengalami attrition.
- Sebagian besar karyawan yang keluar memiliki pengalaman kerja 0-5 tahun, menunjukkan tantangan retensi karyawan baru.
- Gender tidak terlalu berpengaruh pada tingkat attrition.
- Sales dan Research & Development memiliki tingkat attrition yang lebih tinggi dibandingkan Human Resources.

### Rekomendasi Action Items 

Berikan beberapa rekomendasi action items yang harus dilakukan perusahaan guna menyelesaikan permasalahan atau mencapai target mereka.
Rekomendasi action yang bisa dilakukan perusahaan untuk mengurangi tinggat attrition diantaranya adalah:
- Meskipun dari data tingkat attrition paling tinggi berada pada JobSatisfaction pada nilai 3-3.5 tetapi yang perlu diperhatikan justu nilai JobSatisfaction dengan nilai dibawahnya.
- Melakukan survey kepuasaan kerja untuk mengetahui kepuasaan karyawan.
- Pihak HRD dapat melakukan beberapa pertanyaan pada karyawan yang ingin keluar untuk mengetahui alasan keluar dari perusahaan.
