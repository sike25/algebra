### Group
(G *) is a group iff G is closed under *, has an identity element. Each element as inverse in G.

(G *) is an abelian group means * is commutative.

### Division Algorithm 
For any integers a, b, there exists integers q, r such that we can write: a = bq + r where r is between 0 and b - 1 (inclusive).
a = dividend, b = divisor.

Proof given

### Properties of Groups
1. Identity elements and inverses are unique.
2. For all x in G, (x')' = x
3. For all x, y in G, (xy)' = y'x'
4. If x, y in G satisfy xy = e then x = y' and y = x'
5. If x, g in G with xg = x, then g = e

Proof given

### Cancellation Laws
Given G is a group and x, y, z are in G,
1. If xy = xz then y = z
2. If yx = zx then y = z

Proof given

### Corollary
Given G is a group and g in G.   
If f1, f2: G -> G such that f1(x) = gx and f2(x) = xg, then f1, f2 are one-to-one and onto.   

Equivalently, for all y in G
1. There exists uniquely x1 in G such that gx1 = y
2. There exists uniquely x2 in G such that x2g = y

Proof given

### Cyclic Groups and Generators
Let G be a group. Suppose there exists a in G such that for all g in G, there exists m in Z such that g = a^m.    
Then we say a is a generator for G and G is cyclic.

### Cyclic -> Abelian
G is a cyclic group implies G is abelian

Proof given

### Order
1. Order of a group (or |G|, #G) is the number of elements in G.
2. Order of an element g in G  (or o(g)) is the smallest integer n greater than or equals 1 such that g^n = 2, or infinity if such n does not exist.

### Order Theorem
G is a group and g in G then order(g) = |{g}|

Proof given

### n divides m
Let n, m be integers. We say n divides m (n|m) if there exists an integer m = nq

### Order Theorems
G is a group and x in G. Let m, n be integers. 
1. If order(x) = n (greater equal to  1) and x^m = e, then n|m.
2. order(x) = order(x')
3. If order(x) = n then order(x^m) = n / gcd(m, n)

Proof given.

### Order Divides Proposition
G is a group and g in G. Then the following are true:
1. order(g) = inf <-> for all j, k integers, a^j = a^k iff j = k
2. order(g) = n   <-> for all j, k integers, a^j = a^k iff j = k (mod n)

Proof given

### Greastest Common Denominator
Let m, n integers both not zero. The gcd of m and n is the largest positive integer d such that d|m and d|n

### Coprime
Integers m, n are coprime or relatively prime iff gcd(m, n) = 1

### gcd theorem
Let m, n integers both not zero. Then there exists x, y integers such that gcd(m,n) = mx + ny. 
x,y are not unique and can be found with the euclidean algorithm

### Subgroup
Let (G *) be a group. If H subset of G and H is also a group, H is a subgroup of G.

### Intersection of subgroups
Let G be a group with H, K subgroups. (H n K) is a subgroup of G (and H, K)

Proof given

### Subgroup of a Cyclic Group
Let G be a cyclic group with a subgroup H. H is also cyclic.

### Subgroups of a Cyclic Group
Let G  = {a} be a cyclic group with order n. Then:
1. For all integers m, m|n <-> G has a subgroup H with |H| = m
2. This subgroup of order m is unique
3. For all r, s integers, we have {a^r} = {a^s} <-> gcd(r,n) = gcd(s,n)

### Corollary
The subgroups of Cn are for each k >= 1 with k|n, {n/k}

### Center of G
Z(G) = { z in G | gz = zg for all g in G }

### Center of g
Z(g) = { z in G | gz = zg }

### Direct Product
Let G, H be groups.   
G x H = { (g,h) | g, h in G } is the direct product of G and H with operation (g1 h1) * (g2 h2) = (g1g2 h1h2)
G x H is a group.

Let G1,...,Gn be groups.    
G1x...xGn = { (g1...gn) | gi, for all i in 1..n } with operation (g1...gn)(h1...hn) = (g1h1...gnhn) 
is a group called the direct product of G1...Gn.

### Direct Products and Subgroups
If A subset of G and B subset of H are subgroups, then A x B is a subgroup of G x H

### Direct Products and Abelian
G = G1 x ... x Gn is abelian <-> Each Gi is abelian

### Direct Products and Cyclic
G = G1 x ... x Gn is cyclic -> Each Gi is cyclic

### LCM and GCD
lcm(m,n) = mn / gcd(m,n)

### Order of a Direct Product
order[(g1...gn)] = lcm[order(g1)...order(gn)] or infinity if any order(gi) = infinity

### 










