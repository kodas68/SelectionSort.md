(Selection Sort Projesi
Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.



[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.)


Aşamalar:

Bu durumda en küçük elemanı bulmamız ve en baştaki sayı ile yer değiştirmemiz sonra da en küçük 2. elemanı bulmamız ve 2. sıradaki elemanla yer değiştirmemiz gerekmektedir. Liste sıralı hale gelene kadar işlemi tekrar etmemiz lazım.
1.[2,27,16,22,18,6] n tane işlem
2.[2,6,16,22,18,27] n-1 işlem
3.[2,6,16,22,18,27] n-2 işlem
4.[2,6,16,18,22,27] 1 
-Big-o gösterimi O(n²) dir.

-18 sayısı ortada olduğundan avarage case'dir.

##[7,3,5,8,2,9,4,15,6] dizisinin selection sort'a göre ilk 4 adımı:
1.[2,3,5,8,7,9,4,15,6]
2.[2,3,5,8,7,9,4,15,6]
3.[2,3,4,8,7,9,5,15,6]
4.[2,3,4,5,7,9,8,15,6] 

şeklindedir.

https://app.patika.dev/koras