# algortima-veri-analiz
algoritma ve veri analiz odevleri
https://www.patika.dev/tr

Proje 1)


1)        [22,27,16,2,18,6] -> Insertion Sort
          [2,27,16,22,18,6]
          [2,6,16,18,22,27]

2)         O(n^2)
3)         Best case: O(n)
           Ave. ve Worst case: O(n^2)
4)         18 sayısı Average case kapsamına girer.
5)         [7,3,5,8,2,9,4,15,6] nin ilk dört adımı;

           [2,3,5,8,7,9,4,15,6]
           [2,3,4,8,7,9,5,15,6]
           [2,3,4,5,7,9,8,15,6]
           [2,3,4,5,6,9,8,15,7]

Proje 2)
          
          [16,21,11,8,12,22] -> Merge Sort
          
          [16,21,11]                [8,12,22]
          
          [16,21] [11]              [8,12] [22]
          
          [16] [21] [11]            [8] [12] [22]
          [16,21] [11]              [8,12] [22]
          [11,16,21]                [8,12,22]
                     [8,11,12,16,21,22]
          
          * O(logn.n)
          
Proje 3)
          [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamaları;
          
          
                        6               ---> root olarak 6 seçildi
                  3           8         ---> küçük değer olarak 3, büyük değer olarak 8 seçildi
               1     4     7      9     ---> 3 parent ına küçük olarak 1, büyük olarak 4 ; 8 parent ına küçük olarak 7 büyük olarak 9 seçildi.
             0   2     5                ---> parent 1 için 0 küçük,2 büyük değer olarak eklendi son olarak parent 4 için büyük değer 5 girildi.
             
             
