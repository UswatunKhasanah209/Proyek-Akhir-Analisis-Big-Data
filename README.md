![NFL](https://github.com/UswatunKhasanah209/Proyek-Akhir-Analisis-Big-Data/blob/main/Image/NFL%20versi%20Pnjang.png)

# **Pola Kehadiran Penonton di Pertandingan Tim Liga NFL Amerika**

---

✨ **Tentang** 

Liga sepak bola Amerika atau yang biasa disebut NFL (National Football League) memiliki basis penggemar yang tidak sedikit. Kesetiaan penggemar mereka tidak perlu diragukan lagi, mengingat setiap pertandingan yang diadakan, kehadiran penonton di stadion tidak pernah menyisakan kursi yang disediakan. Kehadiran penonton sepak bola sendiri, memiliki peran penting dalam mendukung tim sepak bola yang sedang bertanding, hal ini menjadi salah satu indikator keberhasilan acara olahraga. Tentunya, setiap pertandingan memiliki tingkat kehadiran penonton yang beragam, beberapa pertandingan bahkan memiliki kehadiran penonton paling banyak dan sukses dalam sejarah liga Amerika, namun juga tidak sedikit pertandingan yang diadakan memiliki jumlah penonton yang sangat rendah. Hal ini, bisa disebabkan karena faktor seperti lokasi pertandingan, tim yang bertanding, jadwal pertandingan, dan waktu pertandingan diadakan.
Sehingga perlu adanya suatu analisis mengenai pola kehadiran penonton pada liga NFL di Amerika ini, karena menurunnya kehadiran penonton pertandingan dapat memengaruhi pendapatan klub yang bertanding, pemahaman mengenai pola kehadiran penonton dapat membantu pengelola acara liga dalam membuat keputusan strategis. Dari hasil analisis, anda dapat menelusuri lebih dalam mengenai fakta-fakta yang mungkin belum terungkap dengan informasi yang tersedia pada umumnya. Dengan pendekatan dan analisis yang komprehensif, project ini akan membawa anda melihat pertandingan dari perspektif yang berbeda.

---

🗃 **Dataset** = [Dataset NLF](https://www.dropbox.com/sh/q5a07l8yynlgwa7/AADwJykQfJLSSRZsfzLh2ylsa?dl=1)
Data diambil dari link website _Kaggle_ di atas. Data digunakan untuk analisis pola kehadiran penonton, yang dikumpulkan dari tahun 2001 hingga 2019 oleh pihak _Pro Football Reference_, dengan berisi sebanyak 8 variabel yang ditampilkan pada tabel berikut:

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
🥅 **Rencana Pendekatan** 

Dengan menggunakan dataset yang diambil dari referensi tim Sepak Bola Pro (Pro Football Reference) yang mencakup informasi kehadiran penonton tim sepak bola NFL, baik di kandang maupun tandang. Rencana pendekatan akan dilakukan dengan proses berikut :

1. Pemuatan dan Eksplorasi Data
   - Impor library untuk memproses dataset.
   - Mengeksplorasi struktur data, tipe data, dan distribusi fitur.
2. Pembersihan Data
   - Memastikan tipe data sesuai untuk analisis (misalnya, tahun sebagai int),         untuk memastikan tipe data sesuai dengan analisis yang dibutuhkan
   - Cek nilai hilang dataset, untuk mencegah bias/kesalahan pada hasil analisis.
3. Analisis Deskriptif
   - Visualisasi tren kehadiran sepanjang musim.
   - Analisis hasil dari pola visualisasi dan tren yang terbentuk
4. Rangkuman dan Temuan
   - Menyimpulkan pola yang ditemukan dari seluruh proses analisis.
   - Menampilkan fakta-fakta unik yang ditemukan dari hasil analisis
---

💎 **Teknologi dan Library yang Digunakan**
- Python, Google Colaboratory
- Library: seperti pada file
[File Requirement](https://github.com/UswatunKhasanah209/Proyek-Akhir-Analisis-Big-Data/blob/main/Requirements.txt)
---

💸 **Hasil Analisis**
- 10 Tim dengan penonton total harian terbanyak sepanjang liga NFL (20 tahun)
1. Cowboys			 
2. Giants			          
3. Redskins			      
4. Jets    			        
5. Broncos          
6. Chiefs
7. Eagles
8. Packers
9. Panthers
10. Patriots
--
- Perbandingan kehadiran penonton kandang vs. tandang (10 top tom)
  Sepanjang liga NFL diadakan, jumlah penonton di pertandingan kandang selalu lebih banyak dari pertandingan tandang
--
- Grafik tren kehadiran penonton tahunan seluruh tim
        1. Penonton dengan kehadiran terendah adalah di tahun 2001
        2. Penonton dengan kehadiran tertinggi adalah di tahun 2016
--
- Tim dengan kehadiran tertinggi (2001, 2016 & 2019)
  Dari hasil grafik sebelumnya dan tahun terakhir didapat bahwa:
  1. Tahun 2001 = Tim Jets
  2. Tahun 2016 = Tim Cowboys
  3. Tahun 2019 = Tim Cowboys
  4. Perbandingan kehadiran antar kedua tim pada tahun 2019 hampir mencapai 3 juta penonton
- Tim Redskins menunjukkan perbedaan terbesar dalam kehadiran penonton antara kandang dan tandang dibandingkan dengan 9 tim teratas lainnya.
- Grafik perbandingan penonton tim Jets dan Cowboys adalah grafik tim Jets menurun, sedangkan tim Cowboys naik
---

**Temuan**
1. Dari variabel weekly_attandance, variabel baru dapat dibuat yakni daily_attendance
2. Popularitas tim Jets semakin menurun, namun selalu berada pada 10 top tim dengan penonton terbanyak, menandakan kesetiaan penggemar tim Jets
3. Tim Cowboys pada tahun awal-awal bahkan tidak termasuk dalam 10 top tim, namun bejalannya tahun, popularitasnya semakin naik, dimana puncaknya pada tahun 2016, dan naik paling tajam di tahun 2009. 
---

# 🐣 **Kelompok :**
- [Kharisma Khairun Nisa](https://github.com/KharismaNisa11) - 202110370311202
- [Uswatun Khasanah](https://github.com/UswatunKhasanah209) - 202110370311209



