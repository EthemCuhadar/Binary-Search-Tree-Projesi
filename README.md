# Binary-Search-Tree-Projesi

## Proje 3
### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

### Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

### Çözüm:

+ Root 7 dir. 
+ 5 7 den küçük olduğu için sol çocuğu olur.
+ 1 7 den küçük olduğu için sol tarafına gider. 5 den küçük olduğu için 5 in çocuğu olur.
+ 8 7 den büyük oduğu için 7 nin sağ çocuğu olur.
+ 3 7 den küçük olduğu için sol subtreeye gider. 5 den de küçük olduğu için 5 in sol tarafına gider. 1 den büyük olduğu için 1 in sağ çocuğu olur.
+ 6 7 den küçük olduğu için 7 nin sol tarafına gider. 5 den büyük olduğu için 5 in sağ çocuğu olur.
+ 0 7 den küçük olduğu için sol subtreeye gider. 5 den de küçük olduğu için 5 in sol tarafına gider. 1 den küçük olduğu için 1 in sol çocuğu olur.
+ 9 7 den büyük olduğu için 7 nin sağ tarafına gider. 8 den de büyük olduğu için 8 in sağ çocuğu olur.
+ 4 7 den küçük olduğu için sol subtreeye gider. 5 den de küçük olduğu için 5 in sol tarafına gider. 1 den büyük olduğu için 1 in sağ tarafına gider. 3 den büyük olduğu için 3 ün sağ çocuğu olur.
+ 4 7 den küçük olduğu için sol subtreeye gider. 5 den de küçük olduğu için 5 in sol tarafına gider. 1 den büyük olduğu için 1 in sağ tarafına gider. 3 den küçük olduğu için 3 ün sol çocuğu olur.

                7
               / \
              5   8
             / \    \
            1   6     9
           / \
          0   3
             / \
            2   4
