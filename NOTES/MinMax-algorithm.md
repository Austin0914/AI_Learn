# MinMax-algorithm
## 簡介
常用於有敵我雙方之分對弈的棋類遊戲中
## 核心概念
就是在我方回合最大化我方得分
敵方回合讓得分最小化
## Game Tree
表達遊戲中所有的可能性
將其建立成一棵樹
子樹代表父節點的所有可結果
![image](https://user-images.githubusercontent.com/87524840/165886005-3aafc638-d2dc-4c61-9a69-a8f837c99e1d.png)
## Alpha-Beta 剪枝法 (α - β pruning)
簡單的意義就是降低無效的演算<br>
如果麼一個節點發現不已經是最優的答案就可以<br>
不計算子樹的所有可能<br>
有點像是Greedy的感覺<p>

![image](https://user-images.githubusercontent.com/87524840/165886218-504dd1a5-d73f-4c4b-9db8-334c84a3bfa0.png)

