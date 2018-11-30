# Extended Technology Application

## *Maximum Sustainable Harvest*

In certain situations, biologists are able to determine what is called a *reproduction curve*. This is a function

> $y = f(P)$

such that if $P$ is the population after $P$ years, then $f(P)$ is the population a year later, at time $t + 1$.

&emsp; The line $y = P$ is significant because if it ever coincides with the curve $f(P)$, then we know that the population stays the same from year to year. Here the graph of $f$ lies mostly above the line, indicating that the population is increasing.  
&emsp; Too many deer in a forest can deplete the food supply and eventually cause the population to decrease for lack of food. Often in such cases and with some controversy, hunters are allowed to "harvest" some of the deer. Then with a greater food supply, the remaining deer population might actually prosper and increase.  
&emsp; We know that a population $P$ will grow to a population $f(P)$ in a year. If this were a population of fur-bearing animals and the population were increasing, then hunters could "harvest" the amount

> $f(P) - P$

each year without shrinking the initial population $P$. If the population were remaining the same or decreasing, then such a harvest would deplete the population.  
&emsp; Suppose that we want to know the value of $P_0$ that would allow the harvest to be the largest. If we could determine that $P_0$, we could let the population grow until it reached that level and then begin harvesting year after year the amount $f(P_0) - P_0$.

&emsp; Let the harvest function $H$ be given by

> $H(P) = f(P) - P$.

Then
> $H'(P) = f'(P) - 1$.

Now, if we assume that $H'(P)$ exists for all values of $P$ and that there is only one critical value, it follows that the *maximum sustainable harvest* occurs at that value $P_0$ such that

> $H'(P_0) = f'(P_0) - 1 = 0$

and
> $H''(P_0) = f''(P_0) < 0$.

Or, equivalently, we have the following.
> `THEOREM`  
> ---
> The **maximum sustainable harvest** occurs at $P_0$ such that  
>
> &emsp; &emsp; $f'(P_0) = 1$ and $f''(P_0) < 0$,  
> 
> is given by  
> 
> &emsp; &emsp; $H(P_0) = f(P_0) - P_0$.
