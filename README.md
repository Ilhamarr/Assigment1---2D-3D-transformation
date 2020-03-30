#### Assigment1---2D-3D-transformation

# Affine Transformation

###### 1. transformation 2D
Transformasi Affline 2D biasanya sering digunakan untuk mentransformasikan nilai-nilai koordinat dari suatu sistem koordinat dua dimensi ke sistem koordinat dua dimensi lainya.

ada 4 Transformasi dasar 2D affine yaitu :

1. Translasi
transformasi ini adalah perpindahan titik secara menyeluruh/pindah tempat.
Matriks:
<blockquote> [1, 0, p1],
        [0, 1, p2],
        [0, 0, 1]]) </blockquote>
dimana p1,p2 adalah dalah vektor offset yang menyatakan besarnya pergeseran.
Transformasi Affine 

2. Rotasi
perpindahan titik secara drajat, perputaran titik
matriksnya:
<blockquote> [cos, sin, 0],
        [-sin, cos, 0],
        [0, 0, 1]]) </blockquote>
        

3. Dilatasi / scale
perbersaran posisi titik
Matriks:
<blockquote>  [c1, 0, 0],
        [0, c2, 0],
        [0, 0, 1]
     </blockquote>




4. projeksi
proyeksi gambar dalam sebuah sudut pandang..
Matriks:
<blockquote> [1, 0, 0],
            [0, 1, 0],
            [f1, f2, 1]
     </blockquote>

