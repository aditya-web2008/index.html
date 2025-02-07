# index.html
balajar dikit
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Website Sederhana dengan Pengenalan Diri</title>
  <style>
    /* CSS untuk styling halaman */
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      margin: 0;
      padding: 20px;
    }
    header {
      background-color: #4CAF50;
      color: white;
      padding: 15px;
      text-align: center;
    }
    main {
      margin-top: 20px;
    }
    section {
      background-color: #fff;
      padding: 15px;
      margin: 20px 0;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    button {
      padding: 10px 20px;
      background-color: #4CAF50;
      color: white;
      border: none;
      cursor: pointer;
      margin-top: 10px;
    }
    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <h1>Selamat Datang di Website Saya</h1>
  </header>

  <!-- Konten Utama -->
  <main>
    <p>Ini adalah website sederhana yang dibuat menggunakan HTML, CSS, dan JavaScript.</p>
    <button onclick="tampilkanPesan()">Klik Saya</button>
    
    <!-- Bagian Pengenalan Diri -->
    <section id="pengenalan" style="display: none;">
      <h2>Pengenalan Diri</h2>
      <p><strong>Nama:</strong> [Nama Kamu]</p>
      <p><strong>Umur:</strong> [Umur Kamu]</p>
      <p><strong>Asal:</strong> [Kota/Negara Kamu]</p>
      <p><strong>Hobi:</strong> [Hobi Kamu]</p>
    </section>
    <button onclick="togglePengenalan()">Tampilkan/Sembunyikan Pengenalan Diri</button>
  </main>

  <!-- JavaScript untuk interaktivitas -->
  <script>
    function tampilkanPesan() {
      alert("Halo, terima kasih telah mengklik tombol!");
    }

    function togglePengenalan() {
      var pengenalan = document.getElementById('pengenalan');
      if (pengenalan.style.display === 'none') {
        pengenalan.style.display = 'block';
      } else {
        pengenalan.style.display = 'none';
      }
    }
  </script>
</body>
</html>
