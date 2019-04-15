## 两天之前

- 上午

  > 我们默认你有如下基础:……(多项式全家桶)……

  $[\text{\color{grey}{LMOliver}\color{black}{已掉线}}]$
  
- 下午
  
  <span class="cf-black-red">kcz</span>的杂题选讲~~，还是听不懂~~。
  
  (窝太菜了，因此就没有什么可以说的东西QAQ)

## 一天之前

- 上午

  不同阶莫队好妙啊~

  大于$k$的与小于等于$k$的直接合并？QAQ

  然后看了一下讲义预览。

  > Warning:"水题"与"Ynoi"互斥
  
  果然后面还是掉线了。

  中途被大佬安利了**雀魂**。

- 下午
  
  ~~还是想听模拟退火和遗传算法~~
  
  $1k$行的期望$O(n+m)$最小生成树算法！

看来我爆零预定了。

## Day 1

### T1

对麻将的热情消失殆尽。(雀魂玩家$-1$)

记忆化搜索似乎跑得飞快，看上去难道可以过$n=13$？

### T2

每次操作可以视为以$\frac{1}{2}$概率执行，
考虑维护每个点有$\text{Tag}$的概率。

发现一个点有$\text{Tag}$，要么是直接被标记的，要么是从祖先传下来的。
所以要维护每个点自己是$\text{Tag}$的概率和祖先中有$\text{Tag}$的概率。

然后直接处理标记下传，注意一个点被直接标记时会更新所有子孙祖先有$\text{Tag}$的概率，要打标记。

然后陷入艰苦的调试。

然后发现做法假了。

祖先中有$\text{Tag}$的概率 $\rightarrow$ 自己没$\text{Tag}$且祖先中有$\text{Tag}$的概率。

继续调试。

过大样例了，打上文件操作，去看**T3**。

### T3

$\text{DP}$ing……

只剩下半个小时了，脑子里一团浆糊，最后一分钟打完$10$分暴力。

### 总结

技不如人，甘拜下风。