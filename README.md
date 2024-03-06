<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Project Documentation</title>
    <style>
        table {
            border-collapse: collapse;
            width: 100%;
        }
        th, td {
            border: 1px solid #dddddd;
            text-align: left;
            padding: 8px;
        }
        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>

    <h1><a href="#um">Daftar Isi</a></h1>
        <h2><a id="daftar-isi" href="#um">BAB 1. Tentang Backoffice KedaiReka</a></h2>
            <h3><a href="#um">1.1 Pendahuluan</a></h3>
            <h3><a href="#um">1.2 Manfaat</a></h3>
            <h3><a href="#um">1.3 Kelebihan</a></h3>
            <h3><a href="#um">1.4 Kekurangan</a></h3>
        <h2><a href="#um">BAB 2. Menu Backoffice KedaiReka</a></h2>
            <h3><a href="#um">2.1 Filter</a></h3>
                <li>2.1.1 Pendahuluan</li>
                <li>2.1.2 User Manual</li>
            <h3><a href="#um">2.2 Field Pencarian</a></h3>
                <li>2.2.1 Pendahuluan</li>
                <li>2.2.2 User Manual</li>
            <h3><a href="#um">2.3 Komponen Profil Mitra</a></h3>
                <li>2.3.1 Pendahuluan</li>
                <li>2.3.2 User Manual</li>
            <h3><a href="#um">2.4 Komponen Proposal</a></h3>
                <li>2.4.1 Pendahuluan</li>
                <li>2.4.2 User Manual</li>
            <h3><a href="#um">2.5 detail proposal</a></h3>
                <li>2.5.1 Pendahuluan</li>
                <li>2.5.2 User Manual</li>
                

    <h2>Tentang Backoffice KedaiReka</h2>
    <h3>Pendahuluan</h3>
        Back Office Kedaireka Dirancang khusus untuk menyederhanakan dan mengoptimalkan pengadministrasian program di lingkungan kedaireka. Portal memudahkan pengajuan dan proses seleksi oleh semua pihak yang terlibat dalam manajemen program
    <h3>Manfaat</h3>
    test 1 2 3
    <h3>Kelebihan</h3>
    <h3>Kekurangan</h3>

    <h2>ERD</h2>
    <h3>Pendahuluan</h3>
        Back Office Kedaireka
       
    <h3>Manfaat</h3>
    <h3>Kelebihan</h3>
    <h3>Kekurangan</h3>


    <h2>MENU BACKOFFICE KEDAIREKA</h2>
    <h3></h3>

    <table>
        <tr>
            <th>No</th>
            <th>User Category</th>
            <th>User Main Activity</th>
        </tr>
        <!-- Your data rows go here -->
        <tr>
            <td>1</td>
            <td>Mitra</td>
            <td>Bisa melihat daftar dan detail proposal 2024 <br> Bisa melihat daftar dan detail proposal 2023 <br> Bisa melihat daftar dan detail proposal 2022 <br> Bisa melihat daftar dan detail proposal 2021</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Perguruan Tinggi</td>
            <td>Bisa melihat daftar dan detail proposal 2024 <br> Bisa melihat daftar dan detail proposal 2023 <br> Bisa melihat daftar dan detail proposal 2022 <br> Bisa melihat daftar dan detail proposal 2021</td>
        </tr>
    </table>

    <h2>FITUR YANG DIKEMBANGKAN</h2>

    <table>
        <tr>
            <th>No</th>
            <th>Epic</th>
            <th>Feature</th>
        </tr>
        <!-- Your data rows go here -->
        <tr>
            <td>1</td>
            <td>Halaman Daftar Mitra</td>
            <td>Membuat filter <br> Membuat field pencarian <br> Membuat daftar mitra dengan pagination <br> Filter kategori mitra: Yayasan, UMKM , K/L, DUDI <br> Filter bidang: Kemandirian pangan, Energi dan sumber daya alam, dll. <br></td>
        </tr>
        <tr>
            <td>2</td>
            <td>Halaman Detail Mitra</td>
            <td>Komponen Profil Mitra <br> Komponen Proposal <br> Detail Proposal <br></td>
        </tr>
    </table>

    <h2 id="um">DETAIL FITUR</h2>

    <h3> 1. Filter</h3>
    <h4> Informasi Singkat </h4>
    <table>
        <tr>
            <th>Target Release</th>
            <td>1.0</td>
        </tr>
        <tr>
            <th>Epic</th>
            <td>Mitra</td>
        </tr>
        <tr>
            <th>Short Explanation</th>
            <td>Fitur untuk user/mitra dapat melakukan pencarian berdasarkan kriteria yang diinginkan</td>
        </tr>
        <tr>
            <th>Document Status</th>
            <td>Draft</td>
        </tr>
    </table>

    <h2>REQUIREMENT</h2>

    <table>
        <tr>
            <th>No</th>
            <th>User Story</th>
            <th>Priority</th>
            <th>Notes</th>
        </tr>
        <!-- Your data rows go here -->
        <tr>
            <td>1</td>
            <td> As a Mitra <br> I Want Search category as user <br> So I Can search and acces every Mitra features</td>
            <td>Must Have</td>
            <td>Form filter mitra sebagai berikut <br> 1. Filter kategori Mitra* <br> 2. Filter Bidang* <br> 3. Filter Pengajuan Proposal*</td>
        </tr>
        <tr>
            <td>2</td>
            <td> As a Admin <br> I Want Search category as Admin <br> So I Can search and acces every Admin features</td>
            <td>Must Have</td>
            <td>Form filter mitra sebagai berikut <br> 1. Filter kategori Mitra* <br> 2. Filter Bidang* <br> 3. Filter Pengajuan Proposal*</td>
        </tr>
    </table>

    <h2>Scenario</h2>

    <table>
        <tr>
            <th>No</th>
            <th>Scenario</th>
            <th>Type</th>
            <th>Description</th>
            <th>Validation</th>
        </tr>
        <!-- Your data rows go here -->
        <tr>
            <td>1</td>
            <td>As a Mitra Ikomerz Ilmu Komputer IPB <br>I want login as mitra <br> So i can search and acces every mitra features</td >
            <td>Postive</td>  
            <td>Mitra Ikomerz Ilmu Komputer IPB mendapatkan hasil pencarian sesuai filter</td>
            <td>content</td>
        </tr>

    </table>

    <h2>User Interface & Design</h2>
        
    <table>
        <tr>
            <th>Description</th>
            <th>Login</th>
        </tr>
        <tr>
            <td>Login Page</td>
            <td>Image</td>
        </tr>
        <tr>
            <td>Link figma</td>
            <td>ini ceritanya link figma</td>
        </tr>
        <tr>
            <td>API Mapping</td>
            <td>GET API Endpoint</td>
        </tr>
    </table>
    <script>
        // You can add JavaScript code here if needed
    </script>

    <h1>MF BACKOFFICE BATCH 6</h1>

    <table>
        <tr>
            <th>No</th>
            <th>Nama</th>
            <th>Role</th>
            <th>Nama Mentor</th>
        </tr>
        <!-- Your data rows go here -->
        <tr>
            <td>1.</td>
            <td>Ahmad Jalu F. N. H.	 </td>
            <td>Fullstack Developer</td>
            <td>M. Hilmy.</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>Fullstack Developer </td>
            <td>Techincal Writer</td>
            <td>M. Zulkifli</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>Bintang Rahmatullah </td>
            <td>Fullstack Developer</td>
            <td>M. Hilmy</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>Husein Alhafiz </td>
            <td>Techincal Writer</td>
            <td>Rian AP.</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>Michael Mervin R </td>
            <td>Fullstack Developer</td>
            <td>Rian AP.</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>M. Fadly Febrian </td>
            <td>Quality Assurancer</td>
            <td>Rian AP.</td>
        </tr>
        <tr>
            <td>7.</td>
            <td>M. Ibnu Al Hanif </td>
            <td>Quality Assurance</td>
            <td>Rian AP.</td>
        </tr>
        <tr>
            <td>8.</td>
            <td>Novita Rahmadhani </td>
            <td>UI/UX Engineer</td>
            <td>Rian AP.</td>
        </tr>
        <tr>
            <td>9.</td>
            <td>Reza Irvando </td>
            <td>Fullstack Developer</td>
            <td>Dimas Ahmad</td>
        </tr>
        <tr>
            <td>10.</td>
            <td>Umar Hadi Mukti </td>
            <td>Fullstack Developer</td>
            <td>Dimas Ahmad</td>
        </tr>
    </table>
</body>
</html>
