# Template TA ITS v.1.0

## Deskripsi

Template ini dibuat khusus dalam format LaTeX untuk mempermudah mahasiswa/i 
dalam penyusunan laporan tugas akhir (TA) di lingkungan [Institut Teknologi
Sepuluh Nopember (ITS)](https://www.its.ac.id/), 
khususnya di [Departemen Fisika](https://www.its.ac.id/fisika/).

> Template ini **bukanlah template resmi** dari ITS, namun dibuat sedemikian rupa
sehingga sesuai dengan pedoman penyusunan laporan TA yang dibuat oleh
Departemen Fisika, ITS.

Template ini dapat digunakan dengan bebas (dan bertanggung jawab) dan dapat 
disesuaikan untuk berbagai keperluan.

Template untuk TA ini terdiri dari beberapa bagian, di mana file `main.tex`
merupakan bagian utama yang berguna untuk menyatakan dan mengatur kerangka
serta *input* yang digunakan dalam dokumen TA. 

Template ini dapat dijalankan dengan menggunakan *compiler* LuaLaTeX untuk 
menghasilkan *file* TA dalam format `*.pdf`. Untuk mempermudah penggunaan
template ini, kami sangat menyarankan pengguna untuk menggunakan "Overleaf.com"

## Struktur File

```bash
.
├── halaman-depan             
│   ├── 00-BGcover.jpg
│   ├── 00-Logo-ITS.png
│   ├── abstract.tex
│   ├── abstrak.tex
│   ├── cover.tex
│   ├── daftarGambar.tex
│   ├── daftarIsi.tex
│   ├── daftarTabel.tex
│   ├── kataPengantar.tex
│   └── pengesahan.tex
├── konten
│   ├── bab01.tex
│   ├── bab02.tex
│   ├── bab03.tex
│   ├── bab04.tex
│   └── bab05.tex
├── halaman-belakang
│   ├── biografi.tex
│   └── lampiran
│       └── lampiranA.tex
├── gambar
│   ├── contoh.png
│   ├── flowchart.png
│   └── foto.png
├── pustaka.bib
├── format-pustaka.bst
├── informasi.tex              
├── kodeUnit.tex
├── pengaturan.tex
├── `main.tex`
└── README.md
```

*Folder* **[`halaman-depan`](./halaman-depan)** berisi *file* `*.tex` dan gambar yang akan dimuat di bagian depan,
sebelum bab Pendahuluan, pada dokumen TA. Abstrak dalam Bahasa Indoneisa dituliskan dalam 
*file* `abstrak.tex`, sementara abstrak dalam Bahasa Inggris dituliskan dalam *file* `abstract.tex`

*Folder* `konten` berisi *file* 
