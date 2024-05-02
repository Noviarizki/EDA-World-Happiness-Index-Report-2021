# Exploratory Data Analysis on World Happiness Index Report 2021

## Pendahuluan
Kebahagiaan adalah keadaan emosional yang ditandai dengan perasaan senang, puas, dan terpenuhi. Meskipun kebahagiaan memiliki banyak definisi yang berbeda, kebahagiaan sering  digambarkan sebagai sesuatu yang melibatkan emosi positif dan kepuasan hidup.

Laporan Kebahagiaan Dunia adalah survei penting mengenai kondisi kebahagiaan global. Laporan ini memberi peringkat kepada 149 negara berdasarkan tingkat kebahagiaan yang dirasakan warganya. Peringkat didasarkan pada sejumlah faktor termasuk pertumbuhan ekonomi, dukungan sosial, harapan hidup, kebebasan untuk membuat pilihan hidup, kedermawanan, dan persepsi tentang korupsi. Laporan ini dirilis setiap tahun oleh Perserikatan Bangsa-Bangsa.

Dalam analisis ini akan memvisualisasikan data dari World Happiness Report 2021 menggunakan library data science Python seperti Pandas, numpy, Matplotlib, dan Seaborn. Dengan menampilkan plot dan grafik bertujuan untuk membantu memahami data dan memeberikan wawasan.

## Dataset
Dataset yang digunakan dalam analisis ini adalah World Happiness Report 2021. Dataset ini berisi 20 kolom dan 149 baris, dengan setiap baris mewakili sebuah negara dan setiap kolom mewakili variabel yang terkait dengan kebahagiaan.

- **Ladder score**: skor kebahagiaan atau kesejahteraan subjektif
- **Logged GDP Per capita**: Rangkaian PDB per kapita dari tahun 2021menggunakan perkiraan pertumbuhan PDB riil di setiap negara 
- **Social Support**: dukungan sosial mengacu pada bantuan atau dukungan yang diberikan oleh jaringan sosial kepada seseorang
- **Healthy life expectancy**: angka harapan hidup sehat adalah rata-rata usia hidup dalam kondisi sehat
- **Freedom to make life choice**: kebebasan untuk membuat pilihan hidup
- **Generosity**: kedermawanan dari respons terhadap pertanyaan GWP “Apakah Anda menyumbangkan uang ke badan amal dalam sebulan terakhir?” pada PDB per kapita
- **Perceptions of corruption**: Ukurannya adalah rata-rata nasional dari respons survei terhadap dua pertanyaan dalam GWP: “Apakah korupsi tersebar luas di seluruh pemerintahan atau tidak” dan “Apakah korupsi tersebar luas di dunia usaha atau tidak?”
- **Ladder score in dystopia**: memiliki nilai yang sama dengan rata-rata nasional terendah di dunia.  Dystopia adalah negara imajiner yang memiliki penduduk paling tidak bahagia di dunia

## Insight
1. Bahwa skor kebahagiaan paling dipengaruhi oleh PDB per kapita, dukungan sosial, angka harapan hidup, kebebasan untuk membuat pilihan hidup.
2. Western Europe menjadi wilayah dengan kebahagiaan tertinggi dimana memberikan kontribusi tertinggi terhadap PDB dunia, memiliki angka harapan hidup diatas 70 tahun serta kebebasan untuk menentukan pilihan hidup yang tinggi.
3. Wilayah dengan kebahagiaan rendah berada di South Asia, Latin America and Caribbean, Middle East and North Africa, Sub-Saharan Africa.
4. Meskipun Wilayah Southeast Asia memiliki skor kebagiaan relatif lebih rendah tetapi memiliki kebebasan untuk membuat pilihan hidup tinggi yaitu lebih dari 0.8 
5. 10 negara paling bahagia memiliki angka harapan hidup diatas 70 tahun yaitu Finland, Denmark, Switzerland, Iceland, Netherlands, Norway, Sweden, Luxembourg, New Zealand, Austria.
6. 10 negara paling tidak bahagia memiliki angka harapan hidup kurang dari 60 tahun yaitu Burundi, Yemen, Tanzania, Haiti, Malawi, Lesotho, Botswana, Rwanda, Zimbabwe, Afghanistan.
