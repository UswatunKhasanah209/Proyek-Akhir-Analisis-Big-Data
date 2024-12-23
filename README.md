![NFL](https://github.com/UswatunKhasanah209/Proyek-Akhir-Analisis-Big-Data/blob/main/Image/NFL%20versi%20Pnjang.png)

# **Pola Kehadiran Penonton di Pertandingan Tim Liga NFL Amerika**

---

✨ **Tentang** 

Liga sepak bola Amerika atau yang biasa disebut NFL (National Football League) memiliki basis penggemar yang tidak sedikit. Kesetiaan penggemar mereka tidak perlu diragukan lagi, mengingat setiap pertandingan yang diadakan, kehadiran penonton di stadion tidak pernah menyisakan kursi yang disediakan. Kehadiran penonton sepak bola sendiri, memiliki peran penting dalam mendukung tim sepak bola yang sedang bertanding, hal ini menjadi salah satu indikator keberhasilan acara olahraga. Tentunya, setiap pertandingan memiliki tingkat kehadiran penonton yang beragam, beberapa pertandingan bahkan memiliki kehadiran penonton paling banyak dan sukses dalam sejarah liga Amerika, namun juga tidak sedikit pertandingan yang diadakan memiliki jumlah penonton yang sangat rendah. Hal ini, bisa disebabkan karena faktor seperti lokasi pertandingan, tim yang bertanding, jadwal pertandingan, dan waktu pertandingan diadakan.
Sehingga perlu adanya suatu analisis mengenai pola kehadiran penonton pada liga NFL di Amerika ini, karena menurunnya kehadiran penonton pertandingan dapat memengaruhi pendapatan klub yang bertanding, pemahaman mengenai pola kehadiran penonton dapat membantu pengelola acara liga dalam membuat keputusan strategis. Dari hasil analisis, anda dapat menelusuri lebih dalam mengenai fakta-fakta yang mungkin belum terungkap dengan informasi yang tersedia pada umumnya. Dengan pendekatan dan analisis yang komprehensif, project ini akan membawa anda melihat pertandingan dari perspektif yang berbeda.

---

🥅 **Rencana Pendekatan** 

Dengan menggunakan dataset yang diambil dari referensi tim Sepak Bola Pro (Pro Football Reference) yang mencakup informasi kehadiran mingguan penonton tim sepak bola NFL, baik di kandang maupun tandang. Analisis akan dilakukan dengan langkah-langkah berikut:
1. Eksplorasi data untuk memahami kehadiran distribusi kehadiran penonton
2. Identifikasi tren kehadiran berdasarkan waktu dan lokasi pertandingan, serta tim dengan daya tarik penonton paling banyak.
3. Menyajikan visualisasi data untuk mendukung temuan analisis

---

🐳 **Tujuan**

1. Mengidentifikasi tim dengan jumlah kehadiran penonton harian tertinggi
2. Membandingkan rata-rata kehadiran penonton pada pertandingan kandang dan tandang
3. Mengamati pola kehadiran total tahunan dari seluruh tim
4. Menentukan 10 tim dengan tingkat kehadiran tertinggi pada tahun-tahun tertentu, seperti 2001 dan 2016
5. membandingkan total kehadiran dan rata-rata kehadiran mingguan antara dua tim populer, Cowboys dan Jets, pada tahun 2019.

---

🗃 **Dataset** = [Dataset NLF](https://www.dropbox.com/sh/q5a07l8yynlgwa7/AADwJykQfJLSSRZsfzLh2ylsa?dl=1)

<!DOCTYPE html>
<html>
<body>
    <table>
        <tr>
            <th>Nama Variabel</th>
            <th>Deskripsi</th>
            <th>Tipe Data</th>
        </tr>
        <tr>
            <td>team</td>
            <td>Kode tim</td>
            <td>object</td>
        </tr>
        <tr>
            <td>team_name</td>
            <td>Nama tim</td>
            <td>object</td>
        </tr>
        <tr>
            <td>year</td>
            <td>Tahun</td>
            <td>int64</td>
        </tr>
        <tr>
            <td>total</td>
            <td>Total kehadiran sepanjang musim</td>
            <td>int64</td>
        </tr>
        <tr>
            <td>home</td>
            <td>Kehadiran di pertandingan kandang</td>
            <td>int64</td>
        </tr>
        <tr>
            <td>away</td>
            <td>Kehadiran di pertandingan tandang</td>
            <td>int64</td>
        </tr>
        <tr>
            <td>week</td>
            <td>Pekan Pertandingan</td>
            <td>int64</td>
        <tr>
            <td>weekly_attendance</td>
            <td>Kehadiran mingguan</td>
            <td>float64</td>
    </table>
</body>
</html>

---

📝 **Langkah-langkah Proyek**

1. Pemuatan dan Eksplorasi Data
   - Membaca dataset menggunakan pandas.
   - Mengeksplorasi struktur data, tipe data, dan distribusi fitur.
2. Pembersihan Data
   - Mengisi nilai yang hilang pada kolom weekly_attendance.
   - Memastikan tipe data sesuai untuk analisis (misalnya, tahun sebagai angka).
3. Analisis Deskriptif
   - Membandingkan rata-rata kehadiran antara pertandingan kandang dan tandang.
   - Visualisasi tren mingguan kehadiran sepanjang musim.
4. Insight dan Visualisasi
   - Membuat grafik kehadiran mingguan untuk setiap tim.
   - Analisis perbedaan kehadiran
5. Kesimpulan dan Rekomendasi
   - Menyimpulkan pola yang ditemukan.
   - Memberikan rekomendasi untuk meningkatkan kehadiran penonton.


  
💎 **Teknologi dan Library yang Digunakan**
- Python
- Library: pandas, matplotlib, seaborn


💸 **Hasil**
...


# 🐣 **Kelompok :**
- [Kharisma Khairun Nisa](https://github.com/KharismaNisa11) - 202110370311209
- [Uswatun Khasanah](https://github.com/UswatunKhasanah209) - 202110370311209



