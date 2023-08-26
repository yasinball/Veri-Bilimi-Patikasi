# Proje 1 - Insertion Sort

## 1.Soru
 [22,27,16,2,18,6]

 Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

[22,27,16,2,18,6] n

[2,27,16,22,18,6] n-1

[2,6,16,22,18,27]n-2

[2,6,16,18,22,27]n-3

 [2,6,16,18,22,27] 1

## 2.Soru
 Big-O Gösterimini yazınız.

n+(n-1)+(n-2)+(n-3)+(n-4)+1=

= (n * (n+1)) / 2

= (n² + n) / 2

= O(n²)

## 3.Soru
 Time Complexity : Dizi Sıralandıktan sonra 18 Sayısı aşağıda ki case'lerden hangisinin kapsamına girer?


-- Average case : Aradığımız sayının ortada olması

-- Worst case: Aradığımız sayının sonda olması

-- Best case: Aradığımız sayının dizinin en başında olması.

## Çözüm
18 Sayısı dizinin ortasında bulunmasından dolayı Average case kapsamına girer.

## 4.Soru
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

[7,3,5,8,2,9,4,15,6] n

[2,3,5,8,7,9,4,15,6]n-1

[2-3,8,7,9,5,15,6] n-2

[2,3,4,5,9,7,15,6] n-3 

