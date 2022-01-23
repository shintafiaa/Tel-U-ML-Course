#Tugas:
Memilih arsitektur di d2l.ai bab 7.

#Keterangan:
##Model arsitektur yang berhasil dijalankan:
Sub modul 7.5. Batch Normalization
Sub modul 7.6. ResNet
Sub modul 7.7. DenseNet

##Modul arsitektur yang belum berhasil dijalankan:
* Submodul 7.1. AlexNet
* Submodul 7.2. VGG
* Submodul 7.3. NiN

Error yang muncul yaitu:
ImportError: cannot import name '_check_savefig_extra_args' from 'matplotlib.backend_bases' (/usr/local/lib/python3.7/dist-packages/matplotlib/backend_bases.py)

Sudah mencoba install seperti kumpulan kode berikut dalam satu sel:
!pip uninstall matplotlib
!python -m pip install --upgrade pip
!pip install matplotli

Ataupun kumpulan kode berikut dalam satu sel:
!pip uninstall matplotlib
!pip install --upgrade matplotlib
