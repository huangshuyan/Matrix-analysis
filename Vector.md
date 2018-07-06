# Vector

#### Basics

+ vectors are writen in column format usually.

#### Vector space

+ A ***vector space***  $\chi$ is obtained by equipping vectors with the operations of + and $\times$  by scalar.

#### Subspaces and span

+ A nonempty subset  $\nu$ of a vector space $\chi$ is called a ***subspace*** of $\chi$, if for any scalars $\alpha, \beta$,  x, y $\in \ \nu \ \Rightarrow \ \alpha x+\beta y \in \nu$.  
+ span(S) is the set of all possible linear combinations of the vectors in S = {$x^{(1)},…,x^{(m)}$} forms a subspace.

#### Bases and dimensions

+ *Linearly independent* if no vectors in the collection can be expressed as a linear combination of the others. 
+ A ***basis*** of $S$ is a set of $B$ of vectors of minimal cadinality, such that $span(B)=S$. The **cardinality** of a basis is called *the dimension of $S$*.   

#### Affine sets

+ $A=\{x\in\chi:x=v+x^{(0)},v\in \nu \}$ where $x^{(0)}$ is a given point and $\nu$ is a given subspace of $\chi$. (一个过点$x^{(0)}$的平面)
+ A *line* is a one-dimensional affine set. The line through $x_0$ along direction $u$ is the set $L = \{x\in\chi:x=x_0+v,v\in span(u)\}$, where in this case span(u) = {$\lambda u: \lambda\in \mathbb{R}$}. 

#### Euclidean length

$$
x \dot{=} \sqrt{x_1^2+x_2^{2}+...+x_n^{2}}.
$$

直线长度

####  Norms and $l_p$ norms

$$
\|x\|_p \dot{=} ( \sum_{k=1}^n|x_k|^p)^{1/p}, 1\leq p \lt \infty.
$$

+ p = 2 is the standard Euclidean length
+ p = 1 is the sum-of-absolute-values length
+ p = $\infty$ defines the $\|x\|_\infty \dot{=} \max_{k=1,…n} |x_k|.$
+ $\|x\|_0$ is the cardinality of a vector x. $l_0$ (pseudo) norm.

#### Inner product



















