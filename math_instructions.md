## Step 1: Inline Math Expressions

*Welcome to "Math Notation in Markdown"! Let's start with inline math expressions.*

Inline math expressions allow you to embed mathematical notation within your text. They are enclosed by single dollar signs `$`.

### Example:

```md
The quadratic formula is $ax^2 + bx + c = 0$.
```

How it looks: The quadratic formula is $ax^2 + bx + c = 0$.

### :keyboard: Activity: Add an inline math expression

1. Edit the `mathpractice.md` file you created.
2. Add a sentence that includes an inline math expression. Try using superscripts or subscripts!
3. Use the **Preview** tab to check your Markdown formatting.
4. Commit your changes.

## Step 2: Display Equations

*Great job with inline math! Now let's create display equations.*

Display equations are standalone mathematical expressions, set apart from the text. They use double dollar signs `$$`.

### Example:

```md
The solution to a quadratic equation is given by:

$$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$
```

How it looks:

The solution to a quadratic equation is given by:

$$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$

### :keyboard: Activity: Add a display equation

1. Edit the `mathpractice.md` file you created.
2. Add a display equation of your choice. It could be a famous formula or something related to your field of study.
3. Use the **Preview** tab to check your formatting.
4. Commit your changes.

## Step 3: Greek Letters and Common Symbols

*Excellent work on display equations! Let's explore Greek letters and common mathematical symbols.*

Greek letters are frequently used in mathematics and can be typed using their English names. Common symbols have specific LaTeX commands.

### Example:

```md
- $\alpha$, $\beta$, $\gamma$ are Greek letters
- $\pi \approx 3.14159$
- $\sum_{i=1}^n i = \frac{n(n+1)}{2}$
- $\int_0^1 x^2 dx = \frac{1}{3}$
```

How it looks:
- $\alpha$, $\beta$, $\gamma$ are Greek letters
- $\pi \approx 3.14159$
- $\sum_{i=1}^n i = \frac{n(n+1)}{2}$
- $\int_0^1 x^2 dx = \frac{1}{3}$

### :keyboard: Activity: Use Greek letters and symbols

1. Edit the `mathpractice.md` file you created.
2. Create a list of at least 3 items that use different Greek letters and mathematical symbols.
3. Use the **Preview** tab to check your formatting.
4. Commit your changes.

## Step 4: Matrices and Arrays

*Great job with Greek letters and symbols! Now let's create matrices and arrays.*

Matrices and arrays are created using the `matrix`, `pmatrix`, or `bmatrix` environments.

### Example:

```md
A 2x2 matrix:

$$
\begin{pmatrix}
a & b \\
c & d
\end{pmatrix}
$$

A 3x3 matrix:

$$
\begin{bmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
7 & 8 & 9
\end{bmatrix}
$$
```

How it looks:

A 2x2 matrix:

$$
\begin{pmatrix}
a & b \\
c & d
\end{pmatrix}
$$

A 3x3 matrix:

$$
\begin{bmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
7 & 8 & 9
\end{bmatrix}
$$

### :keyboard: Activity: Create a matrix

1. Edit the `mathpractice.md` file you created.
2. Create a matrix of your choice. It could be an identity matrix, a transformation matrix, or any other matrix you find interesting.
3. Use the **Preview** tab to check your formatting.
4. Commit your changes.

## Step 5: Equation Systems and Cases

*Excellent work with matrices! Let's look at equation systems and cases.*

Equation systems and case definitions can be created using the `align` and `cases` environments.

### Example:

```md
Equation system:

$$
\begin{align}
3x + 2y &= 5 \\
x - y &= 1
\end{align}
$$

Piecewise function:

$$
f(x) = \begin{cases}
x^2 & \text{if } x \geq 0 \\
-x^2 & \text{if } x < 0
\end{cases}
$$
```

How it looks:

Equation system:

$$
\begin{align}
3x + 2y &= 5 \\
x - y &= 1
\end{align}
$$

Piecewise function:

$$
f(x) = \begin{cases}
x^2 & \text{if } x \geq 0 \\
-x^2 & \text{if } x < 0
\end{cases}
$$

### :keyboard: Activity: Create an equation system or piecewise function

1. Edit the `mathpractice.md` file you created.
2. Create either an equation system or a piecewise function. Be creative!
3. Use the **Preview** tab to check your formatting.
4. Commit your changes.

## Step 6: Create a Mathematical Cover Page

*Great job learning various mathematical notations! For the final step, let's create a cover page summarizing an interesting equation.*

Find a cool equation on Wikipedia or in a paper you're interested in. Create a cover page that includes:

1. A title
2. The equation (as a display equation)
3. A brief explanation of what the equation represents
4. At least one inline math expression in your explanation

### Example:

```md
# The Euler Identity

$$e^{i\pi} + 1 = 0$$

This elegant equation, known as Euler's Identity, connects five fundamental mathematical constants:
- $e$ (Euler's number)
- $i$ (the imaginary unit)
- $\pi$ (pi)
- 1 (the multiplicative identity)
- 0 (the additive identity)

It's often regarded as one of the most beautiful equations in mathematics, showing a deep connection between exponential functions and trigonometry, as $e^{i\pi} = \cos(\pi) + i\sin(\pi) = -1$.
```

*Blanking on cool equations? Consider the following:*
- [The Pythagorean Theorem](https://en.wikipedia.org/wiki/Pythagorean_theorem)
- [A Cobb-Douglas Production Function](https://en.wikipedia.org/wiki/Cobb%E2%80%93Douglas_production_function)
- [The Law of Large Numbers](https://en.wikipedia.org/wiki/Law_of_large_numbers) or [the Central Limit Theorem](https://en.wikipedia.org/wiki/Central_limit_theorem)
- [Other Examples](https://www.livescience.com/26681-most-beautiful-mathematical-equations.html)

### :keyboard: Activity: Create your mathematical cover page

1. Edit the `mathpractice.md` file you created or the `mathcoverpage.md` file that is also in the repo.
2. Create a cover page for an equation you find interesting, following the structure in the example above.
3. Use the **Preview** tab to check your formatting.
4. Commit your changes.
