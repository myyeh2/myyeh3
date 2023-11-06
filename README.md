<!--  github/myyeh2/myyeh3   -->

![](Images/09-22-01.png)  

<!--     
#
# \[{   \color{Fuchsia} 精\;銳\;矩\;陣\;計\;算\;求\;解\;器  }\]  
## \[{  \color{Green}  【Sharp \; Matrix \; Solver \quad \; S\; M\; S】 }\]
-->  


![](Images/11-02-01.png)  
<!--    
#### \[{  \color{Brown} Dennis \; G. \; Zill  }\]
#### \[{  \color{Brown} Differential\; Equations \; with \; Boundary-Value \; Problems \; 9th \; Edition  }\]   
#### \[{  \color{Brown} 第 \; 322 \; 頁 \; 至 \; 第 \; 323 \; 頁  }\]
# 
-->  

---  


# [精 銳 矩 陣 計 算 求 解 器 ( SMS Solver ) ：](https://github.com/myyeh2/Docs_2A/blob/main/README.md)  

### 【完全精確，而不是近似】求解動態系統，包含狀態空間變數(state-space variables)的響應值是實數值、【系統特徵值】是複數，其虛數部分是角速度![](Images/Omega.png)、實數部分與振幅相關，【系統特徵向量】也是複數值稱為模態(mode sharp)，兩者互爲共軛( Self-adjoint )的關係，並於微軟 Visual Studio 的開發環境上，使用CSharp程式語言專案執行和實作。    

### 如果實際去量測(measurement)角速度和模態時，角速度就是系統矩陣 A 的特徵值中的虛數值，模態就是特徵向量，分別是虛數和複數，但量測的數據是絕對值，因爲是絕對值，也就失掉【方向和動態】的特性了。

### 動態系統的計算 : 系統矩陣(或稱狀態矩陣) A 是【實數】，但求得的特徵值和特徵向量是【複數】，實數的部分與虛數的部分，必需完全整合在一起運算，不可將實數值和虛數值(即複數值)分開運算，也就是【複數矩陣】的運算，最後運算的結果是狀態空間變數的響應值(即時間軸上的振幅)，本軟體計算動態系統時，中間過程完全都是使用【複數矩陣】的運算，這也是本軟體的最大特色，最後的結果雖然是複數矩陣，但【本人】發現其虛數值為零，故可再轉爲實數值，回到【實數】與【真實】的世界了。  

<!--  myyeh2.github.com   --> 

#### 1. 本實例驗證參考 Dennis G. Zill, " Differential Equations with Boundary-Value Problems 9th edition "  Page 322 Example 1。  

#### 2. 本實例運算的數值結果，其繪圖係採用 Python 程式語言 Matplotlib 套件，但亦可使用 Excel 繪圖。  

#### 3. 多個實例驗證，請參考 [ 精 銳 矩 陣 計 算 求 解 器 ( GitHub 儲存庫 ) ](https://github.com/myyeh2/)  
