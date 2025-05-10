## 1. BINARY OPERATIONS

**Binary Operation**    
A binary operation * on a set S is a function that associates to each ordered pair $$(s_1, s_2)$$ 
of elements of S to an element of S, denoted by $$s_1 * s_2$$.

**Commutativity And Associativity**
- $$*$$ is a commutative binary operation if $$s_1 * s_2 = s_2 * s_1$$ for every $$s_1, s_2 \in S$$.   
- $$*$$ is an associative binary operation if $$(s_1 * s_2) * s_3 = s_1 * (s_2 * s_3)$$ for every $$s_1, s_2, s_3 \in S$$.

## 2. GROUPS

**Group**           
G is set and * is a binary operation on G.      
This binary operation is associative.        
There is an identity element in G, e, such that $$x * e = e * x = x$$ for all $$x \in G$$.    
Every element in G x had an inverse y in G such that $$x * y = y * x = e$$.         
If * is commutative, (G, *) is an abelian group.    

**Lemma 2.1: The Division Algorithm**      
If $$a$$ and $$n$$ are integers and $$n$$ is positive and then there exist unique integers $$q$$ and $$r$$ such that
$$a=qn+r$$ and $$0 \leq r < n$$.     
q = quotient, r = remainder.

## 3. FUNDAMENTAL THEOREM ABOUT GROUPS

**Theorem 3.1: Uniqueness of Identity**      
If $$(G, *)$$ is a group, then there is only one identity element in G.

**Theorem 3.2: Uniqueness of Inverses**      
If $$(G, *)$$ is a group and x is any element of G, then x has only one inverse of G.

**Theorem 3.3: Inverse of Inverses**      
If $$(G, *)$$ is a group and x is any element of G, $$(x^{-1})^{-1} = x$$.

**Theorem 3.4: Inverse of Products**      
If $$(G, *)$$ is a group and x and y are any element of G, $$(x * y)^{-1} = y^{-1} * x ^ {-1}$$.

**Theorem 3.5: Only Inverses Multiply to Identity**        
If $$(G, *)$$ is a group and x and y are any elements of G. If $$x * y = e$$ or $$y * x = e$$. Then $$y = x^{-1}$$.

**Theorem 3.6: Cancellation Laws**        
If $$(G, *)$$ is a group and x, y and z are any elements of G. Then:     
1. If $$x * y = x * z$$, then $$y = z$$; and
2. If $$y * x = z * x$$, then $$y = z$$.

## 4. POWERS AND CYCLIC GROUPS

**Theorem 4.1: Power Laws**   
Let G be a group and let $$x \in G$$. Let m, n be integers. Then:
1. $$x^m x^n = x^{m+n}$$;
2. $$(x^n)^{-1} = x^{-n}$$;
3. $$(x^m)^n = x^{nm} = (x^n)^m$$

**Order and Finite Order**   
If G is a group and $$x \in G$$, then x is of finite order if there is a positive integer n such that $$x^n = e$$.      
If this integer exists, the smallest positive n for which this is true, is the order of x, $$o(x) = n$$.     
If not, we say x is of infinite order or $$o(x) = \infty$$

**Theorem 4.2: GCD as a Linear Combination**     
If m and n are integers, not both zero, then there exist integers x and y such that $$mx+ny = gcd(m,n)$$.
Thus the g.c.d. of m and n can be written as a linear combination of m and n, with integer coefficients.

**Theorem 4.3: Euclid**      
If $$r,s,t$$ are integers, r divides st, and gcd(r,s) = 1, then r divides t.

**Theorem 4.4: Euclid**      
Let G be a group and $$x \in G$$.
1. $$ord(x) = ord(x^{-1})$$
2. If $$ord(x) = n$$ and $$x^m = e$$, then n divides m.
3. If $$ord(x) = n$$ and $$gcd(m,n)=d$$, then $$ord(x^m) = n/d$$.

**Cyclic Group**      
A group G is cyclic if there is an element $$x \in G$$ such that G = { $$x^n | n \in Z$$ } and x is a generator of G.

**Theorem 4.5: Euclid**     
Let $$G=<x>$$. If $$ord(x) = \infty$$, then $$x^j \neq x^k$$ for $$j \neq k$$ and consequently G is infinite.         
If $$ord(x) = n$$, then $$x^j = x^i$$ iff $$j = k (mod n)$$, and consequently the distinct elements of G are $$e, x, x^2, ..., x^{n-1}$$.

**Theorem 4.6: Order of a Cyclic Group**         
If $$G=<x>$$, then $$|G|=ord(x)$$.

**Theorem 4.7: Cyclic -> Abelian**         
If G is a cyclic group, then G is abelian.

## 5. SUBGROUPS

**Subgroup**         
A subset H of a group (G,*) is a subgroup of G if the elements of H form a group under *.

**Theorem 5.1: Subgroup**         
Let H be a subset of a group G. Then H is a subgroup of G if and only if:
(a.) H is non-empty     
(b.) For all $$a,b \in H, ab \in H$$ and;
(c.) For all $$a \in H, a^{-1} \in H$$.

**Theorem 5.2: Subgroup of a Cyclic Group**         
If G is cyclic group, all the subgroups of G are cyclic.

**Theorem 5.3: Subgroup II**         
Let G be a group and let H be a finite nonempty subset of G. Then if H is closed under multiplication in G, H is a subgroup of G.

**Theorem 5.4: Union and Intersection**         
Let H and K be subgroups of a group G. Then:
(a.) $$H \cap K$$ is always a subgroup of G; and
(b.) $$H \cup K$$ is a subgroup of G iff one of H, K is contained in the other.

**Theorem 5.5: Subgroups of a Cyclic Group II**   
Let $$G = <x>$$ be a cyclic group of order n. Then:
(a.) For any positive integer m, G has a subgroup of order m if and only if m divides n.    
(b.) If in fact m does divide n, then G has a unique subgroup of order m.    
(c.) Two powers $$x^r$$ and $$x^s$$ of x generate the same subgroup of G and if and only if $$(r,n)=(s,n)$$.

**Theorem 5.6: Divisors and Subgroups**    
If $$G = <x>$$ is cyclic of order n and $$d_1, d_2, ..., d_{d(n)}$$ are the positive divisors of n, then $$(x^{d1}), (x^{d1}),..., (x^{d_{d(n)}})$$ are distinct subgroups of G.

**Theorem 5.7: Subgroups of an Infinite Cyclic Group**   
Let $$G = <x>$$ be an infinite cyclic group. Then $$(e), (x), (x^2), (x^3), ...$$ are all the distinct subgroups of G.

## 6. DIRECT PRODUCTS

**Theorem 6.1: LCM**       
Let $$G = G_1 \times G_2 \times ... \times G_n$$.     
(a.) If $$g_i \in G_i$$ for $$1 \leq i \leq n$$, and each $$g_i$$ has finite order, then $$ord((g_1, g_2, ..., g_n))$$ is the least common multiple of $$ord(g_1), ord(g_2), ..., ord(g_n)$$.
(b.) If each $$G_i$$ is a cyclic group of finite order, then G is cyclic iff $$|G_i|$$ and $$|G_j|$$ are relatively prime for $$i \neq j$$







