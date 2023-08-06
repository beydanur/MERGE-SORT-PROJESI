# MERGE-SORT-PROJESI
VERİ YAPILARI VE ALGORİTMALAR merge sort projesi


[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

                 [16,21,11,8,12,22]                                
                                                               |
            [16,21,11]    |     [8,12,22]                      |    
                                                               |
         [16]  | [21,11]  |   [8,12] |  [22]                   |     
                                                               |
       [16] | [21] | [11] |  [8] | [12] | [22]                 |      O(n)
                                                               |
         [16]  | [11,21]  |   [8,12]  |  [22]                  |     
                                                               |
             [11,16,21]   |    [8,12,22]                       |
                                                               |
                  [8,11,12,16,21,22]                           | 

        
        __ ___ ___ ___ ___ ___ ___ ___ ___ ___ __              .

            2^x=n   x=logn    O(logn)                          =    O(n)*O(logn)=O(nlogn)

          Big-o gösterimi: Her dizide gruplara ayırmış olsak da eleman sayısı değişmiyor ve her kademede sıralama yaparken n-1 eleman tarıyorum burdan her kademe için  O(n) time complexity geliyor.
          Aşağı doğru gruplara ayırırken de her defasında ikiye bölünerek gidiyor.n^2,n^4...,1.Burdan da O(logn) geliyor.
          Bütün durumları işin içine kattığımızda ise [her işlem için logn defa her kademeden O(n) time complexity'si geliyor]= O(nlogn)  
          
