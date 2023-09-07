# Capstone2_airbnb

Novaldi Halomoan
Capstone 2: Exploratory Data Analisis
Dataset: airBNB bangkok dataset.

Jumlah total wisatawan yang datang ke Bangkok mencapai angka luar biasa sebesar 18.8 juta pengunjung. Dengan angka ini, Bangkok berhasil melampaui kota-kota destinasi wisata terkemuka lainnya, seperti Paris yang mencatat 11.6 juta pengunjung dan Dubai dengan 6.1 juta pengunjung.
Mayoritas wisatawan di Bangkok adalah turis lokal, mencapai 54.3% dari total jumlah wisatawan.
Sisanya, sekitar 45.7%, adalah turis mancanegara. Bangkok merupakan destinasi nomor 1 di dunia untuk wisatawan pada tahun 2023. Dengan sebagian besar turis adalah turis mancanegara, hal ini menunjukkan adanya kebutuhan besar akan akomodasi penginapan. Bangkok juga menjadi kota yang paling banyak dicari di Airbnb, menandakan popularitasnya sebagai tujuan wisata yang terus berkembang di platform airbnb. Terlihat bahwa Bangkok mengalami pertumbuhan pariwisata yang signifikan, sementara Airbnb memiliki kehadiran yang kuat sebagai platform akomodasi di kota tersebut. Bagaimana Airbnb dapat menjaga posisinya dalam konteks ini? Dalam konteks strategi bisnis, jika suatu produk ingin tetap bertahan di pasar yang sudah dikuasai, maka menurut saya strategi yang dapat digunakan adalah strategi penetrasi pasar. Berdasarkan data yang saya peroleh dan analisis yang telah dilakukan, beberapa aspek yang dapat dioptimalkan adalah produk, harga, dan lokasi. Oleh karena itu, pernyataan permasalahannya dapat dirumuskan sebagai berikut: "Optimisasi atribut Airbnb dengan mempertimbangkan potensi industri di Bangkok", dengan fokus utama pada peningkatan produk, penetapan harga, dan pemilihan lokasi.

Sebelum masuk ke data analisis lebih lanjut, saya melakukan data cleaning dengan melihat kolom yang kosong, nilai yang kosong dan juga outliers. Selanjutnya saya akan membahas data analisis secara umum. kita mulai dengan berbicara tentang beberapa wawasan umum dari data yang telah kita peroleh. 

-Distrik,
Ada 50 distrik di kota Bangkok ini. Mari kita periksa beberapa distrik yang menarik perhatian:
Vadhana: Merupakan distrik pusat dengan ekonomi maju di Bangkok.
Khlong Tei: Merupakan distrik kelas atas yang menjadi salah satu daerah paling padat penduduknya di Bangkok.
Ratchatewi: Sebuah lokasi yang menjadi pusat transportasi umum di kota ini.
Phra Nakon: Dikenal sebagai distrik dengan kekayaan budaya dan tujuan pariwisata yang kental.
Phartum Wan: Merupakan distrik paling mewah di Bangkok.

- Tipe room_type,
Entire Home: Jenis ini memungkinkan pengguna untuk menyewa seluruh bangunan atau unit, yang sangat cocok bagi mereka yang bepergian bersama kelompok atau keluarga.

Hotel: Pengguna dapat memesan hotel melalui platform Airbnb, memberikan fleksibilitas tambahan dalam pilihan akomodasi.

Private Room: Jenis ini umumnya cocok untuk satu pengguna atau pasangan yang mencari akomodasi yang lebih pribadi.

Shared Room: Tipe ini cocok bagi pengguna yang berpetualang sendirian dan memiliki anggaran terbatas.

Namun, berdasarkan data yang ada, sebanyak 55.47% tipe Airbnb yang tersedia adalah tipe "Entire Home", menunjukkan bahwa tipe ini merupakan favorit di antara pengguna. Sementara itu, tipe "Shared Room" hanya mencapai 3.04% dari total, yang menandakan bahwa tipe ini kurang diminati oleh pengguna.

- Tipe minimum night,
ada dua tipe tinggal (stays) yang relevan, yaitu "shorter stay" (kurang dari 28 hari) dan "long-term" (28 hari atau lebih). Dari data yang saya peroleh, terlihat bahwa sekitar 7000 listing, atau lebih dari 7000 properti, hanya tersedia untuk pemesanan dengan durasi satu hari. Ini menunjukkan tingginya permintaan untuk tinggal singkat (short-term) di Bangkok. Lebih rinci, porsi listing short-term mencapai 81.2%, sementara listing long-term hanya sebesar 18%.

Data ini menggambarkan tingginya permintaan untuk akomodasi jangka pendek di kota ini. Penting juga dicatat bahwa sekitar 18% dari listing menawarkan opsi long-term, yang mengindikasikan bahwa beberapa tuan rumah telah mengadopsi strategi diversifikasi untuk menanggapi permintaan yang beragam di pasar ini.

Selanjutnya kita akan bahas rekomendasi dari Exploratory Data Analysis untuk optimisasi produk, harga dan lokasi sesuai dengan tujuan ke pernyataan masalah.

1. Product
2. 
- Tipe kamar.
ita akan melakukan analisis yang lebih komprehensif tentang optimasi atribut produk. Dari data yang telah kita peroleh, tipe "Entire" adalah yang paling populer baik untuk short-term maupun long-term stays. Namun, sebaliknya, tipe "Shared Room" adalah yang paling tidak populer untuk kedua jenis tinggal tersebut.

- Rekomendasi,
Encourage Host Baru untuk Investasi di Tipe "Entire": Airbnb dapat menggencarkan upaya untuk mendorong host baru untuk berinvestasi di tipe "Entire," namun dengan memberikan nilai jual yang unik dan istimewa. Ini dapat dilakukan melalui panduan atau insentif khusus bagi host yang ingin menawarkan tipe ini.

Meningkatkan Pengalaman Host Tipe "Shared Room": Airbnb juga dapat meningkatkan pengalaman bagi host yang menawarkan tipe "Shared Room" dengan mendorong mereka untuk melakukan perbaikan pada fasilitas yang mereka tawarkan. Ini dapat melibatkan bimbingan dan saran tentang cara meningkatkan daya tarik bagi pengguna, sehingga meningkatkan permintaan untuk tipe ini.

Dengan mengambil tindakan ini, Airbnb dapat lebih efektif dalam mengoptimalkan pengalaman pengguna dan diversifikasi tipe akomodasi yang mereka tawarkan di Bangkok.

2. Price
3. 
kita akan mendalami strategi optimisasi harga. Dari data yang telah kita analisis, terlihat bahwa tipe "Entire," "Private," dan "Hotel" memiliki median harga tertinggi di daerah Parthum Wan. Hal ini sesuai dengan profil mahalnya distrik Parthum Wan yang telah kita bahas sebelumnya. Sementara itu, tipe "Shared Room" memiliki median harga tertinggi di Chatuchak, yang dikenal sebagai distrik dengan warisan budaya yang kaya.
Pertanyaannya adalah, bagaimana kita dapat merumuskan strategi optimisasi harga? Mari kita perhatikan contoh yang lebih rinci dalam rekomendasi berikutnya untuk menjawab pertanyaan ini

- Rekomendasi,
Dalam konteks Parthum Wan, terdapat kasus outlier atau properti dengan harga yang sangat tinggi, yang mungkin dapat dianggap sebagai "overpriced." Penting untuk dicatat bahwa Airbnb tidak memiliki kontrol atas penetapan harga oleh host. Oleh karena itu, rekomendasi yang diajukan adalah untuk Airbnb memberikan insentif berupa diskon kepada pengguna yang ingin memesan properti dengan harga yang dinilai sebagai "overpriced." Meskipun hal ini mungkin mengakibatkan biaya tambahan bagi Airbnb, namun diharapkan bahwa dengan diskon ini, properti yang awalnya dianggap overpriced akan memiliki daya tarik lebih besar di pasaran. Ini sejalan dengan filosofi bahwa dalam konteks ini, kuantitas dapat diutamakan demi menjaga kualitas.

Lalu bagimana jika kita melihat underpriced seperti grafik yang ada disini, Rekomendasi saya adalah airbnb bisa mengencourage host yang memiliki underpriced listing untuk menggunakan airbnb plus. Karena airbnb plus bisa memberikan informasi terkait standar atau range harga yang ada di sekitar wilayah host-listing tersebut

3. Lokasi
4. 
Saya akan membahas strategi optimasi lokasi. Untuk melakukan analisis ini, saya melakukan penelitian melalui data eksternal dengan mencari 10 website yang memiliki tema "best places to visit in Bangkok." Dari sumber-sumber tersebut, saya menyaring lokasi-lokasi yang sering disebutkan. Hasilnya dapat dilihat dalam tabel yang mencakup daftar lokasi beserta distriknya, serta visualisasi lokasi-lokasi tersebut pada peta geospatial. Dengan menggunakan data ini, saya dapat mengidentifikasi lokasi-lokasi yang paling diminati oleh wisatawan dan menggunakannya sebagai dasar untuk rekomendasi strategi optimasi lokasi di Airbnb. Lalu dari data yang telah saya kumpulkan dari berbagai website, saya berhasil menyusun daftar distrik yang sering disebutkan sebagai destinasi populer di Bangkok. Namun, saya juga melakukan perbandingan dengan data persebaran Airbnb di Bangkok dan menemukan bahwa beberapa distrik seperti Bangkok Yai, Dusit, dan Samphanthawong, yang termasuk dalam daftar dari website tersebut, tidak masuk dalam 10 besar distrik dengan jumlah listing Airbnb terbanyak di Bangkok.

- Rekomendasi,
untuk menjalankan kerjasama (partnership) dengan host potensial di ketiga distrik tersebut. Dengan melakukan kerjasama ini, Airbnb dapat meningkatkan penetrasi dan kualitas penawaran akomodasi di daerah-daerah tersebut, sehingga dapat menarik lebih banyak wisatawan ke distrik-distrik yang sebelumnya kurang diminati. Hal ini dapat menguntungkan baik bagi Airbnb maupun bagi komunitas lokal di daerah-daerah tersebut.
