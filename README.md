# dismathportfolio-rainbacani
dismathportfolio-rainbacani created by Classroom for GitHub

![](https://s3.amazonaws.com/files.digication.com/Md44dd9904e7fd145370066c3cd69f189.jpg)

##Week 1
 - Introduction to Dicrete Mathematics DISMATH: First thing in mind: "This term would be great because of DISMATH."
- That warm up problem about the knaves and knights was mind-blowing (it was crazy).
- I wonder who invented and started the study of discrete mathematics.
- No matter how I want to punch in the face, still, it's genius.
- Dismath only cares about mathematical truth and not other truths such us scientific and authoritative.
- Which is somehow reasonable because even authoritave and scientific people lie. 
- Mathematics never does so.
- I knew the word "proposition" in my english subject. 
- I never knew it can be so tricky when I encountered it in DISMATH.
- Proposition can be either true or false. 
- Which makes declarative sentences a proposition and imperative sentences not.
- DISMATH is like learning a whole new language especially when I saw unfamiliar things like ¬(not), ^(and), ∧(and), v(or),⊕ (ex or), →(implies to), and ↔(biconditional).
- Through proof table we proved that implication is equal to its contrapositive.
- p → q = ¬q → ¬p

##Week 2
- DISMATH is starting to affect the way I talk to people.
- This week, I learned that propositions can also be proved using Logical equivalences.
- Using logical equivalences is similar to identity laws in trigonometry.
- In DISMATH, there are also laws that we can use as a logical proof, such as

|         Name        |                           Equivalence                          |	
|:-------------------:|:--------------------------------------------------------------:|
|    Identity laws    |                      p ∧ T ≡ p<br>p v F ≡ p               |
|   Domination laws   |                       p v T ≡ T<br>p ∧ F ≡ F               |
|    Negation laws    |                     p v ¬p ≡ T<br>p ∧ ¬p ≡ F                   |
| Double negation law |                            ¬(¬p) ≡ p                           |
|   Idempotent laws   |                       p v p ≡ p<br>p ∧ p ≡ p               |
|   Commutative laws  |                   p v q ≡ q v p<br>p ∧ q ≡ q ∧ p               |
|   Associative laws  |       (p v q) v r ≡ p v (q v r)<br>(p ∧ q) ∧ r ≡ p ∧ (q ∧ r)   |
|  Distributive laws  | p v (q ∧ r) ≡ (p v q) ∧ (p v r)<br>p ∧(q v r) ≡ (p ∧ q) v (p ∧ r) |
|   De Morgan's laws  |              ¬(p ∧ q) ≡ ¬p v ¬q<br>¬(p v q) ≡ ¬p ∧ ¬q      |    |
|   Absorption laws   |                 p v (p ∧ q) ≡ p<br>p ∧ (p v q) ≡ p          |   |

- Another lesson I learned was **Quantifiers**
- Quantifiers indicates generality of the open sentence in which a variable occurs.
 - **Existential Quantifiers** indicates "there exists".
 - **Universal Quantifiers** indicates "for all".
- **When is it true? When is it false?**

|        **Quantifiers**       |           **When True**             |
|----------------------|-------------------------------|
|     ∀xP(x)    |    P(x) is true for every x    |
|     ∃xP(x)   |   There is an x for which P(x) is true  
|               |           **When False**            |
|     ∀xP(x)    |    There is an x for which P(x) is false   |
|     ∃xP(x)   |   P(x) is false for every x   |


- I also learned this week about **Predicate Logic**
- **Predicate logic** concerned its internal structure in terms of *subject* and *predicate*.
- Lastly, I've learned the terminologies for Rules of Inference:
- Argument - a sequence of statements that ends with a conclusion.
- Ex. (p1 ∧ p2 ∧ p3 ... ∧ pn) → q
 - Where (p1 ∧ p2 ∧ p3 ... ∧ pn) are the premises and q is the conclusion
- Valid - The conclusion of he argument must follow from the true of the preceding statements of the argument.
- Ex. (p1 ∧ p2 ∧ p3 ... ∧ pn) → q is TAUTOLOGY
- Tautology- A statement is ALWAYS true
- Fallacy - Invalid argument.

##Week 3
- There are **tools** that can be valid argumaents in propositional logic.
  - Truth Table (for less variables)
  - Logical equivalences
  - Quantifiers
  - Rules of Inference
- It is now clear to me that the validity of the argument is different from the thruthfulness of a conlusion.
- Validity focuses on the structure, while the truthfulness of the conlusion is guranteed if all the premises are true. 
- Because some arguments have more than two variables, using rules of inference instead of truth tables would help.
- We can use **rules of inference** as an alternative, the table is shown below:

|   **Rule of Inference**  |            **Tautology**           |          **Name**          |
|:--------------------|:------------------------------:|:----------------------:|
|       p<br>p→q<br>∴ q      |        (p ∧ (p → q)) → q       |      Modus Ponens      |
|     ¬q<br>p→q<br>∴ ¬p     |       (¬q ∧ (p → q)) → ¬p      |      Modus Tollens     |
|     p→q<br>q→r<br>∴ p→r    |  ((p → q) ∧ (q → r)) → (p → r) | Hypothetical Syllogism |
|      p∨q<br>¬p<br>∴ q      |       ((p ∨ q) ∧ ¬p) → q       |  Disjunctive Syllogism |
|       p<br>∴p ∨ q       |           p → (p ∨ q)          |        Addition        |
|       p ∧ q<br>∴ p       |           (p ∧ q) → p          |      Simplication      |
|      p<br>q<br>∴ p ∧ q     |      ((p) ∧ (q)) → (p ∧ q)     |       Conjunction      |
| p ∨ q<br>¬p ∨ r<br>∴ q ∨ r | ((p ∨ q) ∧ (¬p ∨ r)) → (q ∨ r) |       Resolution       | 

- I also learned that biconditional or the statement A if and only if B can be expressed as "A if B and A only if B".
- A ↔ B ≡ (A → B) ∧ (B → A)
- Where: A → B  is the expression for "A only if B"
- B → A is the expression for "A if B"

##Week 4
- January 27, 2016
- We practiced proving a 7-sentence argument using rules of inference.
- We let 's','c','w','t','h' to represent the propositions.
- being s = sunny
- c = colder
- w = swimming
- t = canoe trip
- h = home by sunset
- The premises stated were
- 1. ¬s ∧ c
- 2. ¬s → ¬w
- 3. ¬w → t
- 4. t → h
- ∴ h
- To prove it using Rules of inference
 - ¬s (Simplification of Premise 1)
 - w → s
   - ∴ ¬w   (m.t.)
     - ¬w → t 
      - ∴ t   (m.p.)
        - t → h
         - ∴ h   (m.p.)

- This week I also learned about the different methods of proof
- **Direct proof** (p → q)
  - Steps:
    - 1. Assume *p* is true.
    - 2. Show that *q* is also true (based on 1).
  - Ex. "If n is an integer, then n^2 is odd."
    - Odd number: {2k+1 | k ∈ Z}
    - Even number: {2K | k ∈ Z}

- Proof by Contraposition (Indirect)
 - p → q ≡ ¬q → ¬p
 - Steps for Contraposition
  - 1. Assume *¬q* is true.
    2. Show that *¬p* is also true.
   - This is usually used when *p* is more complicated than *q*.
  - Ex 1. "If n is an integer and 3n+2 is odd, then n is odd."
  - Ex 2. "If n=ab, where a and b are positive intergers, then a≤√n or b≤√n."  
- Vacuous and Trivial Proof
 - **Vacuous Proof** 
  - ¬p → (p → q)
  - Show that *p* is *false*, because *(p → q)* must be *true* when *p* is false.
   - Premise: ¬p ≡ T     
   - Conclusion: (p → q) ≡ T
    - *(p → q) is true when p is false*
  - Ex. "If 6 is a prime number, then 6^2=30."
    - It is a **vacuous proof** because the first and second statement are both *false*.
 - **Trivial Proof** (q → (p → q))
  - Show that *q* is *true*, it follows that *(p → q)* must also be *true*.
  - Ex. "If there are 30 students enrolled in this course this semester, then 6^2=36."
   - Premise: q ≡ T     
   - Conclusion: (p → q) ≡ T 
    - It is a **trivial proof** because the first statement is *vague*, while the second statment is clearly *true*.
- Proof by Contradiction (Indirect)
 -Kind of tricky when the premise has two propositions
 - Steps:
    1. Assume the WHOLE premise is false *¬(premise)*≡T.
    2. Show that (1) will end up in a *contradiction*.


## Week 5

- **proof by contradiction**.
  - Ex 1. Prove that √2 is irrational by giving a proof by contradiction.
    - Rational number: {a/b | a, b ∈ Z, b≠0, *a, b does not have common factor except ±1 (or in lowest terms)}
- From example #2 of proof by contradiction it leads us to **negation of implication**.
- **Negation of Implication** (¬(p → q) → (p ∧ ¬q))
- **Contradiction and Implication**
  - “If *p* s true, then *q* is true” using a **proof by contradiction**:
    1. Assume that *p≡T* and that *q≡F*.
    2. Derive a contradiction.
    3. Conclude that if *p* is *true*, *q* must be *as well*.
- **Proof by Equivalence (Biconditionals)**
  - To prove a theorem that is a biconditional statement *(p ↔ q)*, we show that: *(p → q) → [(p → q) ∧ (q → p)]*
  - Ex 1. "If n is an integer, n is even iff n^2 is even." (r ↔ s)
    - For biconditional statement, we should prove (r → s) and (s → r) are both *true*.

## Week 6

- Today I learned about **Proof by Equivalence (Biconditionals)**
  - Example: Statement 1. "If n is a positive integer, then n is odd if and only if n^2 is odd."
  - Statement 2. For any natural number n, n is even if and only if n^2 is even.
  - Show that these statements about the integer _n_ are equivalent:
    - P1: n is even
    - P2: n-1 is odd
    - P2: n^2 is even.
  - To do this we have to prove P1 ↔ P2, P1 ↔ P3, and P2 ↔ P3 are all true.

- *Counterexample* - It is an example that disproves a universal ("for all") statement.
  - Ex. Prove or disprove the following theorem: 
    - Every positive integer is the sum os the squares of two integers.
      - The statement is *false* due to *counterexample*
- **Mathematical Induction**
  - Like a domino:
  ![myimage-alt-tag]http://www.appsgare.com/wp-content/uploads/2015/03/Domino.jpg)
  - If it started true, and it stays true, then it will always be true.
    - P(1), P(2), P(3), P(k), P(k+1), ...
  - Steps:
    1. Basic step: Show *P(1) ≡ T
      - ![](http://www.gifbin.com/bin/022013/1361304798_dominoes_launch_fail.gif)
        - *If P(1) is false, then the entire domino pile fails!*
    2. Inductive step (via Direct proof): 
      - Assume *P(k)* is true.
      - Show that is also *P(k+1)* true.
  - *Q.E.D. (quod erat demonstrandum)* - "which is what had to be proven" or signals the completion of the proof.
  - Ex. Prove P(n) = 1 + 2 + 3 + … + n = n(n+1)/2
    - 1. Prove P(1) is true
    - 2. Direct proof
      - a. Assume P(k) ≡ T
        - P(k) = 1 + 2 + 3 + … + k = k(k+1)/2
      - b. Show P(k + 1)
        - P(k + 1) = 1 + 2 + 3 + … + k + (k + 1) = (k+1)(k+2)/2
        - P(k + 1) = k(k+1)/2 + k + 1 =  (k+1)(k+2)/2
        - P(k + 1) = (k+1)(k + 2)/2 =  (k+1)(k+2)/2
 - Ths week, we also learned about program correctness or verification.
    - 1. Show that the program produces the correct output (partial correctness).
    - 2. Show that the program always terminates.
 - Partial correctness
    - P: Initial assertion = T
    - s: if ___________
    -    else _________
    - q: Final assertion =T
 - Hoare Triple
    - p { S } q = T
 - Rules of inference
    - proves that a program is correct by spliting the program into subprograms.
     - p { S1 } q 
     - q { S2 } r 
     - ∴ p { S1; S2 } r  --> Composition Rule
 - Conditional Statement
    - ( P ∧ condition ) { S } q    ---> Case I
    - ( P ∧ ¬condition ) → q       ---> Case II
    - ∴ p { if condiition then S } q
 - If else statement
    - ( P ∧ condition ) { S1 } q    ---> Case I
    - ( P ∧ ¬condition ) { S2 } q       ---> Case II
    - ∴ p { if condiition then S1 else S2 } q

## Week 7
  -  This week, we were intorduced to set theory.
  - Set is an unordered collection of distinct objects (including other sets)
     - Ex.
     - Set notation" { A, B, C, D }
     - Diclaimer: A program is not a set because order is very important.
     - Some clarifications
        - { A, B, C, D } ↔ { B, D, C, A }
        - { A, B } ↔ { A, A, B, B, A }
        - 0 != { 0 }
        - 3 != { 3 }
        - A ∈ { A, B, C, D }
  - **Function**
  - Let X & Y be sets. A function f from X to Y is an assignment of exactly one element of B to each element of A
  - We denote f: X → Y or f: X to Y
  - X for domain
  - Y for Co-Domain (Can be called as Range when a particular subset B is connected from set A)
  - Examples:
      - f(x) = x^2 (Domain x ∈ ℤ f: ℤ to ℤ+ (Co-domain; not shown) "Perfect Square" (Range; not shown)
      - int floor (float x) { } Domain: float x (float → ℝ) ℝ Range: int floor (int → ℤ) ℤ
  - Types of Function:
     - One-to-One (Injective) - ∀x∀y(f(x)=f(y) → x=y) and ∀x∀y(x≠y → f(x)≠f(y))
     - Onto (Surjective) Range = Co-domain (and must be filled)
     - One-to-one and Onto (Bijection)
     ----------------------------------------------------------------------------------
 - Another lesson in this week was Algorithms, and this would be the main focus of the quiz number 2.
 - Algorithm is a finite set of instructions for performming a computations.
   - An algorithm has some qualifications/ properties.
     - Properties of Algorithms
      - INPUT
      - OUTPUT
      - DEFINITENESS
      - CORRECTNESS
      - FINITENESS 
      - EFFECTIVENESS 
      - GENERALITY
  Here are some algorithms I learned:
      - Finding the Maximum Element in a Finite Sequence.
      - procedure max(a1, a2, . . . , an: integers)
      - max := a1
      - for i := 2 to n
           - if max < ai then max := ai
      - return max{max is the largest element
      
## Week 8
  - This week we continued our discussion on algrorithms.
    - The Linear Search Algorithm.
    - procedure linear search(x: integer, a1, a2, . . . , an: distinct integers)
    - i := 1
    - while (i ≤ n and x = ai )
    - i := i + 1
    - if i ≤ n then location := i
    - else location := 0
    - return location{location is the subscript of the term that equals x, or is 0 if x is not found}
  - Another Searching algorithm is the Binary Search.
  - It is more efficient than linear search in terms of time complexity.
  - But way more inconvinient for student like me because the algorithm is more complex.
  - The Binary Search Algorithm.
  - procedure binary search (x: integer, a1, a2, . . . , an: increasing integers)
  - i := 1{i is left endpoint of search interval}
  - j := n {j is right endpoint of search interval}
   - while i < j
      - m := (i + j)/2
      - if x > am then i := m + 1
      - else j := m
   - if x = ai then location := i
   - else location := 0
   - return location{location is the subscript i of the term ai equal to x, or 0 if x is not found
  - This week I also learned sorrting algorithms.
  - The Bubble Sort.
      - procedure bubblesort(a1, . . . , an : real numbers with n ≥ 2)
      - for i := 1 to n − 1
      - for j := 1 to n − i
      - if aj > aj+1 then interchange aj and aj+1
      - {a1, . . . , an is in increasing order}
  - The Insertion Sort.
  - procedure insertion sort(a1, a2, . . . , an: real numbers with n ≥ 2)
  - for j := 2 to n
     - i := 1
     - while aj > ai
         - i := i + 1
     - m := aj
     - for k := 0 to j − i − 1
       - aj−k := aj−k−1
     - ai := m
     - {a1, . . . , an is in increasing order}
 
## Week 9
  - I learnied this week that algorithms can also be greedy.
  - Greedy algorithms teach the computer to decide or choose for the best.
  - (I HOPE THERE IS ALSO A GREEDY ALGORITH TO TEACH HUMANS TO DO SO.)
  - Greedy Change-Making Algorithm.
    - procedure change(c1, c2, . . . , cr : values of denominations of coins, where c1 > c2 > · · · > cr ; n: a positive integer)
    - for i := 1 to r
       - di := 0 {di counts the coins of denomination ci used}
       - while n ≥ ci
         - di := di + 1 {add a coin of denomination ci}
         - n := n − ci
    - {di is the number of coins of denomination ci in the change for i = 1, 2, . . . , r}
  - Algorithms can not only be gredy, but they can also grow.
  - (How wish everyone just choose to grow up.)

![](growth.JPG)
  - BIG O NOTATION
  - Let f and g be functions from R-R; f(x) is O(g(x)) 
  - We can take C and k as witnesses such that: |f(x)| ≤ C|g(x)| whenever x > k
  - EXAMPLE 2 Show that 7x2 is O(x3).
  - Solution: Note that whenx > 7, we have 7x2 < x3.(We can obtain this inequality by multiplying both sides ofx > 7 by x2.)
  - Consequently, we can take C = 1 and k = 7 as witnesses to establish
  -  Big-O Estimates for Some Important Functions
    - Let f (x) = anx^n + an−1x^n−1 +· · ·+a1x + a0, where a0, a1, . . . , an−1, an are real numbers.
    - Then f (x) is O(x^n).
    - 1 + 2 + 3+· · ·+n is O(n2)
    - n! is O(n^n)
    - log n is O(n).
  - Big Omega Notation
    -  Because Big O cannot express the lower bound, we use big Omega notation.
       - Let f and g be functions from R-R; f(x) is O(g(x)) 
       - We can take C and k as witnesses such that: |f(x)| ≥ C|g(x)| whenever x < k.
       - f (n) is (n2).
  - Big Theta Notation
    - For both lower bound and upper bound.
  - Algorithm, aside from being greedy, or  growing, the can also be complex.
  
![](meme.jpg)
  - Time Complexity
  - The time complexity of an algorithm can be expressed in terms of the number of operations used by the algorithm when the input has a particular size.
  - Commonly Used Terminology for the complexity of Algorithms.

| Complexity  |   Terminology  |
|:-----------:|:--------------:|
| (1) | Constant  complexity  |
| (log n) | Logarithmic complexity |
| (n) | Linear complexity |
| (n log n) | Linearithmic complexity |
| (n^b) | Polynomial complexity |
| (b^n), where b > 1 | Exponential complexity |
| (n!) | Factorial complexity |

    

  
  

 → ∧ ¬ ∴ ↔

- note: Week count starts with Wednesdays
- Credits to owners of some tables and images
 


Well, another quiz is coming. But still..
*GOD IS GOOD, ALL THE TIME.*
*ALL THE TIME, GOD IS GOOD.*

