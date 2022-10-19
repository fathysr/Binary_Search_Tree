# Binary_Search_Tree
[Patika.dev](https://www.patika.dev/tr)

##  [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Root olarak 7'yi kullanmak istiyorum.
Öncelikle bir sağıma bakıyorum 5 var ve bu benden küçük soluma ekledim. 

   

------------

7
  /
 5
Daha sonrasında sağımda 1 var bu da benden küçük yine soluma ekledim. Hemen sağımda 8 var bu benden büyük artık sağ tarafıma ekliyorum.

------------


7
/  \
5    8
/
1

------------


Sağ tarafımda 3 değeri var bu benden küçük sol tarafa ekliyorum.

7
/  \
5    8
/
1
\
3

------------

Sağ tarafımda 6 var ve benden küçük soluma ekliyorum.
---7--
-/  --- \
5  ----  8
/ -\
1-- 6
\
3

------------


Sağ tarafımda 0 var ve sola ekliyorum.

---7--
-/  --- \
5  ----  8
/ -\
1--- 6
/--\
0---3

------------

Sağ tarafımda  9,4 ve 2 var. Sırasıyla sağ, sol ve sola ekliyorum.
---7--
-/  --- \
5  ----  8
/ -\ ------\
1--- 6-----9
/--\
0---3
--  /---\
  --2----4
  
  

------------

Binary Search Tree tamamlanmış oluyor.
