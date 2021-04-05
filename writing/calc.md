#### Name: Madelyn Kapfhammer

#### Date: 29 March 2021

#### What this is: Calculations from the manual work out of the Needleman-Wunsch algorithm.

### Instructions: Local Alignment calculations

For each entry in the matrix in the lab assignment, there is a letter and you are to place your calculations for each letter below. The first calculation for entry (a) is done for you. Please follow this example in your calculations for the rest of the letters.

Scoring table:


| Score or penalty | value |
| - | - |
| gap penalty | -1 |
| Mismatch penalty | 0 |
| Match score | 1 |

a)

- Match or Mismatch: A = A is a match
- Left entry calculation: -1 - 1 = -2
- Above entry calculation: -1 -1 = -2
- Diagonal entry calculation: 0 + 1 = 1
- Max score: 1 from the Diagonal

b)

- Match or Mismatch:               A != T (mismatch)
- Left entry calculation:           1 + (-1) = 0
- Above entry calculation:         -2 + (-1) = -3
- Diagonal entry calculation:      -1 + 0 = -1
- Max score: 0 from the left entry

c)

- Match or Mismatch:               A != t (mismatch)
- Left entry calculation:          -2 + (-1) = -3
- Above entry calculation:          1 + (-1) = 0
- Diagonal entry calculation:      -1 + 0 = -1
- Max score: 0 from the above entry

d)

- Match or Mismatch:               T = T (match)
- Left entry calculation:          0 + (-1) = -1
- Above entry calculation:         0 + (-1) = -1
- Diagonal entry calculation:      1 + 1 = 2
- Max score: 2 from the Diagonal

e)

- Match or Mismatch:               A != G (mismatch)
- Left entry calculation:          -3 + (-1) = -4
- Above entry calculation:          0 + (-1) = -1
- Diagonal entry calculation:      -2 + (0) = -2
- Max score: -1 from the above entry

f)

- Match or Mismatch:               T != G (mismatch)
- Left entry calculation:          -1 + (-1) = -2
- Above entry calculation:          2 + (-1) = 1
- Diagonal entry calculation:       0 + 0 = 0
- Max score: 1 from the above entry

