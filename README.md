#### 这是一篇论文的仿真复现程序
[1]Lin, Z. Q., et al. (2020). "Evolutionary accumulated temptation game on small world networks." Physica a-Statistical Mechanics and Its Applications 553.

《小世界网络上的累积诱惑博弈》

博弈模型矩阵为
$$
\left(\begin{array}{cc}1 & 0 \\ b_{i}^{t} & 0\end{array}\right)
$$


其中，
$$
b_{i}^{t+1}=\left\{\begin{array}{ll}b_{i}^{t} \times \bar{d}_{n_{i}, t}^{\alpha}, & s_{i}^{t}=C \\ b_{i}^{t} / \bar{d}_{n_{i}, t}^{\alpha}, & s_{i}^{t}=D\end{array}\right.
，
\bar{d}_{n_{i}, t}=\frac{1}{\left|\Omega_{i, t}^{c}\right|} \sum_{j \in \Omega_{i, t}^{c}} d_{j}
$$

