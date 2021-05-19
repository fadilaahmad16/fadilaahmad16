<h1 align='center'> Dashboard Informasi Indeks Pembangunan Manusia Di Indonesia Tahun 2016-2020</h1>

<br></br>

## Pendahuluan
Indeks Pembangunan Manusia (IPM) atau _Human Development Index_ (HDI) adalah pengukuran perbandingan dari harapan hidup, melek huruf, pendidikan, dan standar hidup pada suatu wilayah. Indeks Pembangunan Manusia (IPM) diperkenalkan oleh _United Nations Development Programme_ (UNDP) pada tahun 1990 dan dipublikasikan secara berkala dalam laporan tahunan _Human Development Report_ (HDR).

IPM dibentuk oleh tiga dimensi dasar :
* Umur panjang dan hidup sehat
* Pengetahuan
* Standar hidup layak

Cara menghitung IPM :
- Dimensi Kesehatan
<br></br>
   <a href="https://www.codecogs.com/eqnedit.php?latex=I_{kesehatan}=&space;\frac{AHH-&space;AHH_{min}}{AHH_{maks}-&space;AHH_{min}}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?I_{kesehatan}=&space;\frac{AHH-&space;AHH_{min}}{AHH_{maks}-&space;AHH_{min}}" title="I_{kesehatan}= \frac{AHH- AHH_{min}}{AHH_{maks}- AHH_{min}}" /></a>
  
- Dimensi Pendidikan
<br></br>
   <a href="https://www.codecogs.com/eqnedit.php?latex=I_{HLS}=&space;\frac{HLS-&space;HLS_{min}}{HLS_{maks}-&space;HLS_{min}}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?I_{HLS}=&space;\frac{HLS-&space;HLS_{min}}{HLS_{maks}-&space;HLS_{min}}" title="I_{HLS}= \frac{HLS- HLS_{min}}{HLS_{maks}- HLS_{min}}" /></a>
<br></br>
   <a href="https://www.codecogs.com/eqnedit.php?latex=I_{RLS}=&space;\frac{RLS-&space;RLS_{min}}{RLS_{maks}-&space;RLS_{min}}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?I_{RLS}=&space;\frac{RLS-&space;RLS_{min}}{RLS_{maks}-&space;RLS_{min}}" title="I_{RLS}= \frac{RLS- RLS_{min}}{RLS_{maks}- RLS_{min}}" /></a>
<br></br>
   <a href="https://www.codecogs.com/eqnedit.php?latex=I_{pendidikan}=\frac{I{HLS}-&space;I_{RLS}}{2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?I_{pendidikan}=\frac{I{HLS}-&space;I_{RLS}}{2}" title="I_{pendidikan}=\frac{I{HLS}- I_{RLS}}{2}" /></a>

- Dimensi Pengeluaran
<br></br>
   <a href="https://www.codecogs.com/eqnedit.php?latex=I_{pengeluaran}=&space;\frac{ln(pengeluaran)-&space;ln(pengeluaran_{min})}{ln(pengeluaran_{maks})-&space;ln(pengeluaran_{min})}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?I_{pengeluaran}=&space;\frac{ln(pengeluaran)-&space;ln(pengeluaran_{min})}{ln(pengeluaran_{maks})-&space;ln(pengeluaran_{min})}" title="I_{pengeluaran}= \frac{ln(pengeluaran)- ln(pengeluaran_{min})}{ln(pengeluaran_{maks})- ln(pengeluaran_{min})}" /></a>
   
IPM dihitung sebagai rata-rata geometrik dari indeks kesehatan, pendidikan, dan pengeluaran.
<br></br>
   <a href="https://www.codecogs.com/eqnedit.php?latex=IPM=\sqrt[3]{I_{kesehatan}\times&space;I_{pendidikan}\times&space;I_{pengeluaran}&space;}&space;\times&space;100" target="_blank"><img src="https://latex.codecogs.com/gif.latex?IPM=\sqrt[3]{I_{kesehatan}\times&space;I_{pendidikan}\times&space;I_{pengeluaran}&space;}&space;\times&space;100" title="IPM=\sqrt[3]{I_{kesehatan}\times I_{pendidikan}\times I_{pengeluaran} } \times 100" /></a>

Manfaat yang diperolah dari IPM :
<ol>
  <li>IPM merupakan indikator penting untuk mengukur keberhasilan dalam upaya membangun kualitas hidup manusia (masyarakat/penduduk).</li>
  <li>IPM dapat menentukan peringkat atau level pembangunan suatu wilayah/negara.</li>
  <li>Bagi Indonesia, IPM merupakan data strategis karena selain sebagai ukuran kinerja Pemerintah, IPM juga digunakan sebagai salah satu alokator penentuan Dana Alokasi Umum (DAU).</li>
</ol>

## Latar Belakang
Untuk melihat perkembangan pembangunan di suatu negara banyak sekali indikatornya. Salah satu yang bisa digunakan adalah Indeks Pembangunan Manusia (IPM). Di Indonesia indikator ini juga digunakan untuk mengevaluasi kinerja pemerintah dan sebagai sasaran target pembangunan nasional.



## Data
Data yang digunakan dalam pembuatan Dashboard Informasi Indeks Pembangunan Manusia di Indonesia Tahun 2016-2020 diperoleh dari situs resmi Badan Pusat Statistik (BPS). Data yang diperoleh dari website tersebut berupa file excel untuk beberapa tahun yang kemudian digabung menjadi satu dari tahun 2016 - 2020. Data-data tersebut antara lain :
* [Indeks Pembangunan Manusia](https://bps.go.id/indicator/26/413/1/-metode-baru-indeks-pembangunan-manusia.html)
* [Umur Harapan Hidup Saat Lahir](https://bps.go.id/indicator/26/414/1/-metode-baru-umur-harapan-hidup-saat-lahir-uhh-.html)
* [Harapan Lama Sekolah](https://bps.go.id/indicator/26/417/1/-metode-baru-harapan-lama-sekolah.html)
* [Rata-Rata Lama Sekolah](https://bps.go.id/indicator/26/415/1/-metode-baru-rata-rata-lama-sekolah.html)
* [Pengeluaran Perkapita Disesuaikan](https://bps.go.id/indicator/26/416/1/-metode-baru-pengeluaran-per-kapita-disesuaikan.html)

Dataset memiliki 6 kolom berupa :
- `Provinsi/Kabupten/Kota`: Keterangan masing-masing wilayah di Indoensia baik itu tingkat provinsi, kabupaten, maupun kota.
- `Tahun [5 kolom]`: Isian data dari masing-masing dimensi untuk tahun 2016, 2017, 2018, 2019, dan 2020.

Contoh :
| `Provinsi/Kabupaten/Kota`  | `2020` | `2019` | `2018` | `2017` | `2016` |
| ------------------------ | ---- | ---- | ---- | ---- | ---- |
| ***Aceh***               | 9492 | 9603 | 9186 | 8957 | 8768 |
| Simeulue                 | 7085 | 7210 | 6824 | 6676 | 6542 |
| Aceh Singkil             | 8707 | 8715 | 8506 | 8230 | 8068 |
| Aceh Selatan             | 8089 | 8187 | 7891 | 7567 | 7397 |
| ............             | .... | .... | .... | .... | .... |

_Data tersebut dapat didownload pada folder [Dataset](https://github.com/fadilaahmad16/fadilaahmad16/tree/main/Dataset)_
