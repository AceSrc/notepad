# mobius

if

$$
F(n) = \sum_{d | n}f(d) 
$$

then 

$$
f(n) = \sum_{d | n} \mu(d) F(\frac{n}{d}) 
$$

Some important Properties:

$$
\sum_{d | n} \mu(d) = \begin{cases} 0 \quad n = 1 \\ 1 \quad n \gt 1 \end{cases}
$$

$$
\sum_{d | n} \frac{\mu(d)}{d} = \frac{\phi(n)}{n}
$$
