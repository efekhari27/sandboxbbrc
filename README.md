# sandboxbbrc
Bac à sable pour le projet du stage BBRC

Hi, 

I explored two different ways of adding together UserDefined distributions. I apply operations on my collection of UserDefined distributions $$F = (F_0,\dots, F_n)$$ to build an other collection of UserDefined $$S = (S_0, \dots, S_n)$$. $$S_p$$ is defined by reccurence $$\forall~p \in [0, n]$$:

$$
S_p = S_0 - \sum_{k=0}^{p-1} F_k + \sum_{k=0}^{p-\alpha-1} F_k, \alpha \in \mathbb{N}
$$

The second option is much faster and more compact. I also notice that since the distributions in the collection $$F$$ are close to be identical, the distribution $$S_k$$ seems to tend toward a Normal distribution.
