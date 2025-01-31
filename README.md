<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Program BAZNAS Provinsi Sumatera Barat</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; }
        .program { margin: 10px; padding: 10px; border: 1px solid #ccc; cursor: pointer; font-weight: bold; background-color: #f0f0f0; }
        .submenu { margin: 5px 20px; padding: 10px; border: 1px solid #ddd; cursor: pointer; background-color: #fafafa; }
        .hidden { display: none; }
    </style>
</head>
<body>
    <h1>Program BAZNAS Provinsi Sumatera Barat</h1>
    <p>Syarat umum untuk semua program:</p>
    <ul style="text-align: left; display: inline-block;">
        <li>Surat Rekomendasi dari BAZNAS Kab/Kota (asli)</li>
        <li>Surat Permohonan</li>
        <li>Nomor Handphone (HP) aktif</li>
        <li>Fotokopi Kartu Keluarga (KK)</li>
        <li>Fotokopi Kartu Tanda Penduduk (KTP)</li>
        <li>Surat Keterangan Kurang Mampu (asli)</li>
        <li>Surat Keterangan Jamaah Masjid (asli)</li>
        <li>Fotokopi Buku Rekening (diutamakan Bank Nagari Syari'ah)</li>
    </ul>
    
    <div class="program" onclick="toggle('PENDIDIKAN')">PENDIDIKAN</div>
    <div id="PENDIDIKAN" class="hidden">
        <div class="submenu" onclick="toggle('BEASISWA')">Beasiswa</div>
        <div id="BEASISWA" class="hidden">
            <ul>
                <li>Surat Pernyataan tidak menerima beasiswa asli dari sekolah/kuliah /bermaterai</li>
            </ul>
            <a href="https://wa.me/6282387042013?text=Halo%20Admin,%20saya%20ingin%20info%20Program%20Beasiswa" target="_blank">Hubungi Admin</a>
        </div>
    </div>
    
    <div class="program" onclick="toggle('KESEHATAN')">KESEHATAN</div>
    <div id="KESEHATAN" class="hidden">
        <div class="submenu" onclick="toggle('BANTUAN_MEDIS')">Bantuan Medis</div>
        <div id="BANTUAN_MEDIS" class="hidden">
            <a href="https://wa.me/6282387042013?text=Halo%20Admin,%20saya%20ingin%20info%20Bantuan%20Medis" target="_blank">Hubungi Admin</a>
        </div>
    </div>
    
    <div class="program" onclick="toggle('EKONOMI')">EKONOMI</div>
    <div id="EKONOMI" class="hidden">
        <div class="submenu" onclick="toggle('USAHA_KECIL')">Bantuan Usaha Kecil</div>
        <div id="USAHA_KECIL" class="hidden">
            <a href="https://wa.me/6282387042013?text=Halo%20Admin,%20saya%20ingin%20info%20Bantuan%20Usaha%20Kecil" target="_blank">Hubungi Admin</a>
        </div>
    </div>
    
    <div class="program" onclick="toggle('KEMANUSIAAN')">KEMANUSIAAN</div>
    <div id="KEMANUSIAAN" class="hidden">
        <div class="submenu" onclick="toggle('BANTUAN_BENCANA')">Bantuan Bencana</div>
        <div id="BANTUAN_BENCANA" class="hidden">
            <a href="https://wa.me/6282387042013?text=Halo%20Admin,%20saya%20ingin%20info%20Bantuan%20Bencana" target="_blank">Hubungi Admin</a>
        </div>
    </div>
    
    <div class="program" onclick="toggle('DAKWAH')">DAKWAH</div>
    <div id="DAKWAH" class="hidden">
        <div class="submenu" onclick="toggle('KEAGAMAAN')">Bantuan Keagamaan</div>
        <div id="KEAGAMAAN" class="hidden">
            <a href="https://wa.me/6282387042013?text=Halo%20Admin,%20saya%20ingin%20info%20Bantuan%20Keagamaan" target="_blank">Hubungi Admin</a>
        </div>
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
