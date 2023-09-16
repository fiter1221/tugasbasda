# tugasbasda
# tabel direktur
![image](https://github.com/fiter1221/tugasbasda/assets/145202407/849ce264-6ad1-4da1-96c5-fb8919f76ca5)
![image](https://github.com/fiter1221/tugasbasda/assets/145202407/c493e324-29d1-427c-afad-d14bfc0a964e)
  Tabel "direktur" ini bisa digunakan untuk menyimpan informasi tentang direktur-direktur yang terkait dengan suatu organisasi atau entitas. Data ini dapat digunakan dalam berbagai konteks, seperti manajemen organisasi, pencatatan kepemimpinan, atau pelaporan internal.Pentingnya kolom "Id_direktur" sebagai primary key adalah untuk memastikan integritas data, memungkinkan pencarian dan pengurutan data yang efisien, serta memungkinkan hubungan antara tabel "direktur" dengan tabel lainnya dalam basis data yang lebih besar jika diperlukan.
# tabel cs
![image](https://github.com/fiter1221/tugasbasda/assets/145202407/ebb814ba-bf74-4932-95eb-ce40636cd03c)
![image](https://github.com/fiter1221/tugasbasda/assets/145202407/3953e76f-052e-4baa-b75b-19147d5ec7f5)
  Tabel "cs" ini mungkin digunakan untuk menyimpan informasi tentang customer service dalam suatu organisasi atau entitas. Kolom "Id_cs" sebagai primary key memastikan bahwa setiap entri dalam tabel memiliki identifikasi unik, sementara kolom "Id_direktur" sebagai foreign key memungkinkan untuk menghubungkan setiap customer service dengan direktur yang bersangkutan, menciptakan hubungan antar tabel yang berguna dalam basis data yang lebih besar.Dengan tabel ini, Anda dapat melacak informasi tentang customer service, hubungan mereka dengan direktur, dan detail personal seperti nama mereka.
# tabel nasabah
![image](https://github.com/fiter1221/tugasbasda/assets/145202407/114a2ca8-f31e-499c-827f-04c664b7b036)
![image](https://github.com/fiter1221/tugasbasda/assets/145202407/1147b91a-0846-4c3c-a509-357cb8389053)
  Tabel "nasabah" ini mungkin digunakan untuk menyimpan informasi tentang nasabah dalam suatu lembaga keuangan, seperti bank. Kolom "No_rek" sebagai primary key memastikan bahwa setiap entri dalam tabel memiliki identifikasi unik. Kolom "Id_cs" sebagai foreign key memungkinkan untuk menghubungkan nasabah dengan customer service yang melayani mereka, sementara kolom lainnya berisi detail tentang nasabah seperti nama, status pernikahan, pekerjaan, nomor KTP, dan tanggal lahir.
# tabel teller 
![image](https://github.com/fiter1221/tugasbasda/assets/145202407/e1b17f2b-1cf4-4c3b-81bd-407b78f0413c)
![image](https://github.com/fiter1221/tugasbasda/assets/145202407/bded971e-4994-4651-9496-fa11cd958261)
  Tabel "teller" ini mungkin digunakan dalam konteks lembaga keuangan, seperti bank atau kantor cabang, untuk melacak informasi tentang teller yang bertugas. Kolom "Id_teller" sebagai primary key memastikan bahwa setiap entri dalam tabel memiliki identifikasi unik, sementara kolom "No_rek" sebagai foreign key memungkinkan untuk menghubungkan teller dengan nasabah yang mereka layani jika diperlukan. Selain itu, kolom "Nama_teller" berisi informasi tentang nama teller tersebut.
# tabel saldo tabungan
![image](https://github.com/fiter1221/tugasbasda/assets/145202407/63de57f0-f00d-4eea-a51c-7e9c4ad36495)
![image](https://github.com/fiter1221/tugasbasda/assets/145202407/13320c39-262e-4d66-ae73-e8ad05766c50)
  Tabel "saldo_tabungan" ini mungkin digunakan untuk mencatat semua transaksi yang terkait dengan saldo tabungan dalam suatu lembaga keuangan, seperti bank. Kolom "Kode_transaksi" sebagai primary key memastikan bahwa setiap entri dalam tabel memiliki identifikasi unik. Kolom "Id_teller" dan "Id_direktur" sebagai foreign key memungkinkan untuk menghubungkan transaksi dengan teller dan direktur yang terkait dengan transaksi tersebut. Selain itu, kolom "Tanggal" berisi informasi tentang tanggal kapan transaksi tersebut terjadi. Tabel ini akan berguna dalam mencatat dan melacak aktivitas perbankan.
