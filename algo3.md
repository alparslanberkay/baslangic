### Proje 3
#### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

##### Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

**Verilen dizi: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]**

*BST Özelliği:*

*Her düğümün sol alt ağacındaki tüm değerler, düğümün değerinden küçüktür.*
*Her düğümün sağ alt ağacındaki tüm değerler, düğümün değerinden büyüktür.* <br><hr>

      7
     /  \
    5     8
    /  \   \
   1     6   9
  / \   /
 0  3 4
   /
   2 
<br>
Ağaçtaki Düğümlerin Anlamı:

7: Kök düğüm
5, 8: 7'nin çocukları
1, 6: 5'in çocukları
3, 9: 8'in çocukları
0, 4: 1'in çocukları
2: 3'ün çocuğu
Özetle:

Verilen diziyi kullanarak bir ikili arama ağacı oluşturduk. Her adımda, yeni bir eleman eklerken, o elemanın ağacın hangi yerine yerleştirileceği, kök düğümden başlayarak yapılan karşılaştırmalarla belirlendi. Bu sayede, ikili arama ağacının özelliği olan sıralama koşulu sağlandı.
