# Insertion Sort
### Dizi ile ilgili verilen soruları cevaplayınız
```
[22,27,16,2,18,6]
```
* Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
1. 2 ve 22 yer değiştiri. [2,27,16,22,18,6]
2. 27 ve 6 yer değiştirir. [2,6,16,22,18,27]
3. Sonraki küçük asyı 16 olduğu için yer değiştirilmez. Yanındaki sayıya bakılır 18 ve 22 yer değiştirir. [2,6,16,18,22,27]
4. Değişim sonrası bir blok yana geçtiğimizde 22 en küçük olduğu için değişim olmaz
5. 22den sonra 27 en küçük olduğu için değişim olmaz.
* Big-O gösterimini yazınız.

O(n^2)

* Time Complexity
1. Average Case: Aradığımız sayının ortada olması
2. Best Case: Aranan sayının başta olması.
3. Worst Care: Sayının en sonra olmasıdır.
   
* Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? 
  
  Dizinin ortalarında olduğu için average case kapsamındadır.

```
* [7,3,5,8,2,9,4,15,6] dizisinin ilk 4 adımını yazınız.
```
1. 7 ve 2 yer değiştirir. [2,3,5,8,7,9,4,15,6]
2. Sağdaki stünda 3 en küçük sayı olduğu için bir sonraki stüna geçilir.
3. 5 ve 4 yer değiştirir. [2,3,4,8,7,9,5,15,6]
4. 5 ve 8 yer değiştirir. [2,3,4,5,7,9,8,15,6]

