# Selection-Sort-Projesi

## [22,27,16,2,18,6] en küçük solda olacak şekilde sıralayalım

- En küçük 2 o yüzden 2 ile 22 yer değiştirir      -->                           [2, | 27, 16, 22, 18, 6]           -->                    n
- En küçük 6 o yüzden 6 ile  27 yer değiştirir     -->                           [2, 6, | 16, 22, 18, 27]           -->                    n-1
- En küçük 16 yerinde kalır                        -->                           [2, 6, 16, | 22, 18, 27]           -->                    n-2
- En küçük 18 o yüzden 18 ile 22 yer değiştirir    -->                           [2, 6 16 18 | 22, 27]              -->                      1
- Ve sıralama tamamlanır                           -->                           [2, 6 16 18 ,22, 27]                    

## BiG-O gösterimi 
n + n-1 + n-2 . . . 1 = (n*(n-1))/2 - 0(n^2)

## Case Türü
* 18 sayısı aradığımız sayısının tam ortası olduğu için Average case olur.

## [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
- En küçük 2 o yüzden 2 ile 7 yer değiştirir        -->               [2, | 3,5,8,7,9,4,15,6]
- En küçük 3 yerinde kalır                          -->              [2, 3, | 5,8,7,9,4,15,6]  
- En küçük 4 o yüzden 4 ile 5 yer değiştirir  	    -->              [2, 3, 4, | 8,7,9, 5,15,6]  
- En küçük 5 o yüzden 5 ile 8 yer değiştirir        -->             [2, 3, 4, 5, | 7, 9, 8, 15, 6]
