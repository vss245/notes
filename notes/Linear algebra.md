---
title: Linear algebra
created: '2019-12-20T22:38:52.840Z'
modified: '2019-12-20T23:07:46.677Z'
---

# Linear algebra
LA is about translating things from m-dimensional to n-dimensional spaces

## Numbers
- Complex = a + b*i, i = sqrt(-1)
- Integers - +/- natural 0+/- natural 0
- Rational - Terminating decimals, non-terminating decimals
- Irrational - Pi or sqrt(2) etcPi or sqrt(2) etc
- Imaginary - 0 + bi - for solving things like x^2 + 5 = 0

## Logic 
- Proposition - a sentence that's either true or false
- If P then Q: P=>Q
  - Does not imply Q=>P
  - If both P=>Q and Q=>P are true, then P<=>Q

## Sets
- X belongs to set Y = X ∈ Y 
- Set X is in set Y = X ⊂ Y

## Functions
- Function from X to Y is the rule that binds elements in X to elements in Y 
  - F:X->Y
- X is the domain, Y is the co-domain
### Images
- Assume xi ∈ X
- Elements in Y that correspond to xi are called xi's image under f in Y 
- Element x of the set x goes together with the element 2x-1 in the set Y
- F(2) implies that the image of 2 under f is 2x2-1
- X is the domain
- Y overall is the co-domain, image of x under f in Y is the range (values in Y that actually mapped to)
### Onto and one-to-one
- A function is onto if its image is equal to the codomain (all the elements of Y are
being mapped onto)

- If xi≠xj =>f(xi)≠f(xj),function is one-to-one (no element in the co-domain can
mapped onto more than one)
- can be both

### Inverse functions
- Mapping from Y onto X instead of from X onto Y
- g(f(xi))=xi
- f(g(yi))=yi

## Linear transformations
### Conditions
- f(xi) + f(xj) = f(xi + xj)
- cf(x)=f(cx)
- For example, 2x is linear, 2x-1 is not
## Matrices
- Values organized in m columns and n rows
- Addition, subtraction, scalar multiplication are performed elementwise
(examples)
- Types
  - Zero
  - Transpose (switch R and C)
  - Symmetric (around the diagonal)
  - Upper/lower triangular
  - Diagonal
  - Identity
  - Inverse
- Inverse matrices
  - Found by Gaussian elimination
  (examples)
  - To see if matrix is invertible, use the determinant (if it's not 0, the inverse exists)
## Vectors
- Special interpretation of matrices (1xn and nx1)
- Can represent:
  - Points in space
  - Arrow from origin to point
  - Sum of several arrows to point
  - Arrows from anywhere, not just the origin
## Bases
- If there's a unique solution to c1(M)+c2(M) = zero matrix
  - Vectors are linearly independent
  - Can form the basis for Rn
- If >1 solution
  - Linearly dependent
- Basis - minimal set of vectors needed to express a vector in Rn
## Subspaces
- Closed under multiplication (element in W multiplied by c is still an element in W)
- Closed under addition (sum of two arbitrary elements in W is an element in W)
## Span
- A subspace can be spanned by scalar multiplication and addition of vectors
(example)
## Coordinates
- Can be expressed using trivial bases (0,1) and (1,0)
- But can also be expressed using any bases
(example)
## Linear transformations
- Same definition as above, but for vectors
## Rank
- Defines the transformation (if output is 1D - rank 1, 2D - rank 2 and so on)
## Eigenvalues and eigenvectors
- If the image of X through the transformation defined by M = lambdaX, then lambda is the eigenvalue and X is the corresponding eigenvector
(example)





