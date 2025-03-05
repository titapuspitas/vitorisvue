<template>
    <div class="dashboard">
      <Menu />
      <div class="content">
        <img src="/img/logo.png" alt="Logo" class="logo" />
        <div class="header">
          <h1>Pengembalian Produk</h1>
          <a href="formkembalian.html" class="btn">Mengembalikan</a>
        </div>
        <div class="table-container">
          <h2>Daftar Pengembalian</h2>
          <table>
            <thead>
              <tr>
                <th>No</th>
                <th>Nama</th>
                <th>Barang</th>
                <th>Tanggal Dikembalikan</th>
                <th>Status</th>
                <th>Aksi</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>1</td>
                <td>Bela Nurseha</td>
                <td>Laptop</td>
                <td>02-02-2025</td>
                <td class="status-dipinjam">Belum Dikembalikan</td>
                <td><button class="confirm-btn">Konfirmasi</button></td>
              </tr>
              <tr>
                <td>2</td>
                <td>Tita Puspita Sari</td>
                <td>Proyektor</td>
                <td>01-02-2025</td>
                <td class="status-terlambat">Belum Dikembalikan</td>
                <td><button class="confirm-btn">Konfirmasi</button></td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
    </div>
  </template>
  
  <style scoped>
  .dashboard {
    display: flex;
    height: 100vh;
  }
  
  .content {
    margin-left: 250px;
    padding: 30px;
    width: 100%;
    background-color: #f4f4f4;
  }
  
  .header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 30px;
  }
  
  .header h1 {
    font-size: 28px;
    font-weight: bold;
    color: #005696;
  }
  
  .btn {
    background-color: #ffd700;
    color: black;
    padding: 10px 20px;
    border-radius: 6px;
    font-size: 16px;
    cursor: pointer;
    font-weight: bold;
    text-decoration: none;
    border: none;
  }
  
  .btn:hover {
    background-color: #ffc107;
  }
  
  .table-container {
    background-color: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  }
  
  .table-container table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 10px;
  }
  
  .table-container th,
  .table-container td {
    border: 1px solid #ddd;
    padding: 10px;
    text-align: left;
  }
  
  .table-container th {
    background-color: #005696;
    color: white;
  }
  
  .status-dipinjam {
    color: #e53e3e;
    font-weight: bold;
  }
  
  .status-terlambat {
    color: #e53e3e;
    font-weight: bold;
  }
  
  .status-sudah {
    color: green;
    font-weight: bold;
  }
  
  .confirm-btn {
    background-color: #38a169;
    color: white;
    border: none;
    padding: 8px 12px;
    border-radius: 5px;
    cursor: pointer;
    font-weight: bold;
  }
  
  .confirm-btn:hover {
    background-color: #2f855a;
  }
  
  .logo {
    width: 250px;
    height: auto;
    display: block;
    margin: 0 auto 20px;
  }
  </style>
  