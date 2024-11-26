<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My CV</title>
    <!-- Link ke Google Fonts untuk font yang lebih menarik -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&display=swap" rel="stylesheet">
    <style>
        /* Basic styling to improve readability */
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
            line-height: 1.6;
        }
        h1, h2 {
            text-align: center;
            color: #333;
            margin: 20px 0;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .profile-img {
            display: block;
            margin: 20px auto;
            width: 150px;
            height: 150px;
            border-radius: 50%; /* Membuat gambar menjadi lingkaran */
            object-fit: cover; /* Menjaga proporsi gambar */
        }
        hr {
            border: 0;
            border-top: 2px solid #ddd;
            width: 35%;
            margin: 10px auto;
        }
        table {
            width: 100%;
            margin-bottom: 20px;
            border-collapse: collapse;
        }
        th, td {
            padding: 10px;
            border: 1px solid #ddd;
            text-align: left;
        }
        th {
            background-color: #4CAF50;
            color: white;
        }
        td {
            background-color: #fff;
        }
        ul {
            list-style-type: square;
            margin-left: 20px;
        }
        .section-title {
            margin-top: 30px;
            font-weight: bold;
            font-size: 1.2em;
        }

        /* Responsive design */
        @media screen and (max-width: 768px) {
            .profile-img {
                width: 120px;
                height: 120px;
            }
            h1, h2 {
                font-size: 1.5em;
            }
            table, ul {
                font-size: 14px;
            }
            .container {
                padding: 10px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Curriculum Vitae</h1>
        <img src="fotosya.jpeg" alt="Profile Picture" class="profile-img">

        <h2 class="section-title">Data Pribadi</h2>
        <hr>
        <table>
            <tr>
                <th>NAMA</th>
                <td>: DURORUL LAMI'AH</td>
            </tr>
            <tr>
                <th>TTL</th>
                <td>: SERANG, 27 FEBRUARI 2005</td>
            </tr>
            <tr>
                <th>JENIS KELAMIN</th>
                <td>: PEREMPUAN</td>
            </tr>
        </table>

        <h2 class="section-title">Pendidikan</h2>
        <hr>
        <table>
            <thead>
                <tr>
                    <th>TINGKAT</th>
                    <th>NAMA SEKOLAH</th>
                    <th>TAHUN LULUS</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>SD</td>
                    <td>SDN BUAH GEDE 2</td>
                    <td>2011-2017</td>
                </tr>
                <tr>
                    <td>MTS</td>
                    <td>MTS AL-KHAIRIYAH LAMBANG SARI</td>
                    <td>2017-2021</td>
                </tr>
                <tr>
                    <td>MA</td>
                    <td>MA NURUL HIDAYAH</td>
                    <td>2021-2023</td>
                </tr>
            </tbody>
        </table>

        <h2 class="section-title">Hobi</h2>
        <hr>
        <ul>
            <li>Membaca</li>
            <li>Menulis</li>
            <li>Main Gadget</li>
        </ul>

        <h2 class="section-title">Keahlian</h2>
        <hr>
        <ul>
            <li>Menulis Artikel</li>
            <li>Desain Grafis (menggunakan Adobe Photoshop)</li>
            <li>Editing Video Dasar</li>
        </ul>

        <h2 class="section-title">Pengalaman Kerja</h2>
        <hr>
        <table>
            <thead>
                <tr>
                    <th>Posisi</th>
                    <th>Perusahaan/Instansi</th>
                    <th>Tahun</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Freelance Content Writer</td>
                    <td>Website XYZ</td>
                    <td>2023 - Sekarang</td>
                </tr>
                <tr>
                    <td>Asisten Desain Grafis</td>
                    <td>Creative Studio ABC</td>
                    <td>2022-2023</td>
                </tr>
            </tbody>
        </table>
    </div>
</body>
</html>
