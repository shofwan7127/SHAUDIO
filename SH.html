<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>SH</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      overflow: hidden;
    }

    .wrapper {
      width: 90%;
      max-width: 500px;
      text-align: center;
    }

    .slide-logo {
      font-size: 32px;
      font-weight: bold;
      color: #2196F3;
      transform: translateY(-100%);
      opacity: 0;
      animation: slideDown 1s ease forwards;
    }

    @keyframes slideDown {
      to {
        transform: translateY(0);
        opacity: 1;
      }
    }

    .form-container {
      display: none;
      background-color: #fff;
      padding: 20px;
      margin-top: 20px;
      border-radius: 5px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
    }

    h2 {
      text-align: center;
      color: #333;
    }

    label {
      font-weight: bold;
      display: block;
      margin-bottom: 8px;
    }

    input {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 16px;
    }

    button {
      width: 100%;
      padding: 10px;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 16px;
      cursor: pointer;
    }

    button:hover {
      background-color: #45a049;
    }

    .purchase-info,
    .error-message {
      max-height: 0;
      overflow: hidden;
      transition: max-height 0.5s ease, padding 0.5s ease;
    }

    .slide-down {
      max-height: 1000px;
      padding: 10px 0;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      border: 2px solid black;
    }

    .purchase-info table {
      background-color: #4CAF50;
      color: white;
    }

    .error-message table {
      background-color: #2196F3;
      color: white;
    }

    th, td {
      padding: 12px;
      border: 1px solid black;
      text-align: left;
    }
  </style>
</head>
<body>

  <div class="wrapper">
    <div class="slide-logo" id="introText">SH AUDIO</div>

    <div class="form-container" id="formSection">
      <h2>Masukkan Kode Pembelian</h2>
      <label for="codeInput"></label>
      <input type="text" id="codeInput" placeholder="Masukkan Kode Barang" />
      <button onclick="showPurchaseInfo()">Tampilkan</button>
    </div>

    <div class="purchase-info" id="purchaseInfo">
      <table>
        <tbody>
          <tr><th>No Seri</th><td id="serialNumber"></td></tr>
          <tr><th>Jenis Barang</th><td id="itemName"></td></tr>
          <tr><th>Harga</th><td id="itemPrice"></td></tr>
          <tr><th>Tanggal Masuk</th><td id="purchaseDate"></td></tr>
          <tr><th>Tanggal Selesai</th><td id="purchaseDate1"></td></tr>
          <tr><th>Jenis Penanganan</th><td id="penanganan"></td></tr>
          <tr><th>Status</th><td id="status"></td></tr>
        </tbody>
      </table>
    </div>

    <div class="error-message" id="errorMessage">
      <table>
        <tr><td>Maaf barang tidak ditemukan.</td></tr>
      </table>
    </div>
  </div>

  <script>
    const purchaseData = {
      "SH0001": {
        serialNumber: "SH0001",
        itemName: "Speaker Bluetooth",
        itemPrice: "Belum di tentukan",
        purchaseDate: "08-04-2025",
        purchaseDate1: "Belum di tentukan",
        penanganan: "perbaikan",
        status: "Masih dalam proses"
      },
      "SH0002": {
        serialNumber: "SH0002",
        itemName: "Power Amp 10A",
        itemPrice: "Belum di tentukan",
        purchaseDate: "03-05-2025",
        purchaseDate1: "07-05-2025",
        penanganan: "Ujicoba Set Bias",
        status: "Masih dalam proses"
      }
    };

    setTimeout(() => {
      document.getElementById("introText").style.display = "none";
      document.getElementById("formSection").style.display = "block";
    }, 2000);

    function showPurchaseInfo() {
      const code = document.getElementById("codeInput").value.trim();
      const infoBox = document.getElementById("purchaseInfo");
      const errorBox = document.getElementById("errorMessage");

      infoBox.classList.remove("slide-down");
      errorBox.classList.remove("slide-down");

      if (purchaseData[code]) {
        const data = purchaseData[code];
        document.getElementById("serialNumber").textContent = data.serialNumber;
        document.getElementById("itemName").textContent = data.itemName;
        document.getElementById("itemPrice").textContent = data.itemPrice;
        document.getElementById("purchaseDate").textContent = data.purchaseDate;
        document.getElementById("purchaseDate1").textContent = data.purchaseDate1;
        document.getElementById("penanganan").textContent = data.penanganan;
        document.getElementById("status").textContent = data.status;

        infoBox.classList.add("slide-down");
      } else {
        errorBox.classList.add("slide-down");
      }
    }
  </script>

</body>
</html>
