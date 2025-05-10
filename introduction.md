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




