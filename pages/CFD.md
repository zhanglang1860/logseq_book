public:: true

- 一本介绍OpenFoam 机理的文章 **underlying mathematics** [005](bookxnotepro://opennote/?nb={d462ec64-a84d-4b1e-bd75-946e8e091f85}&book=7ee49bc17847c31cae95d64f60f4fd33&page=4&x=262&y=86&id=1)
	- 所有的守恒公式都可以通过FVE推导出来( **首先**推导出 [[质量守恒]] 与 [[动力守恒]] )，然后推导出来 [[能量方程]]
	- 都是由一般的控制方程，得出其他类型的方程。
- 先看一些概念：
- [[牛顿体剪切力]] $$\tau$$
- [[柯西应力张量]] $$\sigma$$
- [[雷诺平均]] 和[[雷诺应力方程]]
- [[涡流粘性理论]]the equation for theturbulent kinetic energy $$k$$ and dissipation $$\epsilon$$ are deducted [005](bookxnotepro://opennote/?nb={d462ec64-a84d-4b1e-bd75-946e8e091f85}&book=7ee49bc17847c31cae95d64f60f4fd33&page=4&x=252&y=281&id=12)
- 书籍的最后是关于一些剪切力的计算方法。提及一些数值稳定性的概念。numerical stabilization [005](bookxnotepro://opennote/?nb={d462ec64-a84d-4b1e-bd75-946e8e091f85}&book=7ee49bc17847c31cae95d64f60f4fd33&page=4&x=370&y=355&id=13)
  id:: 60a81716-5851-4f01-a8ea-5bced553cb95
-
  ---
- 涉猎到不同的压力项与公式耦合的问题。最终引出**The PIMPLE-algorithm** [005](bookxnotepro://opennote/?nb={d462ec64-a84d-4b1e-bd75-946e8e091f85}&book=7ee49bc17847c31cae95d64f60f4fd33&page=4&x=185&y=382&id=14)
-
-