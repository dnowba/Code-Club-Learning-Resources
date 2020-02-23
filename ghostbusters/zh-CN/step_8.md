## 添加倒计时

现在你需要添加一个倒计时器，使玩家在只有10秒钟的时间内抓住尽可能多的幽灵。

--- task ---

新建一个叫“时间”的变量。

--- /task ---

--- task ---

你能在舞台上添加一个倒计时器以只给玩家10秒的时间来抓幽灵吗？

你的倒计时器应当：

+ 初始设置10秒
+ 按秒倒计时

当倒计时器为0时游戏结束。

--- hints ---
 --- hint --- `当绿旗被点击`{:class="block3events"}，你的`时间`{:class="block3variables"}变量应当被`设为10`{:class="block3variables"}。 然后它应该每秒被`增加 -1`{:class="block3variables"}`直到为0`{:class="block3control"}。
--- /hint ---
 --- hint --- 这些是你需要使用的代码块： ![幽灵角色](images/ghost-backdrop.png)

```blocks3
当 ⚑ 被点击

停止 [全部脚本]

< [ ] = [ ] >

将 [时间 v] 设为 [10]

将 [时间 v] 增加 (-1)

(时间)

等待 (1) 秒

重复执行直到 < >
```

--- /hint --- --- hint --- 以下是创建倒计时器所需要的代码：![背景图标](images/ghost-backdrop.png)

```blocks3
当 ⚑ 被点击
将 [时间 v] 设为 [10]
重复执行直到 < (时间) = [0] >
等待 (1) 秒
将 [时间 v] 增加 (-1)
end
停止 [全部脚本]
```

--- /hint ------ /hints ---

--- /task ---

--- task ---

请一位朋友测试你的游戏。 他们可以等到几分？

--- /task ---

如果你的游戏太简单，你可以：

+ 给玩家更少的时间
+ 减少幽灵的出现频率
+ 让幽灵变小点

--- task ---

反复修改并测试你的游戏，直到你觉得难度适中为止。

--- /task ---