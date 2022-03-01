
Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
  Another Example: 
[16,21,11,8,12,22]
i = 1 (dizinin ikinci elemanı) ile 4 (dizinin son elemanı) arasında döngü yapalım
i = 1. 11, 16'dan küçük olduğundan, 16'yi hareket ettirin ve 12'den önce 11'i ekleyin
11.16,21,8,12,22,
i = 2. A[0..I-1]'deki tüm elemanlar 22'den küçük olduğu için 22 konumunda kalacaktır.
11.16,21,8,12,22
i = 3. 8 başa hareket edecek ve 11'den 22'ye kadar olan diğer tüm elemanlar mevcut konumlarından bir pozisyon ileride hareket edecek.
8,11,16,21,12,22 
i = 4. 12, 11'den sonraki konuma hareket edecek ve 11'den 22'ye kadar olan öğeler, mevcut konumlarından bir konum ileride hareket edecek.
8,11,12,16,21,22
 
