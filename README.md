# insertion-sort-proje
 [Patika.dev](https://www.patika.dev/tr) 
 
[22, 27, 16, 2, 18, 6]  

Insertion Sort
1. Adım  
[16, 22, 27, 2, 18, 6] ---- Dizinin [1] elemanı olan 27yi referans alarak sol taraftaki sıralı sağ tarafı sırasız olacak şekilde sağdaki elemanları sırasıyla sol taraftaki sıralı kısıma yerleştiririz.

2. Adım  
[2, 16, 22, 27, 18, 6]    

3. Adım 
[2, 6, 16, 22, 27, 18]  

4. Adım
[2, 6, 16, 18, 22, 27]


Big O Gösterimi
[22, 27, 16, 2, 18, 6]  ilk önce diziyi ikiye böleriz sağ ve sol kısmı tekrar ikiye bölerek aradığımız elemanı buluruz ya da diziyi daa kısa adımda sıralaya biliriz.

[22, 27, 16 | 2, 18, 6]
[16, 22, 27 | 2, 6, 18]
[2, 6, 16, 18, 22, 27]

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[2,7,3,5,8,9,4,15,6] -----> 1. adım 
[2,3,7,5,8,9,4,15,6] -----> 2. adım 
[2,3,4,7,5,8,9,15,6] -----> 3. adım 
[2,3,4,5,7,8,9,15,6] -----> 4. adım 
