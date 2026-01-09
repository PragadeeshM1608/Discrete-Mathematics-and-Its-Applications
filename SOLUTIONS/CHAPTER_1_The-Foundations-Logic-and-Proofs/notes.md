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

### System Specifications

  - **consistency**: if there is at least one assignment of truth values to its propositions that makes the entire specification true.<br>
  - **inconsistency**: if there is no assignment of truth values to its propositions that makes the entire specification true.




## 1.3 Propositional Equivalences

- **Tautology**: A compound proposition that is always true, regardless of the truth values of its component propositions.
- **Contradiction**: A compound proposition that is always false, regardless of the truth values of its component propositions.
- **Contingency**: A compound proposition that is neither a tautology nor a contradiction; its truth value depends on the truth values of its component propositions.



<details>
  <summary>Logical Equivalences</summary>
  <p>

<br>

- **Common Logical Equivalences:**

  | Name                     | Equivalence                          | Description                                      |
  |--------------------------|--------------------------------------|--------------------------------------------------|
  | Identity Laws            | `P ∧ T ≡ P`, `P ∨ F ≡ P`                 | Identity laws for AND and OR                     |
  | Domination Laws          | `P ∧ F ≡ F`, `P ∨ T ≡ T`                 | Domination laws for AND and OR                   |
  | Idempotent Laws          | `P ∧ P ≡ P`, `P ∨ P ≡ P`                 | Idempotent laws for AND and OR                   |
  | Double Negation Law      | `¬(¬P) ≡ P`                            | Double negation law                              |
  | Commutative Laws         | `P ∧ Q ≡ Q ∧ P`, `P ∨ Q ≡ Q ∨ P`         | Commutative laws for AND and OR                  |
  | Associative Laws         | `(P ∧ Q) ∧ R ≡ P ∧ (Q ∧ R)`, `(P ∨ Q) ∨ R ≡ P ∨ (Q ∨ R)` | Associative laws for AND and OR                  |
  | Distributive Laws        | `(P ∧ Q) ∨ R ≡ (P ∨ R) ∧ (Q ∨ R)`, `(P ∨ Q) ∧ R ≡ (P ∧ R) ∨ (Q ∧ R)` | Distributive laws                                |
  | De Morgan's Laws         | `¬(P ∧ Q) ≡ ¬P ∨ ¬Q`, `¬(P ∨ Q) ≡ ¬P ∧ ¬Q` | De Morgan's laws                                 |
  | Absorption Laws          | `P ∧ (P ∨ Q) ≡ P`, `P ∨ (P ∧ Q) ≡ P`     | Absorption laws                                  |
  | Negation Laws            | `¬T = F`, `¬F = T`                       | Negation laws                                    |

<br>

- **Conditional Equivalences(implications):**
  | Name                     | Equivalence                          | Description                                      |
  |--------------------------|--------------------------------------|--------------------------------------------------|
  | Contrapositive           | `P → Q ≡ ¬Q → ¬P`                      | Contrapositive law                               |
  | Converse                 | `P → Q ≡ Q → P`                        | Converse law                                     |
  | Inverse                  | `P → Q ≡ ¬P → ¬Q`                      | Inverse law                                      |
  | Material Implication    | `P → Q ≡ ¬P ∨ Q`                       | Material implication equivalence                 |
  | Exportation               | `(P ∧ Q) → R ≡ P → (Q → R)`             | Exportation law                                 |
  | Implication as Disjunction | `P → Q ≡ ¬P ∨ Q`                       | Implication expressed as disjunction             |
  | Biconditional as Conjunction of Implications | `P ↔ Q ≡ (P → Q) ∧ (Q → P)`            | Biconditional expressed as conjunction of implications |
  | Tautology of Implication | `P → P ≡ T`                            | Tautology of implication                         |
  | Contradiction of Implication | `P ∧ ¬P → Q ≡ T`                        | Contradiction of implication                     |
  | Implication with Falsehood    | `F → P ≡ T`                            | Implication with falsehood                       |
  | Implication with Truth        | `P → T ≡ T`                            | Implication with truth                           |
  | Implication with Negation      | `P → F ≡ ¬P`                           | Implication with negation                        |
  | Implication with Negated Conclusion | `T → P ≡ P`                            | Implication with negated conclusion              |
  | Implication with Negated Antecedent | `¬P → Q ≡ P ∨ Q`                       | Implication with negated antecedent              |
  | Implication with Negated Consequent | `P → ¬Q ≡ ¬P ∨ ¬Q`                     | Implication with negated consequent              |
  | Implication with Falsehood and Truehood | `F → T ≡ T`                            | Implication with falsehood and truth             |
  | Implication with Truehood and Falsehood | `T → F ≡ F`                            | Implication with truth and falsehood             |
  | Implication with Negated Antecedent and Negated Conclusion | `¬P → ¬Q ≡ P ∨ ¬Q`                     | Implication with negated antecedent and negated conclusion |
  | Implication with Negated Consequent and Negated Antecedent | `¬P → ¬Q ≡ ¬P ∨ ¬Q`                     | Implication with negated consequent and negated antecedent |
  | Implication with Tautology and Contradiction | `T → F ≡ F`, `F → T ≡ T`                     | Implication with tautology and contradiction     |
  | Implication with Negated Tautology and Negated Contradiction | `¬T → F ≡ T`, `F → ¬T ≡ T`                     | Implication with negated tautology and negated contradiction |
  | Implication with Double Negation | `¬(¬P) → Q ≡ P → Q`                       | Implication with double negation                 |
  | Implication with Contrapositive of Negation | `¬Q → ¬P ≡ P → Q`                       | Implication with contrapositive of negation      |
  | Implication with Converse of Negation | `Q → P ≡ ¬P → ¬Q`                      | Implication with converse of negation            |
  | Implication with Inverse of Negation | `¬P → ¬Q ≡ P → Q`                       | Implication with inverse of negation             |
  | Implication with Negated Antecedent and Conclusion | `¬P → Q ≡ P ∨ Q`                       | Implication with negated antecedent and conclusion |
  | Implication with Antecedent and Negated Conclusion | `P → ¬Q ≡ ¬P ∨ ¬Q`                     | Implication with antecedent and negated conclusion |
  | Implication with Negated Antecedent and Negated Conclusion | `¬P → ¬Q ≡ P ∨ ¬Q`                     | Implication with negated antecedent and negated conclusion |
  | Implication with Antecedent and Conclusion | `P → Q ≡ ¬P ∨ Q`                       | Implication with antecedent and conclusion       |
  | Implication with Negated Antecedent and Conclusion | `¬P → Q ≡ P ∨ Q`                       | Implication with negated antecedent and conclusion |
  | Implication with Antecedent and Negated Conclusion | `P → ¬Q ≡ ¬P ∨ ¬Q`                     | Implication with antecedent and negated conclusion |
  | Implication with Negated Antecedent and Negated Conclusion | `¬P → ¬Q ≡ P ∨ ¬Q`                     | Implication with negated antecedent and negated conclusion |
  | Implication with Tautology and Contradiction | `T → F ≡ F`, `F → T ≡ T`                     | Implication with tautology and contradiction     |
  | Implication with Negated Tautology and Negated Contradiction | `¬T → F ≡ T`, `F → ¬T ≡ T`                     | Implication with negated tautology and negated contradiction |

<br>

- **Biconditional Equivalences:**
  | Name                     | Equivalence                          | Description                                      |
  |--------------------------|--------------------------------------|--------------------------------------------------|
  | Definition               | `P ↔ Q ≡ (P → Q) ∧ (Q → P)`            | Definition of biconditional                      |
  | Contrapositive           | `P ↔ Q ≡ ¬Q ↔ ¬P`                      | Contrapositive law for biconditional             |
  | Converse                 | `P ↔ Q ≡ Q ↔ P`                        | Converse law for biconditional                   |
  | Inverse                  | `P ↔ Q ≡ ¬P ↔ ¬Q`                      | Inverse law for biconditional                    |
</details>

### Satisfiability
  - **Satisfiability**: if there is at least one assignment of truth values to its component propositions that makes the entire proposition true.
  - **Unsatisfiability**:if there is no assignment of truth values to its component propositions that makes the entire proposition true.















































