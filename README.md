# Sandwich Shop Price Calculator (Java)

This project is a simple Java program that calculates the final price of a sandwich based on:

- Sandwich size selection
- User's age (for applicable discounts)

---

## Features

### Sandwich Sizes:
| Size Option | Description | Base Price |
|-------------|-------------|------------|
| 1 | Regular | $5.45 |
| 2 | Large   | $8.95 |

---

### Discount Rules:
| Customer Type | Condition | Discount |
|---------------|-----------|----------|
| Student       | Age ≤ 17  | 10% off  |
| Senior        | Age ≥ 65  | 20% off  |
| Others        | No Discount | 0% off |

---

## Program Flow:

1. User is prompted to select a sandwich size (1 or 2).
2. User enters their age.
3. Program calculates:
   - Base price of sandwich.
   - Discount percent (if any).
   - Discount amount.
   - Final price after discount.
4. Displays the result.

---

## Example Run:

Example Input:
