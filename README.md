# TA Mobil dan bis
Deteksi Objek Mobil dan Bus menggunakan tensorflow object detection

1.Untuk Melakukan annotation terhadap gambar sehingga menjadi seperti dataset yang tersedia pada dataset, dapat dilihat [disini](https://www.youtube.com/watch?v=Tlvy-eM8YO4)
^^^^^^^^^^^^^^^^^^
a). lakukan instalasi labelimg.py
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

    pip3 install labelImg
    labelImg
    labelImg [IMAGE_PATH] [PRE-DEFINED CLASS FILE]
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
b). buka cmd dan pergi direktori labelImg
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


    pyrcc4 -o libs/resources.py resources.qrc
    For pyqt5, pyrcc5 -o libs/resources.py resources.qrc

    python labelImg.py
    python labelImg.py [IMAGE_PATH] [PRE-DEFINED CLASS FILE]
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 c). lalu pilih direktori gambar dan pilih gambar yang akan di annotasi
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 d). tempatkan kotak serapat mungkin dengan objek yang di annotasi lalu labeli dengan nama objek yang telah ditetapkan
 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 e). simpan dengan format XML.
 untuk informasi lebih lengkap seputar labelimg dapat dilihat [disini](https://github.com/heartexlabs/labelImg) 


2.Untuk Models hasil training menggunakan dataset bisa dilihat [disini](https://drive.google.com/drive/folders/1fDf8EUF-Gu1I7idLb9EaXlxa0NKb4DuU?usp=sharing)
^^^^^^^^^^^^^^^^^^
