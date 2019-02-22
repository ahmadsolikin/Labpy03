# Labpy03                                                                                                                               

Tugas Ketiga                                                                                                                            
Membuat Latihan Pertama, Kedua, dan Ketiga                                                                                              




# Latihan Pertama                                                                                                                       
Menampilkan bilangan acak yang lebih kecil dari 0,5 serta menggunakan syntac perulangan dan random                                      

1. Buka aplikasi Pycharm                                                                                                                
2. Buka New Scratch File                                                                                                                 

![step11](https://user-images.githubusercontent.com/46926559/53261333-4ea0c000-3706-11e9-892e-954879f89a85.png)

3. Ketikan Syntac :                                                                                                                     

![step 3](https://user-images.githubusercontent.com/46926559/53255388-1befcb00-36f8-11e9-8a57-cf73c6c521cf.png)

print(' Bilangan acak yang lebih kecil dari 0.5')            // Menampilkan 'Bilangan acak yang lebih kecil dari 0.5'                   
import random                                                // Berfungsi meng-acak hasil dari perulangan yang akan kita buat           
n = int(input("Masukkan nilai n :"))                         // Syntac ini kita digunakan untuk memasukan Variabel pada nilai n         
a = 0                                                        // Sebagai Variabel yang mana nanti gunakan untuk mengurutkan data         
for c in range(n):                                           // Sebagai perintah perulangan data dari variabel (n)                      
    a+= 1                                                    // Sebagai bentuk perintah untuk mengurutkan data yang kita buat sebelumnya 
    b = random.uniform(.0,.5)                                // Digunakan sebagai variabel peng-acakan pada nilai (b)                   
    print('data ke:',a,'==>',b)                              // Digunakan untuk memunculkan hasil data (a) pengurutan dan (b) pengacakan
print("----Selesai----")                                     // Menampilkan "----Selesai----"                                          

4. Jalankan syntax yang sudah di buat dengan menu RUN yang terdapat pada aplikasi Pycharm                                               

![step 4](https://user-images.githubusercontent.com/46926559/53255390-1c886180-36f8-11e9-9095-b33f7d8c4aa5.png)
                                                                                                                                        
# Latihan Kedua                                                                                                                         
Mencari bilangan dan menampilkan bilangan terbesar dari (n) sebuah data yang diinputkan.                                                
Dan Memasukkan angka 0 untuk berhenti.                                                                                                  
1. Ketikan Syntax :

![step d](https://user-images.githubusercontent.com/46926559/53255395-1e522500-36f8-11e9-85ce-2ba9a464849b.png)

print('----Menentukan Bilangan Terbesar----')                // Menampilkan '----Menentukan Bilangan Terbesar----'                      
max=0                                                        // Digunakan untuk memberikan varibel pada max                             
while True:                                                  // Bentuk syntax perulangan                                                
    a=int(input('Masukkan bilangan = '))                     // Digunakan untuk memasukan bilangan variabel pada nilai (a)              
    if max < a:                                              // Di gunakan sebagai penegasan bahwa jika max lebih kecil dari nilai(a)   
        max = a                                              // Max nilai a                                                             
    if a==0:                                                 // di gunakan untuk perintah apabila nilai (a) di isi (0) maka pencarian   
        break                                                 nilai berhenti dengan menggunakan break                                  
print('Bilangan terbesarnya adalah = ',max)                  // Menampilkan 'Bilangan terbesarnya adalah ='                             
                                                                                                                                        
2. Pilih menu Run pada menu Pycharm untuk menjalankan hasil dari syntax yang kita buat                                                  
                                                                                                                                         
![step e](https://user-images.githubusercontent.com/46926559/53255396-1e522500-36f8-11e9-9672-922c6d9d1a74.png)

                                                                                                                                      
# Latihan Ketiga                                                                                                                        
Membuat program sederhana dengan perulangan: "program1".py
                                                                                                                                         
1. Seorang pengusaha menginvestasikan uang untuk memulai usahanya dengan modal awal 100 juta,                                         
2. Pada bulan pertama dan kedua belum mendapatkan laba.                                                                                 
3. Pada bulan ketiga baru mulai mendapatkan laba sebesar 1%                                                                             
4. dan pada bulan ke 5, pendapatan meningkat 5%,                                                                                      
5. selanjutnya pada bulan ke 8 mengalami penurunan keuntungan sebesar 2%                                                                
6. sehingga laba menjadi 3%. 7. Hitung total keuntungan selama 8 bulan berjalan usahanya.*                                              
                                                                                                                                         
1. Ketikan syntax :                                                                                                 
                                                                                              
![step3 2](https://user-images.githubusercontent.com/46926559/53255403-214d1580-36f8-11e9-9209-78a4d48a5611.png)
                                                                                                                                         
x=100000000                                              // Variabel pada nilai(x) = modal awal                                         
sum=0                                                    // Digunakan untuk memberikan variabel pada syntax penjumlahan(Sum)            
y=0                                 // Digunakan untuk memberikan variabel pada nilai (y) untuk mengurutkan keterangan laba pada bulan  
lb = [int(0), int(0), int(x) * .1, int(x) * .1, int(x) .5, int(x) * .5, int(x) * .5, int(x) .2]     // menerangkan bahwa (lb) = hasil                                                                                                          atau persenan dari modal awal    
                                                                                                                                        
print('modal awal seorang pengusaha :',x)                // Menampilkan hasil dari hitungan laba di atas                              
                                                                                                                                        
for i in lb :                                            // Syntax ini berfungsi mengulang dan memasukan laba ke dalam nilai(i)         
sum=sum+i                                                // Menjumlah kan nilai laba yang berada di dalam nilai(i)                       
y+=1                                                     // Mengurutkan nilai pada laba                                               
print('laba bulan ke-', y ,'sebesar :',i)                // Menampilkan hasil dari variabel yang di dapat                             
                                                                                                                          
print('total laba yang di dapet adalah :',sum)           // menampilkan hasil pejumlahan variabel atau hasil laba                       
                                                                                                                        
2. Pilih menu Run pada menu Pycharm untuk menjalankan hasil dari syntax yang kita buat                                                  
                                                                                  
![step3 3](https://user-images.githubusercontent.com/46926559/53255405-21e5ac00-36f8-11e9-85e8-a19b8ed21c4e.png)




SEKIAN TUGAS DARI SAYA                                                                                                
                                                          
Ahmad Solkin TI 18 B1                                                         
Terima Kasih                                                      
