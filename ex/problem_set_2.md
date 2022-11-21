# Problem set 2
## Ex 1
1. T
2. F
3. F
4. F
5. T
6. T
7. T
8. F

## Ex 2
1. 6
2. 4
3. 53 -1 + 1 = 53
4. 2077 - 5 + 1 = 2073

## Ex 3
1. {a, b, Δ, 𝛿, c, 𝛾}
2. {b, 𝛿}

## Ex 4
1. F
2. T
3. F
4. F
5. T
6. T
7. F
8. T

## Ex 5
1. 2
2. 1
3. 4
4. 4

## Ex 6
{∅, {∅}} {{∅}, {∅, {∅}}}
1. {∅, {∅}, {∅, {∅}}}
2. {{∅}}
## Ex 7
2<sup>4</sup> = 16
## Ex 8
1. Yes
2. Yes
3. No
4. Yes

## Ex 9
### Show that ⊆ is reflexive
For any set A:
A = A
<=> ∀ a ∈ A. (a ∈ A <=> a ∈ A) (by definition of set equality)
<=> ∀ a ∈ A. (a ∈ A)
<=> A ⊆ A (by definition of ⊆)
### Show that ∈ is not reflexive
A simple counter example would be:
∅ ∉ ∅
### Is  ⊆ symetric
Counter example:

A = {a, b, c}

B = {a}

B ⊆ A but A ⊄ B
### Is ∈ symetric
Counter example:
A = ∅

B = {∅}

A ∈ B but B ∉ A

## Ex 10
As seen in theorem 2.3 ⊆ is transative so yes
## Ex 11
C = 𝐴 ∩ B
<=> ∀ a ∈ A. a ∈ b -> a ∈ c
=> ∀ c ∈ C. c ∈ A
<=> C ⊆ A
## Ex 12
This is an example of [Russell's paradox](https://en.wikipedia.org/wiki/Russell%27s_paradox)
A = {x | x ∉ x}
=> A ∈ A <=> A ∉ A
which is a contradiction
## Ex 13
𝐵 ⊆ 𝐴
<=> ∀ b ∈ B. b ∈ A
<=> 𝐴 ∩ 𝐵 = 𝐵
