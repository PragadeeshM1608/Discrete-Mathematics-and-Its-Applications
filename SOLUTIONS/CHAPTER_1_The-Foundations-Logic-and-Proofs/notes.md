# The Foundations:Logic and Proofs

## 1.1 Proposition logic
<br>

- Propositions are statements that can be true or false.

    |  P   |  Q   | P⋀Q  | P∨Q  | P⨁Q  |P→Q  |   P↔Q|                         
    |------|------|------|------|------|------|------|
    |  T   |  T   |  T   |  T   |  F   |  T   |  T   |
    |  T   |  F   |  F   |  T   |  T   |  F   |  F   |
    |  F   |  T   |  F   |  T   |  T   |  T   |  F   |
    |  F   |  F   |  F   |  F   |  F   |  T   |  T   |

<br>
<br>

### When each operator is true

- **P⋀Q (AND)** is true when **both P and Q are true**.
- **P∨Q (OR)** is true when **at least one of P or Q is true**. → inclusive or
- **P⨁Q (XOR)** is true when **exactly one of P or Q is true**. → exclusive or
- **P→Q (IMPLIES)** is true when **P is false or Q is true**.  P → (Condition/trigger), Q → (Result/cause) 
- **P↔Q (BICONDITIONAL)** is true when **P and Q have the same truth value**.  

<br>
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

    |  |
    |----------------|
    |¬ &nbsp;&nbsp;&nbsp;&nbsp; ∧ &nbsp;&nbsp;&nbsp;&nbsp; ∨ &nbsp;&nbsp;&nbsp;&nbsp; ⊕ &nbsp;&nbsp;&nbsp;&nbsp;  → &nbsp;&nbsp;&nbsp;&nbsp; ↔   |
    | **highest &nbsp;&nbsp;&nbsp;&nbsp;→→→→→ &nbsp;&nbsp;&nbsp;&nbsp; lowest** |


<br>
<br>

- **Symbolic Expressions**

    | Operator | Symbol | Ways to Express in English |
    |----------|--------|----------------------------|
    | AND      | ∧      | and,&nbsp;&nbsp; but&nbsp;&nbsp;, also&nbsp;&nbsp;, moreover&nbsp;&nbsp;, furthermore&nbsp;&nbsp;, together with&nbsp;&nbsp;, as well as |
    | OR       | ∨      | or&nbsp;&nbsp;, unless&nbsp;&nbsp;, otherwise&nbsp;&nbsp;, either…or…&nbsp;&nbsp;, and/or |
    | XOR      | ⊕      | either…or… but not both&nbsp;&nbsp;, or… but not both&nbsp;&nbsp;, exclusively |
    | IMPLIES  | →      | if…then…&nbsp;&nbsp;, implies&nbsp;&nbsp;, therefore&nbsp;&nbsp;, hence&nbsp;&nbsp;, consequently&nbsp;&nbsp;, whenever |
    | BICONDITIONAL | ↔ | if and only if&nbsp;&nbsp;, iff&nbsp;&nbsp;, exactly when&nbsp;&nbsp;, is equivalent to&nbsp;&nbsp;, same as |









