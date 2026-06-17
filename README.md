# Algebra Calculator

A browser-based algebra calculator covering equations, systems, and polynomials. No installation required — single HTML file, runs entirely in the browser.

**Live demo:** https://004-algebra-calculator.vercel.app

---

## Features

### Linear Equation
Solve `ax + b = cx + d` for x. Detects the no-solution and infinite-solutions edge cases.

### Quadratic Equation
Solve `ax² + bx + c = 0`:
- Real roots (distinct or repeated)
- Complex roots when the discriminant is negative
- Discriminant and vertex coordinates

### 2×2 System
Solve two linear equations in x and y using Cramer's rule. Reports when the system has no unique solution (parallel or identical lines).

### 3×3 System
Solve three linear equations in x, y, z using Cramer's rule with 3×3 determinants.

### Polynomial Ops
Add, subtract, or multiply two polynomials, entered as comma-separated coefficients (highest degree first). Returns both the simplified polynomial and its coefficient array.

### Factor Quadratic
Factor `ax² + bx + c` over the rationals when the discriminant is a perfect square; otherwise reports the irrational or complex root form.

### Evaluate Expression
Evaluate any polynomial expression in `x` (supports `+ - * / ^ ( )`) at a given value of x.

---

## Usage

Open `index.html` directly in any modern browser — no build step, no dependencies to install.

```bash
git clone git@github.com:kevb2029-maker/004-Calculator-Algebra.git
cd 004-Calculator-Algebra
open index.html
```

### Examples

| Input | Tool | Result |
|-------|------|--------|
| `2x + 3 = 11` | Linear Equation | `x = 4` |
| `x² − 3x + 2 = 0` | Quadratic Equation | `x₁ = 2, x₂ = 1` |
| `2x + 3y = 8`, `x − y = 1` | 2×2 System | `x = 2.2, y = 1.2` |
| `(1,2,3) × (2,−1)` | Polynomial Ops | `2x³ + 3x² + 4x − 3` |
| `2x² + 7x + 3` | Factor Quadratic | `2(2x + 1)(x + 3)` |

---

## Tech stack

Plain HTML, CSS, and JavaScript. No frameworks, no bundler, no build step, no external dependencies.

---

## License

MIT — see [LICENSE](LICENSE).
