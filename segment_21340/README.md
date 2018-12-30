# SIGNAL COMPARATOR

## Instructions

```
> READ A VALUE FROM IN
> WRITE 1 TO OUT.G IF IN > 0
> WRITE 1 TO OUT.E IF IN = 0
> WRITE 1 TO OUT.L IF IN < 0
> WHEN A 1 IS NOT WRITTEN TO
  AN OUTPUT, WRITE A 0 INSTEAD
```

## Solutions

### [`21340.0` - `1ST SOLUTION`](21340.0.txt)

| Cycles | Nodes | Instructions |
| ------ | ----- | ------------ |
|   283  |   6   |      20      |

![21340.0](21340.0.jpg?raw=true)

### [`21340.1` - `UNCONDITIONAL`](21340.1.txt)

**Goal**: _Solve SIGNAL COMPARATOR without using the JGZ, JLZ, JEZ, or JNZ instructions._

| Cycles | Nodes | Instructions |
| ------ | ----- | ------------ |
|   268  |   6   |      36      |

![21340.1](21340.1.jpg?raw=true)

