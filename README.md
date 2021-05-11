# News Sentimen Analisis
# (Nur Hanifah Amatullah_1184086)
##Aplikasi ini menggunakan library textblob untuk mendapatkan nilai polarynya dan subjectivitynya.
##Aplikasi digunakan untuk menganalisis text dari sebuah url berita yang nantinya akan menghasilkan nilai polaritas dan nilai subjektivitas dari berita tersebut.
##Cara penggunaan aplikasi ini yaitu :
##1. Kita disuruh memasukkan link url berita yang ingin kita ketahui analisis sentimentnya
##2. Lalu klik submit
##3. Setelah itu akan keluar hasil sentiment category type polaritas dan type subjectivitasnya beserta nilai analisis sentimentnya. 
## Nilai sentiment dihasilkan dari polarity dan subjectivitynya dari setiap link yang diinputkan.
a). nilai sentiment polarynya > 0.75, maka termasuk extremely positive
b). nilai sentiment polarynya > 0.5, maka termasuk significantly positive
c). nilai sentiment polarynya > 0.3, maka termasuk Fairly positive
d). nilai sentiment polarynya > 0.1, maka termasuk Slightly positive
e). nilai sentiment polarynya == 0, maka termasuk Netral
f). nilai sentiment polarynya < -0.1, maka termasuk Slightly negative
g). nilai sentiment polarynya < -0.3, maka termasuk Fairly negative
h). nilai sentiment polarynya < -0.5, maka termasuk significantly negative
i). nilai sentiment polarynya < -0.75, maka termasuk extremely negative
# Sedangkan untuk nilai sentiment subjectivitynya yaitu :
a). nilai sentimen subjct >0.75 , maka termasuk ektremely subjective
b). nilai sentimen subjct >0.5 , maka termasuk fairly subjective
c). nilai sentimen subjct >0.3 , maka termasuk fairly objective
d). nilai sentimen subjct >0.1 , maka termasuk ektremely objective
e). nilai sentimen subjct ==0 , maka termasuk netral
