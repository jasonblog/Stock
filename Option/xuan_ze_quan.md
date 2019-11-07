# 選擇權

![](images/option.png)


---


邏輯很簡單： 

假如可口可股價為60元 

我就去sell 履約價為55元的put， 

```
case1 
如果結算的時候股價<=55， 
我就賺到權利金，並且強迫用55的價格買進股票價股票， 
所以現在持有100股可口可樂的股票。 
此時sell call， 
假設sell 履約價為60元的call 
case1-1 
如果結算的時候股價>=60元， 
就會被強迫賣掉股票， 
獲利為 (60-55)+sell call的權利金 
case1-2 
如果結算的時候股價<60元， 
就賺sell call的權利金 

case2 
如果結算價股票>55元， 
賺sell put的權利金。 

此策略羅即很間單， 
但只適用股價長期成長的股票， 
如果股票一直破底再破底，並不適用這個策略。 
```


我會參考巴菲特的持股， 
http://warren-buffett-portfolio.com/ 

或是綠腳推薦的標的， 
VT,BWX,VEU,VTI,IEI,VGK,VPL,VWO,WIP,TIP