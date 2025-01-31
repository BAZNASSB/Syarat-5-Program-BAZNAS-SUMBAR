<!DOCTYPE html>
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
    
    <div class="program" onclick="toggle('PENDIDIKAN')">PENDIDIKAN: Syarat Tambahan Bantuan Pendidikan</div>
    <div id="PENDIDIKAN" class="hidden">
        <p>Tambahan syarat untuk Pendidikan:</p>
        <ul>
            <li>Surat Pernyataan tidak menerima beasiswa asli dari sekolah/kuliah /bermaterai</li>
        </ul>
        <a href="https://wa.me/6282387042013?text=Halo%20Admin,%20saya%20ingin%20info%20Program%20Bantuan%20Pendidikan" target="_blank">Hubungi Admin</a>
    </div>
    
    <div class="program" onclick="toggle('KESEHATAN')">KESEHATAN: Syarat Tambahan Bantuan Kesehatan</div>
    <div id="KESEHATAN" class="hidden">
       <p>Tambahan syarat untuk Kesehatan:</p>
        <ul>
            <li>Surat Pernyataan tidak menerima beasiswa asli dari sekolah/kuliah /bermaterai</li>
        </ul>
        <a href="https://wa.me/6282387042013?text=Halo%20Admin,%20saya%20ingin%20info%20Program%20Bantuan%20Kesehatan" target="_blank">Hubungi Admin</a>
    </div>
    
    <div class="program" onclick="toggle('EKONOMI')">EKONOMI: Syarat Tambahan Bantuan Ekonomi</div>
    <div id="EKONOMI" class="hidden">
        <a href="https://wa.me/6282387042013?text=Halo%20Admin,%20saya%20ingin%20info%20Program%20Bantuan%20Ekonomi" target="_blank">Hubungi Admin</a>
    </div>
    
    <div class="program" onclick="toggle('KEMANUSIAAN')">KEMANUSIAAN: Syarat Tambahan Bantuan Kemanusiaan</div>
    <div id="KEMANUSIAAN" class="hidden">
        <a href="https://wa.me/6282387042013?text=Halo%20Admin,%20saya%20ingin%20info%20Program%20Bantuan%20Kemanusiaan" target="_blank">Hubungi Admin</a>
    </div>
    
    <div class="program" onclick="toggle('DAKWAH')">DAKWAH: Syarat Tambahan Bantuan Dakwah dan Advokasi</div>
    <div id="DAKWAH" class="hidden">
        <a href="https://wa.me/6282387042013?text=Halo%20Admin,%20saya%20ingin%20info%20Program%20Bantuan%20Dakwah" target="_blank">Hubungi Admin</a>
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
