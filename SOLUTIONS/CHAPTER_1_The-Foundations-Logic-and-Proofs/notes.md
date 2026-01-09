# The Foundations:Logic and Proofs

## 1.1 Proposition logic
<br>

### Truth Tables for Logical Operators
<br>


- Propositions are statements that can be true or false.

    |  P   |  Q   | P⋀Q  | P∨Q  | P⨁Q  |P→Q  |   P↔Q|                         
    |------|------|------|------|------|------|------|
    |  T   |  T   |  T   |  T   |  F   |  T   |  T   |
    |  T   |  F   |  F   |  T   |  T   |  F   |  F   |
    |  F   |  T   |  F   |  T   |  T   |  T   |  F   |
    |  F   |  F   |  F   |  F   |  F   |  T   |  T   |

<br>

### When each operator is true

- **P⋀Q (AND)** is true when **both P and Q are true**.
- **P∨Q (OR)** is true when **at least one of P or Q is true**. → `inclusive or`
- **P⨁Q (XOR)** is true when **exactly one of P or Q is true**. → `exclusive or`
- **P→Q (IMPLIES)** is true when **P is false or Q is true**.  `P → (Condition/trigger [Hypothesis,Antecedent,Premise]), Q → (Result/cause [Conclusion,Consequent]) `
- **P↔Q (BICONDITIONAL)** is true when **P and Q have the same truth value**.  


### Related Conditional Terms

- **Converse**: Q → P `(describe a relationship from opposite perspectives)`
- **Contrapositive**: ¬Q → ¬P `(The inverse of the converse)`
- **Inverse**: ¬P → ¬Q `(negating both the premise and conclusion of the original implication)`
<br>


### Precedence of Logical Operators
<br>

- **Associativity**

    | Operator | Associativity |                                   
    |----------|---------------|
    | ∧        | Left          |
    | ∨        | Left          |
    | ⊕       | Left         |
    | →        | Right         |
    | ¬        | Right         |
    | ↔        | Right         |


<br>
<br>

- **Precedence**

    ||
    |----------------|
    |¬ &nbsp;&nbsp;&nbsp;&nbsp; ∧ &nbsp;&nbsp;&nbsp;&nbsp; ∨ &nbsp;&nbsp;&nbsp;&nbsp; ⊕ &nbsp;&nbsp;&nbsp;&nbsp;  → &nbsp;&nbsp;&nbsp;&nbsp; ↔   |
    | **highest &nbsp;&nbsp;&nbsp;&nbsp;→→→→→ &nbsp;&nbsp;&nbsp;&nbsp; lowest** |

<br>

- **Symbolic Expressions**

    | Operator | Symbol | Ways to Express in English |
    |----------|--------|----------------------------|
    | AND      | ∧      | `and`,&nbsp;&nbsp; `but`&nbsp;&nbsp;, `also`&nbsp;&nbsp;, `moreover`&nbsp;&nbsp;, `furthermore`&nbsp;&nbsp;, `together with`&nbsp;&nbsp;, `as well as` |
    | OR       | ∨      | `or`&nbsp;&nbsp;, `unless`&nbsp;&nbsp;, `otherwise`&nbsp;&nbsp;, `either…or…`&nbsp;&nbsp;, `and/or` |
    | XOR      | ⊕      | `either…or… but not both`&nbsp;&nbsp;, `or… but not both`&nbsp;&nbsp;, `exclusively` |
    | IMPLIES  | →      | `if…then…`&nbsp;&nbsp;, `implies`&nbsp;&nbsp;, `therefore`&nbsp;&nbsp;, `hence`&nbsp;&nbsp;, `consequently`&nbsp;&nbsp;, `whenever` |
    | BICONDITIONAL | ↔ | `if and only if`&nbsp;&nbsp;, `iff`&nbsp;&nbsp;, `exactly when`&nbsp;&nbsp;, `is equivalent to`&nbsp;&nbsp;, `same as` |
<br>


## 1.2 Applications of Propositional Logic
<br>

### System Specifications
<br>

**consistency**: if there is at least one assignment of truth values to its propositions that makes the entire specification true.<br>
**inconsistency**: if there is no assignment of truth values to its propositions that makes the entire specification true.





## 1.3 Propositional Equivalences
<br>

- **Tautology**: A compound proposition that is always true, regardless of the truth values of its component propositions.
- **Contradiction**: A compound proposition that is always false, regardless of the truth values of its component propositions.
- **Contingency**: A compound proposition that is neither a tautology nor a contradiction; its truth value depends on the truth values of its component propositions.



<details>
  <summary>Logical Equivalences</summary>
  <p>

  - **De Morgan's Laws**:
  - ¬(P ∧ Q) ≡ ¬P ∨ ¬Q
  - ¬(P ∨ Q) ≡ ¬P ∧ ¬Q
  - 
- **Implication Equivalence**:
  - P → Q ≡ ¬P ∨ Q
  - P ↔ Q ≡ (P → Q) ∧ (Q → P)
- **Double Negation**:
  - ¬(¬P) ≡ P
- **Distributive Laws**:
  - P ∧ (Q ∨ R) ≡ (P ∧ Q) ∨ (P ∧ R)
  - P ∨ (Q ∧ R) ≡ (P ∨ Q) ∧ (P ∨ R)
- **Commutative Laws**: 
  - P ∧ Q ≡ Q ∧ P
  - P ∨ Q ≡ Q ∨ P
- **Associative Laws**:
  - (P ∧ Q) ∧ R ≡ P ∧ (Q ∧ R)
  - (P ∨ Q) ∨ R ≡ P ∨ (Q ∨ R)
- **Identity Laws**:
  - P ∧ T ≡ P
  - P ∨ F ≡ P
- **Domination Laws**:
  - P ∨ T ≡ T
  - P ∧ F ≡ F
- **Idempotent Laws**:
  - P ∨ P ≡ P
  - P ∧ P ≡ P
- **Absorption Laws**:
  - P ∨ (P ∧ Q) ≡ P
  - P ∧ (P ∨ Q) ≡ P
- **Negation Laws**:
  - P ∨ ¬P ≡ T
  - P ∧ ¬P ≡ F
- **Contrapositive**:
  - P → Q ≡ ¬Q → ¬P
- **Biconditional Equivalence**:
  - P ↔ Q ≡ (P ∧ Q) ∨ (¬P ∧ ¬Q)
- **Exclusive OR**:
  - P ⊕ Q ≡ (P ∨ Q) ∧ ¬(P ∧ Q)
- **Absorption with Negation**:
  - P ∨ ¬(P ∧ Q) ≡ P ∨ ¬Q
  - P ∧ ¬(P ∨ Q) ≡ P ∧ ¬Q
- **Distributive with Negation**:
  - ¬P ∨ (P ∧ Q) ≡ ¬P ∨ Q
  - ¬P ∧ (P ∨ Q) ≡ ¬P ∧ Q
- **Redundancy Laws**:
  - P ∨ (P ∧ ¬Q) ≡ P ∨ Q
  - P ∧ (P ∨ ¬Q) ≡ P ∧ Q
- **Consensus Theorem**:
  - (P ∧ Q) ∨ (¬P ∧ R) ∨ (Q ∧ R) ≡ (P ∧ Q) ∨ (¬P ∧ R)
- **Distributive with Biconditional**:
  - P ↔ (Q ∨ R) ≡ (P ↔ Q) ∨ (P ↔ R)
  - P ↔ (Q ∧ R) ≡ (P ↔ Q) ∧ (P ↔ R)
- **Implication with Biconditional**:
  - P → (Q ↔ R) ≡ (P → Q) ↔ (P → R)
  - (P ↔ Q) → R ≡ (P → R) ↔ (Q → R)
- **Negation of Biconditional**:
  - ¬(P ↔ Q) ≡ P ⨁ Q
- **Negation of Implication**:
  - ¬(P → Q) ≡ P ∧ ¬Q
- **Distributive with Implication**:
  - P → (Q ∧ R) ≡ (P → Q) ∧ (P → R)
  - P → (Q ∨ R) ≡ (P → Q) ∨ (P → R)
  - (P ∧ Q) → R ≡ P → (Q → R)
  - (P ∨ Q) → R ≡ (P → R) ∧ (Q → R)
- **Absorption with Implication**:
  - P ∨ (P → Q) ≡ T
  - P ∧ (P → Q) ≡ P
- **Absorption with Biconditional**:
  - P ∨ (P ↔ Q) ≡ T
  - P ∧ (P ↔ Q) ≡ P
- **Redundancy with Implication**:
  - P → (P ∨ Q) ≡ T
  - P → (P ∧ Q) ≡ P
- **Redundancy with Biconditional**:
  - P ↔ (P ∨ Q) ≡ T
  - P ↔ (P ∧ Q) ≡ P
- **Consensus with Implication**:
  - (P → Q) ∨ (¬P → R) ∨ (Q → R) ≡ (P → Q) ∨ (¬P → R)
- **Consensus with Biconditional**:
  - (P ↔ Q) ∨ (¬P ↔ R) ∨ (Q ↔ R) ≡ (P ↔ Q) ∨ (¬P ↔ R)
- **Distributive with Negation of Implication**:
  - ¬(P → Q) ∨ R ≡ (¬P ∨ Q) ∨ R
  - ¬(P → Q) ∧ R ≡ (¬P ∨ Q) ∧ R
- **Distributive with Negation of Biconditional**:
  - ¬(P ↔ Q) ∨ R ≡ (P ⊕ Q) ∨ R
  - ¬(P ↔ Q) ∧ R ≡ (P ⊕ Q) ∧ R
- **Absorption with Negation of Implication**:
  - P ∨ ¬(P → Q) ≡ P ∨ (P ∧ ¬Q) ≡ P ∨ ¬Q
  - P ∧ ¬(P → Q) ≡ P ∧ (P ∧ ¬Q) ≡ P ∧ ¬Q
- **Absorption with Negation of Biconditional**:
  - P ∨ ¬(P ↔ Q) ≡ P ∨ (P ⊕ Q) ≡ T
  - P ∧ ¬(P ↔ Q) ≡ P ∧ (P ⊕ Q) ≡ F
- **Redundancy with Negation of Implication**:
  - P → ¬(P → Q) ≡ P → (P ∧ ¬Q) ≡ P → ¬Q
  -  P ↔ ¬(P → Q) ≡ P ↔ (P ∧ ¬Q) ≡ F
- **Redundancy with Negation of Biconditional**:
  - P → ¬(P ↔ Q) ≡ P → (P ⊕ Q) ≡ T
  - P ↔ ¬(P ↔ Q) ≡ P ↔ (P ⊕ Q) ≡ ¬Q
- **Consensus with Negation of Implication**:
  - (P → Q) ∨ (¬P → R) ∨ ¬(Q → R) ≡ (P → Q) ∨ (¬P → R)
- **Consensus with Negation of Biconditional**:
  - (P ↔ Q) ∨ (¬P ↔ R) ∨ ¬(Q ↔ R) ≡ (P ↔ Q) ∨ (¬P ↔ R)
- **Distributive with Exclusive OR**:
  - P ⊕ (Q ∨ R) ≡ (P ⊕ Q) ∨ (P ⊕ R)
  - P ⊕ (Q ∧ R) ≡ (P ⊕ Q) ∧ (P ⊕ R)
  - (P ∨ Q) ⊕ R ≡ (P ⊕ R) ∨ (Q ⊕ R)
  - (P ∧ Q) ⊕ R ≡ (P ⊕ R) ∧ (Q ⊕ R)
- **Implication with Exclusive OR**:
  - P → (Q ⊕ R) ≡ (P → Q) ⊕ (P → R)
  - (P ⊕ Q) → R ≡ (P → R) ⊕ (Q → R)
- **Biconditional with Exclusive OR**:
  - P ↔ (Q ⊕ R) ≡ (P ↔ Q) ⊕ (P ↔ R)
  - (P ⊕ Q) ↔ R ≡ (P ↔ R) ⊕ (Q ↔ R)
- **Negation of Exclusive OR**:
  - ¬(P ⊕ Q) ≡ P ↔ Q
- **Absorption with Exclusive OR**:
  - P ∨ (P ⊕ Q) ≡ T
  - P ∧ (P ⊕ Q) ≡ F
- **Redundancy with Exclusive OR**:
  - P → (P ⊕ Q) ≡ T
  - P ↔ (P ⊕ Q) ≡ ¬Q
- **Consensus with Exclusive OR**:
  - (P ⊕ Q) ∨ (¬P ⊕ R) ∨ (Q ⊕ R) ≡ (P ⊕ Q) ∨ (¬P ⊕ R)
  - (P ⊕ Q) ∧ (¬P ⊕ R) ∧ (Q ⊕ R) ≡ (P ⊕ Q) ∧ (¬P ⊕ R)
- **Mixed Operations**:
  - Various combinations of the above equivalences can be applied to simplify complex logical expressions involving multiple operators.
- **Nested Expressions**:
  - Logical equivalences can be applied recursively to simplify nested logical expressions.
- **Conditional and Biconditional Chains**:
  - Chains of implications or biconditionals can be simplified using the above equivalences.
- **Distributive with Mixed Operators**:
  - P ∧ (Q → R) ≡ (P ∧ ¬Q) ∨ (P ∧ R)
  - P ∨ (Q → R) ≡ (P ∨ ¬Q) ∧ (P ∨ R)
  - P ∧ (Q ↔ R) ≡ (P ∧ Q ∧ R) ∨ (P ∧ ¬Q ∧ ¬R)
  - P ∨ (Q ↔ R) ≡ (P ∨ Q ∨ ¬R) ∧ (P ∨ ¬Q ∨ R)
  - (P → Q) ∧ R ≡ (¬P ∨ Q) ∧ R
  - (P ↔ Q) ∨ R ≡ (P ∧ Q) ∨ (¬P ∧ ¬Q) ∨ R
  - (P ⊕ Q) ∧ R ≡ ((P ∨ Q) ∧ ¬(P ∧ Q)) ∧ R
  - (P ⊕ Q) ∨ R ≡ ((P ∨ Q) ∧ ¬(P ∧ Q)) ∨ R
- **Combination of Negations**:
  - ¬(P ∧ (Q → R)) ≡ ¬P ∨ (Q ∧ ¬R)
  - ¬(P ∨ (Q ↔ R)) ≡ ¬P ∧ (Q ⊕ R)
  - ¬((P ⊕ Q) ∧ R) ≡ (P ↔ Q) ∨ ¬R
  - ¬((P ⊕ Q) ∨ R) ≡ (P ↔ Q) ∧ ¬R
  - ¬(P → (Q ∧ R)) ≡ P ∧ (¬Q ∨ ¬R)
  - ¬(P ↔ (Q ∨ R)) ≡ P ⊕ (Q ∨ R)
  - ¬(P ⊕ (Q ∧ R)) ≡ P ↔ (Q ∧ R)
  - ¬((P → Q) ∨ R) ≡ P ∧ ¬Q ∧ ¬R
  - ¬((P ↔ Q) ∧ R) ≡ (P ⊕ Q) ∨ ¬R
  - ¬((P ⊕ Q) → R) ≡ (P ∧ ¬Q) ∧ ¬R
   


  </p>
</details>
