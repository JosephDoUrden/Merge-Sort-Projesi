# Merge-Sort-Projesi

Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

## Merge Sort Aşamaları
1. Array eşit olacak şekilde ikiye bölünür.

    [16,21,11] - [8,12,22]
2. Elemanlar tek kalana kadar bu işleme devam edilir.

    [16,21] - [11] -  [8,12] - [22]
    
3. Elemanlar tek kalana kadar bu işleme devam edilir.

    [16] - [21] - [11] -  [8] - [12] - [22]
    
4. Elemanlar küçükten büyüğe doğru olacak şekilde tekrar gruplandırılır.

    [16,21] - [11] - [8,12] - [22]
    
5. Elemanlar küçükten büyüğe doğru olacak şekilde tekrar gruplandırılır.

    [11,16,21] - [8,12,22]
    
6. Elemanlar küçükten büyüğe doğru olacak şekilde tekrar gruplandırılır.

    [8,11,12,16,21,22]

## Big-O Notation
Merge sort:
n/2+n/4+n/8+... = n*(1/2+1/4+1/8+..) = n*((1/2)^(n-1)) olması nedeniyle nedeniyle 0(nlogn) gösterimine sahiptir.
