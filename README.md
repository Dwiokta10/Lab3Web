# Praktikum 3 : Membuat List, Table dan Form

|                |                    |
| -------------- | ------------------ |
|      _Nama_    | Dwi Okta Ramadhani |
|      _NIM_     |      312410056     |
|     _Kelas_    |      TI.24.A1      |
|  _Mata Kuliah_ | Bahasa Pemrograman Web 1 |

# Membuat Ordered List
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="with=device-width, initial-scale=1.0">
    <title>HTML Lanjutkan</title>
</head>
<body>
    <header>
        <h1>Membuat List</h1>
    </header>
</body>
</html>

<section id="order-list">
    <h2>Ordered List</h2>
    <ol>
        <li>Pemrograman Web</li>
        <li>Sistem Informasi</li>
        <li>Basis Data 2</li>
    </ol>
</section>

<section id="unorder-list">
    <h2>Unordered List</h2>
    <ul type="square">
        <li>Jaringan Komputer</li>
        <li>Struktur Data</li>
        <li>Algoritma &amp; Pemrograman</li>
    </ul>
</section>

```
## OUTPUT
<img width="1920" height="1200" alt="2 web pert 4" src="https://github.com/user-attachments/assets/023bfd68-2129-4fd2-9a53-b2094aca5e21" />

# Membuat Ordered List
```html
<section id="unorder-list">
    <h2>Description List</h2>
    <dl>
        <dt>Fakultas Teknik</dt>
        <dd>Teknik Industri</dd>
        <dd>Teknik Informatika</dd>
        <dd>Teknik Lingkungan</dd>
        <dt>Fakultas Ekonomi dan Bisnis</dt>
        <dd>Akuntansi</dd>
        <dd>Manajemen</dd>
        <dd>Bisnis Digital</dd>
    </dl>
</section>

```
## OUTPUT
<img width="1920" height="1200" alt="Cuplikan layar 2025-10-06 174602" src="https://github.com/user-attachments/assets/2d3c9d6f-5b80-495c-8182-a5b696535ca4" />

# Membuat Tabel
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>
<body>
    <header>
        <h1>Membuat Table</h1>
    </header>
</body>
</html>

<table border="1" cellpadding="4" cellspacing="0">
    <thead>
        <tr>
            <th>No.</th>
            <th>Fakultas</th>
            <th>Program Studi</th>
    </tr>
    </thead>
    <tbody>
        <tr>
            <td>1.</td>
            <td>Teknik</td>
            <td>Teknik Informatika</td>
    </tr>
    <tr>
            <td>2.</td>
            <td>Teknik</td>
            <td>Teknik Industri</td>
    </tr>
    <tr>
            <td>3.</td>
            <td>Teknik</td>
            <td>Teknik Lingkungan</td>
    </tr>
    </tbody>
    </table>

```
## OUTPUT
<img width="1920" height="1200" alt="Cuplikan layar 2025-10-06 175130" src="https://github.com/user-attachments/assets/d05775e6-a5a0-40c7-956d-07402b507a1d" />

# Menggabungkan Sel Data
```html     
<table border="1" cellpadding="6" cellspacing="0">
    <thead>
        <tr>
            <th>No.</th>
            <th>Fakultas</th>
            <th>Program Studi</th>
    </tr>
</thead>
<tbody>
    <tr>
            <td>1.</td>
            <td rowspan="3">Teknik</td>
            <td>Teknik Informatika</td>
    </tr>
    <tr>
            <td>2.</td>
            <td>Teknik Industri</td>
    </tr>
    <tr>
            <td>3.</td>
            <td>Teknik Lingkungan</td>
        </tr>
    </tbody>
</table>
```
## OUTPUT
<img width="1920" height="1200" alt="Cuplikan layar 2025-10-06 175356" src="https://github.com/user-attachments/assets/21644353-1217-4377-af8c-bcef146c0270" />


