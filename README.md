# idnp.js

IDNP validation function

## Validation Rules

- Length - 13 digits
- First digit should be 0 or 2
- Every digit from IDNP (from 1 to 12) is multiplied with the corresponding digit in number 731731731731; the sum of all these multiplications is then divided by modulo by 10. 13th digit should be equal to calculated result
