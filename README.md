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
    A->C
    B->D
    C->D
```

`` mermaid
  flowchart TD
    A[Start]-->B[Test];
    B -- Yes --> D[End]
    B -- No --> E[Exception]
```
