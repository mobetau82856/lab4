A
000000000040052d T _Z7averageif
00000000004004ed T _Z7averagePdRd

B
1	8
4	8
4	8
8	8
由於char,int,float,double占用的記憶體空間分別是1,4,4,8，所以這四行的第一個數字分別就是1,4,4,8，而pointer是記錄他們的記憶體位置，因此不管是哪一個的pointer所需要用的記憶體空間都是8。
