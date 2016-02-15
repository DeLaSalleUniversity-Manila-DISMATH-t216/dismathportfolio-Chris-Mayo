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

- 


