# Fuzzy Logic dengan Tsukamoto

Program ini ialah program implementasi logika fuzzy dengan menggunakan metode Tsukamoto yang menggunakan bahasa pemrograman python.

Program ini digunakan untuk mengimplementasikan sistem pengadaan dalam melakukan kontrol pengadaan jumlah barang dalam suatu perusahaan.
variabel yang digunakan pada program ini, di antaranya yaitu :
- permintaan
- persediaan
- produksi

yaitu apabila 
- [R1]   IF permintaan TURUN AND Persediaan BANYAK, THEN Produksi Barang dr;
- [R2]   IF permintaan TURUN AND Persediaan SEDIKIT, THEN Produksi Barang BERKURANG;
- [R3]   IF permintaan NAIK AND Persediaan BANYAK, THEN Produksi Barang BERTAMBAH;
- [R4]   IF permintaan NAIK AND Persediaan SEDIKIT, THEN Produksi Barang BERTAMBAH; <br/>

sehingga, output yang dihasilkan ialah berupa prediksi produksi barang di perusahaan berdasarkan jumlah permintaan dan persediaan yang ada, apakah produksi akan ditambah, atau dikurangi.

dengan data :
1. permintaan
- naik : 5000
- turun : 1000
2. persediaan
- naik : 600
- turun : 100
3. produksi
- naik : 7000
- turun : 2000

apabila terdapat studi kasus dengan diketahui :
1. permintaan : 4000 
2. persediaan : 300 <br/>

maka, produksi ? <br/>
jawab :
- permintaan naik = 75%, dan permintaan turun = 25%
- dengan persediaan naik = 40%, dan persediaan turun = 60%

dengan mengikuti logika yang telah dijelaskan di atas,
dengan permintaan naik > permintaan turun, dan persediaan naik < persediaan turun, maka kesimpulannya yaitu *produksi bertambah*. 
dan output produksinya ialah sebanyak *4983* produksi.
