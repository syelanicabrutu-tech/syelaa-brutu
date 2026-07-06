<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TUGAS PEMROGRAMAN I</title>
    <style>
        * {
            font-family: Arial, sans-serif;
            margin: 20px;
            line-height: 1.6;
        }
        h1 {
            text-align: center;
            text-decoration: underline;
            font-size: 24px;
            margin-bottom: 30px;
        }
        .label {
            display: inline-block;
            width: 120px;
            font-size: 18px;
            margin: 15px 0 5px 0;
        }
        input[type="text"] {
            padding: 8px;
            width: 350px;
            font-size: 16px;
            border: 1px solid #999;
            border-radius: 4px;
        }
        table {
            border-collapse: collapse;
            width: 90%;
            margin: 20px 0;
        }
        th, td {
            border: 1px solid #333;
            padding: 12px;
            text-align: left;
            font-size: 16px;
        }
        th {
            background-color: #f0f0f0;
            text-align: center;
        }
        .file-input {
            margin: 12px 0;
            font-size: 17px;
        }
    </style>
</head>
<body>

    <h1>TUGAS PEMROGRAMAN I</h1>

    <p>
        <span class="label">NAMA</span> : <input type="text" value="Syelanica Olivia Br Brutu">
    </p>
    <p>
        <span class="label">NIM</span> : <input type="text" value="250820006">
    </p>

    <p style="margin: 25px 0 10px 0; font-size: 18px;">DATA PENDIDIKAN :</p>
    <table>
        <tr>
            <th>TAHUN</th>
            <th>PENDIDIKAN</th>
            <th>ALAMAT</th>
        </tr>
        <tr>
            <td><input type="text" value="2013 - 2019"></td>
            <td>SD</td>
            <td><input type="text" value="Jl. Lembaga Pemasyarakatan, Medan"></td>
        </tr>
        <tr>
            <td><input type="text" value="2019 - 2023"></td>
            <td>SMP</td>
            <td><input type="text" value="Jl. Eka Prasetya No. 1 Medan"></td>
        </tr>
        <tr>
            <td><input type="text" value="2023 - 2025"></td>
            <td>SMU/SMK</td>
            <td><input type="text" value="Jl. Eka Prasetya No. 1 Medan"></td>
        </tr>
    </table>

    <div class="file-input">
        <span class="label">Hobby</span> : (Gambar Hobby)
        <br>
        <input type="file" accept="image/*">
    </div>

    <div class="file-input">
        <span class="label">Lagu kesukaan</span> : (Upload Musik)
        <br>
        <input type="file" accept="audio/*">
    </div>

    <div class="file-input">
        <span class="label">Film kesukaan</span> : (Upload Video)
        <br>
        <input type="file" accept="video/*">
    </div>

</body>
</html>
