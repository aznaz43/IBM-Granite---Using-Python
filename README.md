# IBM-Garanite---Using-Python

# Pemanfaatan IBM Granite untuk Analisis Review Restaurant dan Strategi Peningkatan Layanan

Proyek Capstone IBM SkillBuild
Dataset yang digunakan :  https://www.kaggle.com/datasets/moazeldsokyx/restaurant-reviews

# Latar Belakang
Dalam era digital saat ini, ulasan pelanggan memiliki peran yang sangat penting dalam membentuk persepsi dan keputusan konsumen. Sebelum memilih restoran, sebagian besar pelanggan mencari informasi dari platform online seperti Google Review media sosial untuk memastikan kualitas makanan, pelayanan, kebersihan, serta harga. Ulasan ini menjadi indikator kepuasan pelanggan sekaligus sarana evaluasi bagi pemilik usaha.
Analisis terhadap review pelanggan tidak hanya bermanfaat untuk memahami kepuasan konsumen, tetapi juga dapat digunakan untuk mengidentifikasi kelebihan dan kekurangan restoran. Dengan melakukan analisis sentimen dan kategorisasi aspek (seperti pelaynan, harga, makanan), pemilik restoran dapat mengambil keputusan strategis untuk meningkatkan kualitas layanan dan produk yang ditawarkan.
Oleh karena itu, analisis ulasan restoran dapat memberikan wawasan mendalam terkait preferensi konsumen, pola perilaku, serta faktor yang memengaruhi kepuasan pelanggan, yang pada akhirnya akan membantu meningkatkan daya saing bisnis di industri kuliner.

#Tujuan Proyek
1. Mengklasifikasikan data ulasan restoran berdasarkan sentiment positif dan negative atau berdasarkan kategori pelayanan, makanan, dan harga.
2.	Melakukan summarization terhadap ulasan untuk mendapatkan informasi inti yang mewakili pendapat mayoraitas pelanggan.
3.	Menyediakan insight berbasis data untuk membantu pemilik restoran dalam meningkatkan kualitas layanan dan pengalaman pelanggan.

#Proses Analisis
1. Memuat data
   - Dataset yang digunakan dari kaggla berisi 2.220 ulasan pelanggan restoran.
   - Untuk keperluan eksperimen, diambil 25 sampel ulasan pelanggan, mengingat     model IBM Granite memiliki batasan jumlah token per permintaan.
2. Pembersihan Data (Data Cleaning)
   - Melekukan pemeriksaan trhadap data kosong(missing value) untuk memastikan kualitas data.
3. Klasifikasi Data dengan IBM Granite
   - Model yang digunakan : ibm-granite/granite-3.3-8b-instruct
   - Proses klasifikasi untuk melakukan pwngwlompokkan ulasan ke dalam kategori sentimen positf, negatif, netral atau kategori tertentu yaitu pelayanan, makanan, dan harga.
4. Summarisasi Data dengan IBM Granite
   - Melakukan peringkasan untuk mengekstrak inti dari ulaan pelanggan
5. Visualisasi Data
   - Untuk mempermudah pemahaman hasil analisis
  
#Kesimpulan
Berdasarkan analisis terhadap 25 ulasan pelanggan restoran menggunakan IBM Granite untuk klasifikasi sentimen dan summarisasi, diperoleh hasil sebagai berikut :
1. Distribusi Sentimen Keseluruhan
   - Negatif : 12 ulasan
   - Positif : 10 ulasan
   - Netral : 3 ulasan
2. Distribusi Berdasarkan Kategori
   - Pelayanan : 3 ulasan positif
     menunjukkan apresisi terhadap pelayanan restoran, namun masih ada keluhan untuk aspek tersebut.
   - Makanan : 6 ulasan positif
     pelanggan mengapresiasi makanan yang disajikan oleh restoran, namun masih memerlukan peningkatan di beberapa aspek
   - Harga : 1 ulasan positif
     sebagaian pelanggan masih menilai harga yang belum sesuai atau terlalu 
3. Summarisasi
   - Ulasan keseluruhan : beberapa pelanggan memuji suasana restoran, pilihan menu, dan hidangan tertentu seperti Cape Cod Ravioli
   - Kategori Makanan : kualitas makanan yang tidak konsisten, dengan keluhan terkait rasa, tekstur, kualitas bahan, dan masalah kebersihan.
   - Kategori Pelayanan : pelayanan yang diberikan cenderung tidak konsisten, ada yang cepat dan ramha, ada yang lambat dan tidak melayani pelangga dengan ramah.
   - Kategori Harga : sebgaian besar pelanggan mengganggap harga terlalu mahal dan tidak sebanding dengan kualitas makanan yang dihidangkan. 

"Restoran mendapatkan ulasan campuran dengan keunggulan pada suasana dan menu tertentu, namun memiliki kelemahan signifikan pada kualitas makananan, konsistensi pelayanan, dan harga. Pihak restoran perlu fokus melakukan penignkatan kualitas makanan, pelayanan serta mengvaluasi harga untuk meniingkatkan kualitas agar pelanggan kembali ke restoran. "

#Saran
1. Memperbaiki Kualitas Mananan
   Memastikan bahan yang digunakan segar dan berkualitas. Menerapkan prosedur kebersihan yang ketat di dapur untuk menghindari keluhan terkait keberihan pada makanan.
2. Memperbaiki Layanan Pelanggan
   Melakukan pelatihan pada staf dalam melayani pelanggan agar lebih responsif, ramah, dan profesional.
3. Menyesuaikan Harga
   Mempertimbangkan untuk menyesuaikan harga dengan kualitas makanan dan pelayanan yang diberikan, sehingga pelanggan merasa mendapatkan nilai yang sepadan dengan biaya yang dikeluarkan
4. Pemanfaatan Analisis Data Berkelanjutan
   Melakukan analisis rutin agar dapat memantau perkembangan tren kepuaan pelanggan dan melakukan perbaikan yang diperlukan.
   


