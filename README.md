# COMP110 Worksheet 4

Please edit this README.md file with your answers to the worksheet questions.

## Question 1

### a 
A AND B AND NOT C

| A | B | C | A and B | Not C | A and B and Not C |
|:--|:--|:--|:--------|:------|:------------------|
| T | T | F |    T    |   T   |        T          |
| T | F | T |    F    |   F   |        F          |
| F | T | T |    F    |   F   |        F          |
| F | F | T |    F    |   F   |        F          |
| F | F | F |    F    |   T   |        F          |
| T | T | T |    T    |   F   |        T          |

 
### b
A AND NOT (B AND NOT C)

| A | B | C | A and Not B | Not C | A and Not (B and Not C)|
|:--|:--|:--|:------------|:------|:-----------------------|
| T | T | F |      F      |   T   |          F             |
| T | F | T |      T      |   F   |          T             |
| F | T | T |      F      |   F   |          F             |
| F | F | T |      F      |   F   |          F             |
| F | F | F |      F      |   T   |          F             |
| T | T | T |      F      |   F   |          T             |
  


### c
(A OR NOT B) AND (A OR C)

| A | B | C | not B | A or not B| A or C| (A or not B) and (A or C)|
|:--|:--|:--|:------|:----------|:------|:-------------------------|
| T | T | F |   F   |     T     |   T   |            T             |
| T | F | T |   T   |     T     |   T   |            T             |
| F | T | T |   F   |     F     |   T   |            F             |
| F | F | T |   T   |     T     |   T   |            T             |
| F | F | F |   T   |     T     |   F   |            F             |
| T | T | T |   F   |     T     |   T   |            T             |
            

### d
A AND NOT (B OR NOT C) AND (NOT A AND D)

| A | B | C | D | not C | not A | B or not C| not A and D | A and not ((B or not C) and (not A and D))|
|:--|:--|:--|:--|:------|:------|:----------|:------------|:------------------------------------------|
| T | T | T | T |   F   |   F   |     T     |      T      |                     F                     |
| F | F | F | F |   T   |   T   |     T     |      T      |                     F                     |
| T | F | F | F |   T   |   F   |     T     |      F      |                     F                     |
| T | T | F | F |   T   |   F   |     T     |      F      |                     F                     |
| T | T | T | F |   F   |   F   |     T     |      F      |                     F                     |             
| F | T | T | T |   F   |   T   |     T     |      T      |                     F                     |
| F | F | T | T |   F   |   T   |     T     |      T      |                     F                     |
| F | F | F | T |   T   |   T   |     T     |      T      |                     F                     |
 
## Question 2

### a

### b

### c

### d

## Question 3

### a

### b

### c

### d

## Question 4

### a

### b

### c

### d

