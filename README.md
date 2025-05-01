# Big Data dan Data Lakehouse A
## Deskripsi Kasus

Sebuah perusahaan investasi ingin memahami pola dan volatilitas harga dari beberapa mata uang kripto utama untuk merancang strategi investasi yang lebih efektif. Mereka menyediakan data historis harga harian dari beberapa kripto, termasuk Bitcoin (BTC), Ethereum (ETH), dan masih banyak lagi.
Dataset tersedia dalam format CSV dengan kolom: Date, Open, High, Low, Close, Volume, dan Market Cap.

## Tugas Mahasiswa
### Analisis Tren Harga

### Hitung rata-rata harga penutupan (Close) bulanan untuk setiap kripto.
Mengambil 20 Bulan Awal Data
Monthly Average Closing Price:


![image](https://github.com/user-attachments/assets/c427795e-0b13-42e5-aafa-af0176a584fc)



### Identifikasi bulan dengan rata-rata harga penutupan tertinggi dan terendah untuk setiap kripto.
Months with Highest Average Closing Price:


![image](https://github.com/user-attachments/assets/7d7cd1a6-3e66-4490-b1f7-900a25e9bd34)



Months with Lowest Average Closing Price:


![image](https://github.com/user-attachments/assets/0d6319f9-109b-4010-803d-9fedcb7b56c5)



### Analisis Volatilitas

### Hitung volatilitas harian sebagai selisih antara High dan Low.

### Hitung rata-rata volatilitas bulanan untuk setiap kripto.
Mengambil 20 Row Data
Monthly Average Volatility:

![image](https://github.com/user-attachments/assets/e4147045-feaa-4d8e-9aac-14e210bdcc44)


### Identifikasi bulan dengan volatilitas tertinggi dan terendah untuk setiap kripto.

Months with Highest Volatility:

![image](https://github.com/user-attachments/assets/d3f9bf29-4a61-4794-a72b-ad57ce9554b2)


Months with Lowest Volatility:

![image](https://github.com/user-attachments/assets/f126b767-2c46-44e3-a43d-205c14f9b4ff)



### Hitung persentase kenaikan masing masing kripto setiap tahunnya
Mengambil 20 Row Data
Yearly Growth Percentage:


![image](https://github.com/user-attachments/assets/60ed9dd2-c72e-41fd-9428-863fa1e43a0d)


![image](https://github.com/user-attachments/assets/2fbc6f9d-75a5-442a-a412-b83bf09ed203)


### Perbandingan Antar Kripto



### Bandingkan tren harga dan volatilitas antara 5 kripto yang dipilih.
![image](https://github.com/user-attachments/assets/d55c8291-24af-4ab4-95c5-aa828aca6b06)


### Identifikasi kripto dengan tren kenaikan harga paling konsisten.
Kripto dengan kenaikan harga paling konsisten merupakan **$BTC**

Crypto with Most Consistent Growth: 

![image](https://github.com/user-attachments/assets/7387a2c8-f5cf-46b5-9e19-e6a30dafd856)



### Identifikasi kripto dengan volatilitas tertinggi secara keseluruhan.
Jika Dibandingkan dengan aset kripto lainnya, berikut merupakan kripto dengan volatilitas tertinggi secara keseluruhan: 

![image](https://github.com/user-attachments/assets/df3af153-b09b-4f48-9fe7-56b73366005e)


### Interpretasi dan Rekomendasi

Rekomendasi investasi berdasalkan hasil interpretasi yang di dapatkan: 


**BTC Analysis:**
- Average yearly growth: 241.55%
- Growth range: -72.60% to 1318.02%
- Average volatility: 414.84

**ETH Analysis:**
- Average yearly growth: 1502.23%
- Growth range: -82.74% to 9159.42%
- Average volatility: 34.04

**DOGE Analysis:**
- Average yearly growth: 886.53%
- Growth range: -73.67% to 4023.54%
- Average volatility: 0.00

**USD Analysis:**
- Average yearly growth: -0.10%
- Growth range: -0.94% to 0.96%
- Average volatility: 0.01

**SOL Analysis:**
- Average yearly growth: 927.42%
- Growth range: 94.50% to 1760.35%
- Average volatility: 1.55

### Berdasarkan analisis, berikan rekomendasi strategi investasi jangka pendek dan panjang untuk masing-masing kripto.
**Rekomendasi Strategi Investasi:**

**1. BTC (Bitcoin)**

**Jangka Panjang:**
Strategi: Buy and Hold (Beli dan Tahan) bagi investor dengan toleransi risiko tinggi.
Alasan: Rata-rata pertumbuhan tahunan yang kuat (241.55%) menunjukkan potensi apresiasi nilai dalam jangka panjang. Namun, investor harus siap menghadapi volatilitas ekstrem dan potensi penurunan signifikan (hingga -72.60% atau lebih dalam setahun). Cocok sebagai bagian dari portofolio yang terdiversifikasi.

**Jangka Pendek:**
Strategi: Swing Trading atau Day Trading bagi trader berpengalaman dengan toleransi risiko sangat tinggi.
Alasan: Volatilitas yang sangat tinggi (rata-rata 414.84, dan data bulanan menunjukkan fluktuasi besar) menciptakan peluang untuk mengambil keuntungan dari pergerakan harga jangka pendek. Memerlukan analisis teknikal yang kuat, manajemen risiko ketat, dan pemantauan pasar aktif. Sangat tidak disarankan untuk pemula.


**2. ETH (Ethereum)**

**Jangka Panjang:**
Strategi: Buy and Hold bagi investor dengan toleransi risiko sangat tinggi.
Alasan: Rata-rata pertumbuhan tahunan tertinggi (1502.23%) menunjukkan potensi imbalan jangka panjang yang luar biasa. Namun, ini diimbangi oleh risiko paling ekstrem (range -82.74% hingga 9159.42%). Investor harus percaya pada fundamental Ethereum (DeFi, NFT, smart contracts) dan mampu menahan gejolak pasar yang masif.

**Jangka Pendek:**
Strategi: Swing Trading atau Day Trading bagi trader sangat berpengalaman.
Alasan: Range pertumbuhan yang sangat lebar menyiratkan volatilitas ekstrem, menciptakan peluang trading jangka pendek dengan potensi keuntungan (dan kerugian) yang sangat besar. Memerlukan keahlian tinggi dan manajemen risiko yang sangat disiplin.


**3. DOGE (Dogecoin)**

**Jangka Panjang:**
Strategi: Sangat spekulatif. Hanya untuk investor dengan toleransi risiko ekstrem yang menganggapnya sebagai bagian kecil dari portofolio ("uang mainan").
Alasan: Meskipun pertumbuhan rata-rata tinggi (886.53%), nilainya sangat dipengaruhi oleh sentimen sosial media dan hype, bukan fundamental yang kuat. Risiko penurunan sangat tinggi (-73.67% dalam setahun). Masa depannya sangat tidak pasti.

**Jangka Pendek:**
Strategi: Trading berdasarkan momentum/sentimen bagi trader spekulatif.
Alasan: Harga dapat bergerak cepat berdasarkan berita atau tren media sosial. Trader dapat mencoba memanfaatkan lonjakan harga jangka pendek ini, tetapi sangat berisiko dan mirip perjudian.

**4. USD (Diasumsikan Stablecoin)**

**Jangka Panjang:**
Strategi: Hold (Tahan) untuk stabilitas modal atau sebagai safe haven sementara di dalam ekosistem kripto.
Alasan: Volatilitas sangat rendah dan range sempit. Bertujuan menjaga nilai mendekati 1 Dolar AS. Bukan untuk mencari keuntungan dari apresiasi harga, tetapi untuk mengurangi risiko volatilitas aset kripto lain atau menunggu peluang beli. Bisa juga digunakan untuk yield farming/staking jika platform menawarkan (di luar cakupan analisis ini).

**Jangka Pendek:**
Strategi: Digunakan sebagai alat tukar atau penyimpan nilai sementara antar transaksi kripto.
Alasan: Stabilitasnya memudahkan perhitungan dan mengurangi risiko saat keluar-masuk posisi trading aset kripto lain. Tidak cocok untuk ditradingkan demi mencari keuntungan dari pergerakan harganya sendiri.


**5. SOL (Solana)**

**Jangka Panjang:**
Strategi: Buy and Hold bagi investor dengan toleransi risiko tinggi, mungkin sedikit di bawah ETH/BTC berdasarkan data range historis ini.
Alasan: Pertumbuhan rata-rata sangat tinggi (927.42%) dan range pertumbuhan historis yang seluruhnya positif dalam data ini (94.50% hingga 1760.35%) tampak menarik. Namun, perlu diingat ini data historis dan pasar kripto tetap volatil. Cocok bagi yang percaya potensi ekosistem Solana sebagai pesaing Ethereum.

**Jangka Pendek:**
Strategi: Swing Trading bagi trader berpengalaman.
Alasan: Pertumbuhan yang signifikan dan volatilitas (meskipun angka rata-rata ringkasan rendah, range dan data bulanan menunjukkan potensi pergerakan) menciptakan peluang trading. Momentum positif historis (dalam data ini) mungkin menarik bagi trend follower, namun tetap berisiko tinggi.
