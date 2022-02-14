```mermaid
participant A
participant B
participant C
B-->A: start
A-->C: check
C-->A: finish
```

```mermaid
  graph TD;
    A->B
    B->D
    A->C
    C -- Yes --> D
    C -- No --> E
```
