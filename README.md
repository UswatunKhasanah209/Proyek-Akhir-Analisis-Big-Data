![NFL](https://github.com/UswatunKhasanah209/Proyek-Akhir-Analisis-Big-Data/blob/main/Image/nfl.png)

# **Mengungkap Pola Kehadiran Penonton di Pertandingan Tim Liga NFL Amerika**


✨ **Tentang** 

Liga sepak bola Amerika atau yang biasa disebut NFL (National Football League) memiliki basis penggemar yang tidak sediki. Kesetiaan penggemar mereka tidak perlu diragukan lagi, mengingat setiap pertandingan yang diadakan, kehadiran penonton di stadion tidak pernah mengosongkan kursi yang disediakan. Kehadiran penonton sepak bola sendiri, memiliki peran penting dalam mendukung tim sepak bola yang sedang bertanding, hal ini menjadi salah satu indikator keberhasilan acara olahraga. Tentunya, setiap pertandingan memiliki tingkat kehadiran penonton yang beragam, beberapa pertandingan bahkan memiliki kehadiran penonton paling banyak dan sukses dalam sejarah liga Amerika, namun juga tidak sedikit pertandingan yang diadakan memiliki jumlah penonton yang sangat rendah. Hal ini, bisa disebabkan karena faktor seperti lokasi pertandingan, tim yang bertanding, jadwal pertandingan, dan waktu pertandingan diadakan. Sehingga perlu adanya suatu analisis mengenai pola kehadiran penonton pada liga NFL di Amerika ini, karena:
1. Menurunnya kehadiran penonton pertandingan dapat memengaruhi pendapatan klub yang bertanding
2. Pemahaman mengenai pola kehadiran penonton dapat membantu pengelola acara liga dalam membuat keputusan strategis.


Apabila anda adalah seorang penggemar sepak bola, khususnya liga Amerika, analisis ini akan sangat menarik untuk anda, karena diharapkan dapat memberikan wawasan yang berguna untuk meningkatkan pengalaman anda sebagai penggemar sepak bola. Dari hasil analisis, anda dapat menelusuri lebih dalam mengenai fakta-fakta yang mungkin belum terungkap dengan informasi yang tersedia pada umumnya. Dengan pendekatan dan analisis yang komprehensif, project ini akan membawa anda melihat pertandingan dari perspektif yang berbeda. Temukan strategi, statistik, dan cerita menarik di balik pertandingkan liga NFL yang akan memperkaya pengetahuan dan kesenangan anda sebagai penggemar sepak bola liga Amerika.


🥅 **Rencana Pendekatan** 

Dengan menggunakan dataset yang diambil dari referensi tim Sepak Bola Pro (Pro Football Reference) yang mencakup informasi kehadiran mingguan penonton tim sepak bola NFL, baik di kandang maupun tandang. Analisis akan dilakukan dengan langkah-langkah berikut:
1. Eksplorasi data untuk memahami kehadiran distribusi kehadiran penonton
2. Identifikasi tren kehadiran berdasarkan waktu dan lokasi pertandingan, serta tim dengan daya tarik penonton paling banyak.
3. Menyajikan visualisasi data untuk mendukung temuan analisis

**Dataset**
<!DOCTYPE html>
<html>
<body>
    <table>
        <tr>
            <th>Nama Variabel</th>
            <th>Deskripsi</th>
            <th>Tipe Data</th>
            <th>Statistik Ringkas</th>
        </tr>
        <tr>
            <td>team</td>
            <td>Kode tim</td>
            <td>object</td>
            <td>Unik: 32</td>
        </tr>
        <tr>
            <td>team_name</td>
            <td>Nama tim</td>
            <td>object</td>
            <td>Unik: 32</td>
        </tr>
        <tr>
            <td>year</td>
            <td>Tahun</td>
            <td>int64</td>
            <td>min: 2000.0<br>max: 2019.0<br>mean: 2009.53<br>median: 2010.00</td>
        </tr>
        <tr>
            <td>total</td>
            <td>Total kehadiran sepanjang musim</td>
            <td>int64</td>
            <td>min: 760644.0<br>max: 1322087.0<br>mean: 1080910.03<br>median: 1081089.50</td>
        </tr>
        <tr>
            <td>home</td>
            <td>Kehadiran di pertandingan kandang</td>
            <td>int64</td>
            <td>min: 202687.0<br>max: 741775.0<br>mean: 540455.01<br>median: 543185.00</td>
        </tr>
        <tr>
            <td>away</td>
            <td>Kehadiran di pertandingan tandang</td>
            <td>int64</td>
            <td>min: 450295.0<br>max: 601655.0<br>mean: 540455.01<br>median: 541757.00</td>
        </tr>
        <tr>
            <td>week</td>
            <td>Pekan Pertandingan</td>
            <td>int64</td>
            <td>min: 1.0<br>max: 17.0<br>mean: 9.00<br>median: 9.00</td>
        </tr>
        <tr>
            <td>weekly_attendance</td>
            <td>Kehadiran mingguan</td>
            <td>float64</td>
            <td>min: 23127.0<br>max: 105121.0<br>mean: 67656.27<br>median: 68388.50</td>
        </tr>
    </table>
</body>
</html>






