## 7. FUNCTIONS

**Function**    
If S and T are sets, then a function f from S to T assigns to each $$s \in S$$ a unique element $$f(s) \in T$$.

**Injective and Surjective**       
Let $$f:S \to T$$ be a function.        
f is onto (surjective) if for each $$t \in T$$ there is at least one $$s \in S$$ such that $$f(s) = t$$.    
f in one-to-one (injective) if whenever $$s_1, s_2$$ are two different elements in S, we have $$f(s_1) \neq f(s_2)$$.

**Theorem 7.1: Group of Bijective Transformations**    
Let X be a nonempty set, and let $$S_X$$ denote the set of all one-to-one onto mappings $$f:X \to X$$.    
$$S_X$$ is a group under composition.

## 8. SYMMETRIC GROUPS

**Symmetric Group on X**        
The symmetric group on X is $$S_X$$.

**Theorem 8.1: Function As A Product Of Disjoint Cycles**       
Let $$f \in S_n$$. Then there exist disjoint cycles $$f_1, f_2, ..., f_m \in S_n$$ such that $$f = f_1 \cdot f_2 \cdot ... \cdot f_m$$.

**Theorem 8.2: Cycle As A Product of Transpositions**     
If $$n \geq 2$$, then any cycle in $$S_n$$ can be written as a product of transpositions.

**Theorem 8.3: Function As A Product of Transpositions**     
If $$n \geq 2$$, then any element in $$S_n$$ can be written as a product of transpositions.    
This follows from theorem 8.1 and 8.2.

**Odd and Even Permutations**     
A permutation is even if it can be written as the product of an even number of transpositions.     
A permutation is odd  if it can be written as the product of an odd  number of transpositions.   

**Theorem 8.4: Parity is Mutually Exclusive**     
No permutation is both even and odd.

**Theorem 8.5: Alternating Group of Degree N**     
Let $$n \geq 2$$. Then $$A_n$$ is a subgroup of $$S_n$$ called the alternating group of degree n.     
Note that $$|S_n| = n!$$ and $$|A_n| = n!/2$$.

## 9. EQUIVLENCE RELATIONS AND COSETS

**Equivalence Relation**    
A relation R on S is called an equivalence relation on S if R has the following three properties.       
(a.) Reflexivity: For every $$s \in S, s R s$$;       
(b.) Symmetry: For every $$s_1, s_2 \in S$$, if $$s_1 R s_2$$, then $$s_2 R s_1$$;         
(c.) Transitivity: For every $$s_1, s_2, s_3 \in S$$, if $$s_1 R s_2$$ and $$s_2 R s_3$$, then $$s_1 R s_3$$.  

**Equivalence Class**      
For any $$s \in S$$, let $$\overline{s} = [x \in S | x R s]$$ and this is the equivalence class of s under R.

**Theorem 9.1: Equivalence Classes Partition**    
Let R be an equivalence relation on S. Then every element of S is in exactly one equivalence class under R. That is, the 
equivalence classes partition S into a family of mutually disjoint non-empty subsets.






