🪙 UTXO Blockchain Wallet Simulation
Project ini adalah aplikasi berbasis Web3 yang mensimulasikan mekanisme UTXO (Unspent Transaction Output), yaitu model akuntansi yang digunakan oleh Bitcoin. Dibuat untuk memenuhi tugas JP 6: Konsep UTXO.

🎯 Inti Konsep (JP 6)
Berbeda dengan sistem saldo bank konvensional, di dalam aplikasi ini:

Saldo adalah hasil penjumlahan dari lembaran-lembaran transaksi yang belum terpakai (Unspent).

Setiap kali transaksi dilakukan, lembaran lama akan dianggap hangus (Spent) dan sistem akan melahirkan lembaran baru sebagai output.

Analogi: Seperti menggunakan uang tunai fisik di dompet di mana Anda harus memilih lembaran yang pas dan menerima kembalian.

🚀 Fitur Utama
Minting Simulation: Membuat unit aset baru sebagai saldo awal.

UTXO Management: Menampilkan daftar "lembaran" uang yang aktif dengan status Unspent.

Transaction Ledger: Log riwayat transaksi lengkap dengan status Spent untuk transparansi data.

Input Validation: Keamanan sisi klien untuk memastikan ID UTXO yang dipilih valid dan saldo mencukupi sebelum dikirim ke blockchain.

🛠️ Teknologi yang Digunakan
Smart Contract: Solidity (Deployed on Sepolia Testnet).

Frontend: HTML5, Tailwind CSS (Monochromatic Aesthetic).

Interaction: Ethers.js untuk komunikasi antara Web dan Blockchain.

Wallet: MetaMask integration.

📸 Tampilan Interface
Aplikasi ini menggunakan tema Dark Mode dengan aksen warna yang kontras untuk membedakan status aset:

🟢 Green Badge: Menandakan UTXO masih aktif (Unspent).

🔴 Red Badge: Menandakan UTXO sudah digunakan dalam transaksi sebelumnya (Spent).

📖 Cara Penggunaan
Hubungkan wallet MetaMask Anda (pastikan berada di jaringan Sepolia).

Lakukan Minting untuk mendapatkan saldo awal.

Pilih UTXO ID yang ingin digunakan dari daftar "Unspent".

Masukkan alamat tujuan dan jumlah yang ingin dikirim.

Klik Eksekusi Transaksi dan pantau perubahannya di tabel Ledger.
