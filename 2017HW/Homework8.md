作業八

 

計算P級數瑕積分 I=∫1/x^p dx 從1到∞ (p>1 or 0<p <=1)

I_N =  lim   ∫1/x^p dx 從1到N

N→∞

 

虛擬碼：(參考老師的黑板筆記)

p= 2.7 ;

kmax=10;

for k=0: kmax

  N ←10^k;

  Use integral compute I_N

  fprintf (‘N  I_N‘);

end

 

(1) 計算各種p值下(p=0.5、1、2.7、10)，I_N (N=10^1、10^2…、10^10 )，程式碼存成P_integal.m檔案

(2) 將 N, I_N的資料表格存至results.txt

(3) 利用semilogx繪製N-I_N的二維圖形
