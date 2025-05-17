<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cek Nama Peserta Lolos Seleksi</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 50px;
      background-color: #f9f9f9;
    }
    h1 {
      color: #333;
    }
    input, button {
      padding: 10px;
      font-size: 16px;
      margin-top: 10px;
    }
    #result {
      margin-top: 20px;
      font-weight: bold;
      font-size: 18px;
    }
  </style>
</head>
<body>
  <h1>Cek Nama Peserta Lolos Seleksi</h1>
  <input type="text" id="nameInput" placeholder="Masukkan Nama Lengkap">
  <button onclick="checkName()">Cek</button>
  <div id="result"></div>

  <script>
    const acceptedNames = [
      "AINASYA DAMAYANTI SARTODIHARJO",
      "ANDINI APRILIA WASES SAPUTRI",
      "ARINI ROHMATAL ULYA",
      "ARYAPAKSHI AIRLANGGA",
      "ASYIFA HAFIZAH PUTRI",
      "CHYNTIA RAHMA WANDASARI",
      "DESY DWI NOVIANTI",
      "DIANDRA PARAMITHA KUSUMA WARDHANI",
      "ERDIANO ADILA SURYADINATA",
      "FAIZ ARGA FIRMANSYAH",
      "FINGKI MARITA SARI",
      "GHIMAR MUHAMMAD AKMAL SUGANDA",
      "GILANG PUTRA AKBAR",
      "GLENISYA WISDASEPTI AFAZHARI",
      "HUSNUL FARIDA",
      "IKE NUR ROKHMADIANTI",
      "IKHSAN ADHIYASA",
      "KAYRA MAZAYA PUTRI PRASETYO",
      "KEISHA RAFA KIANANDA",
      "KHALIFA RAMZI GHAZALI",
      "MAFAZA MAULANA EFENDI",
      "MANUELA LIZA NAFRATILOVA",
      "MICHELLA CHRISNA",
      "MOHAMMAD ADZIM MALIK",
      "MUHAMMAD IRSYAD DANY",
      "NADIA NURUL AZMI",
      "RAISSA AULIA DEWI",
      "RENA NATANIA HETHARIA",
      "RIVIAN SAMUEL",
      "SIRASD JUDDIN FATTAH",
      "SYAHRUL EMILLIO PRAKOSO",
      "TANTRA BINTANG RAMADHAN",
      "TIARA MERA SIFA",
      "VLANELLA DINNA LARASWATI",
      "YUANDA PUTRA DWI PAMUNGKAS"
    ];

    function checkName() {
      const inputName = document.getElementById("nameInput").value.trim().toUpperCase();
      const resultDiv = document.getElementById("result");

      if (acceptedNames.includes(inputName)) {
        resultDiv.style.color = "green";
        resultDiv.textContent = "SELAMAT ANDA LOLOS KE TAHAP SELEKSI BERIKUTNYA";
      } else {
        resultDiv.style.color = "red";
        resultDiv.textContent = "MOHON MAAF DATA ANDA TIDAK DITEMUKAN DALAM DATA PESERTA LOLOS SELEKSI";
      }
    }
  </script>
</body>
</html>
