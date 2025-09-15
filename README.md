# Monetify: Transforming Photos into Art  

## Deskripsi  
Proyek ini merupakan bagian dari **Final Exam Data Modeling** pada program studi *Information System* (Even Semester 2024/2025).  
Tujuan utama dari **Monetify** adalah mengembangkan model *machine learning* berbasis **CycleGAN** yang mampu mengubah foto biasa menjadi lukisan bergaya **Claude Monet**.  

Dengan memanfaatkan teknologi AI, Monetify berusaha menjawab tantangan keterbatasan keterampilan seni dan kebutuhan akan karya digital unik, baik untuk penggunaan pribadi, konten media sosial, maupun aset NFT.  

---

## Dataset  
Dataset yang digunakan berasal dari kompetisi Kaggle:  
[I'm Something of a Painter Myself](https://www.kaggle.com/competitions/gan-getting-started/overview)  
Dataset ini juga tersedia melalui [Google Drive](https://drive.google.com/drive/folders/18vvFyLTRmM3kInPaHcjpwmwuwEel7lgM?usp=drive_link).  

**Struktur dataset**:  
- `monet_tfrec` → lukisan Monet dalam format **TFRecords**  
- `photo_tfrec` → foto biasa dalam format **TFRecords**  
- `monet_jpg` → lukisan Monet dalam format **JPEG**  
- `photo_jpg` → foto biasa dalam format **JPEG**  

*Keterangan*:  
- Format **TFRecords** digunakan untuk pemrosesan data dengan TensorFlow.  
- Format **JPEG** digunakan untuk visualisasi dan eksplorasi manual.  
- Dataset ini menyediakan pasangan data (foto ↔ Monet) yang ideal untuk melatih *CycleGAN* dalam melakukan *image-to-image translation*.  

---

## Metode  

### Business Understanding  
- **Latar Belakang**: Seni digital semakin populer di media sosial, NFT, dan metaverse. Filter AI konvensional masih terbatas.  
- **Permasalahan**: Melukis manual memerlukan keahlian tinggi, sementara software desain tidak dapat diakses semua orang. Industri kreatif juga membutuhkan aset visual yang unik.  
- **Solusi**: Monetify menghadirkan transformasi otomatis dari foto ke lukisan bergaya Monet.  

### Tujuan Proyek  
1. Mengembangkan model **CycleGAN** untuk transformasi gaya seni.  
2. Memberikan akses seni digital untuk semua orang.  
3. Mendukung kreator konten, fotografer, desainer, dan seniman NFT.  
4. Meningkatkan nilai estetika dalam industri kreatif.  
5. Memfasilitasi monetisasi seni digital melalui NFT.  
6. Mengoptimalkan efisiensi dan skalabilitas produksi karya seni.  

### Implementasi Model  
- **Preprocessing**: normalisasi gambar dan augmentasi dataset.  
- **Arsitektur**: *CycleGAN* untuk *image-to-image translation*.  
- **Training**: melatih model dengan pasangan dataset (foto ↔ Monet).  
- **Evaluasi**: membandingkan kualitas visual hasil transformasi.  

---

## Hasil  
- Model berhasil mengubah foto biasa menjadi gambar dengan gaya impresionis Claude Monet.  
- Hasil menunjukkan tekstur, warna, dan pola khas lukisan Monet dapat diaplikasikan pada berbagai jenis foto.  
- Proyek ini membuktikan bahwa **AI dapat menjadi jembatan antara seni klasik dan era digital modern**.  

---

## Kesimpulan  
Monetify memperlihatkan potensi besar AI dalam dunia seni digital. Dengan CycleGAN, siapa saja dapat menghasilkan karya artistik tanpa keterampilan melukis manual.  
Proyek ini tidak hanya relevan untuk pembelajaran akademis, tetapi juga memiliki aplikasi praktis dalam industri kreatif, media sosial, dan pasar NFT.  

---

## Lisensi  
Proyek ini dibuat untuk keperluan akademik dan dapat digunakan sebagai referensi pembelajaran.  
