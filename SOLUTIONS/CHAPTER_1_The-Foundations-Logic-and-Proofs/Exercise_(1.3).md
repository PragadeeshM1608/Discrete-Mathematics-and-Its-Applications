# Exercise 1.3
****
>### Solutions 
[1](#1) [2](#2) [3](#3) [4](#4) [5](#5) [6](#6) [7](#7) [8](#8) [9](#9) [10](#10) [11](#11) [12](#12) [13](#13) [14](#14) [15](#15) [16](#16) [17](#17) [18](#18) [19](#19) [20](#20) [21](#21) [22](#22) [23](#23) [24](#24) [25](#25) [26](#26) [27](#27) [28](#28) [29](#29) [30](#30) [31](#31) [32](#32) [33](#33) [34](#34) [35](#35) [36](#36) [37](#37) [38](#38) [39](#39) [40](#40) [41](#41) [42](#42) [43](#43) [44](#44) [45](#45) [46](#46) [47](#47) [48](#48) [49](#49) [50](#50) [51](#51) [52](#52) [53](#53) [54](#54) [55](#55) [56](#56) [57](#57) [58](#58) [59](#59) [60](#60) [61](#61) [62](#62) [63](#63) [64](#64) [65](#65) [66](#66) [67](#67) [68](#68) [69](#69) [70](#70) [71](#71) [72](#72) <b>[END](#end)</b>


<div id="1">

#### Question no. 1

<b>a.</b>
- p ⋀ T ↔ p, as verified using a truth table.

    | P | P ⋀ T |
    |-------|-------|
    | T | T |
    | F | F |


<b>b.</b>
- p ⋁ F ↔ p, as verified using a truth table.
  
    | P | P ⋁ F |
    |-------|-------|
    | T | T |
    | F | F |



<b>c.</b>
- p ⋀ F ↔ F, as verified using a truth table.
  
    | P | P ⋀ F |
    |-------|-------|
    | T | F |
    | F | F |



<b>d.</b> 
- p ⋁ T ↔ T, as verified using a truth table.
  
    | P | P ⋁ T |
    |-------|-------|
    | T | T |
    | F | T |



<b>e.</b>
- p ⋁ p ↔ p, as verified using a truth table.
  
    | P | P ⋁ P |
    |-------|-------|
    | T | T |
    | F | F |



<b>f.</b>
- p ⋀ p ↔ p, as verified using a truth table.
  
    | P | P ⋀ P |
    |-------|:-------:|
    | T | T |
    | F | F |



</div>


<div id="2">

#### Question no. 2

- ¬(¬p) ↔ p, verified using a truth table.
  
    | P | ¬P | ¬(¬P) |
    |-------|-------|:-------:|
    | T | F | T |
    | F | T | F |


</div>


<div id="3">

#### Question no. 3

<b>a.</b>
- Table for P ⋁ Q ↔ Q ⋁ P:

    | P | Q | P ⋁ Q | Q ⋁ P | P ⋁ Q ↔ Q ⋁ P |
    |-------|-------|-------|-------|:-----------------:|
    | T | T | T | T | T |
    | T | F | T | T | T |
    | F | T | T | T | T |
    | F | F | F | F | T |

<i>p ⋁ q ↔ q ⋁ p, showing that OR is commutative.</i>

<b>b.</b>
- Table for P ⋀ Q ↔ Q ⋀ P:

    | P | Q | P ⋀ Q | Q ⋀ P | P ⋀ Q ↔ Q ⋀ P |
    |-------|-------|-------|-------|:-----------------:|
    | T | T | T | T | T |
    | T | F | F | F | T |
    | F | T | F | F | T |
    | F | F | F | F | T |

<i>p ⋀ q ↔ q ⋀ p, showing that AND is commutative.</i>

</div>


<div id="4">

#### Question no. 4

<b>a.</b>
- Table for (P ⋁ Q) ⋁ R ↔ P ⋁ (Q ⋁ R):

    | P | Q | R | P ⋁ Q | (P ⋁ Q) ⋁ R | Q ⋁ R | P ⋁ (Q ⋁ R) | (P ⋁ Q) ⋁ R ↔ P ⋁ (Q ⋁ R) |
    |-------|-------|-------|-------|---------------|-------|---------------|:-----------------------------:|
    | T | T | T | T | T | T | T | T |
    | T | T | F | T | T | T | T | T |
    | T | F | T | T | T | T | T | T |
    | T | F | F | T | T | F | T | T |
    | F | T | T | T | T | T | T | T |
    | F | T | F | T | T | F | F | T |
    | F | F | T | F | T | T | T | T |
    | F | F | F | F | F | F | F | T |

<i>(p ⋁ q) ⋁ r ↔ p ⋁ (q ⋁ r), showing associativity of OR.</i>

<b>b.</b>
- Table for (P ⋀ Q) ⋀ R ↔ P ⋀ (Q ⋀ R):

    | P | Q | R | P ⋀ Q | (P ⋀ Q) ⋀ R | Q ⋀ R | P ⋀ (Q ⋀ R) | (P ⋀ Q) ⋀ R ↔ P ⋀ (Q ⋀ R) |
    |-------|-------|-------|-------|---------------|-------|---------------|:-----------------------------:|
    | T | T | T | T | T | T | T | T |
    | T | T | F | T | F | F | F | T |
    | T | F | T | F | F | F | F | T |
    | T | F | F | F | F | F | F | T |
    | F | T | T | F | F | T | F | T |
    | F | T | F | F | F | F | F | T |
    | F | F | T | F | F | F | F | T |
    | F | F | F | F | F | F | F | T |

<i>(p ⋀ q) ⋀ r ↔ p ⋀ (q ⋀ r), showing associativity of AND.</i>

</div>


<div id="5">

#### Question no. 5

- Table for p ⋀ (q ⋁ r) ↔ (p ⋀ q) ⋁ (p ⋀ r):

    | P | Q | R | Q ⋁ R | P ⋀ (Q ⋁ R) | P ⋀ Q | P ⋀ R | (P ⋀ Q) ⋁ (P ⋀ R) | P ⋀ (Q ⋁ R) ↔ (P ⋀ Q) ⋁ (P ⋀ R) |
    |-------|-------|-------|-------|-------------------|-------|-------|-------------------------|:-------------------------------------:|
    | T | T | T | T | T | T | T | T | T |
    | T | T | F | T | T | T | F | T | T |
    | T | F | T | T | T | F | T | T | T |
    | T | F | F | F | F | F | F | F | T |
    | F | T | T | T | F | F | F | F | T |
    | F | T | F | T | F | F | F | F | T |
    | F | F | T | T | F | F | F | F | T |
    | F | F | F | F | F | F | F | F | T |

<i>p ⋀ (q ⋁ r) ↔ (p ⋀ q) ⋁ (p ⋀ r), verified using a truth table.</i>

</div>


<div id="6">

#### Question no. 6

- Table for ¬(P ⋀ Q) ↔ (¬P ⋁ ¬Q):

    | P | Q | P ⋀ Q | ¬(P ⋀ Q) | ¬P | ¬Q | ¬P ⋁ ¬Q | ¬(P ⋀ Q) ↔ (¬P ⋁ ¬Q) |
    |-------|-------|-------|-------------|-------|-------|-----------|:-------------------------:|
    | T | T | T | F | F | F | F | T |
    | T | F | F | T | F | T | T | T |
    | F | T | F | T | T | F | T | T |
    | F | F | F | T | T | T | T | T |

<i>¬(p ⋀ q) ↔ (¬p ⋁ ¬q), which is the first De Morgan law.</i>

</div>


<div id="7">

#### Question no. 7

<b>a.</b> <i>¬(Jan is rich ⋀ Jan is happy) ↔ (Jan is not rich ⋁ Jan is not happy).</i>

<b>b.</b> <i>¬(Carlos will bicycle ⋁ Carlos will run) ↔ (Carlos will not bicycle ⋀ Carlos will not run).</i>

<b>c.</b> <i>¬(Mei walks ⋁ Mei takes the bus) ↔ (Mei does not walk ⋀ Mei does not take the bus).</i>

<b>d.</b> <i>¬(Ibrahim is smart ⋀ Ibrahim is hard working) ↔ (Ibrahim is not smart ⋁ Ibrahim is not hard working).</i>

</div>


<div id="8">

#### Question no. 8

<b>a.</b> <i>¬(Kwame takes a job ⋁ Kwame goes to graduate school) ↔ (Kwame does not take a job ⋀ Kwame does not go to graduate school).</i>

<b>b.</b> <i>¬(Yoshiko knows Java ⋀ Yoshiko knows calculus) ↔ (Yoshiko does not know Java ⋁ Yoshiko does not know calculus).</i>

<b>c.</b> <i>¬(James is young ⋀ James is strong) ↔ (James is not young ⋁ James is not strong).</i>

<b>d.</b> <i>¬(Rita moves to Oregon ⋁ Rita moves to Washington) ↔ (Rita does not move to Oregon ⋀ Rita does not move to Washington).</i>

</div>


<div id="9">

#### Question no. 9

<b>a.</b>
- Table for p → ¬q ↔ ¬p ⋁ ¬q:

    | P | Q | ¬Q | P → ¬Q | ¬P | ¬P ⋁ ¬Q | P → ¬Q ↔ ¬P ⋁ ¬Q |
    |-------|-------|-------|-----------|-------|-----------|:-------------------------:|
    | T | T | F | F | F | F | T |
    | T | F | T | T | F | T | T |
    | F | T | F | T | T | T | T |
    | F | F | T | T | T | T | T |

<i>p → ¬q ↔ ¬p ⋁ ¬q.</i>

<b>b.</b>
- Table for (p → q) → r ↔ (p ⋀ ¬q) ⋁ r:

    | P | Q | R | P → Q | (P → Q) → R | ¬Q | P ⋀ ¬Q | (P ⋀ ¬Q) ⋁ R | (P → Q) → R ↔ (P ⋀ ¬Q) ⋁ R |
    |-------|-------|-------|-------|---------------|-------|---------|-------------------|:-------------------------------------:|
    | T | T | T | T | T | F | F | T | T |
    | T | T | F | T | F | F | F | F | T |
    | T | F | T | F | T | T | T | T | T |
    | T | F | F | F | F | T | T | T | F |
    | F | T | T | T | T | F | F | T | T |
    | F | T | F | T | F | F | F | F | T |
    | F | F | T | T | T | T | F | T | T |
    | F | F | F | T | F | T | F | F | T |

<i>(p → q) → r ↔ (p ⋀ ¬q) ⋁ r.</i>

<b>c.</b>
- Table for (¬q → p) → (p → ¬q) ↔ ¬p ⋁ ¬q:

    | P | Q | ¬Q | ¬Q → P | P → ¬Q | (¬Q → P) → (P → ¬Q) | ¬P | ¬P ⋁ ¬Q | (¬Q → P) → (P → ¬Q) ↔ ¬P ⋁ ¬Q |
    |-------|-------|-------|-----------|-----------|---------------------------|-------|-----------|:-------------------------------------:|
    | T | T | F | T | F | F | F | F | T |
    | T | F | T | T | T | T | F | T | T |
    | F | T | F | F | T | T | T | T | T |
    | F | F | T | F | T | T | T | T | T |

<i>(¬q → p) → (p → ¬q) ↔ ¬p ⋁ ¬q.</i>

</div>


<div id="10">

#### Question no. 10

<b>a.</b>
- Table for ¬p → ¬q ↔ p ⋁ ¬q:

    | P | Q | ¬P | ¬Q | ¬P → ¬Q | P ⋁ ¬Q | ¬P → ¬Q ↔ P ⋁ ¬Q |
    |-------|-------|-------|-------|-----------|-----------|:-------------------------:|
    | T | T | F | F | T | T | T |
    | T | F | F | T | T | T | T |
    | F | T | T | F | F | F | T |
    | F | F | T | T | T | T | T |

<i>¬p → ¬q ↔ p ⋁ ¬q.</i>

<b>b.</b>
- Table for (p ⋁ q) → ¬p ↔ ¬p:

    | P | Q | P ⋁ Q | ¬P | (P ⋁ Q) → ¬P | (P ⋁ Q) → ¬P ↔ ¬P |
    |-------|-------|-------|-------|-------------------|:-------------------------:|
    | T | T | T | F | F | T |
    | T | F | T | F | F | T |
    | F | T | T | T | T | T |
    | F | F | F | T | T | T |

<i>(p ⋁ q) → ¬p ↔ ¬p.</i>
- Table for (p → ¬q) → (¬p → q) ↔ p ⋁ q:

    | P | Q | ¬Q | P → ¬Q | ¬P | ¬P → Q | (P → ¬Q) → (¬P → Q) | P ⋁ Q | (P → ¬Q) → (¬P → Q) ↔ P ⋁ Q |
    |-------|-------|-------|-----------|-------|-----------|---------------------------|-------|:-------------------------------------:|
    | T | T | F | F | F | T | T | T | T |
    | T | F | T | T | F | F | F | T | F |
    | F | T | F | T | T | T | T | T | T |
    | F | F | T | T | T | F | F | F | T |

<i>(p → ¬q) → (¬p → q) ↔ p ⋁ q.</i>

</div>


<div id="11">

#### Question no. 11

<b>a.</b>
- Table for (p ⋀ q) → p:

    | P | Q | P ⋀ Q | (P ⋀ Q) → P |
    |-------|-------|-------|:-------------------:|
    | T | T | T | T |
    | T | F | F | T |
    | F | T | F | T |
    | F | F | F | T |

<i>(p ⋀ q) → p is a tautology.</i>

<b>b.</b>
- Table for p → (p ⋁ q):

    | P | Q | P ⋁ Q | P → (P ⋁ Q) |
    |-------|-------|-------|:-------------------:|
    | T | T | T | T |
    | T | F | T | T |
    | F | T | T | T |
    | F | F | F | T |

<i>p → (p ⋁ q) is a tautology.</i>

<b>c.</b>
- Table for ¬p → (p → q):

    | P | Q | ¬P | P → Q | ¬P → (P → Q) |
    |-------|-------|-------|-----------|:-----------------------:|
    | T | T | F | T | T |
    | T | F | F | F | T |
    | F | T | T | T | T |
    | F | F | T | T | T |

<i>¬p → (p → q) is a tautology.</i>

<b>d.</b>
- Table for (p ⋀ q) → (p → q):

    | P | Q | P ⋀ Q | P → Q | (P ⋀ Q) → (P → Q) |
    |-------|-------|-------|-----------|:--------------------------:|
    | T | T | T | T | T |
    | T | F | F | F | T |
    | F | T | F | T | T |
    | F | F | F | T | T |

<i>(p ⋀ q) → (p → q) is a tautology.</i>

<b>e.</b>
- Table for ¬(p → q) → p:

    | P | Q | P → Q | ¬(P → Q) | ¬(P → Q) → P |
    |-------|-------|-----------|-------------|:-----------------------:|
    | T | T | T | F | T |
    | T | F | F | T | T |
    | F | T | T | F | T |
    | F | F | T | F | T |

<i>¬(p → q) → p is a tautology.</i>

<b>f.</b>
- Table for ¬(p → q) → ¬q:

    | P | Q | P → Q | ¬(P → Q) | ¬Q | ¬(P → Q) → ¬Q |
    |-------|-------|-----------|-------------|-------|:-------------------------:|
    | T | T | T | F | F | T |
    | T | F | F | T | T | T |
    | F | T | T | F | F | T |
    | F | F | T | F | T | T |

<i>¬(p → q) → ¬q is a tautology.</i>

</div>


<div id="12">

#### Question no. 12

<b>a.</b>
- Table for [¬p ⋀ (p ⋁ q)] → q:

    | P | Q | ¬P | P ⋁ Q | ¬P ⋀ (P ⋁ Q) | [¬P ⋀ (P ⋁ Q)] → Q |
    |-------|-------|-------|-------|---------------------|:---------------------------:|
    | T | T | F | T | F | T |
    | T | F | F | T | F | T |
    | F | T | T | T | T | T |
    | F | F | T | F | F | T |

<i>[¬p ⋀ (p ⋁ q)] → q is a tautology.</i>

<b>b.</b>
- Table for [(p → q) ⋀ (q → r)] → (p → r):

    | P | Q | R | P → Q | Q → R | (P → Q) ⋀ (Q → R) | P → R | [(P → Q) ⋀ (Q → R)] → (P → R) |
    |-------|-------|-------|-----------|-----------|---------------------------|-----------|:-------------------------------------:|
    | T | T | T | T | T | T | T | T |
    | T | T | F | T | F | F | F | T |
    | T | F | T | F | T | F | T | T |
    | T | F | F | F | F | F | F | T |
    | F | T | T | T | T | T | T | T |
    | F | T | F | T | F | F | T | T |
    | F | F | T | T | T | T | T | T |
    | F | F | F | T | F | F | T | T |

<i>[(p → q) ⋀ (q → r)] → (p → r) is a tautology.</i>

<b>c.</b>
- Table for [p ⋀ (p → q)] → q:

    | P | Q | P → Q | P ⋀ (P → Q) | [P ⋀ (P → Q)] → Q |
    |-------|-------|-----------|---------------------|:---------------------------:|
    | T | T | T | T | T |
    | T | F | F | F | T |
    | F | T | T | F | T |
    | F | F | T | F | T |

<i>[p ⋀ (p → q)] → q is a tautology.</i>

<b>d.</b>
- Table for [(p ⋁ q) ⋀ (p → r) ⋀ (q → r)] → r:

    | P | Q | R | P ⋁ Q | P → R | Q → R | (P ⋁ Q) ⋀ (P → R) ⋀ (Q → R) | [(P ⋁ Q) ⋀ (P → R) ⋀ (Q → R)] → R |
    |-------|-------|-------|-------|-----------|-----------|-------------------------------|:-------------------------------------:|
    | T | T | T | T | T | T | T | T |
    | T | T | F | T | F | F | F | T |
    | T | F | T | T | T | T | T | T |
    | T | F | F | T | F | T | F | T |
    | F | T | T | T | T | T | T | T |
    | F | T | F | T | T | F | F | T |
    | F | F | T | F | T | T | F | T |
    | F | F | F | F | T | F | F | T |

<i>[(p ⋁ q) ⋀ (p → r) ⋀ (q → r)] → r is a tautology.</i>

</div>

<div id="13">

#### Question no. 13

<i>Each conditional in Exercise 11 is false only if its hypothesis is true and its conclusion is false. In every case, whenever the hypothesis is true, the conclusion is also true. Therefore, none of the conditionals can be false, so each is a tautology.</i>

</div>


<div id="14">

#### Question no. 14

<i>Each conditional in Exercise 12 is false only when the hypothesis is true and the conclusion is false. In all cases, assuming the hypothesis holds necessarily forces the conclusion to be true. Hence, none of the conditionals can be false, and all are tautologies.</i>

</div>


<div id="15">

#### Question no. 15

<i>Each conditional in Exercise 11 can be reduced using logical identities such as replacing implications with ¬p ⋁ q, applying De Morgan’s laws, and simplifying. In every case, the expression simplifies to true, proving each statement is a tautology.</i>

</div>


<div id="16">

#### Question no. 16

<i>Each conditional in Exercise 12 can be rewritten using ¬p ⋁ q for implications and simplified step by step. Every expression reduces to true under all interpretations, so each statement is a tautology.</i>

</div>


<div id="17">

#### Question no. 17

<b>a.</b>
- Table for p ⋁ (p ⋀ q) ↔ p:

    | P | Q | P ⋀ Q | P ⋁ (P ⋀ Q) | P ⋁ (P ⋀ Q) ↔ P |
    |-------|-------|-------|---------------------|:-------------------------:|
    | T | T | T | T | T |
    | T | F | F | T | T |
    | F | T | F | F | T |
    | F | F | F | F | T |
    
<i>p ⋁ (p ⋀ q) ↔ p, since p being true already makes the whole expression true, and if p is false, both sides are false.</i>

<b>b.</b>
- Table for p ⋀ (p ⋁ q) ↔ p:

    | P | Q | P ⋁ Q | P ⋀ (P ⋁ Q) | P ⋀ (P ⋁ Q) ↔ P |
    |-------|-------|-------|---------------------|:-------------------------:|
    | T | T | T | T | T |
    | T | F | T | T | T |
    | F | T | T | F | T |
    | F | F | F | F | T |
    
<i>p ⋀ (p ⋁ q) ↔ p, since p must be true for the conjunction to be true, and then both sides match.</i>

</div>


<div id="18">

#### Question no. 18

<i>(¬p ⋀ (p → q)) → ¬q is a tautology, because when ¬p is true, the implication p → q is automatically true, and the conclusion ¬q cannot be false while the hypothesis is true.</i>

</div>


<div id="19">

#### Question no. 19

<i>(¬q ⋀ (p → q)) → ¬p is a tautology, because if q is false and p → q holds, then p must be false, making the conclusion true whenever the hypothesis is true.</i>

</div>


<div id="20">

#### Question no. 20

<i>p ↔ q and (p ⋀ q) ⋁ (¬p ⋀ ¬q) are logically equivalent, since both are true exactly when p and q have the same truth value.</i>

</div>


<div id="21">

#### Question no. 21

<i>¬(p ↔ q) and p ↔ ¬q are logically equivalent, since both are true exactly when p and q have opposite truth values.</i>

</div>


<div id="22">

#### Question no. 22

<i>p → q and ¬q → ¬p are logically equivalent, because both fail only when p is true and q is false.</i>

</div>


<div id="23">

#### Question no. 23

<i>¬p ↔ q and p ↔ ¬q are logically equivalent, since both express that p and q have opposite truth values.</i>

</div>


<div id="24">

#### Question no. 24

<i>¬(p ⊕ q) and p ↔ q are logically equivalent, since exclusive OR is false exactly when p and q have the same truth value.</i>

</div>


<div id="25">

#### Question no. 25

<i>¬(p ↔ q) and ¬p ↔ q are logically equivalent, since both are true when p and q differ in truth value.</i>

</div>


<div id="26">

#### Question no. 26

<i>(p → q) ⋀ (p → r) and p → (q ⋀ r) are logically equivalent, since if p is true then both q and r must be true, and if p is false both expressions are true.</i>

</div>


<div id="27">

#### Question no. 27

<i>(p → r) ⋀ (q → r) and (p ⋁ q) → r are logically equivalent, since r must be true whenever either p or q is true.</i>

</div>


<div id="28">

#### Question no. 28

<i>(p → q) ⋁ (p → r) and p → (q ⋁ r) are logically equivalent, since if p is true at least one of q or r must be true, and if p is false both sides are true.</i>

</div>


<div id="29">

#### Question no. 29

<i>(p → r) ⋁ (q → r) and (p ⋀ q) → r are logically equivalent, since r is required only when both p and q are true.</i>

</div>


<div id="30">

#### Question no. 30

<i>¬p → (q → r) and q → (p ⋁ r) are logically equivalent, since both fail only when p is false, q is true, and r is false.</i>

</div>


<div id="31">

#### Question no. 31

<i>p ↔ q and (p → q) ⋀ (q → p) are logically equivalent, since biconditional means implication in both directions.</i>

</div>


<div id="32">

#### Question no. 32

<i>p ↔ q and ¬p ↔ ¬q are logically equivalent, since negating both sides preserves equality of truth values.</i>

</div>


<div id="33">

#### Question no. 33

<i>(p → q) ⋀ (q → r) → (p → r) is a tautology, because if p implies q and q implies r, then p must imply r.</i>

</div>


<div id="34">

#### Question no. 34

<i>(p ⋁ q) ⋀ (¬p ⋁ r) → (q ⋁ r) is a tautology, since if p is false then q must be true, and if p is true then r must be true.</i>

</div>


<div id="35">

#### Question no. 35

<i>(p → q) → r and p → (q → r) are not logically equivalent, because they differ in truth value when p is false and r is false.</i>

</div>


<div id="36">

#### Question no. 36

<i>(p ⋀ q) → r and (p → r) ⋀ (q → r) are not logically equivalent, since the second requires r when either p or q is true, but the first requires r only when both are true.</i>

</div>


<div id="37">

#### Question no. 37

<i>(p → q) → (r → s) and (p → r) → (q → s) are not logically equivalent because there exist truth assignments (for example, p false, q true, r true, s false) where one statement is true and the other is false.</i>

</div>


<div id="38">

#### Question no. 38

<b>a.</b> <i>The dual of p ⋁ ¬q is p ⋀ ¬q.</i>

<b>b.</b> <i>The dual of p ⋀ (q ⋁ (r ⋀ T)) is p ⋁ (q ⋀ (r ⋁ F)).</i>

<b>c.</b> <i>The dual of (p ⋀ ¬q) ⋁ (q ⋀ F) is (p ⋁ ¬q) ⋀ (q ⋁ T).</i>

</div>


<div id="39">

#### Question no. 39

<b>a.</b> <i>The dual of p ⋀ ¬q ⋀ ¬r is p ⋁ ¬q ⋁ ¬r.</i>

<b>b.</b> <i>The dual of (p ⋀ q ⋀ r) ⋁ s is (p ⋁ q ⋁ r) ⋀ s.</i>

<b>c.</b> <i>The dual of (p ⋁ F) ⋀ (q ⋁ T) is (p ⋀ T) ⋁ (q ⋀ F).</i>

</div>


<div id="40">

#### Question no. 40

<i>s∗ = s exactly when s is self-dual, meaning that interchanging ⋀ with ⋁ and T with F leaves the proposition unchanged.</i>

</div>


<div id="41">

#### Question no. 41

<i>Applying the dual operation twice replaces each operator and constant two times, returning everything to its original form; hence (s∗)∗ = s.</i>

</div>


<div id="42">

#### Question no. 42

<i>Each logical equivalence in Table 6 (except double negation) has a corresponding dual equivalence obtained by swapping ⋀ with ⋁ and T with F, so the equivalences naturally occur in dual pairs.</i>

</div>


<div id="43">

#### Question no. 43

<i>If two propositions involving only ⋀, ⋁, and ¬ are equivalent, then their duals are also equivalent because the dual operation preserves truth values under the same substitutions.</i>

</div>


<div id="44">

#### Question no. 44

<i>A compound proposition that is true exactly when p and q are true and r is false is p ⋀ q ⋀ ¬r.</i>

</div>


<div id="45">

#### Question no. 45

<i>A compound proposition that is true exactly when two of p, q, r are true is (p ⋀ q ⋀ ¬r) ⋁ (p ⋀ ¬q ⋀ r) ⋁ (¬p ⋀ q ⋀ r).</i>

</div>


<div id="46">

#### Question no. 46

<i>For any truth table, a compound proposition can be formed by taking a disjunction of conjunctions, where each conjunction corresponds to a row in which the proposition is true. This produces the disjunctive normal form.</i>

</div>


<div id="47">

#### Question no. 47

<i>The operators ¬, ⋀, and ⋁ are functionally complete because any compound proposition can be written in disjunctive normal form using only these operators.</i>

</div>


<div id="48">

#### Question no. 48

<i>The operators ¬ and ⋀ are functionally complete because p ⋁ q can be expressed as ¬(¬p ⋀ ¬q), allowing all propositions to be built from ¬ and ⋀ alone.</i>

</div>


<div id="49">

#### Question no. 49

<i>The operators ¬ and ⋁ are functionally complete because p ⋀ q can be expressed as ¬(¬p ⋁ ¬q), allowing all propositions to be built from ¬ and ⋁ alone.</i>

</div>


<div id="50">

#### Question no. 50

<i>The NAND operator p | q is false only when both p and q are true. It is true in all other cases: when p and q are both false, when p is true and q is false, and when p is false and q is true.</i>

</div>


<div id="51">

#### Question no. 51

<i>p | q is logically equivalent to ¬(p ⋀ q) because NAND is defined to be false exactly when p and q are both true, and true otherwise.</i>

</div>


<div id="52">

#### Question no. 52

<i>The NOR operator p ↓ q is true only when both p and q are false. It is false when p is true, when q is true, or when both are true.</i>

</div>


<div id="53">

#### Question no. 53

<i>p ↓ q is logically equivalent to ¬(p ⋁ q) because NOR is true exactly when neither p nor q is true.</i>

</div>


<div id="54">

#### Question no. 54

<b>a.</b> <i>p ↓ p is logically equivalent to ¬p, because p ⋁ p is p, and negating it gives ¬p.</i>

<b>b.</b> <i>(p ↓ q) ↓ (p ↓ q) is logically equivalent to p ⋁ q, since p ↓ q equals ¬(p ⋁ q), and negating it yields p ⋁ q.</i>

<b>c.</b> <i>Since ¬ and ⋁ can be expressed using ↓, and these operators are functionally complete, the set {↓} is functionally complete.</i>

</div>


<div id="55">

#### Question no. 55

<i>A compound proposition equivalent to p → q using only ↓ is (p ↓ p) ↓ q, because p ↓ p equals ¬p and ¬p ⋁ q is equivalent to p → q.</i>

</div>


<div id="56">

#### Question no. 56

<i>The set {|} is functionally complete because ¬p can be written as p | p, and p ⋁ q can be written using NAND and negation, allowing all compound propositions to be constructed.</i>

</div>


<div id="57">

#### Question no. 57

<i>p | q and q | p are logically equivalent because p ⋀ q and q ⋀ p have the same truth values, and negating them gives the same result.</i>

</div>


<div id="58">

#### Question no. 58

<i>p | (q | r) and (p | q) | r are not logically equivalent, because there exist truth assignments where one expression is true and the other is false. Hence, the NAND operator is not associative.</i>

</div>


<div id="59">

#### Question no. 59

<i>There are 16 different truth tables involving propositional variables p and q, since each of the four possible input combinations can independently be assigned true or false.</i>

</div>


<div id="60">

#### Question no. 60

<i>If p is logically equivalent to q and q is logically equivalent to r, then p and r always have the same truth values. Therefore, p and r are logically equivalent.</i>

</div>


<div id="61">

#### Question no. 61

<i>An equivalent and clearer specification is: The directory database is not opened, or the system is in its initial state, or the monitor is put in a closed state.</i>

</div>


<div id="62">

#### Question no. 62

<i>At most three of the given disjunctions can be made simultaneously true by a suitable assignment of truth values to p, q, and r.</i>

</div>


<div id="63">

#### Question no. 63

<i>At most five of the listed disjunctions can be made simultaneously true by an assignment of truth values to p, q, r, and s.</i>

</div>


<div id="64">

#### Question no. 64

<i>The negation of an unsatisfiable compound proposition is a tautology, because it is true under all assignments. Likewise, the negation of a tautology is unsatisfiable, because it is false under all assignments.</i>

</div>


<div id="65">

#### Question no. 65

<b>a.</b> <i>The proposition is satisfiable; for example, when p is false and q is false, all parts are true.</i>

<b>b.</b> <i>The proposition is unsatisfiable, because it requires q to be both true and false under the same conditions.</i>

<b>c.</b> <i>The proposition is unsatisfiable, because p ↔ q and ¬p ↔ q cannot both be true at the same time.</i>

</div>


<div id="66">

#### Question no. 66

<b>a.</b> <i>The compound proposition is satisfiable. For example, assigning p = true and s = false makes every disjunction true, regardless of the values of q and r.</i>

<b>b.</b> <i>The compound proposition is satisfiable. A suitable assignment such as p = false, q = false, r = true, and s = false satisfies all conjuncts.</i>

<b>c.</b> <i>The compound proposition is satisfiable. There exists an assignment of truth values to p, q, r, and s that makes each disjunction true simultaneously.</i>

</div>


<div id="67">

#### Question no. 67

<i>The compound proposition Q from Example 10 encodes the constraints that exactly one queen appears in each row and column and that no two queens attack each other diagonally.</i>

<b>a.</b> <i>When n = 2, Q is unsatisfiable, so no arrangement of 2 queens is possible.</i>

<b>b.</b> <i>When n = 3, Q is unsatisfiable, so no arrangement of 3 queens is possible.</i>

<b>c.</b> <i>When n = 4, Q is satisfiable and has exactly two distinct solutions corresponding to the two standard 4-queens arrangements.</i>

</div>


<div id="68">

#### Question no. 68

<i>The required compound proposition is obtained by adding a constraint to Q that forces the queen in the first column to lie in an odd-numbered row. This is done by conjoining Q with a disjunction stating that the queen in column one is in row 1, 3, 5, or any other odd row.</i>

</div>


<div id="69">

#### Question no. 69

<i>A 4 × 4 Sudoku puzzle can be solved by introducing propositional variables that represent placing a particular number in a particular cell. Compound propositions are constructed to enforce that each cell contains exactly one number, each row and column contains each number exactly once, and each subgrid satisfies the same condition. Solving the resulting satisfiability problem yields the Sudoku solution.</i>

</div>


<div id="70">

#### Question no. 70

<i>A compound proposition asserting that every cell of a 9 × 9 Sudoku puzzle contains at least one number is formed by taking a conjunction over all cells of a disjunction stating that the cell contains 1 ⋁ 2 ⋁ … ⋁ 9.</i>

</div>


<div id="71">

#### Question no. 71

<i>The proposition is constructed by first fixing a column and a number, then forming a disjunction that asserts the number appears in at least one row of that column. Taking the conjunction over all numbers and all columns ensures that every column contains every number.</i>

</div>


<div id="72">

#### Question no. 72

<i>The construction begins by fixing a 3 × 3 block and a number, then forming a disjunction asserting that the number appears in at least one cell of the block. Conjoining these expressions over all numbers and all blocks ensures that every block contains every number.</i>

</div>
<div id = "end">

### END