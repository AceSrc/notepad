# determinant
行列式的计算, 用Leibniz formula:

$$
det(A)=\sum_{\sigma\in S_{n}} sgn(\sigma) \prod_{i=1}^{n} a_{i, \sigma_{i}}
$$

## determinant and Permutation
easy to know that, 全一矩阵的行列式的值为$$n!$$, 同时$$n$$个元素的排列个数也是$$n!$$

而且Leibniz公式中也出现了$$n$$个元素的所有排列构成的集合$$S_{n}$$, 所以我们是否能够考虑, 用行列式这一工具, 去抽象化一些排列相关的题目呢?

### 排列的个数
把$$n$$个元素进行排列, 假设我们只允许某些位置放某些元素, 定义$$n$$阶矩阵$$A$$为:

$$
A_{i, j}=\begin{cases} 1 \quad \text{j can be placed at i} \\ 0 \quad \text{j can't be placed at i} \end{cases}
$$

通过手(wan)算(quan)数(bu)据(suan), 我们可以发现, $$det(A)$$就是合法的排列的个数! 我们记作$$cnt$$.

那么我们需要一点小小的证明:

首先先证明$$ det(A) \leq cnt$$.
$$
  \sum_{\sigma\in S_{n}} sgn(\sigma) \prod_{i=1}^{n} a_{i, \sigma_{i}} =...
$$
(作者表示写着写着不想写了就先放着吧.)

