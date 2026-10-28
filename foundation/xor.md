# xor

| A | B | A XOR B |
|---|---|---------|
| 0 | 0 |    0    |
| 0 | 1 |    1    |
| 1 | 0 |    1    |
| 1 | 1 |    0    |

## C++

`bool result = a ^ b;`

## Edge detection

| Previous | Current | Rising Edge | Falling Edge | Any Edge (XOR) |
|----------|---------|-------------|--------------|----------------|
| 0        | 0       | 0           | 0            | 0              |
| 0        | 1       | 1           | 0            | 1              |
| 1        | 0       | 0           | 1            | 1              |
| 1        | 1       | 0           | 0            | 0              |