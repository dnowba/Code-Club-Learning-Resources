--- challenge ---
## 挑战：更多障碍
如果你认为你的游戏仍太过简单，你可以向你的关卡添加更多障碍。你可以添加任何你喜欢的东西，以下是一些想法：

+ 一只飞行的蝴蝶杀手；
+ 能出现和消失的平台；
+ 必须躲避的坠落网球。

![screenshot](images/dodge-obstacles.png)

你甚至可以创建多个背景，然后在你的角色到达绿门时进入下一个关卡：

```blocks
	如果 <碰到颜色 [#00FF00] ?> 那么 
    背景换成 [next backdrop v]
    定位到 x: (-210) y: (-120)
    等待 (1) 秒
  end
```




--- /challenge ---
