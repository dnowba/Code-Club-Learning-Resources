## 挑戰：看誰最快到 10 分

你可以改變遊戲規則嗎？看看玩家能多快答對 10 個問題，而不是看玩家在 30 秒內能回答幾個問題。

要進行這樣的變更，只需要修改計時部分的程式就可以了。你能看出有哪些積木不同嗎？

```blocks3
    當收到訊息 (開始 v)
    變數 [計時 v] 設為 (30)
    重複直到 <(計時) = (0)>
        等待 (1) 秒
        變數 [計時 v] 改變 (-1)
    end
    廣播訊息 (結束 v)
```