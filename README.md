## Image-Stitching-Python
# Panduan Cara Image Stitching Menggunakan Python dan OpenCV
Image Stitching adalah proses menggabungkan beberapa gambar menjadi satu gambar panorama yang lebih besar. Hal ini dilakukan dengan mencocokkan dan menyatukan bagian-bagian gambar yang tumpang tindih atau saling berdekatan. Teknik ini umumnya digunakan dalam fotografi panorama untuk mencakup sudut pandang yang lebih luas.
Laporan ini untuk memenuhi tugas akhir dari mata kuliah Pemrosesan Paralel Dosen pengampu Pak Adi Hermansyah 

## Daftar Isi
   - [Topologi](#Topologi)
   - [Tools Requirements](#Tools-Requirements)
   - [Input Image](#Input-Image)
   - [Condingan Python](#Condingan-Python)
   - [Execute the code](#Execute-the-code)
   - [Output](#Output)

## Topologi
   ![Topologi]()
   
## Tools Requirements
Sebelumnya itu pastikan update terlbih dahulu Operating System anda dengan cara `sudo apt update`. 
Berikut Tools yang perlu diinstal terlebih dahulu sebelum, menjalankan Image Stitching

    pip3 install numpy

Jika sudah lanjut ke tools yang kedua, dengan perintah berikut

    pip3 install opencv-python

OpenCV memiliki fungsi untuk melakukan penyesuaian geometri,menemukan titik kunci pada gambar yang dapat digunakan dalam proses pencocokan antar gambar

    pip3 install imutils

Selanjutnya install piexif

    pip3 install piexif


## Input Image

   <div align="center">
     <div style="display:flex; flex-wrap:wrap;">
       <img src="" alt="1" width="200"/>
       <img src="" alt="1" width="200"/>
       <img src="" alt="1" width="200"/>
       <img src="" alt="1" width="200"/>
     </div>
   </div>

## Condingan Python
Buatlah codingan image stitching pyhton dengan OpenCV

```py

```

## Execute the code
Step selanjutnya jalankan kodingan pythonya

    python3 <image stitching file> --images <images input direcotry> --output <image output directory>/<output name.png>
    
Contohnya

    python3 image_stitching.py --images image-input/image1 --output image-output/image1/output.png
    
Jika berhasil akan menghasilkan command seperti ini

 ```
    [INFO] loading image...
    [INFO] stitching images...
    [INFO] Image stitched and saves to image-output/image1/output.png
```
![Output](https://github.com/FakhriNaufal25/Image-Stitching-Python_Pemrosesan-Parallel/blob/main/execute%20codingan.png)

## Output
Output akan menghasilkan seperti dibawah ini

<p align="center">
  <img src="https://github.com/FakhriNaufal25/Image-Stitching-Python_Pemrosesan-Parallel/blob/main/Image%20Stitching%20Python/image%20stitching%20output.png" alt="Your Image Description">
</p>




