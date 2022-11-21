# Problem set 1
## Ex 1
1. Atomic statement
2. Not a statement
3. Not a statement
4. Not a statement
5. Compound statement
6. Compound statement
7. Atomic statement
8. Compound statement
## Ex 2
1. The banana is not my favorite fruit.
2. 7 ≤ 3
3. You are alone
4. The function *f* is not differentiable everywhere
## Ex 3
1. 9 is a perfect square and orange is a primary color
2. A frog is not a reptile
3. if 9 is a perfect square, a frog is a reptile
4. orange is a primary color if and only if a frog is a reptile
5. 9 is not a perfect square and orange is a primary color
6. ¬(𝑝 ∧ 𝑞) = ¬𝑝 ∨ ¬𝑞. 9 is not a perfect square or orange is not a primary color
7. 9 is not a perfect square or orange is not a primary color
8. If 9 is a perfect square and orange is primary color, a frog is a reptile
## Ex 4
|p|q|p ⊕ r|
|-|-|-----|
|T|T|F|
|T|F|T|
|F|T|T|
|F|F|F|

##Ex 5
1. T
2. F
3. T
4. T
5. F
6. T
7. F
8. F

## Ex 6
p ⊕ q is true if p is true and q is false (inclusive) or if p is false and q is true
(¬q ∧ p) ∨ (q ∧ ¬p)
|p|q|(¬q ∧ p) ∨ (q ∧ ¬p)|
|-|-|-----|
|T|T|F|
|T|F|T|
|F|T|T|
|F|F|F|

This truth table is the same as the one presented in ex 4 thus we can conclude that
the proposed expression matches xor

## Ex 7
1. T
2. NDF
3. T
4. T
5. NDF
6. NDF
7. T
8. T

## Ex 8

1. p = T, q = T
2. p = T, q = F
3. p = T, q = F
4. r = F, q = T, p = T

## Ex 9

|p|q|r|[𝑝 ∧ (𝑞 ∨ 𝑟)]|[(𝑝 ∧ 𝑞) ∨ (𝑝 ∧ 𝑟)]|[𝑝 ∧ (𝑞 ∨ 𝑟)] ↔ [(𝑝 ∧ 𝑞) ∨ (𝑝 ∧ 𝑟)]|
|-|-|-|-------------|-------------------|-----------------------------------|
|T|T|T|T|T|T|
|F|T|T|F|F|T|
|T|F|T|T|T|T|
|T|T|F|T|T|T|
|F|F|T|F|F|T|
|F|F|F|F|F|T|
|T|F|F|T|T|T|
