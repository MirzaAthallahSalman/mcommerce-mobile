Tugas 7
1. Pengertian Stateless Widget dan Stateful Widget
   Stateless Widget: Widget yang nggak berubah; tampilannya tetap sama. Contoh: Text, Icon.
   Stateful Widget: Widget yang bisa berubah-ubah saat aplikasi jalan, biasanya merespon input atau data yang update. Contoh: ListView yang datanya dinamis.

2. Widget yang Dipakai di Proyek Ini
   Scaffold: Kerangka utama layar.
   AppBar: Header di atas layar.
   Padding: Tambahan jarak antar widget.
   Column & Row: Menyusun widget secara vertikal dan horizontal.
   GridView.count: Membuat tampilan grid dengan kolom yang sudah diatur (3 kolom).
   Material & InkWell: Bikin efek klik pada item.
   Card: Bikin box dengan bayangan.
   SnackBar: Menampilkan pesan sementara di bawah layar.

3. Fungsi setState()
   Dipakai di Stateful Widget untuk memberi tahu Flutter kalau ada yang berubah di tampilan, jadi dia bakal di-refresh. Misalnya, kalau kita update data atau status login, setState() bikin tampilan menyesuaikan perubahan itu.

4. const vs. final
   const: Nilainya harus sudah pasti sejak awal (compile time), nggak bisa diubah.
   final: Nilainya baru ditentukan saat runtime, tapi setelah di-set nggak bisa diubah lagi.

5. 1. Membuat Flutter baru :
      Pasti pertama liat tutorial kemaren cara buat projek flutter baru
   2. Membuat Tombol Sederhana :
      Tombol nya lihat kaya di tutorial lalu sesuaiin dengan yang kita mau
   3. Mengubah Warna
      Pertama, tambahin field color di class ItemHomepage trus sesuaiin pada ItemCard
      Trus, pilih warna yang kita mau
      Trus, gunain deh item.color jadi warna bg dari box 
