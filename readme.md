## Collective Github Repo for
# Big Data Algorithms 

quick mafs

$$1+1 = 2$$

**`Bernoulli distribution`** is a discrete Probability indicator.

Used to determine possible outcome of a single random experiment, success or failure

$$P(X=x) = p^x(1-p)^{1-x}$$

$$P(x) = \begin{cases}
\ \ \ \ \ \ \ \ p \ : \ x=1
\\
\ 1-p \ : \  x=0
\end{cases}$$
$$ q = 1-p $$

**`Expected Value/Mean`** $E(X)$ of Bernouli distribution is the arithmetic average of all the possible outcomes for random variable X, in this case, **success or failure only** 

$$ E(X) = \sum_{i=1}^n P(X_i) X_i $$ 

Weighted average of the outcomes: 

$$E(X) = P(X=1) \times 1 \ + P(X=0) \times 0$$
$$E(X) = p \times 1 + (1-p) \times 0 $$
$$E(X) = p $$




---
---
`anything above this line has been "reviewed and approved" by someone `

![img here](./assets/pagebreak.png)


`feel free to add any material relevant to the course below these lines, if it gets approved it'll be moved up to the main section `

---
---

with the mean, we can compute the Bernouli distribution **`Variance`**. It is the difference between the expected mean of $X^2$ and the expected mean squared:
 $$ Var(X) = E(X^2) - E(X)^2$$

$$ \rightarrow E(X^2) = P(X=1) \times 1^2 \ + P(X=0) \times 0^2 $$
$$ \rightarrow E(X^2)= p \times 1 + (1-p) \times 0 $$
$$ \rightarrow E(X^2) = p $$
$$ Var(X) = p - E(X)^2$$
$$ Var(X) = p - p^2 $$
$$ Var(X) = p(1-p) = pq $$




---








$$ 1 \le -999 \ ?\ ?\ ?\ ?\ ?\ ? $$






















![img here](./assets/pagebreak.png)

# Syntax examples


```
$$ \mathbb{E}[X] = \sum_{i=1}^{n} x_i \cdot p_i $$

$$ \mathbb{E}[X] = \frac{\displaystyle\sum_{i=1}^{n} x_i \cdot p_i}{\displaystyle\sum_{i=1}^{n} p_i} $$

$$ \mathbb{E}[X] = \int_{-\infty}^{\infty} xf(x) \, dx $$

$$ \mathbb{E}[X] = \frac{1}{n} \sum_{i=1}^{n} x_i $$

$$ \mathbb{E}[X] = \int_{-\infty}^{\infty} x \, dF(x) $$

```

renders

$$  \mathbb{E}[X] = \sum_{i=1}^{n} x_i \cdot p_i $$

$$ \mathbb{E}[X] = \frac{\displaystyle\sum_{i=1}^{n} x_i \cdot p_i}{\displaystyle\sum_{i=1}^{n} p_i} $$

$$ \mathbb{E}[X] = \int_{-\infty}^{\infty} xf(x) \, dx $$

$$ \mathbb{E}[X] = \frac{1}{n} \sum_{i=1}^{n} x_i $$

$$ \mathbb{E}[X] = \int_{-\infty}^{\infty} x \, dF(x) $$











![img here](./assets/pagebreak.png)

# Questions



![img here](./assets/pagebreak.png)


## some links to explore

[Coin Example](https://notebook.community/d00d/quantNotebooks/Notebooks/quantopian_research_public/drafts/Probability,%20expected%20value,%20and%20variance)

[bernouli distribution](https://www.wallstreetmojo.com/bernoulli-distribution/)

[god](https://chat.openai.com/chat)