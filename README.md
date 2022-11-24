# Insertion Sort küçükten büyüğe sıralama

### Big-O gösterimi
Insertion sort:
Time Complexity = **O(n²)** şeklindedir. <br>

* n adet öğe için ***n(n+1)/2 = (n²+n)/2*** adet işlem yapılır dominant değer **n²**'dir.

* 18 sayısı Average case: Aradığımız sayının ortada olması kapsamına girer.

---
## Insertion sort adımlarının açıklamamları

> [22,27,16,2,18,6]<br/>
[22],[27] --> kıyaslandı ve sıralama değişmedi

---
> [22,16,27,2,18,6]<br/>
[27],[16] --> kıyaslandı ve yer değiştirdi

---
> [16,22,27,2,18,6]<br/>
[22],[16] --> kıyaslandı ve yer değiştirdi

---
> [16,22,2,27,18,6]<br/>
[27],[2] --> kıyaslandı ve yer değiştirdi

---
> [16,2,22,27,18,6]<br/>
[22],[2] --> kıyaslandı ve yer değiştirdi

---
> [2,16,22,27,18,6]<br/>
[16],[2] --> kıyaslandı ve yer değiştirdi

---
> [2,16,22,18,27,6]<br/>
[27],[18] --> kıyaslandı ve yer değiştirdi

---
> [2,16,18,22,27,6]<br/>
[22],[18] --> kıyaslandı ve yer değiştirdi

---
> [2,16,18,22,6,27]<br/>
[6],[27] --> kıyaslandı ve yer değiştirdi

---
> [2,16,18,6,22,27]<br/>
[22],[6] --> kıyaslandı ve yer değiştirdi

---
> [2,16,6,18,22,27]<br/>
[18],[6] --> kıyaslandı ve yer değiştirdi

---
> [2,6,16,18,22,27]<br/>
[16],[6] --> kıyaslandı ve yer değiştirdi

---

# Selection Sort

### Big-O gösterimi
Selection sort:
Time Complexity = **O(n²)** şeklindedir. <br>

* n adet öğe için ***n(n+1)/2 = (n²+n)/2*** adet işlem yapılır dominant değer **n²**'dir.

## Selection sort adımları
[7,3,5,8,2,9,4,15,6]  dizisinin selection sort'a göre ilk 4 adımı: <br>

Adım - 1:
> [2,3,5,8,7,9,4,15,6] --> index 0'dan başlayarak en küçük değer 2 olarak bulundu ve index 0'daki 7 ile 2 yer değiştirildi
---
Adım - 2:
> [2,3,5,8,7,9,4,15,6] --> index 1'den başlayarak en küçük değer 3 olarak bulundu ve yer değiştirmeye gerek yok.
---
Adım - 3:
> [2,3,4,8,7,9,5,15,6] --> index 2'dan başlayarak en küçük değer 4 olarak bulundu ve index 2'deki 5 ile 4 yer değiştirildi
---
Adım - 4:
> [2,3,4,8,7,9,5,15,6] --> index 3'den başlayarak en küçük değer 5 olarak bulundu ve index 3'teki 8 ile 5 yer değiştirildi


![Alparslan KELCİ](https://lh3.googleusercontent.com/a/ALm5wu1pYPsDvQWEiGDN4_5-kfp9v0HHO-jqfs2mDqXB3bU=s96-c-rg-br100)
<br/>

[Alparslan KELCİ](https://github.com/AlparslanKelci "My github repository")


