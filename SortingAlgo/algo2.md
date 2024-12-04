# Merge Sort
#### Dizimiz [16,21,11,8,12,22] -> Merge Sort yanda verilen dizinin sort türüne göre aşamalarını yazınız.

**Big-O gösterimini yazınız.** <br>
<br>
**Merge Sort Aşamaları** 
*Merge Sort, "böl ve birleştir" prensibine dayanan etkili bir sıralama algoritmasıdır. Diziyi sürekli olarak ikiye bölerek daha küçük alt dizilere ayırır, bu alt dizileri sıralar ve ardından birleştirir.*

*Verilen dizi: [16, 21, 11, 8, 12, 22]*

**Aşamalar:**

**Bölme:**
Diziyi ortadan ikiye böleriz: [16, 21, 11] ve [8, 12, 22]
Bölme (devam):
Her iki alt diziyi de tekrar ortadan ikiye böleriz:
[16, 21, 11] -> [16, 21] ve [11]
[8, 12, 22] -> [8, 12] ve [22] <br>
**Sıralama ve Birleştirme:**<br>
En küçük alt diziler (tek elemanlı diziler) zaten sıralıdır. <br>
**İkişerli olarak birleştirerek sıralama yaparız:** <br>
[16, 21] ve [11] -> [11, 16, 21]
[8, 12] ve [22] -> [8, 12, 22]
Son olarak bu iki sıralı diziyi birleştiririz: [11, 16, 21, 8, 12, 22] <br>
**Tekrarlı Birleştirme**:
Son olarak elde ettiğimiz diziyi tekrar ortadan ikiye böler ve sıralama işlemini tamamlarız:
[11, 16, 21] ve [8, 12, 22] -> [8, 11, 12, 16, 21, 22]
Sıralı Dizi: [8, 11, 12, 16, 21, 22]

**Big-O Gösterimi**
*Merge Sort'un en iyi, ortalama ve en kötü durum zaman karmaşıklığı hep O(n log n)'dir. Bu, Merge Sort'u büyük veriler için oldukça verimli kılar*.