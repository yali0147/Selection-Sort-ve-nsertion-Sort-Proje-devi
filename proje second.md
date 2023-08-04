###Proje 2-Merge Sort Projesi
[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.

---
***1.Yukarıdakı dizinin Merge sort türüne göre aşamaları aşağıdaki gibidir.***
| Veriler |[16]|[21]|[11]|[8]|[12]|[22]|
|:---:|:---|:---:|:---|:---:|:---:|:---:|           
|1.Aşama||[16,21]||[8,11]||[12,22]|
|2.Aşama |||[8,16,21]||[11,12,22]|
|3.Aşama||||[8,11,12,16,21,22]|

***2.Yukarıdaki dizinin merge sorta göre Big-O'su aşağıdaki gibidir.***
Dizinin her seferinde ikiye bölündüğünden bölünmesi 
**logn** ile ifade edilir. Her bölünmede de bütün elemanlarla 
karşılaştırması da **n** ile ifade edilirse sonuç olarak 
**Big-O:(nlogn)** olur.  
|**O:(nlogn)**|
|:---:|
