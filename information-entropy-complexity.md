# Shannon Entropy
----
## property
- the amount of information of event X depends on it's probability $P_x$.
- Continuity: $I(p)$ is a continuous function of $p$.
- Additivity: $I(p_x, p_y)$ = $I(p_x) + I(p_y)$ for independent events X
and Y.

Due to the additivity, for any rational r = s/t, 

$$
I(p_x^r)=rI(p_x)
$$

Therefore, continuity yields 

$$
I(p_x) = I((\frac{1}{2})^{-log_2(p_x)}) = -log_2(p_x)I(\frac{1}{2})
$$

## Definition

**if X is a random varible over a set of events x such that event x occurs with probability $p_x$, then the Shannon entropy of event x is $-{\rm {log}}_2(p_x)$.**
