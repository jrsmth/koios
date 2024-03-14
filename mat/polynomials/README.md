# Polynomials

## Topics
- The Quadratic Formula
- Completing The Square
- Discriminant
- Factorisation
- Factor Theorem

## The Quadratic Formula
- The Quadratic Formula gives us a method to solve quadratic equations:
  - When $a \ne 0$, there are two solutions to $(ax^2 + bx + c = 0)$ and they are
    $x = {-b \pm \sqrt{b^2-4ac} \over 2a}$
- Derivations:
  1. Completing The Square: 
      - Dividing by $a$ (allowed because $a \ne 0$) and subtracting $\frac{c}{a}$, gives us $x^2 + \frac{b}{a}x = \frac{-c}{a}$
      - The *LHS* is now ready for solving by Completing The Square:
        - We add $k^2$ in the form of $\frac{b}{2a}$ to create a squared binomial of the form $x^2 + 2kx + k^2$
        - Thus, $x^2 + 2(\frac{b}{2a})x + (\frac{b}{2a})^2 = \frac{-c}{a} + (\frac{b}{2a})^2$
          - Contracting the squared binomial gives $(x + \frac{b}{2a})^2 = {b^2 - 4ac \over 4a^2}$
          - Taking the square root and subtracting $b \over 2a$ gives the Quadratic Formula:
            - $x = {-b \pm \sqrt{b^2-4ac} \over 2a}$
      - Practise this derivation, line by line
  2. Complete The Square (without fractions):
      - Multiply each side by $4a$ and Complete The Square by adding $b^2 - 4ac$ to both sides
          - Giving, $4a^2x^2 + 4abx + b^2 = b^2 - 4ac$
          - Contract the binomial square, $(2ax + b)^2 = b^2 - 4ac$
          - Square root and solve for $x$, with $2ax + b = \pm \sqrt{b^2-4ac}$
  3. By Substitution (Change of Variables):
      - Put the equation in the form $u^2 = s$
        - Substituting $x = u - {b \over 2a}$ into $ax^2 + bx + c = 0$
          - Expanding the products, combining the like terms and solving for $u^2$
          - $a(u - {b \over 2a})^2 + b(u - {b \over 2a}) + c = 0$
          - $au^2 +{4ac - b^2 \over 4a} = 0$
          - $u^2 = {b^2 - 4ac \over 4a^2}$
        - Substituting $x = u - {b \over 2a}$ back gives us the Quadratic Formula
  4. By Algebraic Identities:
      - Lets the roots of $ax^2 + bx + c = 0$ be $\alpha$ and $\beta$
      - The following is a valid identity for any two complex numbers:
        - $(\alpha - \beta)^2 = (\alpha + \beta)^2 - 4\alpha\beta$
        - Hence, $\alpha - \beta = \pm \sqrt{(\alpha + \beta)^2 - 4\alpha\beta}$
      - Since $a \ne 0$, we can divide our original polynomial by $a$ to obtain a monic polynomial with the same roots
        - Note: a monic polynomial is one where the coefficient of the highest power is $1$
        - Hence, $x^2 + {b \over a}x + {c \over a} = 0$
          - Continue...
      
- For given coefficients, the solutions correspond to the roots of the graphed equation
  - More on this...

## Completing The Square
- Like the Quadratic Formula, Completing The Square gives us a method of solving quadratic equations


## Sources
- https://en.wikipedia.org/wiki/Quadratic_formula
- https://en.wikipedia.org/wiki/Completing_the_square
- https://en.wikipedia.org/wiki/Monic_polynomial
