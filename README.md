<!BAZNASSB html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Program BAZNAS Provinsi Sumatera Barat</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; }
        .program { margin: 10px; padding: 10px; border: 1px solid #ccc; cursor: pointer; }
        .hidden { display: none; }
    </style>
</head>
<body>
    <h1>Program BAZNAS Provinsi Sumatera Barat</h1>
    
    <div class="program" onclick="toggle('PENDIDIKAN')">PENDIDIKAN: Bantuan Pendidikan</div>
    <div id="PENDIDIKAN" class="hidden">
        <p>Persyaratan: KTP, Kartu Keluarga, Surat Keterangan Tidak Mampu</p>
        <a href="https://wa.me/6282387042013?text=Halo%20Admin,%20saya%20ingin%20mendaftar%20Program%20Bantuan%20Pendidikan" target="_blank">Hubungi Admin</a>
    </div>
    
    <div class="program" onclick="toggle('KESEHATAN')">KESEHATAN: Bantuan Kesehatan</div>
    <div id="KESEHATAN" class="hidden">
        <p>Persyaratan: KTP, Surat Keterangan Dokter, Bukti Tidak Mampu</p>
        <a href="https://wa.me/6282387042013?text=Halo%20Admin,%20saya%20ingin%20mendaftar%20Program%20Bantuan%20Kesehatan" target="_blank">Hubungi Admin</a>
    </div>
    
    <script>
        function toggle(id) {
            var el = document.getElementById(id);
            if (el) {
                el.classList.toggle("hidden");
            } else {
                console.error("Element with ID " + id + " not found.");
            }
        }
    </script>
</body>
</html>
