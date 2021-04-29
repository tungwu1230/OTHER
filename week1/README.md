
# Python挑戰 Week 1

> 挑戰者: Benson  
> 截止日期: 2021/4/30

## 任務內容
+ 建立一個猜數字的函數，可放入兩個參數min和max  
+ 當呼叫該函數時，產生min~max的隨機數，並讓玩家開始猜數字遊戲
+ 告訴玩家猜數字範圍，當玩家輸入數字時，告訴玩家是否答對  
+ 若玩家答對則遊戲結束，並顯示玩家正確答案及猜題次數  
+ 若答錯則讓玩家繼續猜，並提示玩家新的猜數字範圍
  1. 若猜數字範圍為1-100
  2. 正確答案是35，玩家答20，提示玩家新範圍20-100
  3. 正確答案是35，玩家答80，再次提示玩家新範圍20-80

## Hint:
 `random.randint(a,b)` #可產生a~b之間隨機數，使用前需`import random`  

## 預計學會的技巧
1. 建立函數
2. while迴圈
3. `random.randint()`
4. `if...elif...if` 流程控制


## 呈現方式
1. 呼叫猜數字函數
2. 試玩一輪

```python
guessing(1,100)
```

    
    答案位於1~100之間
    請猜數字: 50
    
    答案位於1~50之間
    請猜數字: 35
    
    答案位於1~35之間
    請猜數字: 20
    
    答案位於20~35之間
    請猜數字: 30
    
    答案位於30~35之間
    請猜數字: 33
    恭喜答對，正確答案是33，您猜了5次

## 答案與作答結果
[Tung Ans](https://nbviewer.jupyter.org/github/tungwu1230/OTHER/blob/main/week1/Guessing%20Number%20Game.ipynb)  
[Benson Ans](https://nbviewer.jupyter.org/github/tungwu1230/OTHER/blob/main/week1/Guessing%20Number%20Game%20Benson.ipynb)
