# Insertion Sort
#### Dizimiz [22,27,16,2,18,6] Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

**Big-O gösterimini yazınız.**
<br>
1.adım key=dizi[1] 
27>22 olduğu için aynen kalır <br>
2.adım key=dizi[2] 22 ve 27 sağa kayıyor.Dizimizin son hali = [16,22,27,2,18,6] bu şekilde oluyor.<br>
3.adım key=dizi[3] Dizinin 3.adımdaki son hali = [2,16,22,27,18,6] <br>

4.adım key=dizi[4] Dizinin 4.adımdaki son hali = [2,16,18,22,27,6]
5.adım key=dizi[5] Dizinin 5.adımdaki son hali = [2,6,16,18,22,27]<br>
Worst Case: O(n^2)
Best Case: O(n)
18 sayısı ortalarda olduğu için Average Case olacak.
<hr>

# Selection Sort
#### [7,3,5,8,2,9,4,15,6] dizisini selection sorta göre ilk 4 adımını yazınız.

1.adım key = dizi[0] swap(7,2) [2,3,5,8,7,9,4,15,6]
2.adım key = dizi[1] *aynen kalır swap olmaz* 
3.adım key = dizi[2] swap(5,4) [2,3,4,8,7,9,5,15,6]
4.adım key = dizi[3] swap(8,5) [2,3,4,5,7,9,8,15,6]