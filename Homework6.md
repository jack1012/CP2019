作業一 一元二次⽅程式求解

1. 撰寫 MATLAB 程式，求解一元二次方程式(ax^2+bx+c=0)的零根 (zeros or rots)，包含相異的實數根、重根，以及複數根。(參考老師ppt ch4 第35頁)



2. 定義輸入與輸出

鍵入關鍵係數 a,b,c。

顯⽰零根解 x1,x2 = (−b ±√b^2 − 4ac)/2a 。



3. 設計演算法

(1)讀取輸入資料 

(2)計算判別式 discriminant = b^2 − 4ac。

(3)依據判別式是否⼤於零、等於零或⼩於零

(4)輸出結果。



作業二：一元三次方程式求解

1. 撰寫 MATLAB 程式，求解⼀元三次⽅程(ax^3+bx^2+cx+d=0)式的零根 (zeros or rots)，判別根式狀況。解出三個根



2. 定義輸入與輸出

鍵入關鍵係數 a,b,c,d。

顯示零根解的狀況

顯⽰零根解 x1,x2,x3 (加分題)



3設計演算法

(1)讀取輸入資料

(2)計算判別式 discriminant = b^2c^2-4ac^3-4b^3d-27a^2d^2+18abcd。

(3)依據判別式判斷零根解狀況

	Case1 discriminant<0方程有一個實根和一對共軛復根

	Case2 discriminant=0 ，(c/3a)-(b^2/9a^2)=0，方程有三重實根

	Case3 discriminant=0 ，(c/3a)-(b^2/9a^2)=/=0方程有三個實根，其中有兩個根相等。

	Case4 discriminant>0方程有三個不相等的實根。

(4)輸出結果。(不需要算出三個根，算出三個根為加分題)