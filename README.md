# dismathportfolio-Chris-Mayo
dismathporfolio-Chris-Mayo- created by Classroom for GitHub

#DISCRETE MATHEMATICS PORTFOLIO



# Week 1
- Introduction to Discrete Mathematics ( DISMATH ) which is understanding more about the knowledge closer to the machines ( the commands and the Binary: 0 and 1 )
- I've learned that PROPOSITION is a statement that is "True" or "False" but not both






# Week 2 ( 1st meeting; 1/25 )

- I've learned about the Logical Connectives and its truth tables

| **LOGICAL SYMBOL** | **LOGICAL OPERATOR** | **SIMPLE TERM** | **FORMULA** |   **LOGICAL EQUATION**     |
|:------------------:|:--------------------:|:-------------:|:-----------:|:----------------------------:|
| ¬  |Negation|not|val(¬p)= 1 - val(p)|¬p|
|^|Conjunction|and|val (p ^ q) = min(val(p), val(q))|p^q|
| v |Disjunction| or | val(p  v q) = max(val(p), val(q))|p v q|
|⊕ |Exclusive Disjunction| xor | if val(p) not equal val(q) = 1 ,otherwise 0 | p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |

- Conjunction ( ^ ) is the minimum value; Disjunction ( v ) is the maximum value; Exclusive or ( ⊕ ) ≡ (p v q) ∧ (¬p v ¬q)

# Week 2 ( 2nd Meeting; 1/27 )

| **LOGICAL SYMBOL** | **LOGICAL OPERATOR** | **SIMPLE TERM** | **FORMULA** |   **LOGICAL EQUATION**     |
|:------------------:|:--------------------:|:-------------:|:-----------:|:----------------------------:|
| → | Conditional | if then | if val(p) ≤ val(q) = 1, otherwise 0| p → q ≡  ¬p v q |
|↔ | Biconditional | iff | if val(p) equals val(q) = 1, otherwise 0 | p ↔ q ≡ (p → q) ∧ (q → p) |
  
  
- Conditional ( → ) when q is True = True, and when p is false = True; Biconditional is NEGATED XOR ¬(p ⊕ q) ≡ p ↔ q

- I've also learned about the Logic Laws and Logical Equivalences ( Implication Equivalence: p → q = ¬p v q )
- When proving it is important to develop a series of logical equivalences

| **NAME** |  | |
|:------------------:|:--------------------:|:-------------:|
| **Identity Laws**  |p ∨ F ≡ p|p ∧ T ≡ p|
|**Domination Laws**|p ∨ T ≡ T|p ∧ F ≡ F|
| **Negation Laws** |p ∧ ¬p ≡ F| p ∨ ¬p ≡ T |
|**Double Negation Laws** |(¬(¬p) ≡ p)| |
|**Idempotent Laws** | p ∨ p ≡ p| p ∧ p ≡ p|
|**Commutative Laws** |p ∨ q ≡ q ∨ p| p ∧ q ≡ q ∧ p|
|**Associative Laws** |(p ∨ q) ∨ r ≡ p ∨ (q ∨ r)|(p ∧ q) ∧ r ≡ p ∧ (q ∧ r)| 
|**Distributive Laws** |p ∨ (q ∧ r) ≡ (p ∨ q) ∧ (p ∨ r) 	|p ∧ (q ∨ r) ≡ (p ∧ q) ∨ (p ∧ r)|
|**De Morgan's Laws** |¬(p ∧ q) ≡ ¬p ∨ ¬q | ¬(p ∨ q) ≡ ¬p ∧ ¬q|
|**Absorption Laws** 	 |p ∨ (p ∧ q) ≡ p| p ∧ (p ∨ q) ≡ p|



 


# Week 3 ( 1st Meeting; 2/1 )

- I've learned about Converse, Inverse and Contrapositive **FROM p → q**; **Converse** is **q → p**; **Inverse** is **¬p → ¬q**; **Contraposition** is the **negation of Converse** **¬q → ¬p**

- Tautology = Always true in all conditions

- Quantifiers ( Existential and Universal ) **Existential ( ∃x )** is easy to prove, hard to disprove; when at least one domain is True, it can be true ; while **Universal ( ∀x )** is hard to prove, easy to disprove in which all conditions must be true to consider it Universally true



# Week 3 ( 2nd Meeting 2/3 )

- I've learned about the Rules of Inferences 
- Arguments = sequence of statements **THAT END** with A **CONCLUSION** ; Valid - if there is a tautology that depends on the sequence pattern ; Fallacy = if it is not valid


| **TAUTOLOGY** | **NAME** |
|:------------------:|:--------------------:|
|(p ∧ (p → q)) → q | **Modus Ponens** |
|(¬q ∧ (p → q)) → ¬p | **Modus Tollens** |
|((p → q) ∧ (q → r)) → (p → r) | **Hypothetical Syllogism** |
|((p ∨ q) ∧ ¬p) → q | **Disjunctive Syllogism** |
|p → (p ∨ q) | **Addition** |
|(p ∧ q) → p | **Simplification** |
|((p) ∧ (q)) → (p ∧ q) | **Conjunction** |
|((p) ∧ (q)) → (p ∧ q) | **Resolution** |







# Week 4 ( 1st Meeting NO CLASS; 2nd Meeting 2/10 )

- We are introduced to **Proofs** specifically **Direct Proofing** where We **Assume P is TRUE** and **Show that Q is TRUE**
- Another type of Proof: **Indirect Proof or Contraposition** was discussed where **Assumpe ¬Q is TRUE** and **Show that ¬P is TRUE**






# Week 5 ( 1st Meeting 2/15; 2nd Meeting NO CLASS 2/17 )

- Other methods of proving were discussed: **Vacuous Proof ( Also having Trivial Proof ), Proof by Contradiction and Proof by Equivalence**
- In Vacuous Proof, if **P is FALSE, then the implication is TRUE** while in Trivial Proof, **if Q is TRUE, then the implication is TRUE** 
- In Proof by Contradiction, **We show that ¬PREMISE is true and show that at least one of its statement and rule will be violated so the it will be proven true**
- In Proof by Equivalence, it is the concept of combination of the previous proofs






# Week 6 ( 1st Meeting 2/22; 2nd Meeting NO CLASS 2/24 )

- We've discussed about **Mathematcal Induction** where there are 2 procedures: 1st is the **BASIS: where we show P(1) is TRUE**, 2nd is the **INDUCTIVE STEP:** Using **Direct Proof**, A) we **Assume that P(k) is TRUE** and **Show that P(k+1) is TRUE** ( based on A )
- **Recursive / Induction Definition** was also discussed where there is also the **Basis Step: where you specify the value at the function at zero** and the **Recursive Step/Inductive Step: where you define the next term using the previous term** 
 





# Week 7 ( 1st Meeting 2/29 )
- We are Introduced to Set Theory ( remember that Program is no a set ) **Set** = unordered collection of distinct objects (may include other sets)
- **Subset** - A set S is a subset of a set T Denotes:**(S ⊆ T)** if all elements of S are also elements of T
- **Cardinality** - the number of elements that the set contains
- We've discussed about the terms from Algebra: **Union, Intersection, Set Difference and Symmetric Difference**
- **Union A ∪ B** - objects that **belong to Set A or Set B** ; Example: {x|(x∈A) ∨ (x∈B)}
- **Intersection A ∩ B** - also objects that **belong to set A or Set B** ; Example: {x|(x∈A) ∧ (x∈B)}
- **Set Difference A - B or A \ B** - objects that **belong to A and NOT to B** ; Example: {x|(x∈A) ^ (x∉B)}
- **Symmetrical Difference A∆B** - objects that **belong to A or B but not to their intersection**; Example: {x|((x∈A) ∧ (x∉B)) ∨ ((x∈B) ∧ (x∉A))}
- Cardinality of Natural Numbers ( is infinity ) is called **Alephnought or Alephnull or Aleph-zero**

# Week 7 ( 2nd Meeting 3/2 )

- Introduction to Sets ( where I'm having a confusion )
- Difference between Domain, Co Domain and Range were discussed
- There are 3 Types of Functions: **One to One (Injective), Onto Fuction (Surjective), One to One Correspondence (Bijective)**
- **One to One (Injective)** - Functions that never assign the same value to two different domain elements; No value in the range is used by more than one value in the domain
- **Onto Function (Surjective)** -  Functions have equal range and codomain; For every value in the codomain, there is a value in the domain that is mapped to it ( Everythings assigned to Y )
- **One to One Correspondence (Bijective)** - When a function is both Injective and Surjective





# Week 8 ( 1st Meeting 3/7 )

- Introduction to **Algorithm** ( which is a finite ste of precise instructions for performing a computation or for solving a problem )
- **Precondition** ( statements that describe valid output ) and **Postcondition** ( conditions that the output should satisfy when the program has run ) was discussed
- Pseudocode that contains: Procedure, Input, Output and The Body
- The Properties of Algorithm are: Input, Output, Definiteness, Correctness, Finiteness, Generality
- **Searching Algorithm** is about locating an element in a ordered list
 
# Week 8 ( 2nd Meeting 3/9 ) 

- Two types of **Searching Algorithm** was discussed: **Linear and Binary*8
- Two types of **Sorting Algorithm** was also discussed: **Bubble Sort and Insertion Sort**





# Week 9 ( 1st Meeting 3/14 )

- **Greedy Algorithm**: selecting the best choice for each step, instead of considering all seuqences of steps that may lead to an optimal solution ( An example would be from coin change )
- Growth of Functions ( Big O Notation ) that requires witnesses ( Constant C and k ); also the Upperbound of the function
- X-axis is for the input and Y-axis is for the Number of operation

# Week 9 ( 2nd Meeting 3/16 )

- Continued Discussion for Big O Notation with more examples
- I've missed the Time Complexity topic that will be included in Quiz # 2 ( Which is the Next Meeting )






# Week 10 ( 1st Meeting 3/21 QUIZ #2 ) 







# Week 11 ( 1st Meeting 3/28 )

- **Graph Theory** was discussed ( A graph is a discrete structure consisting of vertices (nodes, points) and edges(lines, connections) that connect these vertices )
- Graph G consist of **Vertices/Nodes** ( endpoints of graph ) and **Edges** ( connection between 2 Vertices/Nodes )
- Degree: A Vertex with a number of edges incident with it ( Loop = 2 edges )
- **Handshake Theory: 2e=∑deg(v)** then Solve for e ( Number of Edges )
- **Path:** a sequence of edges, as long as you can connect the nodes, there is a path, no edge means no path
- **Subgraph:** Elements are only taken from Graph, "Subset" to the original vertices & edges
- **Union:** Connecting Vertices & Edges of two graphs
 
# Week 11 ( 2nd Meeting 3/30 )
- Continue the Discussion about Graph Theory in PArticualt Starting with Euler Circuit and Euler Path
- To be considered as a **Euler PATH:** a graph should have EXACTLY 2 nodes/vertices with ODD degree
- To be considered as a **Euler CIRCUIT:** a graph should have ONLY EVEN degree for all nodes/vertices
- We also talked about the **Hamilton Circuit and Hamilton Path* ( The difference is that Euler are for Edges and Hamilton are for Vertices/Nodes )
- There is **no Hamilton Path if there are 2 Pendants** ( Pendant is a vertex/node with 1 degree )
- Adjacency Matrix was discussed to help us graph using the given matrix ( and vice versa )
- The Isomorphism of Graphs is when two graphs are still the same when the orientation changes
- Planar Graphs is done by making the edges not cross each other ( Remember that K3 / Petersen Graph and K5 are not Planar )
- **Eulers Formula: r = e - v + 2** ( Where r is the number of regions, e is the number of edges and v is the number of matrices; Formula is used to solve for Number of regions )
- **Kuratowski's Theorem** is when a graph is nonplanar iff it contains a subgraph homeomorphic (simply deleting nodes based on the exiting connection / subset to the original graph ) to the following graph






# Week 12 ( 1st Meeting 4/4 QUIZ# 3 )

 
# Week 12 ( 2nd Meeting  4/6 )

- **Graph Coloring** was discussed and ADJACENT regions couldnt have the same color
- The Chromatic number of a graph is the **LEAST** number of colors needed for a coloring of this graph
- **Four Color Theorem** - states that the chromatic number of a planar graph is no greater than four
- When given a cycle, if the number of vertices is **even**, then the **chromatic number is 2**, if it is **odd**, then the **chromatic number is 3**
- A K5 has a chromatic number of 5 and a k6 has a chromatic number of 6
- **Tree** - is a connected undirected graph with no simple circuits
- **Forest** - when there are two or more trees in a graph
- Some terminologies related to trees: parent, siblings, child, ancestors, descendants, leaf, and internal vertices
- The tree is called a **full m-ary tree** if every internal vertex has exactly **m children**
- A tree with n vertices has **n-1 edges**
- A Full m-ary tree with i internal vertices contains **n = mi + 1 vertices**
- A **Full m-ary tree** : **n vertices has i - (n-1) / m internal vertices; l = [(m-1) n+1] / m leaves**
- From Full m-ary Tree: **i internal vertices has n = mi + 1 vertices and l = (m-1)i + 1 leaves**
- Still from Full m-ary Tree: **L leaves has n = (ml-1) / (m-1) vertices and i = (l-1) / (m-1) internal vertices**
- Automata - studies the law of Computation




