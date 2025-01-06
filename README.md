Penjelasan
1.Kelas Data:
•	Kelas ini digunakan untuk menyimpan informasi tentang produk skincare.
•	Metode __init__: Ini adalah konstruktor yang dipanggil saat objek dari kelas Data dibuat. Ia menerima dua parameter: nama_produk dan skincare, yang kemudian disimpan sebagai atribut objek.

2. Kelas View:
•	Kelas ini bertanggung jawab untuk menampilkan data kepada pengguna.
•	Metode tampilkan_data: Ini adalah metode statis yang menerima daftar produk skincare (skincare_list) dan mencetaknya dalam format tabel. Ia menggunakan f-string untuk format output yang rapi.

3. Kelas Process:
•	Kelas ini bertanggung jawab untuk memproses input dari pengguna.
•	Metode input_data: Ini adalah metode statis yang meminta pengguna untuk memasukkan data skincare. Pengguna dapat terus memasukkan data hingga mereka mengetik 'exit'. Metode ini juga melakukan validasi input, seperti memastikan nama produk tidak kosong. Jika input valid, objek Data baru dibuat dan ditambahkan ke daftar skincare_list.

4.Fungsi main:
•	Fungsi ini adalah titik masuk program. Ia memanggil metode input_data dari kelas Process untuk mendapatkan daftar produk skincare dari pengguna, kemudian memanggil metode tampilkan_data dari kelas View untuk menampilkan data tersebut.

5. Pernyataan if __name__ == "__main__":
•	Ini adalah cara untuk memastikan bahwa fungsi main() hanya dipanggil jika skrip dijalankan sebagai program utama, bukan jika diimpor sebagai modul di skrip lain.

CONTOH JALANNYA PROGAM

INPUT:


![Cuplikan layar 2025-01-06 102433](https://github.com/user-attachments/assets/fa8e6eb3-0445-4ea6-be6d-00595824801b)







OUTPUT:


![Cuplikan layar 2025-01-06 102502](https://github.com/user-attachments/assets/ebb2256c-b497-4437-b279-63b149f2f914)


