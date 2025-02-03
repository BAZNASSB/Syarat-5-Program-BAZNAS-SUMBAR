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
    <p>Syarat umum *WAJIB* untuk semua program:</p>
    <ul style="text-align: left; display: inline-block;">
        <li>Surat Rekomendasi dari BAZNAS Kab/Kota (ASLI)</li>
        <li>Surat Permohonan</li>
        <li>Nomor Handphone (HP) aktif</li>
        <li>Fotokopi Kartu Keluarga (KK)</li>
        <li>Fotokopi Kartu Tanda Penduduk (KTP)</li>
        <li>Surat Keterangan Tidak Mampu (ASLI)</li>
        <li>Surat Keterangan Jamaah Masjid (ASLI)</li>
        <li>Fotokopi Buku Rekening (diutamakan Bank Nagari Syari'ah/ BANK Nagari atau Perbankan Lainnya)</li>
    
     <h2>Selain Syarat Umum; Terdapat Syarat Tambahan Berikut Pada Masing-masing Program</h2>
     <ul style="text-align: left; display: inline-block;">
    </ul>        
    <div class="program" onclick="toggle('PENDIDIKAN')">PENDIDIKAN</div>
    <div id="PENDIDIKAN" class="hidden">
        <div class="submenu" onclick="toggle('PENDIDIKAN_SMA_SEDERAJAT')">Pendidikan SMA/SMK/SLB & SEDERAJAT</div>
        <div id="PENDIDIKAN_SMA_SEDERAJAT" class="hidden">
            <ul><li> Surat Keterangan Aktif Sekolah (ASLI)</li></ul>
             <ul><li>Surat Pernyataan Tidak Menerima Beasiswa</li></ul>
            <ul><li>Permohonan diberikan kepada perwakilan UPZ Sekolah masing-masing</li></ul>
            <a href="https://wa.me/6282387042013?text=Assalamu'alaikum wr.wb.%20Admin,%20saya%20ingin%20info%20Program%20Pendidikan SMA" target="_blank">Hubungi Admin Whatsapp</a>
        </div>
        <div class="submenu" onclick="toggle('PENDIDIKAN_S1')">Pendidikan S1</div>
        <div id="PENDIDIKAN_S1" class="hidden">
            <ul><li>Surat Keterangan Aktif Kuliah (ASLI)</li></ul>
            <ul><li>Surat Pernyataan Tidak Menerima Beasiswa dari Sumber Lainnya</li></ul>
            <ul><li>Permohonan diajukan ke UPZ di Kampus masing-masing</li></ul>
            <a href="https://wa.me/6282387042013?text=Assalamu'alaikum wr.wb.%20Admin,%20saya%20ingin%20info%20Program%20Pendidikan S1" target="_blank">Hubungi Admin Whatsapp</a>
        </div>
       <div class="submenu" onclick="toggle('PENDIDIKAN_S2')">Pendidikan S2</div>
        <div id="PENDIDIKAN_S2" class="hidden">
            <ul><li> SK Mengajar / SK Homebase dari Pesantren</li></ul>
            <ul><li> Surat Keterangan Aktif Kuliah (ASLI)</li></ul>
            <ul><li>Surat Pernyataan Tidak Menerima Beasiswa</li></ul>
            <ul><li>Bukti penghasilan dari yayasan/ slip gaji</li></ul>
            <a href="https://wa.me/6282387042013?text=Assalamu'alaikum wr.wb.%20Admin,%20saya%20ingin%20info%20Program%20Pendidikan SMA" target="_blank">Hubungi Admin Whatsapp</a>
        </div>
       <div class="submenu" onclick="toggle('PENDIDIKAN_LN')">Pendidikan Luar Negeri</div>
        <div id="PENDIDIKAN_LN" class="hidden">
            <ul><li>Calling Visa</li></ul>
            <ul><li>Visa</li></ul>
            <ul><li>Passport</li></ul>
            <ul><li>Tiket Keberangkatan</li></ul>
            <a href="https://wa.me/6282387042013?text=Assalamu'alaikum wr.wb.%20Admin,%20saya%20ingin%20info%20Program%20Pendidikan SMA" target="_blank">Hubungi Admin Whatsapp</a>
        </div>
    </div>
    
    <div class="program" onclick="toggle('KESEHATAN')">KESEHATAN</div>
    <div id="KESEHATAN" class="hidden">
        <div class="submenu" onclick="toggle('BANTUAN_Berobat')">Bantuan Pengobatan</div>
        <div id="BANTUAN_Berobat" class="hidden">
             <ul><li> Surat Keterangan Rawat Inap Rumah Sakit (ASLI)</li></ul>
             <ul><li>  Foto Pasien (optional)</li></ul>
             <a href="https://wa.me/6282387042013?text=Assalamu'alaikum wr.wb.%20Admin,%20saya%20ingin%20info%20Program%20Kesehatan Berobat" target="_blank">Hubungi Admin Whatsapp</a>
        </div>
      <div class="submenu" onclick="toggle('BANTUAN_Hutang')">Bantuan Hutang Pengobatan</div>
        <div id="BANTUAN_Hutang" class="hidden">
            <ul><li> Surat Keterangan Rawat Inap Rumah Sakit (ASLI)</li></ul>   
            <ul><li>  Surat Keterangan Hutang/ tunggakan BPJS terbaru (optional)</li></ul>
            <ul><li>  Foto Pasien (optional)</li></ul>
           <a href="https://wa.me/6282387042013?text=Assalamu'alaikum wr.wb.%20Admin,%20saya%20ingin%20info%20Program%20Kesehatan Hutang" target="_blank">Hubungi Admin Whatsapp</a>
        </div>
    </div>
    
    <div class="program" onclick="toggle('EKONOMI')">EKONOMI</div>
    <div id="EKONOMI" class="hidden">
        <div class="submenu" onclick="toggle('Tambahan_Modal_Usaha')">Bantuan Tambahan Modal Usaha</div>
        <div id="Tambahan_Modal_Usaha" class="hidden">
            <ul><li> Rincian Anggaran Biaya Usaha (RAB)</li></ul>
            <ul><li>  Denah Lokasi Usaha/ Rumah</li></ul>
            <ul><li>  Foto Usaha</li></ul>
             <a href="https://wa.me/6282387042013?text=Assalamu'alaikum wr.wb.%20Admin,%20saya%20ingin%20info%20Program%20Ekonomi Tambahan Modal Usaha" target="_blank">Hubungi Admin Whatsapp</a>
        </div>
    </div>
    
    <div class="program" onclick="toggle('KEMANUSIAAN')">KEMANUSIAAN</div>
    <div id="KEMANUSIAAN" class="hidden">
        <div class="submenu" onclick="toggle('BANTUAN_BENCANA')">Bantuan Bencana / RUTILAHU</div>
        <div id="BANTUAN_BENCANA" class="hidden">
            <ul><li> Denah Lokasi Rumah </li></ul>
            <ul><li> Surat Penyataan yang menerangkan tanah milik sendiri / Hibah</li></ul>
            <ul><li>  Surat Keterangan dari kepolisian (jika kebakaran)	</li></ul>
            <a href="https://wa.me/6282387042013?text=Assalamu'alaikum wr.wb.%20Admin,%20saya%20ingin%20info%20Program%20Kemanusiaan Bencana / RUTILAHU" target="_blank">Hubungi Admin Whatsapp</a>
        </div>
       <div class="submenu" onclick="toggle('BANTUAN_Konsumtif')">Bantuan Konsumtif</div>
        <div id="BANTUAN_Konsumtif" class="hidden">
             <ul><li> Tidak Ada Syarat Tambahan</li></ul>
          
             <a href="https://wa.me/6282387042013?text=Assalamu'alaikum wr.wb.%20Admin,%20saya%20ingin%20info%20Program%20Kemanusiaan Konsumtif" target="_blank">Hubungi Admin Whatsapp</a>
      
        </div>
    </div>
    
    <div class="program" onclick="toggle('DAKWAH')">DAKWAH & ADVOKASI</div>
    <div id="DAKWAH" class="hidden">
        <div class="submenu" onclick="toggle('KEAGAMAAN')">Bantuan Dakwah & Advokasi</div>
        <div id="KEAGAMAAN" class="hidden">
              <ul><li> Tidak Ada Syarat Tambahan</li></ul>
            <a href="https://wa.me/6282387042013?text=Assalamu'alaikum wr.wb.%20Admin,%20saya%20ingin%20info%20Program%20Dakwah dan Advokasi" target="_blank">Hubungi Admin Whatsapp</a>
        
        </div>
    </div>

   <h2>Istilah dalam Program</h2>
    <ul style="text-align: left; display: inline-block;">
        <li><strong>UPZ</strong> = Unit Pengumpul Zakat</li>
        <li><strong>ZIS</strong> = Zakat Infak Sedekah</li>
        <li><strong>RAB</strong> = Rincian Anggaran Biaya</li>
        <li><strong>RUTILAHU</strong> = Rumah Tidak Layak Huni</li>
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
