解非線性方程式，f(x) = x -cos(x)=0的解 [0,pi/2]。說明：兩個程式都用while迴圈寫

作業1：Fixed-Point Method (檔案名稱 fpm.m)

說明：g(x) = x = cos(x)，利用while設計迭代計算出近似解c

p0  (初始值)

p1=g(p0)

p2=g(p1)

...

pk=g(pk-1)

在while 迴圈中需要設定終止迴全的條件。最後回傳近似解c

作業2：Newtons Method (檔案名稱ntm.m)

說明：g(x) = x = x - f(x)/f'(x) (Newtons Method)，利用while設計迭代計算出近似解c


p0  (初始值)

p1=g(p0)

p2=g(p1)

...

pk=g(pk-1)

在while 迴圈中需要設定終止迴全的條件。最後回傳近似解c
請繳交兩個.m檔案，及一個word檔案
