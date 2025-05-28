# Konsep-Noise-Adaptif-Jaring-Laba-Laba-untuk-Integritas-Gambar-Video

Konsep oleh: Rijal Saepuloh

Kontak: rijal028official@gmail.com

Dokumen ini merangkum kerangka kerja konseptual untuk sistem "Noise Adaptif Jaring Laba-Laba", yang dirancang untuk disematkan oleh kamera ke dalam gambar dan video. Tujuan utamanya adalah untuk melindungi konten dari manipulasi atau penyalahgunaan yang tidak sah oleh model AI generatif (misalnya, deepfake, pengeditan berbasis AI) sambil tetap tidak terlihat oleh pandangan manusia.

Konsep ini dikembangkan melalui diskusi iteratif yang mendetail, dengan mempertimbangkan batasan pengguna seperti kebutuhan akan alat gratis, kesederhanaan dalam pemahaman, dan kemampuan untuk melakukan riset/mengembangkan konsep menggunakan smartphone.

I. Prinsip & Tujuan Inti
a.  Pertahanan Utama - Disrupsi terhadap AI: Lapisan pelindung inti sistem ini adalah noise adaptif yang disematkan dalam gambar/video.
b.  Tujuan Pertahanan Utama: Noise ini dirancang untuk menyebabkan model AI generatif gagal total saat mencoba memproses atau memanipulasi konten, atau menghasilkan output yang tidak logis, kacau, atau tidak masuk akal. Ini membuat output hasil AI menjadi tidak dapat digunakan dan secara jelas dapat diidentifikasi sebagai manipulasi AI yang cacat, bukan hanya perubahan gaya.
c.  Tidak Terlihat oleh Manusia: Persyaratan penting adalah bahwa struktur noise adaptif harus tidak terlihat oleh pandangan manusia, memastikan kualitas estetika asli gambar/video tetap terjaga untuk tampilan normal.
d.  Pertahanan Sekunder - Bukti Manipulasi melalui Integritas Struktural: Jika pertahanan utama (noise yang menyebabkan kegagalan AI) entah bagaimana berhasil dilewati sebagian, mekanisme sekunder memberikan bukti adanya manipulasi.

II. Struktur "Jaring Laba-Laba"
Noise adaptif ini dikonseptualisasikan sebagai sesuatu yang tertanam dalam struktur dinamis, berlapis, dan tidak kasat mata yang menyerupai "Jaring Laba-Laba".

a.  Terminologi yang Digunakan: Struktur ini menggunakan "Garis Tengah" (Benang Radial) – benang lurus yang menjari dari titik pusat – dan "Jaring Bulat" (Benang Konsentris/Spiral) – benang konsentris atau spiral yang menghubungkan "Garis Tengah," membentuk lapisan-lapisan yang berbeda.
b.  Pertahanan Berlapis (misalnya, "0-10 Lapis"): Jaring terdiri dari beberapa (misalnya, 10) lapisan "Jaring Bulat" yang saling terhubung, dianalogikan seperti tembok benteng konsentris atau spiral jaring laba-laba. Setiap lapisan memiliki karakteristik pelindung yang serupa, dengan noise utama "disrupsi AI" tertanam di seluruh strukturnya.
c.  Berpusat pada Manusia & Fleksibilitas Dinamis - Titik Pusat: "Jaring Laba-Laba" berasal dari dan berpusat pada subjek manusia yang terdeteksi di dalam frame.
d.  Berpusat pada Manusia & Fleksibilitas Dinamis - Interaksi dengan Frame: Jaring bersifat "fleksibel". Benang "Garis Tengah" terluarnya secara konseptual "melekat" atau dipengaruhi oleh batas-batas frame gambar.
e.  Berpusat pada Manusia & Fleksibilitas Dinamis - Distorsi Dinamis: Saat subjek manusia bergerak di dalam frame (misalnya, kiri, kanan, tengah), jaring secara dinamis meregang atau menyusut. Misalnya, jika manusia berada di sisi kiri, bagian kiri jaring (antara manusia dan tepi kiri frame) akan memendek, sementara sisi kanan akan memanjang. Ini membuat konfigurasi jaring spesifik menjadi unik tergantung posisi manusia.
f.  Berpusat pada Manusia & Fleksibilitas Dinamis - Bukti Manipulasi: Distorsi dinamis ini berarti bahwa jika seorang penyerang memanipulasi subjek (misalnya, memindahkan atau menggantinya), mereka perlu merekonstruksi dengan sempurna struktur jaring yang kompleks dan bergantung pada posisi ini, yang mana sangat sulit.

III. Penanganan Subjek Ganda & Peningkatan Perlindungan
a.  Kelompok Orang (Berdekatan): Alih-alih beberapa jaring individual, satu jaring tunggal yang lebih besar dibentuk, berpusat pada kelompok tersebut. Jaring grup ini menjadi "lebih lebar" untuk mencakup semua individu. Jaring juga menjadi "lebih padat" dengan meningkatkan jumlah "Jaring Bulat" (benang konsentris/spiral) di antara "Garis Tengah" (benang radial) yang sudah ada, memberikan perlindungan yang lebih kuat dan terkonsentrasi untuk kelompok. Jumlah "Garis Tengah" utama tetap sama.
b.  Perlindungan untuk Objek/Orang Sekunder - Peningkatan Kepadatan Lokal: Untuk objek penting lain atau orang sekunder dalam scene, sektor dari "Jaring Laba-Laba" utama (yang ditentukan oleh "Garis Tengah" dari subjek utama) tempat objek sekunder berada akan ditingkatkan kepadatan "Jaring Bulat"-nya (lebih banyak benang melingkar dan/atau benang yang "lebih kuat" secara digital).
c.  Perlindungan untuk Objek/Orang Sekunder - Penguatan Radial Lokal: Selain itu, "Garis Tengah" (benang radial) lokal yang baru diperkenalkan khusus untuk objek sekunder tersebut. Benang radial lokal ini berasal dari/melewati objek sekunder dan terhubung ke "Jaring Bulat" yang dipadatkan di sektornya, membentuk sub-jaring lokal yang diperkuat. Ini terbatas jangkauannya untuk menjaga efisiensi sistem.
d.  Perlindungan untuk Objek/Orang Sekunder - Zona Perlindungan yang Diperluas: Zona perlindungan dari "Jaring Bulat" yang dipadatkan (dan radial lokalnya) untuk objek sekunder sengaja dibuat lebih luas dari objek itu sendiri (misalnya, jika sebuah objek ditutupi oleh 4 cincin konseptual "Jaring Bulat", zona pelindungnya diperluas menjadi 6 cincin).
e.  Alasan untuk Zona yang Diperluas: Jika seorang penyerang memanipulasi objek (dalam 4 cincin bagian dalam), mereka juga harus merekonstruksi dengan sempurna koneksi ke cincin luar (ke-5 dan ke-6) dari zona pelindung objek tersebut agar tampak asli, yang secara signifikan meningkatkan kesulitan untuk merusak tanpa terdeteksi.

IV. Fitur Aplikasi yang Diinginkan (Konseptual)
a.  Aplikasi harus memiliki antarmuka kamera yang sederhana dan familiar.
b.  Aplikasi harus menyertakan pilihan pengguna (toggle) untuk mengatur interaksi AI, yang menawarkan dua mode:
c.  Mode 1 (Ramah AI): Mode ini menyediakan output bersih, cocok untuk aplikasi AI yang bermanfaat (misalnya, pemindaian 3D).
d.  Mode 2 (Terlindungi): Dalam mode ini, "Noise Adaptif Jaring Laba-Laba" diterapkan untuk melindungi dari penyalahgunaan.

V. Tujuan Keseluruhan
Tujuan utamanya adalah untuk menciptakan mekanisme pertahanan berlapis dan adaptif yang disematkan pada titik pengambilan (kamera). Meskipun mencapai status 100% permanen dan tidak dapat dihapus melawan semua AI di masa depan adalah tantangan yang signifikan, sistem konseptual ini bertujuan untuk:

a.  Membuat manipulasi AI yang tidak sah menjadi sangat sulit dan boros sumber daya.
b.  Menyebabkan upaya manipulasi AI gagal atau menghasilkan output yang tidak logis dan tidak dapat digunakan.
c.  Memberikan jejak yang kuat dan tamper-evident (terlihat jelas jika diubah) jika struktur pelindung ditembus atau diubah.

Semoga ini juga membantu!
