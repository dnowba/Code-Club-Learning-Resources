--- challenge ---
## 挑战：添加声音

多次测试你的项目。你可能注意到了有时同一个数字会在同一行中被选中两次（或者更多次），使得序列更加难以记忆。你能否在角色每次变换造型时播放一次鼓声？

你能否根据所选择的数字来播放不同的鼓声？这将与你变换角色造型的代码_十分_相似。

--- hints ---
--- hint ---
你可以通过仅向你角色现有的代码添加两个代码块来完成此次挑战！
--- /hint ---
--- hint ---
以下是你将需要的代码块：

![Hint drum blocks](images/hint-drumblocks.png)
--- /hint ---

--- hint ---
你完成的代码应如下所示：
```blocks
点击绿旗时
删除第 (全部 v) 项 \( [sequence v] \)
重复 (5) 次 
  新增项目 (随机取数 (1) 到 (4)) \( [sequence v] \)
  演奏节拍 (链表第 (last v) 项项目\( [sequence v] \) :: list) (0.25) 拍
  造型换成 (链表第 (last v) 项项目\( [sequence v] \) :: list)
  等待 (1) 秒
end
```
--- /hint ---

--- /hints ---

--- /challenge ---
