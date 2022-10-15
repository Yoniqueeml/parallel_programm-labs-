[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%2336BCF7&lines=Lab+2)](https://git.io/typing-svg)
About lab
------------
Info for files:
-  Data.txt              - all values from two matrices
-  Time without.txt           - time for multiply matrices without parallel
-  Time with omp.txt    - time for multiply with parallel
-  main.cpp             - obviously
-  main.py              - correctness check

##### About main.cpp: I represented matrices as arrays and used a formula to get the elements from the desired rows or columns (see code).
### Time without
Matrix's size is: 100
Def meth's time: 15.0113
_______________________________
Matrix's size is: 200
Def meth's time: 117.037
_______________________________
Matrix's size is: 300
Def meth's time: 396.682
_______________________________
Matrix's size is: 400
Def meth's time: 936.371
_______________________________ 
![](without_omp.png)

### Time with omp
Matrix's size is: 100
Def meth's time: 26.6091
_______________________________
Matrix's size is: 200
Def meth's time: 28.5437
_______________________________
Matrix's size is: 300
Def meth's time: 96.3207
_______________________________
Matrix's size is: 400
Def meth's time: 224.973
_______________________________
Matrix's size is: 800
Def meth's time: 1823.44
_______________________________
![](without_omp.png)
###### Lab1: matrix product, and subsequent improvement in the form of parallel streams. Looking at file Result.txt we can say that the time directly depends on the size of the matrices, so for better time we can use parallel programming, which i'll show in the next branches of this rep
